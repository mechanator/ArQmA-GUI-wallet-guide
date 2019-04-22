# A copy of this Makefile should be included in every folder containing a translation of the guide.
CHAPTERS = *.md

BUILD_PATH = $(BUILD)/$(LANGUAGE)


all: book

book: epub html pdf

clean:
	rm -r $(BUILD)

# Make sure there is a link to the media directory in the root of the repository.
ifeq ("$(wildcard media)","")
medialink::
	ln -s ../media media
else
medialink::
endif


epub: $(BUILD_PATH)/epub/$(BOOKNAME)

html: $(BUILD_PATH)/html/$(BOOKNAME)

pdf: $(BUILD_PATH)/pdf/$(BOOKNAME)

$(BUILD_PATH)/epub/$(BOOKNAME): | medialink
	mkdir -p ../$(BUILD_PATH)/epub
	pandoc $(TOC) -S --epub-metadata=../$(METADATA) --epub-cover-image=../$(COVER_IMAGE) -o ../$@.epub $(CHAPTERS)

$(BUILD_PATH)/html/$(BOOKNAME):  | medialink
	sudo mkdir -p ../$(BUILD_PATH)/html
	sudo ln -s ../../../media ../$(BUILD_PATH)/html/media
	sudo pandoc $(TOC) --standalone -fmarkdown-implicit_figures --to=html5 -o ../$@.html $(CHAPTERS)

$(BUILD_PATH)/pdf/$(BOOKNAME): | medialink
	sudo mkdir -p ../$(BUILD_PATH)/pdf
	sudo pandoc $(TOC) --latex-engine=$(LATEX_ENGINE) -V documentclass=$(LATEX_CLASS) -V geometry:$(MARGIN) -V urlcolor=$(URL_COLOR) -V lang=${LANGUAGE} -o ../$@.pdf $(CHAPTERS)

.PHONY: all book clean epub html pdf

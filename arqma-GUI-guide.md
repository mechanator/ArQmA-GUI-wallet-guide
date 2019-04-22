





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://github.githubassets.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" media="all" integrity="sha512-OBabailf0Gja8rWVZO1xyYAw//CQdLOJF4riG050gTxsVqVD7az4Sq56hPWfv3AoaxuEhYXgQlGQcNxzZzDyVA==" rel="stylesheet" href="https://github.githubassets.com/assets/frameworks-d69542a4a3958db914b3bec3f757de26.css" />
  
    <link crossorigin="anonymous" media="all" integrity="sha512-wJhnzAfXEZIRVozNeRj3om7LYMKNuN4/pWiws3GvDrVcYuSnHZVWzVFF0nocd7vibgFePdnbVtr/SgFIOP/FcA==" rel="stylesheet" href="https://github.githubassets.com/assets/github-038ca28f0d66963cc8fcdd04180ca5e0.css" />
    
    
    
    

  <meta name="viewport" content="width=device-width">
  
  <title>ArQmA-GUI-wallet-guide/arqma-GUI-guide.md at master · mechanator/ArQmA-GUI-wallet-guide</title>
    <meta name="description" content="Guide and documentation for the ArQmA GUI wallet. Contribute to mechanator/ArQmA-GUI-wallet-guide development by creating an account on GitHub.">
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    <meta name="twitter:image:src" content="https://avatars0.githubusercontent.com/u/40085316?s=400&amp;v=4" /><meta name="twitter:site" content="@github" /><meta name="twitter:card" content="summary" /><meta name="twitter:title" content="mechanator/ArQmA-GUI-wallet-guide" /><meta name="twitter:description" content="Guide and documentation for the ArQmA GUI wallet. Contribute to mechanator/ArQmA-GUI-wallet-guide development by creating an account on GitHub." />
    <meta property="og:image" content="https://avatars0.githubusercontent.com/u/40085316?s=400&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="mechanator/ArQmA-GUI-wallet-guide" /><meta property="og:url" content="https://github.com/mechanator/ArQmA-GUI-wallet-guide" /><meta property="og:description" content="Guide and documentation for the ArQmA GUI wallet. Contribute to mechanator/ArQmA-GUI-wallet-guide development by creating an account on GitHub." />

  <link rel="assets" href="https://github.githubassets.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6Mzk2MTY2MTA2OjNiZjUyMGFhZjE2ZDIwNjM1MjEwNjZiYTUxMjM3YjZjNzU0OGZjZDVjNTUzNDQyNWNmYzQ5NDM0MTBiOTRiNWU=--150dfb327a79b542dc570706a099c4ac0aad6864">
  <meta name="pjax-timeout" content="1000">
  <link rel="sudo-modal" href="/sessions/sudo_modal">
  <meta name="request-id" content="FC01:57DC:F2625:1855C7:5CBDF48E" data-pjax-transient>


  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

      <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">

  <meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-request_id" content="FC01:57DC:F2625:1855C7:5CBDF48E" /><meta name="octolytics-dimension-region_edge" content="sea" /><meta name="octolytics-dimension-region_render" content="iad" /><meta name="octolytics-actor-id" content="40085316" /><meta name="octolytics-actor-login" content="mechanator" /><meta name="octolytics-actor-hash" content="74d071998606535f2eee9df6a4433c5ce0d0df7f49ef5e85b48c16f22656bb49" />
<meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" />



    <meta name="google-analytics" content="UA-3769691-2">

  <meta class="js-ga-set" name="userId" content="a4f1a0baaf2a4171d452277a3d485f3a">

<meta class="js-ga-set" name="dimension1" content="Logged In">



  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="mechanator">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="MzlkOGRmYzA1YmExZGJkODNjMDdiZTFkNDM0ZTY3NjNhZWFkYzhjYWFlNzI1OTBhMzdhMmZmOTYxYTRiNjczZHx7InJlbW90ZV9hZGRyZXNzIjoiNzMuMTgwLjIzLjIxNiIsInJlcXVlc3RfaWQiOiJGQzAxOjU3REM6RjI2MjU6MTg1NUM3OjVDQkRGNDhFIiwidGltZXN0YW1wIjoxNTU1OTUyNzgyLCJob3N0IjoiZ2l0aHViLmNvbSJ9">

    <meta name="enabled-features" content="UNIVERSE_BANNER,MARKETPLACE_INVOICED_BILLING,MARKETPLACE_SOCIAL_PROOF_CUSTOMERS,MARKETPLACE_TRENDING_SOCIAL_PROOF,MARKETPLACE_RECOMMENDATIONS,NOTIFY_ON_BLOCK,RELATED_ISSUES">

  <meta name="html-safe-nonce" content="5fcc155361dd3ad86358382c172deaf630d3289c">

  <meta http-equiv="x-pjax-version" content="7d174e573145e30ac002780c2257882e">
  

      <link href="https://github.com/mechanator/ArQmA-GUI-wallet-guide/commits/master.atom" rel="alternate" title="Recent Commits to ArQmA-GUI-wallet-guide:master" type="application/atom+xml">

  <meta name="go-import" content="github.com/mechanator/ArQmA-GUI-wallet-guide git https://github.com/mechanator/ArQmA-GUI-wallet-guide.git">

  <meta name="octolytics-dimension-user_id" content="40085316" /><meta name="octolytics-dimension-user_login" content="mechanator" /><meta name="octolytics-dimension-repository_id" content="182302194" /><meta name="octolytics-dimension-repository_nwo" content="mechanator/ArQmA-GUI-wallet-guide" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="false" /><meta name="octolytics-dimension-repository_network_root_id" content="182302194" /><meta name="octolytics-dimension-repository_network_root_nwo" content="mechanator/ArQmA-GUI-wallet-guide" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="true" />


    <link rel="canonical" href="https://github.com/mechanator/ArQmA-GUI-wallet-guide/blob/master/arqma-GUI-guide.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://github.githubassets.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://github.githubassets.com/favicon.ico">

<meta name="theme-color" content="#1e2327">


  <meta name="u2f-enabled" content="true">


  <link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">

  </head>

  <body class="logged-in env-production page-responsive min-width-0 page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="p-3 bg-blue text-white show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    


          <header class="Header js-details-container Details flex-wrap flex-lg-nowrap p-responsive" role="banner">

    <div class="Header-item d-none d-lg-flex">
      <a class="Header-link" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg class="octicon octicon-mark-github v-align-middle" height="32" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>

    </div>

    <div class="Header-item d-lg-none">
      <button class="Header-link btn-link mt-1 js-details-target" type="button" aria-label="Toggle navigation" aria-expanded="false">
        <svg height="24" class="octicon octicon-three-bars" viewBox="0 0 12 16" version="1.1" width="18" aria-hidden="true"><path fill-rule="evenodd" d="M11.41 9H.59C0 9 0 8.59 0 8c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zm0-4H.59C0 5 0 4.59 0 4c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zM.59 11H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1H.59C0 13 0 12.59 0 12c0-.59 0-1 .59-1z"/></svg>
      </button>
    </div>

    <div class="Header-item Header-item--full flex-column flex-lg-row width-full flex-order-2 flex-lg-order-none mr-0 mr-lg-3 mt-3 mt-lg-0 Details-content--hidden">
        <div class="header-search flex-self-stretch flex-lg-self-auto mr-0 mr-lg-3 mb-3 mb-lg-0 scoped-search site-scoped-search js-site-search position-relative js-jump-to"
  role="combobox"
  aria-owns="jump-to-results"
  aria-label="Search or jump to"
  aria-haspopup="listbox"
  aria-expanded="false"
>
  <div class="position-relative">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-site-search-form" role="search" aria-label="Site" data-scope-type="Repository" data-scope-id="182302194" data-scoped-search-url="/mechanator/ArQmA-GUI-wallet-guide/search" data-unscoped-search-url="/search" action="/mechanator/ArQmA-GUI-wallet-guide/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
      <label class="form-control input-sm header-search-wrapper p-0 header-search-wrapper-jump-to position-relative d-flex flex-justify-between flex-items-center js-chromeless-input-container">
        <input type="text"
          class="form-control input-sm header-search-input jump-to-field js-jump-to-field js-site-search-focus js-site-search-field is-clearable"
          data-hotkey="s,/"
          name="q"
          value=""
          placeholder="Search or jump to…"
          data-unscoped-placeholder="Search or jump to…"
          data-scoped-placeholder="Search or jump to…"
          autocapitalize="off"
          aria-autocomplete="list"
          aria-controls="jump-to-results"
          aria-label="Search or jump to…"
          data-jump-to-suggestions-path="/_graphql/GetSuggestedNavigationDestinations#csrf-token=OWUE0nrEgdll1jIlgKEgJSnnlhaf7ibZsZHtcQ6XEYY1dHzXe67+Yd5PEBU6UAIzxfw/SUFZGxb0QSa7OHuE5A=="
          spellcheck="false"
          autocomplete="off"
          >
          <input type="hidden" class="js-site-search-type-field" name="type" >
            <img src="https://github.githubassets.com/images/search-key-slash.svg" alt="" class="mr-2 header-search-key-slash">

            <div class="Box position-absolute overflow-hidden d-none jump-to-suggestions js-jump-to-suggestions-container">
              
<ul class="d-none js-jump-to-suggestions-template-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-suggestion" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

</ul>

<ul class="d-none js-jump-to-no-results-template-container">
  <li class="d-flex flex-justify-center flex-items-center f5 d-none js-jump-to-suggestion p-2">
    <span class="text-gray">No suggested jump to results</span>
  </li>
</ul>

<ul id="jump-to-results" role="listbox" class="p-0 m-0 js-navigation-container jump-to-suggestions-results-container js-jump-to-suggestions-results-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-scoped-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-global-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>


    <li class="d-flex flex-justify-center flex-items-center p-0 f5 js-jump-to-suggestion">
      <img src="https://github.githubassets.com/images/spinners/octocat-spinner-128.gif" alt="Octocat Spinner Icon" class="m-2" width="28">
    </li>
</ul>

            </div>
      </label>
</form>  </div>
</div>


      <nav class="d-flex flex-column flex-lg-row flex-self-stretch flex-lg-self-auto" aria-label="Global">
    <a class="Header-link d-block d-lg-none py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:dashboard:user" aria-label="Dashboard" href="/dashboard">
      Dashboard
</a>
  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g p" data-ga-click="Header, click, Nav menu - item:pulls context:user" aria-label="Pull requests you created" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls" href="/pulls">
    Pull requests
</a>
  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g i" data-ga-click="Header, click, Nav menu - item:issues context:user" aria-label="Issues you created" data-selected-links="/issues /issues/assigned /issues/mentioned /issues" href="/issues">
    Issues
</a>
    <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-octo-click="marketplace_click" data-octo-dimensions="location:nav_bar" data-selected-links=" /marketplace" href="/marketplace">
      Marketplace
</a>      

  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore" href="/explore">
    Explore
</a>
    <a class="Header-link d-block d-lg-none mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" aria-label="View profile and more" aria-expanded="false" aria-haspopup="false" href="https://github.com/mechanator">
      <img class="avatar" src="https://avatars0.githubusercontent.com/u/40085316?s=40&amp;v=4" width="20" height="20" alt="@mechanator" />
      mechanator
</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="l8ufthmFFmTFSDG9kO4f1vvLpHp78v6xwA1Xnr6g8YjQ16rAkyk4kWmvjSKIT2WeBPhml9Uf/Ok5IHK3HalsRA==" />
      <button type="submit" class="Header-link mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15 d-lg-none btn-link d-block width-full text-left" data-ga-click="Header, sign out, icon:logout" style="padding-left: 2px;">
        <svg class="octicon octicon-sign-out v-align-middle" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9V7H8V5h4V3l4 3-4 3zm-2 3H6V3L2 1h8v3h1V1c0-.55-.45-1-1-1H1C.45 0 0 .45 0 1v11.38c0 .39.22.73.55.91L6 16.01V13h4c.55 0 1-.45 1-1V8h-1v4z"/></svg>
        Sign out
      </button>
</form></nav>

    </div>

    <div class="Header-item Header-item--full flex-justify-center d-lg-none position-relative">
      <div class="css-truncate css-truncate-target width-fit position-absolute left-0 right-0 text-center">
              <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
    <a class="Header-link" href="/mechanator">mechanator</a>
    /
    <a class="Header-link" href="/mechanator/ArQmA-GUI-wallet-guide">ArQmA-GUI-wallet-guide</a>

</div>
    </div>

    <div class="Header-item mr-0 mr-lg-3 flex-order-1 flex-lg-order-none">
      
    <a aria-label="You have no unread notifications" class="Header-link notification-indicator tooltipped tooltipped-s my-2 my-lg-0 js-socket-channel js-notification-indicator" data-hotkey="g n" data-ga-click="Header, go to notifications, icon:read" data-channel="notification-changed:40085316" href="/notifications">
        <span class="mail-status "></span>
        <svg class="octicon octicon-bell" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 12v1H0v-1l.73-.58c.77-.77.81-2.55 1.19-4.42C2.69 3.23 6 2 6 2c0-.55.45-1 1-1s1 .45 1 1c0 0 3.39 1.23 4.16 5 .38 1.88.42 3.66 1.19 4.42l.66.58H14zm-7 4c1.11 0 2-.89 2-2H5c0 1.11.89 2 2 2z"/></svg>
</a>
    </div>


    <div class="Header-item position-relative d-none d-lg-flex">
      <details class="details-overlay details-reset">
  <summary class="Header-link"
      aria-label="Create new…"
      data-ga-click="Header, create new, icon:add">
    <svg class="octicon octicon-plus" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5v2z"/></svg> <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw">
    
<a role="menuitem" class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a role="menuitem" class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a role="menuitem" class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a role="menuitem" class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>


  <div role="none" class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="mechanator/ArQmA-GUI-wallet-guide">This repository</span>
  </div>
    <a role="menuitem" class="dropdown-item" href="/mechanator/ArQmA-GUI-wallet-guide/issues/new" data-ga-click="Header, create new issue" data-skip-pjax>
      New issue
    </a>


  </details-menu>
</details>

    </div>

    <div class="Header-item position-relative mr-0 d-none d-lg-flex">
      
<details class="details-overlay details-reset">
  <summary class="Header-link"
    aria-label="View profile and more"
    data-ga-click="Header, show menu, icon:avatar">
    <img alt="@mechanator" class="avatar" src="https://avatars0.githubusercontent.com/u/40085316?s=40&amp;v=4" height="20" width="20">
    <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw mt-2" style="width: 180px">
    <div class="header-nav-current-user css-truncate"><a role="menuitem" class="no-underline user-profile-link px-3 pt-2 pb-2 mb-n2 mt-n1 d-block" href="/mechanator" data-ga-click="Header, go to profile, text:Signed in as">Signed in as <strong class="css-truncate-target">mechanator</strong></a></div>
    <div role="none" class="dropdown-divider"></div>

      <div class="pl-3 pr-5 f6 user-status-container js-user-status-context pb-1" data-url="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1">
        
<div class="js-user-status-container  user-status-compact rounded-1 px-2 py-1 mt-2 border" data-team-hovercards-enabled>
  <details class="js-user-status-details details-reset details-overlay details-overlay-dark">
    <summary class="btn-link no-underline js-toggle-user-status-edit toggle-user-status-edit width-full d-flex link-gray " aria-haspopup="dialog" role="menuitem" data-hydro-click="{&quot;event_type&quot;:&quot;user_profile.click&quot;,&quot;payload&quot;:{&quot;profile_user_id&quot;:40085316,&quot;target&quot;:&quot;EDIT_USER_STATUS&quot;,&quot;user_id&quot;:40085316,&quot;client_id&quot;:&quot;1293665596.1555791383&quot;,&quot;originating_request_id&quot;:&quot;FC01:57DC:F2625:1855C7:5CBDF48E&quot;,&quot;originating_url&quot;:&quot;https://github.com/mechanator/ArQmA-GUI-wallet-guide/blob/master/arqma-GUI-guide.md&quot;,&quot;referrer&quot;:&quot;https://github.com/mechanator/ArQmA-GUI-wallet-guide&quot;}}" data-hydro-click-hmac="aaf9c1619aa1c13635391d0c3f917f8d7189f2e72978096f41f8d130cf065d41">
      <div class="f6 d-inline-block v-align-middle user-status-emoji-only-header circle pr-2 lh-condensed user-status-header " style="max-width: 29px">
        <div class="user-status-emoji-container flex-shrink-0 mr-1 mt-1 lh-condensed-ultra v-align-bottom" style="">
          <svg class="octicon octicon-smiley" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8s3.58 8 8 8 8-3.58 8-8-3.58-8-8-8zm4.81 12.81a6.72 6.72 0 0 1-2.17 1.45c-.83.36-1.72.53-2.64.53-.92 0-1.81-.17-2.64-.53-.81-.34-1.55-.83-2.17-1.45a6.773 6.773 0 0 1-1.45-2.17A6.59 6.59 0 0 1 1.21 8c0-.92.17-1.81.53-2.64.34-.81.83-1.55 1.45-2.17.62-.62 1.36-1.11 2.17-1.45A6.59 6.59 0 0 1 8 1.21c.92 0 1.81.17 2.64.53.81.34 1.55.83 2.17 1.45.62.62 1.11 1.36 1.45 2.17.36.83.53 1.72.53 2.64 0 .92-.17 1.81-.53 2.64-.34.81-.83 1.55-1.45 2.17zM4 6.8v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2H5.2C4.53 8 4 7.47 4 6.8zm5 0v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2h-.59C9.53 8 9 7.47 9 6.8zm4 3.2c-.72 1.88-2.91 3-5 3s-4.28-1.13-5-3c-.14-.39.23-1 .66-1h8.59c.41 0 .89.61.75 1z"/></svg>
        </div>
      </div>
      <div class="
        d-inline-block v-align-middle
        
        
         css-truncate css-truncate-target 
         user-status-message-wrapper f6"
        style="line-height: 20px;">
        <div class="d-inline-block text-gray-dark v-align-text-top">
            <span class="text-gray ml-2">Set status</span>
        </div>
      </div>
</summary>    <details-dialog class="details-dialog rounded-1 anim-fade-in fast Box Box--overlay" role="dialog" tabindex="-1">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="position-relative flex-auto js-user-status-form" action="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="pZfbVHiCb+Bx7EPh4X3/DiUxofWaEvrSaJ4da9kX0kvJWUtjzNGFr+ZjGnmCGjZLLB8L5zyS5a9gMGsUeLW/ZA==" />
        <div class="Box-header bg-gray border-bottom p-3">
          <button class="Box-btn-octicon js-toggle-user-status-edit btn-octicon float-right" type="reset" aria-label="Close dialog" data-close-dialog>
            <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
          </button>
          <h3 class="Box-title f5 text-bold text-gray-dark">Edit status</h3>
        </div>
        <input type="hidden" name="emoji" class="js-user-status-emoji-field" value="">
        <input type="hidden" name="organization_id" class="js-user-status-org-id-field" value="">
        <div class="px-3 py-2 text-gray-dark">
          <div class="js-characters-remaining-container js-suggester-container position-relative mt-2">
            <div class="input-group d-table form-group my-0 js-user-status-form-group">
              <span class="input-group-button d-table-cell v-align-middle" style="width: 1%">
                <button type="button" aria-label="Choose an emoji" class="btn-outline btn js-toggle-user-status-emoji-picker btn-open-emoji-picker p-0">
                  <span class="js-user-status-original-emoji" hidden></span>
                  <span class="js-user-status-custom-emoji"></span>
                  <span class="js-user-status-no-emoji-icon" >
                    <svg class="octicon octicon-smiley" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8s3.58 8 8 8 8-3.58 8-8-3.58-8-8-8zm4.81 12.81a6.72 6.72 0 0 1-2.17 1.45c-.83.36-1.72.53-2.64.53-.92 0-1.81-.17-2.64-.53-.81-.34-1.55-.83-2.17-1.45a6.773 6.773 0 0 1-1.45-2.17A6.59 6.59 0 0 1 1.21 8c0-.92.17-1.81.53-2.64.34-.81.83-1.55 1.45-2.17.62-.62 1.36-1.11 2.17-1.45A6.59 6.59 0 0 1 8 1.21c.92 0 1.81.17 2.64.53.81.34 1.55.83 2.17 1.45.62.62 1.11 1.36 1.45 2.17.36.83.53 1.72.53 2.64 0 .92-.17 1.81-.53 2.64-.34.81-.83 1.55-1.45 2.17zM4 6.8v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2H5.2C4.53 8 4 7.47 4 6.8zm5 0v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2h-.59C9.53 8 9 7.47 9 6.8zm4 3.2c-.72 1.88-2.91 3-5 3s-4.28-1.13-5-3c-.14-.39.23-1 .66-1h8.59c.41 0 .89.61.75 1z"/></svg>
                  </span>
                </button>
              </span>
              <input type="text" autocomplete="off" data-maxlength="80" class="js-suggester-field d-table-cell width-full form-control js-user-status-message-field js-characters-remaining-field" placeholder="What's happening?" name="message" value="" aria-label="What is your current status?">
              <div class="error">Could not update your status, please try again.</div>
            </div>
            <div class="suggester-container">
              <div class="suggester js-suggester js-navigation-container" data-url="/autocomplete/user-suggestions" data-no-org-url="/autocomplete/user-suggestions" data-org-url="/suggestions" hidden>
              </div>
            </div>
            <div style="margin-left: 53px" class="my-1 text-small label-characters-remaining js-characters-remaining" data-suffix="remaining" hidden>
              80 remaining
            </div>
          </div>
          <include-fragment class="js-user-status-emoji-picker" data-url="/users/status/emoji"></include-fragment>
          <div class="overflow-auto ml-n3 mr-n3 px-3" style="max-height: 33vh">
            <div class="user-status-suggestions js-user-status-suggestions collapsed overflow-hidden">
              <h4 class="f6 text-normal my-3">Suggestions:</h4>
              <div class="mx-3 mt-2 clearfix">
                  <div class="float-left col-6">
                      <button type="button" value=":palm_tree:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="palm_tree" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f334.png">🌴</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          On vacation
                        </div>
                      </button>
                      <button type="button" value=":face_with_thermometer:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="face_with_thermometer" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f912.png">🤒</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Out sick
                        </div>
                      </button>
                  </div>
                  <div class="float-left col-6">
                      <button type="button" value=":house:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="house" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3e0.png">🏠</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Working from home
                        </div>
                      </button>
                      <button type="button" value=":dart:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="dart" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3af.png">🎯</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Focusing
                        </div>
                      </button>
                  </div>
              </div>
            </div>
            <div class="user-status-limited-availability-container">
              <div class="form-checkbox my-0">
                <input type="checkbox" name="limited_availability" value="1" class="js-user-status-limited-availability-checkbox" data-default-message="I may be slow to respond." aria-describedby="limited-availability-help-text-truncate-true" id="limited-availability-truncate-true">
                <label class="d-block f5 text-gray-dark mb-1" for="limited-availability-truncate-true">
                  Busy
                </label>
                <p class="note" id="limited-availability-help-text-truncate-true">
                  When others mention you, assign you, or request your review,
                  GitHub will let them know that you have limited availability.
                </p>
              </div>
            </div>
          </div>
            

<div class="d-inline-block f5 border-top mr-2 pt-3 pb-2" >
  <div class="d-inline-block mr-1">
    Clear status
  </div>

  <details class="js-user-status-expire-drop-down f6 dropdown details-reset details-overlay d-inline-block mr-2">
    <summary class="f5 btn-link link-gray-dark border px-2 py-1 rounded-1" aria-haspopup="true">
      <div class="js-user-status-expiration-interval-selected d-inline-block v-align-baseline">
        Never
      </div>
      <div class="dropdown-caret"></div>
    </summary>

    <ul class="dropdown-menu dropdown-menu-se pl-0 overflow-auto" style="width: 220px; max-height: 15.5em">
      <li>
        <button type="button" class="btn-link dropdown-item js-user-status-expire-button ws-normal" title="Never">
          <span class="d-inline-block text-bold mb-1">Never</span>
          <div class="f6 lh-condensed">Keep this status until you clear your status or edit your status.</div>
        </button>
      </li>
      <li class="dropdown-divider" role="none"></li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 30 minutes" value="2019-04-22T10:36:22-07:00">
            in 30 minutes
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 1 hour" value="2019-04-22T11:06:22-07:00">
            in 1 hour
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 4 hours" value="2019-04-22T14:06:22-07:00">
            in 4 hours
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="today" value="2019-04-22T23:59:59-07:00">
            today
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="this week" value="2019-04-28T23:59:59-07:00">
            this week
          </button>
        </li>
    </ul>
  </details>
  <input class="js-user-status-expiration-date-input" type="hidden" name="expires_at" value="">
</div>

          <include-fragment class="js-user-status-org-picker" data-url="/users/status/organizations"></include-fragment>
        </div>
        <div class="d-flex flex-items-center flex-justify-between p-3 border-top">
          <button type="submit" disabled class="width-full btn btn-primary mr-2 js-user-status-submit">
            Set status
          </button>
          <button type="button" disabled class="width-full js-clear-user-status-button btn ml-2 ">
            Clear status
          </button>
        </div>
</form>    </details-dialog>
  </details>
</div>

      </div>
      <div role="none" class="dropdown-divider"></div>


    <a role="menuitem" class="dropdown-item" href="/mechanator" data-ga-click="Header, go to profile, text:your profile">Your profile</a>
    <a role="menuitem" class="dropdown-item" href="/mechanator?tab=repositories" data-ga-click="Header, go to repositories, text:your repositories">Your repositories</a>

    <a role="menuitem" class="dropdown-item" href="/mechanator?tab=projects" data-ga-click="Header, go to projects, text:your projects">Your projects</a>

    <a role="menuitem" class="dropdown-item" href="/mechanator?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">Your stars</a>
      <a role="menuitem" class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, your gists, text:your gists">Your gists</a>

    <div role="none" class="dropdown-divider"></div>
    <a role="menuitem" class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
    <a role="menuitem" class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">Settings</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="logout-form" action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="qV2gkefKwKImvAM39mId8ps0fEQ6MzcaTSgbeWh/W6ruQZXnbWbuV4pbv6juw2e6ZAe+qZTeNUK0BT5Qy3bGZg==" />
      
      <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout" role="menuitem">
        Sign out
      </button>
</form>  </details-menu>
</details>

    </div>

  </header>

      

  </div>

  <div id="start-of-content" class="show-on-focus"></div>


    <div id="js-flash-container">

</div>



  <div class="application-main " data-commit-hovercards-enabled>
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <main  >
      


  






  <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav pt-0 pt-lg-4 ">
    <div class="repohead-details-container clearfix container-lg p-responsive d-none d-lg-block">

      <ul class="pagehead-actions">



  <li>
    
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form data-remote="true" class="clearfix js-social-form js-social-container" action="/notifications/subscribe" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="lU/vGGLNU+ZIY/le4PY0aX2dZX23C2nUUAZ285WeYK4VgwoHCYiarvVoa9eIYY2Bxm0iYfWUoS4w+jg1C3mCRg==" />      <input type="hidden" name="repository_id" value="182302194">

      <details class="details-reset details-overlay select-menu float-left">
        <summary class="select-menu-button float-left btn btn-sm btn-with-count" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;WATCH_BUTTON&quot;,&quot;repository_id&quot;:182302194,&quot;client_id&quot;:&quot;1293665596.1555791383&quot;,&quot;originating_request_id&quot;:&quot;FC01:57DC:F2625:1855C7:5CBDF48E&quot;,&quot;originating_url&quot;:&quot;https://github.com/mechanator/ArQmA-GUI-wallet-guide/blob/master/arqma-GUI-guide.md&quot;,&quot;referrer&quot;:&quot;https://github.com/mechanator/ArQmA-GUI-wallet-guide&quot;,&quot;user_id&quot;:40085316}}" data-hydro-click-hmac="d7e1af16d169a97f92c905eb29f26f09dc96755baee933d4891aed9261f384f2" data-ga-click="Repository, click Watch settings, action:blob#show">          <span data-menu-button>
              <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
              Watch
          </span>
</summary>        <details-menu
          class="select-menu-modal position-absolute mt-5"
          style="z-index: 99;">
          <div class="select-menu-header">
            <span class="select-menu-title">Notifications</span>
          </div>
          <div class="select-menu-list">
            <button type="submit" name="do" value="included" class="select-menu-item width-full" aria-checked="true" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Not watching</span>
                <span class="description">Be notified only when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Watch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="release_only" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Releases only</span>
                <span class="description">Be notified of new releases, and when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Unwatch releases
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="subscribed" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Watching</span>
                <span class="description">Be notified of all conversations.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Unwatch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="ignore" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Ignoring</span>
                <span class="description">Never be notified.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-mute v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
                  Stop ignoring
                </span>
              </div>
            </button>
          </div>
        </details-menu>
      </details>
        <a class="social-count js-social-count"
          href="/mechanator/ArQmA-GUI-wallet-guide/watchers"
          aria-label="0 users are watching this repository">
          0
        </a>
</form>
  </li>

  <li>
      <div class="js-toggler-container js-social-container starring-container ">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="starred js-social-form" action="/mechanator/ArQmA-GUI-wallet-guide/unstar" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="DVVoW8omaoiTE9L4tQMwDGjXqlsPOUFfJd4t600SEG6ou0270uLCOIs72g1iSW7ylRItU3C2KeVb+8YEsBnm5A==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Unstar mechanator/ArQmA-GUI-wallet-guide" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;UNSTAR_BUTTON&quot;,&quot;repository_id&quot;:182302194,&quot;client_id&quot;:&quot;1293665596.1555791383&quot;,&quot;originating_request_id&quot;:&quot;FC01:57DC:F2625:1855C7:5CBDF48E&quot;,&quot;originating_url&quot;:&quot;https://github.com/mechanator/ArQmA-GUI-wallet-guide/blob/master/arqma-GUI-guide.md&quot;,&quot;referrer&quot;:&quot;https://github.com/mechanator/ArQmA-GUI-wallet-guide&quot;,&quot;user_id&quot;:40085316}}" data-hydro-click-hmac="1b08cd4b521eeae2d9e531494cb100b4d8a05dc81bcb6d9dbc9f42cf00c93e1b" data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">        <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
        Unstar
</button>        <a class="social-count js-social-count" href="/mechanator/ArQmA-GUI-wallet-guide/stargazers"
           aria-label="0 users starred this repository">
          0
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="unstarred js-social-form" action="/mechanator/ArQmA-GUI-wallet-guide/star" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="I/aG1CJanBkOlNBurV2EsIlvm/GRsDGzoZ5bQ7QOUXLjGOk/1DJgt4rENTesZfG93RhykOf5/263KJAAzHfdPw==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Star mechanator/ArQmA-GUI-wallet-guide" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;STAR_BUTTON&quot;,&quot;repository_id&quot;:182302194,&quot;client_id&quot;:&quot;1293665596.1555791383&quot;,&quot;originating_request_id&quot;:&quot;FC01:57DC:F2625:1855C7:5CBDF48E&quot;,&quot;originating_url&quot;:&quot;https://github.com/mechanator/ArQmA-GUI-wallet-guide/blob/master/arqma-GUI-guide.md&quot;,&quot;referrer&quot;:&quot;https://github.com/mechanator/ArQmA-GUI-wallet-guide&quot;,&quot;user_id&quot;:40085316}}" data-hydro-click-hmac="9e2ae5ed05fe9f57a6def37b97f51481901046d58df6a3ee68199598d89f0472" data-ga-click="Repository, click star button, action:blob#show; text:Star">        <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
        Star
</button>        <a class="social-count js-social-count" href="/mechanator/ArQmA-GUI-wallet-guide/stargazers"
           aria-label="0 users starred this repository">
          0
        </a>
</form>  </div>

  </li>

  <li>
        <span class="btn btn-sm btn-with-count disabled tooltipped tooltipped-sw" aria-label="Cannot fork because you own this repository and are not a member of any organizations.">
          <svg class="octicon octicon-repo-forked v-align-text-bottom" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
          Fork
</span>
    <a href="/mechanator/ArQmA-GUI-wallet-guide/network/members" class="social-count"
       aria-label="0 users forked this repository">
      0
    </a>
  </li>
</ul>

      <h1 class="public ">
  <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a class="url fn" rel="author" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=40085316" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/mechanator">mechanator</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a data-pjax="#js-repo-pjax-container" href="/mechanator/ArQmA-GUI-wallet-guide">ArQmA-GUI-wallet-guide</a></strong>
  

</h1>

    </div>
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax container-lg p-responsive d-none d-lg-block"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
    aria-label="Repository"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a class="js-selected-navigation-item selected reponav-item" itemprop="url" data-hotkey="g c" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /mechanator/ArQmA-GUI-wallet-guide" href="/mechanator/ArQmA-GUI-wallet-guide">
      <svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" data-hotkey="g i" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /mechanator/ArQmA-GUI-wallet-guide/issues" href="/mechanator/ArQmA-GUI-wallet-guide/issues">
        <svg class="octicon octicon-issue-opened" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a data-hotkey="g p" itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /mechanator/ArQmA-GUI-wallet-guide/pulls" href="/mechanator/ArQmA-GUI-wallet-guide/pulls">
      <svg class="octicon octicon-git-pull-request" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>



    <a data-hotkey="g b" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /mechanator/ArQmA-GUI-wallet-guide/projects" href="/mechanator/ArQmA-GUI-wallet-guide/projects">
      <svg class="octicon octicon-project" viewBox="0 0 15 16" version="1.1" width="15" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      Projects
      <span class="Counter" >0</span>
</a>

    <a class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /mechanator/ArQmA-GUI-wallet-guide/wiki" href="/mechanator/ArQmA-GUI-wallet-guide/wiki">
      <svg class="octicon octicon-book" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg>
      Wiki
</a>
    <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse people alerts /mechanator/ArQmA-GUI-wallet-guide/pulse" href="/mechanator/ArQmA-GUI-wallet-guide/pulse">
      <svg class="octicon octicon-graph" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
      Insights
</a>
    <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_settings repo_branch_settings hooks integration_installations repo_keys_settings issue_template_editor /mechanator/ArQmA-GUI-wallet-guide/settings" href="/mechanator/ArQmA-GUI-wallet-guide/settings">
      <svg class="octicon octicon-gear" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 8.77v-1.6l-1.94-.64-.45-1.09.88-1.84-1.13-1.13-1.81.91-1.09-.45-.69-1.92h-1.6l-.63 1.94-1.11.45-1.84-.88-1.13 1.13.91 1.81-.45 1.09L0 7.23v1.59l1.94.64.45 1.09-.88 1.84 1.13 1.13 1.81-.91 1.09.45.69 1.92h1.59l.63-1.94 1.11-.45 1.84.88 1.13-1.13-.92-1.81.47-1.09L14 8.75v.02zM7 11c-1.66 0-3-1.34-3-3s1.34-3 3-3 3 1.34 3 3-1.34 3-3 3z"/></svg>
      Settings
</a>
</nav>

  <div class="reponav-wrapper reponav-small d-lg-none">
  <nav class="reponav js-reponav text-center no-wrap"
       itemscope
       itemtype="http://schema.org/BreadcrumbList">

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a class="js-selected-navigation-item selected reponav-item" itemprop="url" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /mechanator/ArQmA-GUI-wallet-guide" href="/mechanator/ArQmA-GUI-wallet-guide">
        <span itemprop="name">Code</span>
        <meta itemprop="position" content="1">
</a>    </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /mechanator/ArQmA-GUI-wallet-guide/issues" href="/mechanator/ArQmA-GUI-wallet-guide/issues">
          <span itemprop="name">Issues</span>
          <span class="Counter">0</span>
          <meta itemprop="position" content="2">
</a>      </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /mechanator/ArQmA-GUI-wallet-guide/pulls" href="/mechanator/ArQmA-GUI-wallet-guide/pulls">
        <span itemprop="name">Pull requests</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="3">
</a>    </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /mechanator/ArQmA-GUI-wallet-guide/projects" href="/mechanator/ArQmA-GUI-wallet-guide/projects">
          <span itemprop="name">Projects</span>
          <span class="Counter">0</span>
          <meta itemprop="position" content="4">
</a>      </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_wiki /mechanator/ArQmA-GUI-wallet-guide/wiki" href="/mechanator/ArQmA-GUI-wallet-guide/wiki">
          <span itemprop="name">Wiki</span>
          <meta itemprop="position" content="5">
</a>      </span>

      <a class="js-selected-navigation-item reponav-item" data-selected-links="pulse /mechanator/ArQmA-GUI-wallet-guide/pulse" href="/mechanator/ArQmA-GUI-wallet-guide/pulse">
        Pulse
</a>
      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="community /mechanator/ArQmA-GUI-wallet-guide/community" href="/mechanator/ArQmA-GUI-wallet-guide/community">
          Community
</a>      </span>

  </nav>
</div>


  </div>
<div class="container-lg new-discussion-timeline experiment-repo-nav  p-responsive">
  <div class="repository-content ">

    
    



  
    <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/mechanator/ArQmA-GUI-wallet-guide/blob/e4e10c19758d01b0a915c20bb615c4a52562c1bb/arqma-GUI-guide.md">Permalink</a>

    <!-- blob contrib key: blob_contributors:v21:6e627882e779c5d4082c25ef8788feb8 -->
      

    <div class="d-flex flex-items-start mb-3 flex-column flex-md-row">
      <span class="d-flex flex-justify-between width-full width-md-auto">
        
<details class="details-reset details-overlay select-menu branch-select-menu ">
  <summary class="btn btn-sm select-menu-button css-truncate"
           data-hotkey="w"
           
           title="Switch branches or tags">
    <i>Branch:</i>
    <span class="css-truncate-target">master</span>
  </summary>

  <details-menu class="select-menu-modal position-absolute" style="z-index: 99;" src="/mechanator/ArQmA-GUI-wallet-guide/ref-list/master/arqma-GUI-guide.md?source_action=show&amp;source_controller=blob" preload>
    <include-fragment class="select-menu-loading-overlay anim-pulse">
      <svg height="32" class="octicon octicon-octoface" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M14.7 5.34c.13-.32.55-1.59-.13-3.31 0 0-1.05-.33-3.44 1.3-1-.28-2.07-.32-3.13-.32s-2.13.04-3.13.32c-2.39-1.64-3.44-1.3-3.44-1.3-.68 1.72-.26 2.99-.13 3.31C.49 6.21 0 7.33 0 8.69 0 13.84 3.33 15 7.98 15S16 13.84 16 8.69c0-1.36-.49-2.48-1.3-3.35zM8 14.02c-3.3 0-5.98-.15-5.98-3.35 0-.76.38-1.48 1.02-2.07 1.07-.98 2.9-.46 4.96-.46 2.07 0 3.88-.52 4.96.46.65.59 1.02 1.3 1.02 2.07 0 3.19-2.68 3.35-5.98 3.35zM5.49 9.01c-.66 0-1.2.8-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.54-1.78-1.2-1.78zm5.02 0c-.66 0-1.2.79-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.53-1.78-1.2-1.78z"/></svg>
    </include-fragment>
  </details-menu>
</details>

        <div class="BtnGroup flex-shrink-0 d-md-none">
          <a href="/mechanator/ArQmA-GUI-wallet-guide/find/master"
                class="js-pjax-capture-input btn btn-sm BtnGroup-item"
                data-pjax
                data-hotkey="t">
            Find file
          </a>
          <clipboard-copy value="arqma-GUI-guide.md" class="btn btn-sm BtnGroup-item">
            Copy path
          </clipboard-copy>
        </div>
      </span>
      <h2 id="blob-path" class="breadcrumb flex-auto min-width-0 text-normal flex-md-self-center ml-md-2 mr-md-3 my-2 my-md-0">
        <span class="js-repo-root text-bold"><span class="js-path-segment"><a data-pjax="true" href="/mechanator/ArQmA-GUI-wallet-guide"><span>ArQmA-GUI-wallet-guide</span></a></span></span><span class="separator">/</span><strong class="final-path">arqma-GUI-guide.md</strong>
      </h2>

      <div class="BtnGroup flex-shrink-0 d-none d-md-inline-block">
        <a href="/mechanator/ArQmA-GUI-wallet-guide/find/master"
              class="js-pjax-capture-input btn btn-sm BtnGroup-item"
              data-pjax
              data-hotkey="t">
          Find file
        </a>
        <clipboard-copy value="arqma-GUI-guide.md" class="btn btn-sm BtnGroup-item">
          Copy path
        </clipboard-copy>
      </div>
    </div>



    
  <div class="Box Box--condensed d-flex flex-column flex-shrink-0">
      <div class="Box-body d-flex flex-justify-between bg-blue-light flex-column flex-md-row flex-items-start flex-md-items-center">
        <span class="pr-md-4 f6">
          <a rel="author" data-skip-pjax="true" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=40085316" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/mechanator"><img class="avatar" src="https://avatars0.githubusercontent.com/u/40085316?s=40&amp;v=4" width="20" height="20" alt="@mechanator" /></a>
          <a class="text-bold link-gray-dark lh-default v-align-middle" rel="author" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=40085316" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/mechanator">mechanator</a>
            <span class="lh-default v-align-middle">
              <a data-pjax="true" title="edited" class="link-gray" href="/mechanator/ArQmA-GUI-wallet-guide/commit/fe437f2d01cc032f8637bdbeb670fbdf12417b67">edited</a>
            </span>
        </span>
        <span class="d-inline-block flex-shrink-0 v-align-bottom f6 mt-2 mt-md-0">
          <a class="pr-2 text-mono link-gray" href="/mechanator/ArQmA-GUI-wallet-guide/commit/fe437f2d01cc032f8637bdbeb670fbdf12417b67" data-pjax>fe437f2</a>
          <relative-time datetime="2019-04-22T16:36:32Z">Apr 22, 2019</relative-time>
        </span>
      </div>

    <div class="Box-body d-flex flex-items-center flex-auto f6 border-bottom-0 flex-wrap" >
      <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark float-left mr-2" id="blob_contributors_box">
        <summary class="btn-link" aria-haspopup="dialog">
          <span><strong>1</strong> contributor</span>
        </summary>
        <details-dialog
          class="Box Box--overlay d-flex flex-column anim-fade-in fast"
          aria-label="Users who have contributed to this file"
          >
          <div class="Box-header">
            <button class="Box-btn-octicon btn-octicon float-right" type="button" aria-label="Close dialog" data-close-dialog>
              <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
            </button>
            <h3 class="Box-title">
              Users who have contributed to this file
            </h3>
          </div>
              <ul class="list-style-none overflow-auto">
    <li class="Box-row">
      <a class="link-gray-dark no-underline" href="/mechanator">
        <img class="avatar mr-1" alt="" src="https://avatars0.githubusercontent.com/u/40085316?s=40&amp;v=4" width="20" height="20" />
        mechanator
</a>    </li>
</ul>

        </details-dialog>
      </details>
    </div>
  </div>





    <div class="Box mt-3 position-relative">
      
<div class="Box-header py-2 d-flex flex-column flex-shrink-0 flex-md-row flex-md-items-center">

  <div class="text-mono f6 flex-auto pr-3 flex-order-2 flex-md-order-1 mt-2 mt-md-0">
      973 lines (793 sloc)
      <span class="file-info-divider"></span>
    40.9 KB
  </div>

  <div class="d-flex py-1 py-md-0 flex-auto flex-order-1 flex-md-order-2 flex-sm-grow-0 flex-justify-between">

    <div class="BtnGroup">
      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="/mechanator/ArQmA-GUI-wallet-guide/raw/master/arqma-GUI-guide.md">Raw</a>
        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="/mechanator/ArQmA-GUI-wallet-guide/blame/master/arqma-GUI-guide.md">Blame</a>
      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="/mechanator/ArQmA-GUI-wallet-guide/commits/master/arqma-GUI-guide.md">History</a>
    </div>


    <div>
            <a class="btn-octicon tooltipped tooltipped-nw hide-sm"
               href="x-github-client://openRepo/https://github.com/mechanator/ArQmA-GUI-wallet-guide?branch=master&amp;filepath=arqma-GUI-guide.md"
               aria-label="Open this file in GitHub Desktop"
               data-ga-click="Repository, open with desktop, type:windows">
                <svg class="octicon octicon-device-desktop" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
            </a>

            <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form js-update-url-with-hash" action="/mechanator/ArQmA-GUI-wallet-guide/edit/master/arqma-GUI-guide.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="r8YzlQV39lV/9To8bWsB3lBWCLcJqJNFw5aCqR0lhv/e+iC+MhwVy3o/9y/rTlUwFA+eFykoDqnN6239WOC1pw==" />
              <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
                aria-label="Edit this file" data-hotkey="e" data-disable-with>
                <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
              </button>
</form>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form" action="/mechanator/ArQmA-GUI-wallet-guide/delete/master/arqma-GUI-guide.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="HG2avL+HFG9YHZpD2L2aa3FhkQRrqHnq/hdL0yZCSG2+wSHX+U1AeQTDkTNwZAf14kM0GFYbhVO0etaqGDfnJg==" />
            <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
              aria-label="Delete this file" data-disable-with>
              <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
            </button>
</form>    </div>
  </div>
</div>

      
  <div id="readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-3 p-md-6" itemprop="text"><ul>
<li><a href="#preface">Preface</a>
<ul>
<li><a href="#translations">Translations</a></li>
<li><a href="#windows-preparation">Windows Preparation</a></li>
<li><a href="#shortcuts">Shortcuts</a></li>
</ul>
</li>
<li><a href="#welcome">Welcome</a>
<ul>
<li><a href="#choose-a-language">Choose a Language</a></li>
<li><a href="#choose-wallet-mode">Choose wallet mode</a></li>
<li><a href="#about-the-simplebootstrap-mode">About the Simple/Bootstrap
mode</a></li>
</ul>
</li>
<li><a href="#create-a-wallet">Create a Wallet</a>
<ul>
<li><a href="#create-new-wallet">Create new wallet</a>
<ul>
<li><a href="#add-a-password">Add a password</a></li>
<li><a href="#daemon-settings-advanced-mode">Daemon settings
(Advanced mode)</a></li>
<li><a href="#run-a-full-node">Run a full node</a></li>
</ul>
</li>
<li><a href="#create-new-wallet-from-hardware">Create new wallet from
hardware</a>
<ul>
<li><a href="#create-the-wallet">Create the wallet</a></li>
<li><a href="#add-a-password-1">Add a password</a></li>
<li><a href="#daemon-settings-advanced-mode-1">Daemon settings
(Advanced mode)</a></li>
<li><a href="#run-a-full-node-1">Run a full node</a></li>
</ul>
</li>
<li><a href="#restore-wallet-from-keys-or-mnemonic-seed">Restore wallet from keys or mnemonic
seed</a>
<ul>
<li><a href="#restoring-from-seed">Restoring from seed</a></li>
<li><a href="#restoring-from-keys">Restoring from keys</a></li>
</ul>
</li>
<li><a href="#open-a-wallet-from-file">Open a wallet from file</a></li>
</ul>
</li>
<li><a href="#ArQmA-account">ArQmA Account</a></li>
<li><a href="#send-ArQmA">Send ArQmA</a>
<ul>
<li><a href="#address-book">Address Book</a></li>
</ul>
</li>
<li><a href="#receive-ArQmA">Receive ArQmA</a>
<ul>
<li><a href="#merchant-view">Merchant view</a></li>
</ul>
</li>
<li><a href="#transaction-history">Transaction History</a></li>
<li><a href="#advanced-features">Advanced Features</a>
<ul>
<li><a href="#solo-mining">Solo mining</a></li>
<li><a href="#prove---check">Prove - Check</a>
<ul>
<li><a href="#prove-transaction">Prove Transaction</a></li>
<li><a href="#check-transaction">Check Transaction</a></li>
</ul>
</li>
<li><a href="#shared-ringdb">Shared RingDB</a></li>
<li><a href="#sign---verify-message">Sign - verify Message</a>
<ul>
<li><a href="#sign">Sign</a></li>
<li><a href="#verify">Verify</a></li>
</ul>
</li>
<li><a href="#sign---verify-file">Sign - verify File</a>
<ul>
<li><a href="#sign-1">Sign</a></li>
<li><a href="#verify-1">Verify</a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#settings">Settings</a>
<ul>
<li><a href="#wallet">Wallet</a></li>
<li><a href="#layout">Layout</a></li>
<li><a href="#local-node">Local Node</a></li>
<li><a href="#remote-node">Remote Node</a></li>
<li><a href="#log">Log</a></li>
<li><a href="#info">Info</a></li>
<li><a href="#seed-and-keys">Seed and keys</a></li>
</ul>
</li>
<li><a href="#binaries-verification">Binaries Verification</a></li>
<li><a href="#about-remote-nodes">About remote nodes</a>
<ul>
<li><a href="#bootstrap-nodes">Bootstrap nodes</a></li>
</ul>
</li>
<li><a href="#common-issues-and-solutions">Common issues and solutions</a></li>
</ul>
<h1><a id="user-content-preface" class="anchor" aria-hidden="true" href="#preface"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/monero-logo-1280.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/monero-logo-1280.png" alt="ArQmA_logo" style="max-width:100%;"></a>
Preface</h1>
<p>This guide is open source and maintained by Argonator, of the ArQmA
community. If you have suggestions or wish to contribute to the
development of this guide, feel free to open Pull Requests or Issues on
the GitHub repository where this document is maintained:
<a href="https://github.com/arqma/arqma.github.io/ArQmA-GUI-guide">github.com/arqma/arqma.github.io/ArQmA-GUI-guide</a>.
 </p>
<p>For the online version of this guide, click
<a href="https://github.com/arqma/arqma.github.io/ArQmA-GUI-guide/blob/master/ArQmA-GUI-guide.md">here</a></p>
<h2><a id="user-content-translations" class="anchor" aria-hidden="true" href="#translations"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Translations</h2>
<p>This document will be localized into several languages. You can find all
available translations in the <a href="https://github.com/arqma/arqma.github.io/ArQmA-GUI-guide/tree/master/translations">dedicated section on
GitHub</a>.</p>
<h2><a id="user-content-windows-preparation" class="anchor" aria-hidden="true" href="#windows-preparation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows Preparation</h2>
<p>If you are on Windows:</p>
<ul>
<li>Make sure that your antivirus does not block the program.</li>
</ul>
<p>A miner is included in the ArQmA GUI software and, as a result, most
anti virus software flags the ArQmA GUI files as malware and
subsequently quarantines them. Fortunately, however, there's a fairly
trivial work around you can use. That is:</p>
<ul>
<li>Create a new directory / folder.</li>
<li>Open your AV software.</li>
<li>Add an exception for the newly created directory / folder. Put
differently, you have to whitelist the newly created directory
/ folder.</li>
<li>Extract the .zip file (in case of Windows) or the .tar.bz2 file (in
case of Linux or Mac OS X) to the whitelisted directory / folder.</li>
</ul>
<p><em>Note:</em> if you're using Windows and did not install custom anti virus
software, Windows Defender is, most likely, acting as active anti virus
software.</p>
<ul>
<li>The first time you start the wallet you must give permission to
connect to the network via a pop-up. Check the appropriate boxes and
click <code>Allow access</code>.</li>
</ul>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/win-firewall-check.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/win-firewall-check.png" alt="win firewall check" style="max-width:100%;"></a></p>
<h2><a id="user-content-shortcuts" class="anchor" aria-hidden="true" href="#shortcuts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Shortcuts</h2>
<p>Some shortcuts are available to make the user experience with the GUI
easier:  </p>
<p><strong>On all operating systems:</strong><br>
Press <code>Ctrl</code> to view each page shortcut. Press <code>ctrl+"shortcut"</code> to go
to that page  </p>
<p><strong>On Linux/Windows:</strong><br>
<code>ctrl + tab</code> -&gt; go to the next page<br>
<code>ctrl + shift + tab</code> -&gt; go to the previous page  </p>
<p><strong>On macOS:</strong><br>
<code>cmd + tab</code> -&gt; go to the next page<br>
<code>cmd + shift + tab</code> -&gt; go to the previous page</p>
<h1><a id="user-content-welcome" class="anchor" aria-hidden="true" href="#welcome"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Welcome</h1>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/wizard_0-welcome.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/wizard_0-welcome.png" alt="Welcome" style="max-width:100%;"></a></p>
<p>Extract the package and click on <code>ArQmA-wallet-gui</code>.</p>
<p>Welcome to ArQmA GUI Wallet.</p>
<p>(1) <strong>Language:</strong> Click here to see a list of available languages.<br>
(2) <strong>Continue:</strong> If you are satisfied with the current language,
continue to the next screen.</p>
<h2><a id="user-content-choose-a-language" class="anchor" aria-hidden="true" href="#choose-a-language"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Choose a Language</h2>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/wizard_1-lang.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/wizard_1-lang.png" alt="Language" style="max-width:100%;"></a></p>
<p>You'll see a list of available languages, click on the one of your
choice to change it and continue from the welcome screen. <em>Note:</em> You
will be able to change the language later by clicking on the <em>flag</em> in
the upper-left corner.</p>
<p>(1) <strong>Close:</strong> Cancel and return to the previous screen.</p>
<h2><a id="user-content-choose-wallet-mode" class="anchor" aria-hidden="true" href="#choose-wallet-mode"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Choose wallet mode</h2>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/wizard_1_1-mode.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/wizard_1_1-mode.png" alt="mode" style="max-width:100%;"></a></p>
<p>This page lets you choose the mode that best suits your accessibility
and privacy needs.<br>
<em>Note:</em> Stagenet and Testnnet only supports <em>Advanced mode</em>.</p>
<p>(1) <strong>Simple mode:</strong> This mode will connect your wallet to a
remote node. Please note that remote nodes may weaken your privacy.
Choose this if you have low privacy requirement, need to quickly
access the ArQmA network, and only intend to manage small amount of
ArQmA.<br>
(2) <strong>Simple mode (bootstrap):</strong> This mode is similar to the previous
one, as it will connect you to a remote node, but will download the
blockchain to your local drive in the background. As soon as you
have a local copy of the entire blockchain, you will be connected to
your local node. It allows you to start using ArQmA immediately and
have a fallback option if your local blockchain needs to sync new
blocks while offering the privacy benefits of a full node when fully
synced.<br>
(3) <strong>Advanced mode:</strong> Using this mode will let you run a full node,
which downloads and maintains an entire copy of the blockchain. Your
wallet will not be usable until your local copy of the blockchain is
fully synchronized. Choose this mode if the maximum privacy matters
to you.<br>
(4) <strong>Change language:</strong> This will let you choose the language from the
startup page (again).</p>
<h2><a id="user-content-about-the-simplebootstrap-mode" class="anchor" aria-hidden="true" href="#about-the-simplebootstrap-mode"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>About the Simple/Bootstrap mode</h2>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/wizard_1_2-warning.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/wizard_1_2-warning.png" alt="acknowledgement" style="max-width:100%;"></a></p>
<p>Upon choosing simple mode or bootstrap mode, an acknowledgement page
will be shown, explaining the features, behavior, and privacy
constraints of the mode.<br>
Please carefully read those informations before accepting the
implications of this mode and proceed to the next step.<br>
You must understand the inherent risks of using a remote node for your
privacy, and you should avoid using it with large amounts of money. If
you connect to a <em>malicious</em> remote node, it could track your IP
address, your "restore height" and associated block request data, and
send you inaccurate information to learn more about transactions you
make.</p>
<p>(1) <strong>Region:</strong> Choose a region to pick up the remote nodes from. The
closer the node is, the better the wallet performance will be.<br>
(2) <strong>Acknowledgement:</strong> Check This box if you have <strong>fully understood</strong>
the privacy implications of a remote node and agree to <strong>weaken your
privacy</strong> by using it.</p>
<h1><a id="user-content-create-a-wallet" class="anchor" aria-hidden="true" href="#create-a-wallet"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Create a Wallet</h1>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/wizard_2-options.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/wizard_2-options.png" alt="welcome" style="max-width:100%;"></a></p>
<p>On this page you can choose how to connect to the wallet and to the
network:</p>
<p>(1) <strong>Create a new wallet:</strong> Start the procedure to make a new wallet.
Choose this option if this is your first time using ArQmA.<br>
(2) <strong>Create new wallet from hardware:</strong> Create a new wallet from an
hardware device (like Ledger or Trezor)<br>
(3) <strong>Open a wallet from file:</strong> Choose this option to select a
pre-existing wallet from your files with the extension <code>.keys</code>.<br>
(4) <strong>Restore wallet from keys or mnemonic seed:</strong> Click here if you
want to recover a pre-existing wallet using the mnemonic seed or the
keys.<br>
(5) <strong>Change wallet mode:</strong> Click here to switch between modes and
choose the wallet mode that best fits your needs.<br>
(6) <strong>Mainnet:</strong> <em>Advanced:</em> Select this from the dropdown list to use
the main ArQmA network<br>
(7) <strong>Testnet:</strong> <em>Advanced:</em> Select this from the dropdown list if you
would like to use a development network instead of the main network.
Testnet is designed to let developers test new features that are not
available on Mainnet or Stagenet.<br>
(8) <strong>Stagenet:</strong> <em>Advanced:</em> Select this from the dropdown list if you
would like to use a network for staging instead of the main network.
Stagenet mimics the features of Mainnet and is designed to let end
users test ArQmA without the risk of losing funds.<br>
(9) <strong>Number of KDF rounds:</strong> <em>Advanced:</em> Adjust the number of Key
Derivation Function rounds in order to enhance the overall security
of the generated keys. Any random large number will increase
the security.</p>
<h2><a id="user-content-create-new-wallet" class="anchor" aria-hidden="true" href="#create-new-wallet"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Create new wallet</h2>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/wizard_3-create.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/wizard_3-create.png" alt="new" style="max-width:100%;"></a></p>
<p>Here you can create a new wallet:</p>
<p>(1) <strong>Wallet name:</strong> Give a name for your wallet (in this example
<code>testname</code> is used).<br>
(2) <strong>Mnemonic seed: Write down your <a href="https://getmonero.org/resources/moneropedia/mnemonicseed.html" rel="nofollow">mnemonic
seed</a>
and keep it safe. Your seed is the master key of your wallet, you
can use it to recover your funds.</strong><br>
(3) <strong>Wallet location:</strong> Select the destination folder of the wallet.</p>
<h3><a id="user-content-add-a-password" class="anchor" aria-hidden="true" href="#add-a-password"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Add a password</h3>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/wizard_4-pass.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/wizard_4-pass.png" alt="add password" style="max-width:100%;"></a></p>
<p>Add a strong password to protect your wallet. If you lose your password,
then only your mnemonic seed can recover your wallet.</p>
<h3><a id="user-content-daemon-settings-advanced-mode" class="anchor" aria-hidden="true" href="#daemon-settings-advanced-mode"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Daemon settings (Advanced mode)</h3>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/wizard_5-daemon-settings.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/wizard_5-daemon-settings.png" alt="daemon settings" style="max-width:100%;"></a></p>
<p>Here you can choose if you are going to run a full node or use a remote
one:</p>
<p>(1) <strong>Start node in background:</strong> Check this box to run a full node and
begin blockchain sync.<br>
(2) <strong>Blockchain location (optional):</strong> To store the blockchain
somewhere other than default, enter that location here.<br>
(3) <strong>Bootstrap node:</strong> To use a bootstrap node enter the host and port.
A bootstrap node allows you to use your wallet while you are
downloading the blockchain by connecting to a remote node. For a
list of available remote nodes and info about them, check the <a href="#about-remote-nodes">About
remote nodes</a> section of this guide.<br>
(4) <strong>Connect to a remote node:</strong> Check this box if you want to use only
a remote node without downloading the blockchain. You will need to
put the host and port of the remote node after checking the box.</p>
<h3><a id="user-content-run-a-full-node" class="anchor" aria-hidden="true" href="#run-a-full-node"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Run a full node</h3>
<p>Upon completion of the setup you will be prompted to the settings menu,
but first you will see a window like this pop up:</p>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/daemon-launch.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/daemon-launch.png" alt="sync" style="max-width:100%;"></a></p>
<p>If you want to create a normal wallet using your personal full node, you
don't need to do anything, let the countdown finish, then wait until
your node is fully synced.<br>
If you need some special settings, like setting up a view-only wallet or
adding the blockchain manually, go to <a href="#settings">Settings</a>.</p>
<h2><a id="user-content-create-new-wallet-from-hardware" class="anchor" aria-hidden="true" href="#create-new-wallet-from-hardware"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Create new wallet from hardware</h2>
<h3><a id="user-content-create-the-wallet" class="anchor" aria-hidden="true" href="#create-the-wallet"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Create the wallet</h3>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/create_hardware_wallet.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/create_hardware_wallet.png" alt="2.4.1" style="max-width:100%;"></a></p>
<p>(1) <strong>Wallet name:</strong> Give a name for your wallet (in this example
<code>ledger-test</code> is used).<br>
(2) <strong>Wallet location:</strong> Select the destination folder of the wallet.<br>
(3) <strong>Create a new wallet from device:</strong> Select this option if this is
the first time you use a hardware wallet.<br>
(4) <strong>Restore a wallet from device:</strong> Choose this option if you already
had a hardware wallet and want to restore it.<br>
<strong>Creation Date or Restore height (optional):</strong> <em>Restore only:</em> If
you know the date or block height that your wallet was created at,
you can specify it here so the wallet doesn't have to scan the
entire blockchain looking for your funds. For example, if your first
transaction was included on <code>2017-07-08</code> in block <code>1350000</code>, you
should put the previous day date (e.g. <code>2017-07-06</code>) or a slightly
lower height (e.g. <code>1330000</code>) so the wallet will start scanning from
there, saving you some time. More information about restore height
on
<a href="https://monero.stackexchange.com/questions/7581/what-is-the-relevance-of-the-restore-height" rel="nofollow">StackExchange</a>.<br>
(5) <strong>Subaddress lookahead (optional):</strong> pregenerate a number of
accounts with a number of subaddresses each.<br>
(6) <strong>Device name:</strong> Select the hardware wallet you want to use.<br>
 </p>
<p>Step by step guide on how to generate a Ledger wallet with the ArQmA
GUI for all operating systems (StackExchange):<br>
<a href="https://monero.stackexchange.com/questions/9901/how-do-i-generate-a-ledger-monero-wallet-with-the-gui-monero-wallet-gui" rel="nofollow">How do I generate a Ledger ArQmA wallet with the GUI
(monero-wallet-gui)?</a></p>
<h3><a id="user-content-add-a-password-1" class="anchor" aria-hidden="true" href="#add-a-password-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Add a password</h3>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/wizard_4-pass.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/wizard_4-pass.png" alt="add password" style="max-width:100%;"></a></p>
<p>Add a strong password to protect your wallet. If you lose your password,
then only your mnemonic seed can recover your wallet.</p>
<h3><a id="user-content-daemon-settings-advanced-mode-1" class="anchor" aria-hidden="true" href="#daemon-settings-advanced-mode-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Daemon settings (Advanced mode)</h3>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/wizard_5-daemon-settings.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/wizard_5-daemon-settings.png" alt="daemon settings" style="max-width:100%;"></a></p>
<p>Here you can choose if you are going to run a full node or use a remote
one:</p>
<p>(1) <strong>Start node in background:</strong> Check this box to run a full node and
begin blockchain sync.<br>
(2) <strong>Blockchain location (optional):</strong> To store the blockchain
somewhere other than default, enter that location here.<br>
(3) <strong>Bootstrap node:</strong> To use a bootstrap node enter the host and port.
A bootstrap node allows you to use your wallet while you are
downloading the blockchain by connecting to a remote node. For a
list of available remote nodes and info about them, check the <a href="#about-remote-nodes">About
remote nodes</a> section of this guide.<br>
(4) <strong>Connect to a remote node:</strong> Check this box if you want to use only
a remote node without downloading the blockchain. You will need to
put the host and port of the remote node after checking the box.</p>
<h3><a id="user-content-run-a-full-node-1" class="anchor" aria-hidden="true" href="#run-a-full-node-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Run a full node</h3>
<p>Upon completion of the setup you will be prompted to the settings menu,
but first you will see a window like this pop up:</p>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/daemon-launch.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/daemon-launch.png" alt="sync" style="max-width:100%;"></a></p>
<p>If you want to create a normal wallet using your personal full node, you
don't need to do anything, let the countdown finish, then wait until
your node is fully synced.<br>
If you need some special settings, like setting up a view-only wallet or
adding the blockchain manually, go to <a href="#settings">Settings</a>.</p>
<h2><a id="user-content-restore-wallet-from-keys-or-mnemonic-seed" class="anchor" aria-hidden="true" href="#restore-wallet-from-keys-or-mnemonic-seed"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Restore wallet from keys or mnemonic seed</h2>
<h3><a id="user-content-restoring-from-seed" class="anchor" aria-hidden="true" href="#restoring-from-seed"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Restoring from seed</h3>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/wizard_6-restore-seed.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/wizard_6-restore-seed.png" alt="restore from seed" style="max-width:100%;"></a></p>
<p>Restoring from your mnemonic seed is the easiest way to recover your
wallet. You need to put the following information:</p>
<p>(1) <strong>Wallet name:</strong> Give a name for your wallet (in this example
<code>testname</code> is used).<br>
(2) <strong>Mnemonic seed:</strong> Paste your seed made of 25 (or 24) words.<br>
(3) <strong>Creation Date or Restore height (optional):</strong> If you know the date
or block height that your wallet was created at, you can specify it
here so the wallet doesn't have to scan the entire blockchain
looking for your funds. For example, if your first transaction was
included on <code>2017-07-08</code> in block <code>1350000</code>, you should put the
previous day date (e.g. <code>2017-07-06</code>) or a slightly lower
height (e.g. <code>1330000</code>) so the wallet will start scanning from
there, saving you some time. More information about restore height
on
<a href="https://monero.stackexchange.com/questions/7581/what-is-the-relevance-of-the-restore-height" rel="nofollow">StackExchange</a>.<br>
(4) <strong>Wallet location:</strong> Select the destination folder of the wallet.</p>
<p>A detailed guide is available on getmonero.org: <a href="https://getmonero.org/resources/user-guides/restore_account.html" rel="nofollow">'How to restore your
account'</a></p>
<h3><a id="user-content-restoring-from-keys" class="anchor" aria-hidden="true" href="#restoring-from-keys"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Restoring from keys</h3>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/wizard_7-restore-keys.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/wizard_7-restore-keys.png" alt="restore from key" style="max-width:100%;"></a></p>
<p>Restoring from keys is quite easy and can be extremely useful,
especially if you are moving your wallet from an online service like
myarqma. You need to put the following information:</p>
<p>(1) <strong>Wallet name:</strong> Give a name for your wallet (in this example
<code>testname</code> is used).<br>
(2) <strong>Account address:</strong> The address of the wallet you are recovering.<br>
(3) <strong>View key:</strong> Your private view key (needed to be able to check your
funds).<br>
(4) <strong>Spend key:</strong> Your private spend key (needed to spend your funds).<br>
(5) <strong>Creation Date or Restore height (optional):</strong> If you know the date
or block height that your wallet was created at, you can specify it
here so the wallet doesn't have to scan the entire blockchain
looking for your funds. For example, if your first transaction was
included on <code>2017-07-08</code> in block <code>1350000</code>, you should put the
previous day date (e.g. <code>2017-07-06</code>) or a slightly lower
height (e.g. <code>1330000</code>) so the wallet will start scanning from
there, saving you some time. More information about restore height
on
<a href="https://monero.stackexchange.com/questions/7581/what-is-the-relevance-of-the-restore-height" rel="nofollow">StackExchange</a>.<br>
(6) <strong>Wallet location:</strong> Select the destination folder of the wallet.</p>
<p>When everything is ready click the right arrow and then the <code>Use ArQmA</code>
button.<br>
A detailed guide is available on getmonero.org: <a href="https://getmonero.org/resources/user-guides/restore_from_keys.html" rel="nofollow">'Restoring wallet from
keys'</a></p>
<h2><a id="user-content-open-a-wallet-from-file" class="anchor" aria-hidden="true" href="#open-a-wallet-from-file"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Open a wallet from file</h2>
<p>After clicking this option a window will pop up. Navigate to your file
with the extension <code>.keys</code>, select it and click the right arrow.</p>
<h1><a id="user-content-monero-account" class="anchor" aria-hidden="true" href="#monero-account"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Monero Account</h1>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_account.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_account.png" alt="account" style="max-width:100%;"></a></p>
<p>The <code>Account</code> tab provides tool to handle your different ArQmA accounts
within your wallet.</p>
<p>(1) <strong>Balance All:</strong> Let you see the sum of all your accounts balances,
unlocked or not.<br>
(2) <strong>Accounts:</strong> This is the list of accounts already generated on your
wallet.<br>
(3) <strong>Create new account:</strong> Click on this button to create a new account
and set its <em>optional</em> label.</p>
<p>You can change the current account by simply clicking on it on the
list.<br>
Each of your accounts are filled with their own informations:</p>
<p>(4) <strong>Label:</strong> A name or description of the account for convenience.<br>
(5) <strong>Address:</strong> The account primary address. <em>Note: Primary account
addresses and secondary account addresses have different heading
numbers</em><br>
(6) <strong>Balance:</strong> The account total balance. It cumulates the main
address and all subaddresses for this account. <em>Note: Subaddresses
are managend through the <a href="#send-monero">Send</a> screen</em><br>
(7) <strong>Set Label:</strong> Click on this button to set this account label.<br>
(8) <strong>Copy Address:</strong> Click on this button to copy this account address
to the clipboard</p>
<h1><a id="user-content-send-monero" class="anchor" aria-hidden="true" href="#send-monero"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Send Monero</h1>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_send.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_send.png" alt="send" style="max-width:100%;"></a></p>
<p>The <code>Send</code> tab provides tools for creating outgoing transactions.</p>
<p>(1) <strong>Amount:</strong> This is how much ArQmA you want to send.<br>
(2) <strong>Transaction priority:</strong> This is the priority level your
transaction will receive in the pool of transactions waiting to
be confirmed. The more you pay, the higher your transactions
priority for inclusion in a block.<br>
<em>Currently staying with the default or the slow option is likely to
get you into the next block.</em><br>
(3) <strong>Address:</strong> This is where you put the ArQmA address that you are
sending to. Best practice is to copy and paste the address to
prevent errors, accompanied with visually checking that the pasted
address is correct.<br>
(4) <strong>Payment ID (optional):</strong> The payment ID is an identifier attached
to the transaction you are about to send. Often when sending to an
exchange they will give you a payment ID that you must include here.
This is so they know which incoming transaction is from you.<br>
<em>If you forget to add your payment ID you should still be able to
recover your funds by contacting the party you sent ArQmA to.</em><br>
<em>Long payment IDs are being deprecated. It is hidden by default. If
you need to specify a long payment ID, you should enable it first on
the <a href="#layout">Settings &gt; Layout</a> tab. You should encourage
services to accept payments that need to be identified with unique
subaddresses instead</em><br>
(5) <strong>Description (optional):</strong> This is for your record keeping. You can
add some information regarding your transaction for future
reference.<br>
(6) <strong>Sweep unmixable:</strong> This allows you to get rid of outputs in your
wallet which have strange amounts like <code>0.000006839355</code>. These are
unmovable without combining them with another output.<br>
<em>Most users will never need to use this feature.</em><br>
(7) <strong>Sign tx file:</strong> This button allows you to sign a transaction file
that was created on a view-only wallet.<br>
(8) <strong>Export key images:</strong> This option will allow you to export your
key images. They are needed to get the true balance of a
view-only wallet.</p>
<h2><a id="user-content-address-book" class="anchor" aria-hidden="true" href="#address-book"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Address Book</h2>
<p>The <code>Address Book</code> tab lets you save addresses that you frequently
transact with. This is a convenient place to copy addresses from when
creating transactions.</p>
<h1><a id="user-content-receive-monero" class="anchor" aria-hidden="true" href="#receive-monero"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Receive Monero</h1>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_receive.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_receive.png" alt="receive" style="max-width:100%;"></a></p>
<p>The <code>Receive</code> tab provides tools for generating subaddresses.</p>
<p>(1) <strong>Addresses:</strong> This is a list of your primary address and
subaddresses.<br>
(2) <strong>Create new address:</strong> This button allows you to create
new subaddresses. You can create as many as you would like. <em>Learn
more about
<a href="https://monero.stackexchange.com/questions/3673/what-is-a-sub-address" rel="nofollow">subaddresses</a>.</em><br>
(3) <strong>Set Label:</strong> Click on this button to set this subaddress label.<br>
(4) <strong>QR code:</strong> This is a QR code that has your selected address
embedded into it. It can be used as a way to give others your ArQmA
address by scanning the code.<br>
(5) <strong>Save:</strong> Click here to save the QR code as a <code>png</code> image.<br>
(6) <strong>Copy:</strong> Click here to copy the QR code corresponding URL formated
as *monero:
</p>
-<p></p>
<h2><a id="user-content-merchant-view" class="anchor" aria-hidden="true" href="#merchant-view"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Merchant view</h2>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/merchant.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/merchant.png" alt="merchant" style="max-width:100%;"></a></p>
<p>The <code>Merchant</code> view is intending to offer professionals a nice app on
their points of sell. It let you craft payment requests, and monitor
incoming transactions</p>
<p>(1) <strong>QR code:</strong> This is a QR code that has your selected address, and
optionally the amount, embedded into it. It can be used as a way to
give others your ArQmA address by scanning the code.<br>
(2) <strong>Amount:</strong> This is for creating a payment request, enter the amount
of ArQnA you would like to receive.<br>
(3) <strong>Payment URL:</strong> This is the URL corresponding to the address and
amount you have chosen. It could be copied by clicking on it and
sent to a customer.<br>
(4) <strong>Tracking:</strong> If you tick this box, you'll see a list of incoming
transactions.<br>
(5) <strong>Incoming transaction:</strong> Those are the transaction currently seen
on the blockchain and the transaction pool, with
associated confirmations.</p>
<h1><a id="user-content-transaction-history" class="anchor" aria-hidden="true" href="#transaction-history"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Transaction History</h1>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_history.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_history.png" alt="history" style="max-width:100%;"></a></p>
<p>The <code>History</code> tab let you walk through the transactions sent and
received on your account.</p>
<p>(1) <strong>Export:</strong> This will create a CSV file of the record in a folder of
your choice.<br>
(2) <strong>Search:</strong> Quickly find a transaction using any field to look up
from.<br>
(3) <strong>Filters:</strong> You can choose to filter out the transaction between
specific dates. This can be useful if your wallet has tons of
transactions.<br>
(4) <strong>Sort:</strong> You can sort transaction by block height or date. <em>Those
methods are actually equivalent</em><br>
(5) <strong>Transaction list:</strong> Here are displayed your transactions on
this account. Each transaction is displayed with it's informations:
<code>Amount</code>, <code>Tx ID</code>, <code>Height</code>, <code>Date</code>, <code>Fee</code> (for outgoing
transactions), and <code>Description</code> <em>Optional</em>.<br>
(6) <strong>Set description:</strong> You can optionally click here to set a
description of your choice to this transaction.<br>
(7) <strong>Prove transaction:</strong> Clicking here will generate a payment proof
in case of a dispute. More details on proving payments can be found
<a href="https://getmonero.org/resources/user-guides/prove-payment.html" rel="nofollow">here</a>
<em>For outgoing transaction only</em><br>
(8) <strong>Details:</strong> Clicking here will show you the transaction details:
<code>Tx ID</code>, <code>Address Label</code>, <code>Address</code>, and <code>Payment ID</code>.</p>
<h1><a id="user-content-advanced-features" class="anchor" aria-hidden="true" href="#advanced-features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Advanced Features</h1>
<h2><a id="user-content-solo-mining" class="anchor" aria-hidden="true" href="#solo-mining"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Solo mining</h2>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_mining.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_mining.png" alt="mining" style="max-width:100%;"></a></p>
<p>The Mining tab provides a one click CPU miner that is embedded into the
GUI.</p>
<p>(1) <strong>CPU threads:</strong> Number of CPU threads to use for mining.<br>
(2) <strong>threads auto-configuration:</strong> Set automatically the number of
threads either to the recommended number, or to the max number.<br>
(3) <strong>Background mining:</strong> Check this box to enable experimental
background mining. This should allow you to use your computer
normally while mining.<br>
(4) <strong>Start mining:</strong> Start the miner.<br>
(5) <strong>Stop mining:</strong> Stop the miner.<br>
(6) <strong>Status:</strong> Indicates the mining state and hashrate.</p>
<h2><a id="user-content-prove---check" class="anchor" aria-hidden="true" href="#prove---check"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Prove - Check</h2>
<p>The <code>Prove/check</code> tab provides tools for proving a payment or validating
proof of a payment. This is necessary with ArQmA because these details
are not available on the blockchain.</p>
<h3><a id="user-content-prove-transaction" class="anchor" aria-hidden="true" href="#prove-transaction"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Prove Transaction</h3>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_prove.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_prove.png" alt="Prove payment" style="max-width:100%;"></a></p>
<p>This will generate a proof that you made a payment to a certain address.
You need to put the following information:</p>
<p>(1) <strong>Transaction ID:</strong> This is the ID of the payment you are creating
proof for. You can find the transaction details by selecting the
History tab from the left menu.<br>
(2) <strong>Address:</strong> This is the address you are proving payment to.<br>
(3) <strong>Message (optional):</strong> This an optional message that will be signed
with the transaction details. If you choose to include a message
then the other party must also include the exact same message in
order to verify your proof.<br>
(4) <strong>Generate:</strong> Click here once you've entered all the details to
generate your proof.  </p>
<p>A detailed guide is available on getmonero.org: <a href="https://getmonero.org/resources/user-guides/prove-payment.html" rel="nofollow">'How to prove
payment'</a></p>
<h3><a id="user-content-check-transaction" class="anchor" aria-hidden="true" href="#check-transaction"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Check Transaction</h3>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_check.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_check.png" alt="Check payment" style="max-width:100%;"></a></p>
<p>This will verify that a payment was made. You need to put the following
information:</p>
<p>(1) <strong>Transaction ID:</strong> This is the ID of the payment you are attempting
to verify.<br>
(2) <strong>Address:</strong> This is the receiving address of the payment you are
attempting to verify.<br>
(3) <strong>Message (optional):</strong> This is the optional message that may have
been included with the proof.<br>
(4) <strong>Signature:</strong> This is the signature generated to prove payment.<br>
(5) <strong>Check:</strong> Click here once you've entered all the details to check
that the transaction proof is valid.</p>
<h2><a id="user-content-shared-ringdb" class="anchor" aria-hidden="true" href="#shared-ringdb"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Shared RingDB</h2>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_sharedringdb.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_sharedringdb.png" alt="shared ringdb 1/2" style="max-width:100%;"></a></p>
<p>This is an advanced tool that can be used to improve the privacy of ring
signatures. The outputs used in ring signatures can be adapted to
mitigate the privacy loss when using a key-reusing fork or to avoid
outputs that could not be spent in this transaction.</p>
<p>(1) <strong>Mark as spent filename:</strong> This tool will mark outputs that are
known to be spent. After running
arqma-blockchain-mark-spent-outputs, import the resulting file to
avoid using these outputs as decoys in constructed ring signatures.
This file is stored in the .shared-ringdb folder by default.<br>
(2) <strong>Mark as spent output:</strong> This will mark or unmark as spent a chosen
single output. Outputs are represented by 64-character strings. The
outputs added in this field will not be used as decoys in
constructed ring signatures. Unmarked outputs may (but will
not necessarily) by used as decoys.</p>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_sharedringdb_2.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_sharedringdb_2.png" alt="shared ringdb 2/2" style="max-width:100%;"></a></p>
<p>(3) <strong>Key image input:</strong> Add the key image that was used on the
key-reusing fork.<br>
(4) <strong>Get ring:</strong> Press the "Get Ring" button to get the ring members
for the given key image in 3.<br>
(5) <strong>Set ring:</strong> Press the "Set Ring" button to set the ring members
for a transaction. Copy the ring members from 4 to get those for the
key image, or manually type in your own.<br>
(6) <strong>Intent to spend:</strong> Select this if you are certain that you will
spend ArQmA on a key-reusing fork. This will aggressively modify
the input selection algorithm to give you the greatest plausible
deniability.<br>
(7) <strong>Possibility to spend:</strong> Select this if you may spend ArQmA on a
key-reusing fork. This will modify the input selection algorithm.
Uncheck this only if you are certain you will not use a key-reusing
fork.<br>
(8) <strong>Relative:</strong> When selected, the offsets are encoded relative to the
previous, as opposed to absolute (transactions use relative
offsets).<br>
(9) <strong>Segregation height:</strong> The block height at which the key-reusing
fork splits.</p>
<h2><a id="user-content-sign---verify-message" class="anchor" aria-hidden="true" href="#sign---verify-message"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Sign - verify Message</h2>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_sign-verify.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_sign-verify.png" alt="sign/verify" style="max-width:100%;"></a></p>
<p>The <code>Sign/verify</code> tab provides tools for signing a message or file with
your private key or verifying the authenticity of a singed message or
file.</p>
<h3><a id="user-content-sign" class="anchor" aria-hidden="true" href="#sign"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Sign</h3>
<p>(1) <strong>Message:</strong> This is where you can enter a message to be signed.<br>
(2) <strong>Signature:</strong> This is where your unique signature will appear once
you click the Sign button. This is linked to your private key and
the message you entered. It will be given as proof along with the
message which was signed.</p>
<h3><a id="user-content-verify" class="anchor" aria-hidden="true" href="#verify"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Verify</h3>
<p>(3) <strong>Verify message:</strong> This is where you will put a message that has
been signed.<br>
(4) <strong>Address:</strong> This is where you will enter the public ArQmA address
of the signer.<br>
(5) <strong>Signature:</strong> This is where you will enter the signature you
are verifying. Once all the required information has been entered
click the Verify button. A pop-up will tell you if the signature
is valid.</p>
<h2><a id="user-content-sign---verify-file" class="anchor" aria-hidden="true" href="#sign---verify-file"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Sign - verify File</h2>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_sign-verify-file.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_sign-verify-file.png" alt="sign/verify" style="max-width:100%;"></a></p>
<p>The <code>Sign/verify</code> tab provides tools for signing a message or file with
your private key or verifying the authenticity of a singed message or
file.</p>
<h3><a id="user-content-sign-1" class="anchor" aria-hidden="true" href="#sign-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Sign</h3>
<p>(1) <strong>File:</strong> This is where you can choose a file to be signed. Click
Browse to navigate the file system.<br>
(2) <strong>Signature:</strong> This is where your unique signature will appear once
you click the Sign button. This is linked to your private key and
the file you entered. It will be given as proof along with the file
which was signed.</p>
<h3><a id="user-content-verify-1" class="anchor" aria-hidden="true" href="#verify-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Verify</h3>
<p>(3) <strong>File:</strong> This is where you enter the path to a file that has
been signed. Click Browse to navigate the file system.<br>
(4) <strong>Address:</strong> This is where you will enter the public ArQmA address
of the signer.<br>
(5) <strong>Signature:</strong> This is where you will enter the signature you
are verifying. Once all the required information has been entered
click the Verify button. A pop-up will tell you if the signature
is valid.</p>
<h1><a id="user-content-settings" class="anchor" aria-hidden="true" href="#settings"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Settings</h1>
<p>The <code>Settings</code> tab provides tools for customizing configuration options.</p>
<h3><a id="user-content-wallet" class="anchor" aria-hidden="true" href="#wallet"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Wallet</h3>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_settings-wallet.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_settings-wallet.png" alt="settings-wallet" style="max-width:100%;"></a></p>
<p>(1) <strong>Close this wallet:</strong> Click here to safely close the current
wallet<br>
(2) <strong>Create a view-only wallet:</strong> Click here to generate a view-only
(or audit) wallet, which is capable to see existing outgoing
transactions and all incoming transactions. See this
<a href="https://getmonero.org/resources/user-guides/view_only.html" rel="nofollow">user-guide</a>
for more information.<br>
(3) <strong>Show seed &amp; keys:</strong> This button will redirect you to the <a href="#seed-and-keys">Seed and
keys</a> tab.<br>
(4) <strong>Rescan wallet balance:</strong> Click here to rescan the blockchain for
all the transaction. <em>Note: You will lose any information not stored
on the blockchain (this includes destination addresses, tx secret
keys, tx notes, etc.)</em><br>
(5) <strong>Change wallet password:</strong> Click here to change your password.</p>
<h3><a id="user-content-layout" class="anchor" aria-hidden="true" href="#layout"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Layout</h3>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_settings-layout.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_settings-layout.png" alt="settings_layout" style="max-width:100%;"></a></p>
<p>The <code>layout</code> tab is where you can adjust the settings of the GUI wallet.
The most important options are:</p>
<p>(1) <strong>Hide balance:</strong> If you are running your wallet in public, you may
want to hide its balance. This can be useful for point of sales
systems.<br>
(2) <strong>Enable Payment ID:</strong> Long payment IDs are disabled by default.
Click here to enable it. This can be useful for transfers to
exchanges that require a long payment ID such as Binance (at the
time of writing). Using long payment IDs is detrimental to
your privacy. Please ask services that still use this deprecated
feature to use subaddresses instead.<br>
(3) <strong>Lock wallet:</strong> Set this to automatically lock your wallet after N
minutes of inactivity. This ensures no one is able to use your
wallet while you are away from keyboard.</p>
<h3><a id="user-content-local-node" class="anchor" aria-hidden="true" href="#local-node"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Local Node</h3>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_settings-node-local_node.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_settings-node-local_node.png" alt="settings_local-node" style="max-width:100%;"></a></p>
<p>(1) <strong>Start/Stop Local Node:</strong> Depending on its current state, either
start or stop the local node.<br>
(2) <strong>Blockchain location:</strong> Manually enter a non-default path to the
blockchain, or click <code>change</code> to choose a new path.<br>
(3) <strong>Startup flags:</strong> When using a local node, this will be where you
enter additional command line options.<br>
(4) <strong>Bootstrap Address:</strong> Enter the hostname or IP address of the
bootstrap remote node. See section <a href="#bootstrap-nodes">Bootstrap
nodes</a> for a brief explanation of what a bootstrap
node is.<br>
(5) <strong>Bootstrap Port:</strong> Enter the port of the bootstrap remote node.</p>
<h3><a id="user-content-remote-node" class="anchor" aria-hidden="true" href="#remote-node"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Remote Node</h3>
<p>Use a remote node, do not download the blockchain. Check the <a href="#about-remote-nodes">'About
remote nodes' section</a> of this guide.</p>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_settings-node-remote_node.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_settings-node-remote_node.png" alt="settings_remote-node" style="max-width:100%;"></a></p>
<p>(1) <strong>Address:</strong> Enter the hostname or IP address of the remote node.<br>
(2) <strong>Port:</strong> Enter the port of the remote node.<br>
(3) <strong>Daemon Username:</strong> enter a username in case authentication to the
remote node is required.<br>
(4) <strong>Daemon Password:</strong> enter a password in case authentication to the
remote node is required.<br>
(5) <strong>Trusted Daemon:</strong> By default, data requests to remote nodes are
obfuscated, and this process requires more resources. If your remote
node is under your control (i.e. a dedicated server of your own) you
can mark it trusted so that data requests will not be obfuscated
anymore (just like a local node).</p>
<h3><a id="user-content-log" class="anchor" aria-hidden="true" href="#log"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Log</h3>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_settings-log.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_settings-log.png" alt="settings-log" style="max-width:100%;"></a></p>
<p>(1) <strong>Log level:</strong> Change the verbosity of the debug logs.<br>
(2) <strong>Log categories:</strong> Add specific categories to the debug logs.<br>
(3) <strong>Daemon log:</strong> Real time output of the log.<br>
(4) <strong>Command line:</strong> Interact with the daemon.</p>
<h3><a id="user-content-info" class="anchor" aria-hidden="true" href="#info"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Info</h3>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_settings-info.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_settings-info.png" alt="settings-info" style="max-width:100%;"></a></p>
<p>(1) <strong>GUI Version:</strong> Version of the GUI wallet installed.<br>
(2) <strong>Embedded ArQmA Version:</strong> Version of the embedded daemon in use.<br>
(3) <strong>Wallet path:</strong> Where the wallet is located on your computer.<br>
(4) <strong>Wallet creation height:</strong> Change the block height that a wallet
rescan will go back to.<br>
(5) <strong>Wallet log path:</strong> Where the logs for this wallet will be saved.<br>
(6) <strong>Wallet mode:</strong> Display the wallet mode chosen in the
<a href="#choose-wallet-mode">wizard</a>.<br>
(7) <strong>Copy to clipboard:</strong> Copy all information to clipboard.</p>
<h2><a id="user-content-seed-and-keys" class="anchor" aria-hidden="true" href="#seed-and-keys"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Seed and keys</h2>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_seed-keys.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_seed-keys.png" alt="seed-keys" style="max-width:100%;"></a></p>
<p>The <code>Seeds &amp; Keys</code> tab displays your wallets mnemonic seed as well as
your secret view key, public view key, secret spend key, and public
spend key.</p>
<p>(1) <strong>Mnemonic seed: DO NOT share your mnemonic seed with anyone. Store
a copy securely.</strong> The mnemonic seed is a 25 word phrase that
contains all the information needed to view and spend funds. <em>Learn
more about <a href="https://getmonero.org/resources/moneropedia/mnemonicseed.html" rel="nofollow">mnemonic
seeds</a>.</em><br>
(2) <strong>Secret view key:</strong> Secret view keys allows the holder to view your
wallets incoming transactions, but not outgoing. It is sometimes
useful for auditing purposes to give your secret view key to a third
party.<br>
(3) <strong>Public view key:</strong> The public view key is used for stealth
address creation. <em>Learn more about <a href="https://getmonero.org/resources/moneropedia/viewkey.html" rel="nofollow">view
keys</a>.</em><br>
(4) <strong>Secret spend key: DO NOT share your secret spend key with anyone.
The secret spend key is used to sign transactions and should be
regarded with the same security as your mnemonic seed.</strong><br>
(5) <strong>Public spend key:</strong> The public spend key is used by the network to
verify the signature of the key image you generate when you make
a transaction. This is what prevents double-spends as the network
enforces the rule that a key image can be spent only once. <em>Learn
more about <a href="https://getmonero.org/resources/moneropedia/spendkey.html" rel="nofollow">spend
keys</a>.</em></p>
<p><a target="_blank" rel="noopener noreferrer" href="/mechanator/ArQmA-GUI-wallet-guide/blob/master/media/black_seed-keys_2.png"><img src="/mechanator/ArQmA-GUI-wallet-guide/raw/master/media/black_seed-keys_2.png" alt="seed-keys" style="max-width:100%;"></a></p>
<p>(6) <strong>Export Spendable Wallet: DO NOT share your spendable wallet QR
code with anyone. This can be used like a mnemonic seed for
recovering your wallet.</strong> This creates a qrcode that contains all of
your keys.<br>
(7) <strong>Export View Only Wallet:</strong> This creates a QR code that contains
only the keys for viewing the transactions that this wallet sends or
receives, but cannot create transactions.</p>
<h1><a id="user-content-binaries-verification" class="anchor" aria-hidden="true" href="#binaries-verification"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Binaries Verification</h1>
<p>Verify that the files you downloaded match the official ones. You can
use <a href="https://getmonero.org/resources/user-guides/verification-windows-beginner.html" rel="nofollow">this step-by-step
guide</a>
with pictures (easy, for Windows user).</p>
<h1><a id="user-content-about-remote-nodes" class="anchor" aria-hidden="true" href="#about-remote-nodes"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>About remote nodes</h1>
<p>Remote nodes are useful if you are not able/don't want to download the
whole blockchain, but be advised that malicious remote nodes could
compromise some privacy. They may track your IP address, track your
"restore height" and associated block request data, and send you
inaccurate information to learn more about transactions you make. Please
make sure to use a node you trust (hopefully your own) and remain aware
of these limitations. Users who prioritize privacy should use a full
node instead. A number of open nodes are listed at
<a href="https://moneroworld.com" rel="nofollow">moneroworld.com</a> and
<a href="https://node.pwned.systems" rel="nofollow">node-o-matic</a></p>
<h2><a id="user-content-bootstrap-nodes" class="anchor" aria-hidden="true" href="#bootstrap-nodes"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Bootstrap nodes</h2>
<p>A bootstrap node is a remote node to use whilst also syncing the
blockchain. This is different than the remote node setting, since it
will only use the specified remote node until the blockchain is fully
synced locally. It is a reasonable tradeoff for most people who care
about privacy but also want the convenience of an automatic fallback
option. Be aware that when using remote nodes (including with the
bootstrap setting), nodes may track your IP address, track your "restore
height" and associated block request data, and send you inaccurate
information to learn more about transactions you make. Please make sure
to use a node you trust (hopefully your own) and remain aware of these
limitations. Keep the ArQmA full node software operating on your
computer even when you are not using the wallet to reduce the amount of
leaked data. More information at
<a href="https://getmonero.org/resources/moneropedia/bootstrap-node.html" rel="nofollow">https://getmonero.org/resources/moneropedia/bootstrap-node.html</a></p>
<h1><a id="user-content-common-issues-and-solutions" class="anchor" aria-hidden="true" href="#common-issues-and-solutions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Common issues and solutions</h1>
<ul>
<li><strong><a href="https://monero.stackexchange.com/questions/6640/i-am-missing-not-seeing-a-transaction-to-in-the-gui-zero-balance" rel="nofollow">I am missing (not seeing) a transaction to (in) the GUI
(zero balance)</a></strong></li>
<li><strong><a href="https://monero.stackexchange.com/questions/6825/i-am-using-the-gui-and-my-daemon-doesnt-start-anymore" rel="nofollow">I am using the GUI and my daemon doesn't start
anymore</a></strong></li>
<li><strong><a href="https://monero.stackexchange.com/questions/6649/transaction-stuck-as-pending-in-the-gui" rel="nofollow">Transaction stuck as “pending” in the
GUI</a></strong></li>
<li><strong><a href="https://monero.stackexchange.com/questions/6651/my-gui-feels-buggy-freezes-all-the-time" rel="nofollow">My GUI feels buggy / freezes all the
time</a></strong></li>
<li><strong><a href="https://monero.stackexchange.com/questions/6823/my-name-contains-a-special-non-ascii-character-e-g-%c3%a9-%c3%b8-%c3%a2-%c3%96-and-i-cant-c" rel="nofollow">My name contains a special (non-ASCII) character (e.g. é, ø,
â, Ö) and I can't create a wallet with the
GUI</a></strong></li>
<li><strong><a href="https://monero.stackexchange.com/questions/6653/the-gui-uses-all-my-bandwidth-and-i-cant-browse-anymore-or-use-another-applicat" rel="nofollow">The GUI uses all my bandwidth and I can't browse anymore or use
another application that requires internet
connection</a></strong></li>
<li><strong><a href="https://monero.stackexchange.com/questions/7225/how-do-i-move-the-blockchain-data-mdb-to-a-different-directory-during-or-afte" rel="nofollow">How do I move the blockchain (data.mdb) to a different directory
during (or after) the initial sync without losing the
progress?</a></strong></li>
<li><strong><a href="https://monero.stackexchange.com/questions/7373/how-do-i-change-the-language-of-the-25-word-mnemonic-seed-in-the-gui/" rel="nofollow">How do I change the language of the 25 word mnemonic seed in the
GUI or
CLI?</a></strong></li>
<li><strong><a href="https://monero.stackexchange.com/questions/4462/my-blockchain-is-stuck-how-do-i-unstuck-it" rel="nofollow">My blockchain is stuck, how do I “unstuck”
it?</a></strong></li>
<li><strong><a href="https://monero.stackexchange.com/questions/6324/using-remote-node-still-syncs-blockchain" rel="nofollow">I am using remote node, but the GUI still syncs
blockchain?</a></strong></li>
<li><strong>I use a high resolution display and the GUI looks extremely
small</strong><br>
This problem will be fixed soon, but there is a workaround for
Windows: right click on ArQmA-wallet-gui.exe, select properties
--&gt; compatibility. you'll find a 'high DPI' option, change value
there from "Application" to "System" or vice versa</li>
</ul>
</article>
  </div>

    </div>

  

  <details class="details-reset details-overlay details-overlay-dark">
    <summary data-hotkey="l" aria-label="Jump to line"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form Box-body d-flex" action="" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
        <button type="submit" class="btn" data-close-dialog>Go</button>
</form>    </details-dialog>
  </details>



  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </main>
  </div>
  

  </div>

        
<div class="footer container-lg width-full p-responsive" role="contentinfo">
  <div class="position-relative d-flex flex-row-reverse flex-lg-row flex-wrap flex-lg-nowrap flex-justify-center flex-lg-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap col-12 col-lg-6 flex-justify-center flex-lg-justify-start mb-2 mb-lg-0">
      <li class="mr-3">&copy; 2019 <span title="0.55032s from unicorn-695fd57cb6-fzg6r">GitHub</span>, Inc.</li>
        <li class="mr-3"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3"><a data-ga-click="Footer, go to security, text:security" href="https://github.com/security">Security</a></li>
        <li class="mr-3"><a href="https://githubstatus.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:help" href="https://help.github.com">Help</a></li>
    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon mx-lg-4" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap col-12 col-lg-6 flex-justify-center flex-lg-justify-end mb-2 mb-lg-0">
        <li class="mr-3"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
        <li class="mr-3"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
      <li class="mr-3"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
        <li class="mr-3"><a href="https://github.blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>

    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
    </button>
    You can’t perform that action at this time.
  </div>


    
    <script crossorigin="anonymous" integrity="sha512-4ogGmCoGByNTJS1EuaHWf5OW9jaaUimTV7C1yWJY2cewmcDQ2BxWQA6/AULidNxvYt3uagTFcU1CQsobKN01XQ==" type="application/javascript" src="https://github.githubassets.com/assets/frameworks-1f9870ed.js"></script>
    
    <script crossorigin="anonymous" async="async" integrity="sha512-ndUkGfxixq38E/uBsdXO4speen983F90aEEOnJrL67GsP+YOemia80Qo3NInrqoYqn5dDv5QpLvXcYlvUsyyTQ==" type="application/javascript" src="https://github.githubassets.com/assets/github-bootstrap-afe22710.js"></script>
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner" hidden
    >
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark" open>
    <summary aria-haspopup="dialog" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

  <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
  </div>
</div>

  <div aria-live="polite" class="js-global-screen-reader-notice sr-only"></div>

  </body>
</html>


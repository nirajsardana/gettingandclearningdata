



<!DOCTYPE html>
<html lang="en" class="">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>gettingandclearningdata/readMe.md at master · bfisseler/gettingandclearningdata</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="bfisseler/gettingandclearningdata" name="twitter:title" /><meta content="gettingandclearningdata - This repository contains the project of the course &amp;quot;Getting and Cleaning Data&amp;quot; on Coursera." name="twitter:description" /><meta content="https://avatars2.githubusercontent.com/u/3033970?v=2&amp;s=400" name="twitter:image:src" />
<meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars2.githubusercontent.com/u/3033970?v=2&amp;s=400" property="og:image" /><meta content="bfisseler/gettingandclearningdata" property="og:title" /><meta content="https://github.com/bfisseler/gettingandclearningdata" property="og:url" /><meta content="gettingandclearningdata - This repository contains the project of the course &quot;Getting and Cleaning Data&quot; on Coursera." property="og:description" />

      <meta name="browser-stats-url" content="/_stats">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="conduit-xhr" href="https://ghconduit.com:25035">
    <link rel="xhr-socket" href="/_sockets">
    <meta name="pjax-timeout" content="1000">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>
      <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="31CD4A09:6728:25291A1:544D301F" name="octolytics-dimension-request_id" /><meta content="8679180" name="octolytics-actor-id" /><meta content="nirajsardana" name="octolytics-actor-login" /><meta content="b040d9d4bd9fe845ebe5eadbb6c57040b4f005099b6442ed92f40ecbf1d9fb4b" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" name="analytics-event" />

    
    
    <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="M7nnhJMEIfaKB5stUWP9ITpW0HWptlCJwd9l5R4vYsMYzGDYdKux/z8HqfErv3cbAkSZSyK7aBhI0o4/kX9Jnw==" name="csrf-token" />

    <link href="https://assets-cdn.github.com/assets/github-fd24da028f7f2d737c9a6d97bdd8aa7a5d7ec419c4cc4e89b169d30c58bed96b.css" media="all" rel="stylesheet" type="text/css" />
    <link href="https://assets-cdn.github.com/assets/github2-e601e4dc2eec6decc441b9f7e15eec77891539a1a5e2d8af7af600d1d061a150.css" media="all" rel="stylesheet" type="text/css" />
    
    


    <meta http-equiv="x-pjax-version" content="e375408a179f2ef68cd4fb7efa2d26f7">

      
  <meta name="description" content="gettingandclearningdata - This repository contains the project of the course &quot;Getting and Cleaning Data&quot; on Coursera.">
  <meta name="go-import" content="github.com/bfisseler/gettingandclearningdata git https://github.com/bfisseler/gettingandclearningdata.git">

  <meta content="3033970" name="octolytics-dimension-user_id" /><meta content="bfisseler" name="octolytics-dimension-user_login" /><meta content="20094244" name="octolytics-dimension-repository_id" /><meta content="bfisseler/gettingandclearningdata" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="20094244" name="octolytics-dimension-repository_network_root_id" /><meta content="bfisseler/gettingandclearningdata" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/bfisseler/gettingandclearningdata/commits/master.atom" rel="alternate" title="Recent Commits to gettingandclearningdata:master" type="application/atom+xml">

  </head>


  <body class="logged_in  env-production windows vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      
      


      <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" ga-data-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <form accept-charset="UTF-8" action="/bfisseler/gettingandclearningdata/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/bfisseler/gettingandclearningdata/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <input type="text"
    class="js-site-search-field is-clearable"
    data-hotkey="s"
    name="q"
    placeholder="Search"
    data-global-scope-placeholder="Search GitHub"
    data-repo-scope-placeholder="Search"
    tabindex="1"
    autocapitalize="off">
  <div class="scope-badge">This repository</div>
</form>
      </div>
      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item explore">
          <a class="header-nav-link" href="/explore" data-ga-click="Header, go to explore, text:explore">Explore</a>
        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="/blog" data-ga-click="Header, go to blog, text:blog">Blog</a>
          </li>
        <li class="header-nav-item">
          <a class="header-nav-link" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
        </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name" href="/nirajsardana" data-ga-click="Header, go to profile, text:username">
      <img alt="nirajsardana" class="avatar" data-user="8679180" height="20" src="https://avatars1.githubusercontent.com/u/8679180?v=2&amp;s=40" width="20" />
      <span class="css-truncate">
        <span class="css-truncate-target">nirajsardana</span>
      </span>
    </a>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link js-menu-target tooltipped tooltipped-s" href="#" aria-label="Create new..." data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      
<ul class="dropdown-menu">
  <li>
    <a href="/new"><span class="octicon octicon-repo"></span> New repository</a>
  </li>
  <li>
    <a href="/organizations/new"><span class="octicon octicon-organization"></span> New organization</a>
  </li>


    <li class="dropdown-divider"></li>
    <li class="dropdown-header">
      <span title="bfisseler/gettingandclearningdata">This repository</span>
    </li>
      <li>
        <a href="/bfisseler/gettingandclearningdata/issues/new"><span class="octicon octicon-issue-opened"></span> New issue</a>
      </li>
</ul>

    </div>
  </li>

  <li class="header-nav-item">
        <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
        <span class="mail-status all-read"></span>
        <span class="octicon octicon-inbox"></span>
</a>
  </li>

  <li class="header-nav-item">
    <a class="header-nav-link tooltipped tooltipped-s" href="/settings/profile" id="account_settings" aria-label="Settings" data-ga-click="Header, go to settings, icon:settings">
      <span class="octicon octicon-gear"></span>
    </a>
  </li>

  <li class="header-nav-item">
    <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="2d663134rqvZ3FVfG6nhfN6n80peE9F6VCufucHHHEQ8/m734iAQJ4uAf5VSJFcmqLQOQSyUndImR8FfcyGbTw==" /></div>
      <button class="header-nav-link sign-out-button tooltipped tooltipped-s" aria-label="Sign out" data-ga-click="Header, sign out, icon:logout">
        <span class="octicon octicon-sign-out"></span>
      </button>
</form>  </li>

</ul>


    
  </div>
</div>

      

        


      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">
        
<ul class="pagehead-actions">

    <li class="subscription">
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="gbgctopLUOQjWM5zGTEIXY9XceJo1SqHb3qeOLvJHC3F2ek2Sm8nDzf+iW9NrMrkmsk5YaF5iAGYb41drs+xHg==" /></div>  <input id="repository_id" name="repository_id" type="hidden" value="20094244" />

    <div class="select-menu js-menu-container js-select-menu">
      <a class="social-count js-social-count" href="/bfisseler/gettingandclearningdata/watchers">
        1
      </a>
      <a href="/bfisseler/gettingandclearningdata/subscription"
        class="minibutton select-menu-button with-count js-menu-target" role="button" tabindex="0" aria-haspopup="true">
        <span class="js-select-button">
          <span class="octicon octicon-eye"></span>
          Watch
        </span>
      </a>

      <div class="select-menu-modal-holder">
        <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
          <div class="select-menu-header">
            <span class="select-menu-title">Notifications</span>
            <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
          </div> <!-- /.select-menu-header -->

          <div class="select-menu-list js-navigation-container" role="menu">

            <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                <h4>Not watching</h4>
                <span class="description">Be notified when participating or @mentioned.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-eye"></span>
                  Watch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                <h4>Watching</h4>
                <span class="description">Be notified of all conversations.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-eye"></span>
                  Unwatch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input id="do_ignore" name="do" type="radio" value="ignore" />
                <h4>Ignoring</h4>
                <span class="description">Never be notified.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-mute"></span>
                  Stop ignoring
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

          </div> <!-- /.select-menu-list -->

        </div> <!-- /.select-menu-modal -->
      </div> <!-- /.select-menu-modal-holder -->
    </div> <!-- /.select-menu -->

</form>
    </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <form accept-charset="UTF-8" action="/bfisseler/gettingandclearningdata/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="C10yZgJaRiBFW4Q7YHfMzDCZyG3FwDuCrVA7YhYm/0wHNtXQllBUE1eKrJInZoOcsNvMYhCSB1gX8Byg8ZumoA==" /></div>
      <button
        class="minibutton with-count js-toggler-target star-button"
        aria-label="Unstar this repository" title="Unstar bfisseler/gettingandclearningdata">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/bfisseler/gettingandclearningdata/stargazers">
          0
        </a>
</form>
    <form accept-charset="UTF-8" action="/bfisseler/gettingandclearningdata/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="jwesHXlrG1DNEw0V9kfUnIVLBpElf+zUV9DaBBGons9XdVcm5ker8mFSyGkdTGdasxzs2AkwWn+845u9x5mvXA==" /></div>
      <button
        class="minibutton with-count js-toggler-target star-button"
        aria-label="Star this repository" title="Star bfisseler/gettingandclearningdata">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/bfisseler/gettingandclearningdata/stargazers">
          0
        </a>
</form>  </div>

  </li>


        <li>
          <a href="/bfisseler/gettingandclearningdata/fork" class="minibutton with-count js-toggler-target fork-button tooltipped-n" title="Fork your own copy of bfisseler/gettingandclearningdata to your account" aria-label="Fork your own copy of bfisseler/gettingandclearningdata to your account" rel="nofollow" data-method="post">
            <span class="octicon octicon-repo-forked"></span>
            Fork
          </a>
          <a href="/bfisseler/gettingandclearningdata/network" class="social-count">2</a>
        </li>

</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/bfisseler" class="url fn" itemprop="url" rel="author"><span itemprop="title">bfisseler</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/bfisseler/gettingandclearningdata" class="js-current-repository js-repo-home-link" data-pjax-container-selector="#js-repo-pjax-container">gettingandclearningdata</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
          </span>

        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline  ">
        <div class="repository-sidebar clearfix">
            
<div class="sunken-menu vertical-right repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders" role="navigation" data-issue-count-url="/bfisseler/gettingandclearningdata/issues/counts" data-pjax-container-selector="#js-repo-pjax-container">
  <div class="sunken-menu-contents">
    <ul class="sunken-menu-group">
      <li class="tooltipped tooltipped-w" aria-label="Code">
        <a href="/bfisseler/gettingandclearningdata" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-pjax="true" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /bfisseler/gettingandclearningdata">
          <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

        <li class="tooltipped tooltipped-w" aria-label="Issues">
          <a href="/bfisseler/gettingandclearningdata/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item js-disable-pjax" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /bfisseler/gettingandclearningdata/issues">
            <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
            <span class="js-issue-replace-counter"></span>
            <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>        </li>

      <li class="tooltipped tooltipped-w" aria-label="Pull Requests">
        <a href="/bfisseler/gettingandclearningdata/pulls" aria-label="Pull Requests" class="js-selected-navigation-item sunken-menu-item js-disable-pjax" data-hotkey="g p" data-selected-links="repo_pulls /bfisseler/gettingandclearningdata/pulls">
            <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull Requests</span>
            <span class="js-pull-replace-counter"></span>
            <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>


        <li class="tooltipped tooltipped-w" aria-label="Wiki">
          <a href="/bfisseler/gettingandclearningdata/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item js-disable-pjax" data-hotkey="g w" data-selected-links="repo_wiki /bfisseler/gettingandclearningdata/wiki">
            <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
            <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>        </li>
    </ul>
    <div class="sunken-menu-separator"></div>
    <ul class="sunken-menu-group">

      <li class="tooltipped tooltipped-w" aria-label="Pulse">
        <a href="/bfisseler/gettingandclearningdata/pulse/weekly" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-pjax="true" data-selected-links="pulse /bfisseler/gettingandclearningdata/pulse/weekly">
          <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

      <li class="tooltipped tooltipped-w" aria-label="Graphs">
        <a href="/bfisseler/gettingandclearningdata/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-pjax="true" data-selected-links="repo_graphs repo_contributors /bfisseler/gettingandclearningdata/graphs">
          <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
    </ul>


  </div>
</div>

              <div class="only-with-full-nav">
                
  
<div class="clone-url open"
  data-protocol-type="http"
  data-url="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group">
    <input type="text" class="input-mini input-monospace js-url-field"
           value="https://github.com/bfisseler/gettingandclearningdata.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-clipboard-text="https://github.com/bfisseler/gettingandclearningdata.git" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="ssh"
  data-url="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone">
  <h3><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group">
    <input type="text" class="input-mini input-monospace js-url-field"
           value="git@github.com:bfisseler/gettingandclearningdata.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-clipboard-text="git@github.com:bfisseler/gettingandclearningdata.git" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="subversion"
  data-url="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group">
    <input type="text" class="input-mini input-monospace js-url-field"
           value="https://github.com/bfisseler/gettingandclearningdata" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-clipboard-text="https://github.com/bfisseler/gettingandclearningdata" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>


<p class="clone-options">You can clone with
      <a href="#" class="js-clone-selector" data-protocol="http">HTTPS</a>,
      <a href="#" class="js-clone-selector" data-protocol="ssh">SSH</a>,
      or <a href="#" class="js-clone-selector" data-protocol="subversion">Subversion</a>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</p>


  <a href="http://windows.github.com" class="minibutton sidebar-button" title="Save bfisseler/gettingandclearningdata to your computer and use it in GitHub Desktop." aria-label="Save bfisseler/gettingandclearningdata to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>

                <a href="/bfisseler/gettingandclearningdata/archive/master.zip"
                   class="minibutton sidebar-button"
                   aria-label="Download the contents of bfisseler/gettingandclearningdata as a zip file"
                   title="Download the contents of bfisseler/gettingandclearningdata as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>
          

<a href="/bfisseler/gettingandclearningdata/blob/107d64d841f091b1fcf41513ae528ed1373dd601/readMe.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:73ec6a91c662f816dc05d6c848d800e0 -->

<div class="file-navigation">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="minibutton select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-master-branch="master"
    data-ref="master"
    title="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div> <!-- /.select-menu-header -->

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" class="js-select-menu-tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" class="js-select-menu-tab">Tags</a>
            </li>
          </ul>
        </div><!-- /.select-menu-tabs -->
      </div><!-- /.select-menu-filters -->

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <div class="select-menu-item js-navigation-item selected">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/bfisseler/gettingandclearningdata/blob/master/readMe.md"
                 data-name="master"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="master">master</a>
            </div> <!-- /.select-menu-item -->
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div> <!-- /.select-menu-list -->

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div> <!-- /.select-menu-list -->

    </div> <!-- /.select-menu-modal -->
  </div> <!-- /.select-menu-modal-holder -->
</div> <!-- /.select-menu -->

  <div class="button-group right">
    <a href="/bfisseler/gettingandclearningdata/find/master"
          class="js-show-file-finder minibutton empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button class="js-zeroclipboard minibutton zeroclipboard-button"
          data-clipboard-text="readMe.md"
          aria-label="Copy to clipboard"
          data-copied-hint="Copied!">
      <span class="octicon octicon-clippy"></span>
    </button>
  </div>

  <div class="breadcrumb">
    <span class='repo-root js-repo-root'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/bfisseler/gettingandclearningdata" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">gettingandclearningdata</span></a></span></span><span class="separator"> / </span><strong class="final-path">readMe.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="" class="avatar" height="24" src="https://1.gravatar.com/avatar/3bdb576470a5e9d7cb7e999931836503?d=https%3A%2F%2Fassets-cdn.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png&amp;r=x&amp;s=140" width="24" />
        <span class="author"><span>bjoern.fisseler@gmail.com</span></span>
        <time datetime="2014-05-23T09:38:53Z" is="relative-time">May 23, 2014</time>
        <div class="commit-title">
            <a href="/bfisseler/gettingandclearningdata/commit/107d64d841f091b1fcf41513ae528ed1373dd601" class="message" data-pjax="true" title="Upload the local files

05/23/14">Upload the local files</a>
        </div>
    </div>

    <div class="participation">
      <p class="quickstat">
        <a href="#blob_contributors_box" rel="facebox">
          <strong>0</strong>
           contributors
        </a>
      </p>
      
    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
      </ul>
    </div>
  </div>

<div class="file-box">
  <div class="file">
    <div class="meta clearfix">
      <div class="info file-name">
          <span>107 lines (92 sloc)</span>
          <span class="meta-divider"></span>
        <span>6.664 kb</span>
      </div>
      <div class="actions">
        <div class="button-group">
          <a href="/bfisseler/gettingandclearningdata/raw/master/readMe.md" class="minibutton " id="raw-url">Raw</a>
            <a href="/bfisseler/gettingandclearningdata/blame/master/readMe.md" class="minibutton js-update-url-with-hash">Blame</a>
          <a href="/bfisseler/gettingandclearningdata/commits/master/readMe.md" class="minibutton " rel="nofollow">History</a>
        </div><!-- /.button-group -->

          <a class="octicon-button tooltipped tooltipped-nw"
             href="http://windows.github.com" aria-label="Open this file in GitHub for Windows">
              <span class="octicon octicon-device-desktop"></span>
          </a>

              <a class="octicon-button tooltipped tooltipped-n js-update-url-with-hash"
                 aria-label="Clicking this button will fork this project so you can edit the file"
                 href="/bfisseler/gettingandclearningdata/edit/master/readMe.md"
                 data-method="post" rel="nofollow"><span class="octicon octicon-pencil"></span></a>

            <a class="octicon-button danger tooltipped tooltipped-s"
               href="/bfisseler/gettingandclearningdata/delete/master/readMe.md"
               aria-label="Fork this project and delete file"
               data-method="post" data-test-id="delete-blob-file" rel="nofollow">
          <span class="octicon octicon-trashcan"></span>
        </a>
      </div><!-- /.actions -->
    </div>
      <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1>
<a name="user-content-project-for-getting-and-cleaning-data" class="anchor" href="#project-for-getting-and-cleaning-data" aria-hidden="true"><span class="octicon octicon-link"></span></a>Project for "Getting and Cleaning Data"</h1>

<p>This document explains how the script "run_analysis.R" works.</p>

<p>The script first checks if the ZIP-archive with the dataset exists in the current working directory. In case the archive does not exist, the script throws an error and stops. Please notice the name of the archive, this must be changed to match the name of your file.</p>

<div class="highlight highlight-r"><pre>archiveName <span class="o">&lt;-</span> <span class="s">"getdata_projectfiles_UCI HAR Dataset.zip"</span>
<span class="kr">if</span> <span class="p">(</span> <span class="kp">file.exists</span><span class="p">(</span>archiveName<span class="p">)</span> <span class="o">==</span> <span class="kc">FALSE</span><span class="p">)</span> stop <span class="p">(</span><span class="s">"File not found."</span><span class="p">)</span>
</pre></div>

<p>The next instructions directly read the different data from the archive. The archive is not unzipped completely, to avoid having to delete the files after running the script. The script does not read the headers and also assumes certain classes for the columns.</p>

<div class="highlight highlight-r"><pre>trainSubjectDT <span class="o">&lt;-</span> read.table <span class="p">(</span> unz <span class="p">(</span>archiveName<span class="p">,</span> <span class="s">"UCI HAR Dataset/train/subject_train.txt"</span><span class="p">),</span> header <span class="o">=</span> <span class="kc">FALSE</span><span class="p">,</span> colClasses<span class="o">=</span><span class="s">"integer"</span><span class="p">)</span>
trainXDT <span class="o">&lt;-</span> read.table <span class="p">(</span> unz <span class="p">(</span>archiveName<span class="p">,</span> <span class="s">"UCI HAR Dataset/train/X_train.txt"</span><span class="p">),</span> header <span class="o">=</span> <span class="kc">FALSE</span><span class="p">,</span> colClasses<span class="o">=</span><span class="s">"numeric"</span><span class="p">)</span>
trainYDT <span class="o">&lt;-</span> read.table <span class="p">(</span> unz <span class="p">(</span>archiveName<span class="p">,</span> <span class="s">"UCI HAR Dataset/train/y_train.txt"</span><span class="p">),</span> header <span class="o">=</span> <span class="kc">FALSE</span><span class="p">,</span> colClasses<span class="o">=</span><span class="s">"integer"</span><span class="p">)</span>
testSubjectDT <span class="o">&lt;-</span> read.table <span class="p">(</span> unz <span class="p">(</span>archiveName<span class="p">,</span> <span class="s">"UCI HAR Dataset/test/subject_test.txt"</span><span class="p">),</span> header <span class="o">=</span> <span class="kc">FALSE</span><span class="p">,</span> colClasses<span class="o">=</span><span class="s">"integer"</span><span class="p">)</span>
testXDT <span class="o">&lt;-</span> read.table <span class="p">(</span> unz <span class="p">(</span>archiveName<span class="p">,</span> <span class="s">"UCI HAR Dataset/test/X_test.txt"</span><span class="p">),</span> header <span class="o">=</span> <span class="kc">FALSE</span><span class="p">,</span> colClasses<span class="o">=</span><span class="s">"numeric"</span><span class="p">)</span>
testYDT <span class="o">&lt;-</span> read.table <span class="p">(</span> unz <span class="p">(</span>archiveName<span class="p">,</span> <span class="s">"UCI HAR Dataset/test/y_test.txt"</span><span class="p">),</span> header <span class="o">=</span> <span class="kc">FALSE</span><span class="p">,</span> colClasses<span class="o">=</span><span class="s">"integer"</span><span class="p">)</span>
</pre></div>

<p>Now we build three large blocks, as we have three different data sets, both available for training and testing.
The script does not build one large block, but simply combines the the train and test data. The big block is build later, because the variable names will change; and combining the subject and activity data later makes this easier to accomplish.
The script also frees some memory and removes no longer needed data tables.</p>

<div class="highlight highlight-r"><pre>subjectDT <span class="o">&lt;-</span> rbind <span class="p">(</span>trainSubjectDT<span class="p">,</span> testSubjectDT<span class="p">)</span>
featureDataDT <span class="o">&lt;-</span> rbind <span class="p">(</span>trainXDT<span class="p">,</span> testXDT<span class="p">)</span>
activityDT <span class="o">&lt;-</span> rbind <span class="p">(</span>trainYDT<span class="p">,</span> testYDT<span class="p">)</span>

<span class="c1"># free some memory and remove no longer needed data tables</span>
rm <span class="p">(</span>trainSubjectDT<span class="p">,</span> trainXDT<span class="p">,</span> trainYDT<span class="p">,</span> testSubjectDT<span class="p">,</span> testXDT<span class="p">,</span> testYDT<span class="p">)</span>
</pre></div>

<p>Now it's time to read the variable/feature names. Once again, the variable names are read directly from the zip archive.
The script then sets the names for the variables/features as well as for subject and activity.</p>

<div class="highlight highlight-r"><pre><span class="c1"># read the names of the features</span>
varNamesDT <span class="o">&lt;-</span>read.table <span class="p">(</span> unz <span class="p">(</span>archiveName<span class="p">,</span> <span class="s">"UCI HAR Dataset/features.txt"</span><span class="p">),</span> sep <span class="o">=</span> <span class="s">" "</span><span class="p">)</span>
<span class="c1"># the second column contains the feature names</span>
featureNames <span class="o">&lt;-</span> as.character <span class="p">(</span>varNamesDT<span class="p">[,</span><span class="m">2</span><span class="p">])</span>
rm <span class="p">(</span>varNamesDT<span class="p">)</span> <span class="c1"># again, free some memory</span>
<span class="kp">names</span><span class="p">(</span>featureDataDT<span class="p">)</span> <span class="o">&lt;-</span> featureNames
<span class="kp">names</span><span class="p">(</span>subjectDT<span class="p">)</span> <span class="o">&lt;-</span> <span class="kt">c</span><span class="p">(</span><span class="s">"Subject"</span><span class="p">)</span>
<span class="kp">names</span><span class="p">(</span>activityDT<span class="p">)</span> <span class="o">&lt;-</span> <span class="kt">c</span><span class="p">(</span><span class="s">"Activity"</span><span class="p">)</span>
</pre></div>

<p>Now we select only the variables that contain a mean oder std value. These can be easily identified using the variable names the script read before. Please note that the script only selects those variables whose names contain either "mean()" or "std()". This excludes variables like "meanFreq()", which contains the "weighted average of the frequency components to obtain a mean frequency".</p>

<div class="highlight highlight-r"><pre>selectedFeatureDT <span class="o">&lt;-</span> featureDataDT<span class="p">[,</span> <span class="kp">grep</span><span class="p">(</span><span class="s">"mean\\()|std\\()"</span><span class="p">,</span> featureNames<span class="p">)]</span>
</pre></div>

<p>Let's make the variable names more descriptive. The script uses camelCase for the variable names, which is more readable than just lower case variable names. First, the script substitutes "mean()" and "std()" with "Mean" and "Std". Then it removes all hyphens.
It's discussible if the abbreviations "f", "t", "Acc", and "Gyrr" have to be expanded. The script does so, but this could also make the variables too long.</p>

<div class="highlight highlight-r"><pre><span class="c1"># Step 3b, was step 5 - Rename the variables, use descriptive variable names</span>
<span class="c1"># lets convert the variables/features like this: variableNameAndMore</span>
<span class="c1"># first, we convert mean() and std() to Mean and Std</span>
<span class="kp">names</span><span class="p">(</span>selectedFeatureDT<span class="p">)</span> <span class="o">&lt;-</span> <span class="kp">gsub</span><span class="p">(</span><span class="s">"mean\\()"</span><span class="p">,</span> <span class="s">"Mean"</span><span class="p">,</span> <span class="kp">names</span><span class="p">(</span>selectedFeatureDT<span class="p">))</span>
<span class="kp">names</span><span class="p">(</span>selectedFeatureDT<span class="p">)</span> <span class="o">&lt;-</span> <span class="kp">gsub</span><span class="p">(</span><span class="s">"std\\()"</span><span class="p">,</span> <span class="s">"Std"</span><span class="p">,</span> <span class="kp">names</span><span class="p">(</span>selectedFeatureDT<span class="p">))</span>
<span class="c1"># remove all "-"</span>
<span class="kp">names</span><span class="p">(</span>selectedFeatureDT<span class="p">)</span> <span class="o">&lt;-</span> <span class="kp">gsub</span><span class="p">(</span><span class="s">"-"</span><span class="p">,</span> <span class="s">""</span><span class="p">,</span> <span class="kp">names</span><span class="p">(</span>selectedFeatureDT<span class="p">))</span>
<span class="c1"># expand abbr, also this makes the variable names very long</span>
<span class="kp">names</span><span class="p">(</span>selectedFeatureDT<span class="p">)</span> <span class="o">&lt;-</span> <span class="kp">gsub</span><span class="p">(</span><span class="s">"^f"</span><span class="p">,</span> <span class="s">"frequency"</span><span class="p">,</span> <span class="kp">names</span><span class="p">(</span>selectedFeatureDT<span class="p">))</span>
<span class="kp">names</span><span class="p">(</span>selectedFeatureDT<span class="p">)</span> <span class="o">&lt;-</span> <span class="kp">gsub</span><span class="p">(</span><span class="s">"^t"</span><span class="p">,</span> <span class="s">"time"</span><span class="p">,</span> <span class="kp">names</span><span class="p">(</span>selectedFeatureDT<span class="p">))</span>
<span class="kp">names</span><span class="p">(</span>selectedFeatureDT<span class="p">)</span> <span class="o">&lt;-</span> <span class="kp">gsub</span><span class="p">(</span><span class="s">"Acc"</span><span class="p">,</span> <span class="s">"Acceleration"</span><span class="p">,</span> <span class="kp">names</span><span class="p">(</span>selectedFeatureDT<span class="p">))</span>
<span class="kp">names</span><span class="p">(</span>selectedFeatureDT<span class="p">)</span> <span class="o">&lt;-</span> <span class="kp">gsub</span><span class="p">(</span><span class="s">"Gyro"</span><span class="p">,</span> <span class="s">"Gyroscope"</span><span class="p">,</span> <span class="kp">names</span><span class="p">(</span>selectedFeatureDT<span class="p">))</span>
</pre></div>

<p>The script finally builds one large data frame, which contains all selected variables as well as the activity and subject variable.</p>

<div class="highlight highlight-r"><pre><span class="c1"># now we add the activities and subjects to the features, for the complete block</span>
selectedFeatureDT <span class="o">&lt;-</span> <span class="kp">cbind</span><span class="p">(</span>selectedFeatureDT<span class="p">,</span> subjectDT<span class="p">,</span> activityDT<span class="p">)</span>
<span class="c1"># and free some memory</span>
rm <span class="p">(</span>featureDataDT<span class="p">,</span> subjectDT<span class="p">,</span> activityDT<span class="p">)</span>
</pre></div>

<p>Then we load the labels for the activities directly from the zip file and apply the labels to the data.</p>

<div class="highlight highlight-r"><pre>actLabels <span class="o">&lt;-</span> read.table <span class="p">(</span> unz <span class="p">(</span>archiveName<span class="p">,</span> <span class="s">"UCI HAR Dataset/activity_labels.txt"</span><span class="p">),</span> header <span class="o">=</span> <span class="kc">FALSE</span><span class="p">,</span> stringsAsFactors <span class="o">=</span> <span class="kc">FALSE</span><span class="p">)</span>
<span class="c1"># now apply the labels to the data</span>
selectedFeatureDT<span class="o">$</span>Activity <span class="o">&lt;-</span> <span class="kp">factor</span><span class="p">(</span>selectedFeatureDT<span class="o">$</span>Activity<span class="p">,</span> levels <span class="o">=</span> actLabels<span class="p">[,</span><span class="m">1</span><span class="p">],</span> labels <span class="o">=</span> actLabels<span class="p">[,</span><span class="m">2</span><span class="p">])</span>
</pre></div>

<p>We now create a tidy data set with the average of each variable for each activity and each subject. The library "reshape" is loaded first, as it contains the functions "melt" and "cast".
Then the data is melt, using mean and std as variables. Then the molten data frame is cast into its final form. This contains the mean for each variable for each activity and every subject.</p>

<div class="highlight highlight-r"><pre><span class="c1"># load the library</span>
<span class="kn">library</span><span class="p">(</span>reshape<span class="p">)</span>
<span class="c1"># first, melt the data, using the variables for Mean and Std</span>
measures <span class="o">&lt;-</span> grep <span class="p">(</span><span class="s">"Mean|Std"</span><span class="p">,</span> names <span class="p">(</span>selectedFeatureDT<span class="p">),</span> value <span class="o">=</span> <span class="kc">TRUE</span><span class="p">)</span>
moltenDT <span class="o">&lt;-</span> melt<span class="p">(</span>selectedFeatureDT<span class="p">,</span> id.vars <span class="o">=</span> <span class="kt">c</span><span class="p">(</span><span class="s">"Subject"</span><span class="p">,</span> <span class="s">"Activity"</span><span class="p">),</span> measure.vars <span class="o">=</span> measures<span class="p">)</span>
<span class="c1"># then cast the the data into the wanted form</span>
tidyDT <span class="o">&lt;-</span> cast<span class="p">(</span>moltenDT<span class="p">,</span> Subject <span class="o">+</span> Activity <span class="o">~</span> variable<span class="p">,</span> <span class="kp">mean</span><span class="p">)</span>
</pre></div>

<p>In the last step, the script writes the tidy data to a csv file. It uses "write.csv()" as a wrapper for "write.table()"; write.csv uses "." for the decimal point and a comma for the separator.
The script finishes with cleaning up, removes the remaining variables and data frames from memory, and prints a message that it is finished. </p>

<div class="highlight highlight-r"><pre>write.csv<span class="p">(</span>tidyDT<span class="p">,</span> file <span class="o">=</span> <span class="s">"tidyData.csv"</span><span class="p">,</span> row.names <span class="o">=</span> <span class="kc">FALSE</span><span class="p">)</span>

<span class="c1"># do some cleaning</span>
<span class="kp">rm</span><span class="p">(</span>actLabels<span class="p">,</span> moltenDT<span class="p">,</span> selectedFeatureDT<span class="p">,</span> tidyDT<span class="p">)</span>
<span class="kp">rm</span><span class="p">(</span>archiveName<span class="p">,</span> featureNames<span class="p">,</span> measures<span class="p">)</span>
<span class="kp">message</span><span class="p">(</span><span class="s">"Script finished, CSV file written."</span><span class="p">)</span>
</pre></div>
</article>
  </div>

  </div>
</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" class="js-jump-to-line-form">
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="button">Go</button>
  </form>
</div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
      <li><a href="https://status.github.com/">Status</a></li>
      <li><a href="https://developer.github.com">API</a></li>
      <li><a href="http://training.github.com">Training</a></li>
      <li><a href="http://shop.github.com">Shop</a></li>
      <li><a href="/blog">Blog</a></li>
      <li><a href="/about">About</a></li>

    </ul>

    <a href="/" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
    </a>

    <ul class="site-footer-links">
      <li>&copy; 2014 <span title="0.03725s from github-fe127-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="/site/terms">Terms</a></li>
        <li><a href="/site/privacy">Privacy</a></li>
        <li><a href="/security">Security</a></li>
        <li><a href="/contact">Contact</a></li>
    </ul>
  </div><!-- /.site-footer -->
</div><!-- /.container -->


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents js-suggester-field" placeholder=""></textarea>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w"
      aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-dabc650f8a51dffd1d4376a3522cbda5536e4807e01d2a86ff7e60d8d6ee3029.js" type="text/javascript"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-d01013daa80c5a341ba3ddb684f2f26679eb369d67459151d5175a634a9e98a5.js" type="text/javascript"></script>
      
      
  </body>
</html>


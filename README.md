<html lang="en">
  
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <meta property="og:title" content="996.ICU">
    <meta property="og:site_name" content="Developers' Lifes Matter">
    <meta property="og:url" content="https://996.icu">
    <meta property="og:description" content="The name 996.ICU refers to 'Work by 996, sick in ICU', an ironic saying among Chinese programmers, which means that by following the 996 work schedule, you are risking yourself getting into ICU (Intensive Care Unit)">
    <meta property=" og:type" content="website">
    <meta property="og:image" content="https://github.com/996icu/996.ICU/blob/master/assets/images/logo.png">
    <link rel="shortcut icon" type="image/x-icon" href="https://avatars2.githubusercontent.com/u/48942249?s=60&amp;v=4">
    <title>996.ICU</title>
    <link href="/js/de_DE.b86bff42.js" rel="prefetch">
    <link href="/js/en_US.2acb8805.js" rel="prefetch">
    <link href="/js/es_MX.3bab821a.js" rel="prefetch">
    <link href="/js/fr_FR.9e0db5fa.js" rel="prefetch">
    <link href="/js/it_IT.6fdf7e49.js" rel="prefetch">
    <link href="/js/ja_JP.619229ea.js" rel="prefetch">
    <link href="/js/zh_CN.ebdfefe2.js" rel="prefetch">
    <link href="/js/app.a87731b8.js" rel="preload" as="script">
    <link href="/js/chunk-vendors.99abbef2.js" rel="preload" as="script">
    <link rel="icon" type="image/png" sizes="32x32" href="/img/icons/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="/img/icons/favicon-16x16.png">
    <link rel="manifest" href="/manifest.json">
    <meta name="theme-color" content="#4DBA87">
    <meta name="apple-mobile-web-app-capable" content="no">
    <meta name="apple-mobile-web-app-status-bar-style" content="default">
    <meta name="apple-mobile-web-app-title" content="icu">
    <link rel="apple-touch-icon" href="/img/icons/apple-touch-icon-152x152.png">
    <link rel="mask-icon" href="/img/icons/safari-pinned-tab.svg" color="#4DBA87">
    <meta name="msapplication-TileImage" content="/img/icons/msapplication-icon-144x144.png">
    <meta name="msapplication-TileColor" content="#000000">
    <meta http-equiv="origin-trial" content="AymqwRC7u88Y4JPvfIF2F37QKylC04248hLCdJAsh8xgOfe/dVJPV3XS3wLFca1ZMVOtnBfVjaCMTVudWM//5g4AAAB7eyJvcmlnaW4iOiJodHRwczovL3d3dy5nb29nbGV0YWdtYW5hZ2VyLmNvbTo0NDMiLCJmZWF0dXJlIjoiUHJpdmFjeVNhbmRib3hBZHNBUElzIiwiZXhwaXJ5IjoxNjk1MTY3OTk5LCJpc1RoaXJkUGFydHkiOnRydWV9">
    <style type="text/css">@font-face{font-family:octicons-link;src:url(data:font/woff;charset=utf-8;base64,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) format("woff")}.markdown-body .octicon{display:inline-block;fill:currentColor;vertical-align:text-bottom}.markdown-body .anchor{float:left;line-height:1;margin-left:-20px;padding-right:4px}.markdown-body .anchor:focus{outline:none}.markdown-body h1 .octicon-link,.markdown-body h2 .octicon-link,.markdown-body h3 .octicon-link,.markdown-body h4 .octicon-link,.markdown-body h5 .octicon-link,.markdown-body h6 .octicon-link{color:#1b1f23;vertical-align:middle;visibility:hidden}.markdown-body h1:hover .anchor,.markdown-body h2:hover .anchor,.markdown-body h3:hover .anchor,.markdown-body h4:hover .anchor,.markdown-body h5:hover .anchor,.markdown-body h6:hover .anchor{text-decoration:none}.markdown-body h1:hover .anchor .octicon-link,.markdown-body h2:hover .anchor .octicon-link,.markdown-body h3:hover .anchor .octicon-link,.markdown-body h4:hover .anchor .octicon-link,.markdown-body h5:hover .anchor .octicon-link,.markdown-body h6:hover .anchor .octicon-link{visibility:visible}.markdown-body{-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%;color:#24292e;font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica,Arial,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol;font-size:16px;line-height:1.5;word-wrap:break-word}.markdown-body .pl-c{color:#6a737d}.markdown-body .pl-c1,.markdown-body .pl-s .pl-v{color:#005cc5}.markdown-body .pl-e,.markdown-body .pl-en{color:#6f42c1}.markdown-body .pl-s .pl-s1,.markdown-body .pl-smi{color:#24292e}.markdown-body .pl-ent{color:#22863a}.markdown-body .pl-k{color:#d73a49}.markdown-body .pl-pds,.markdown-body .pl-s,.markdown-body .pl-s .pl-pse .pl-s1,.markdown-body .pl-sr,.markdown-body .pl-sr .pl-cce,.markdown-body .pl-sr .pl-sra,.markdown-body .pl-sr .pl-sre{color:#032f62}.markdown-body .pl-smw,.markdown-body .pl-v{color:#e36209}.markdown-body .pl-bu{color:#b31d28}.markdown-body .pl-ii{background-color:#b31d28;color:#fafbfc}.markdown-body .pl-c2{background-color:#d73a49;color:#fafbfc}.markdown-body .pl-c2:before{content:"^M"}.markdown-body .pl-sr .pl-cce{color:#22863a;font-weight:700}.markdown-body .pl-ml{color:#735c0f}.markdown-body .pl-mh,.markdown-body .pl-mh .pl-en,.markdown-body .pl-ms{color:#005cc5;font-weight:700}.markdown-body .pl-mi{color:#24292e;font-style:italic}.markdown-body .pl-mb{color:#24292e;font-weight:700}.markdown-body .pl-md{background-color:#ffeef0;color:#b31d28}.markdown-body .pl-mi1{background-color:#f0fff4;color:#22863a}.markdown-body .pl-mc{background-color:#ffebda;color:#e36209}.markdown-body .pl-mi2{background-color:#005cc5;color:#f6f8fa}.markdown-body .pl-mdr{color:#6f42c1;font-weight:700}.markdown-body .pl-ba{color:#586069}.markdown-body .pl-sg{color:#959da5}.markdown-body .pl-corl{color:#032f62;text-decoration:underline}.markdown-body details{display:block}.markdown-body summary{display:list-item}.markdown-body a{background-color:transparent}.markdown-body a:active,.markdown-body a:hover{outline-width:0}.markdown-body strong{font-weight:inherit;font-weight:bolder}.markdown-body h1{margin:.67em 0}.markdown-body img{border-style:none}.markdown-body code,.markdown-body kbd,.markdown-body pre{font-family:monospace,monospace;font-size:1em}.markdown-body hr{box-sizing:content-box;overflow:visible}.markdown-body input{font:inherit;margin:0;overflow:visible}.markdown-body [type=checkbox]{box-sizing:border-box;padding:0}.markdown-body *{box-sizing:border-box}.markdown-body input{font-family:inherit;font-size:inherit;line-height:inherit}.markdown-body a{color:#0366d6;text-decoration:none}.markdown-body a:hover{text-decoration:underline}.markdown-body strong{font-weight:600}.markdown-body hr{background:transparent;border-bottom:1px solid #dfe2e5;height:0;margin:15px 0;overflow:hidden}.markdown-body hr:after,.markdown-body hr:before{content:"";display:table}.markdown-body hr:after{clear:both}.markdown-body table{border-collapse:collapse;border-spacing:0}.markdown-body td,.markdown-body th{padding:0}.markdown-body details summary{cursor:pointer}.markdown-body h1,.markdown-body h2,.markdown-body h3,.markdown-body h4,.markdown-body h5,.markdown-body h6{margin-bottom:0;margin-top:0}.markdown-body h1{font-size:32px}.markdown-body h1,.markdown-body h2{font-weight:600}.markdown-body h2{font-size:24px}.markdown-body h3{font-size:20px}.markdown-body h3,.markdown-body h4{font-weight:600}.markdown-body h4{font-size:16px}.markdown-body h5{font-size:14px}.markdown-body h5,.markdown-body h6{font-weight:600}.markdown-body h6{font-size:12px}.markdown-body p{margin-bottom:10px;margin-top:0}.markdown-body blockquote{margin:0}.markdown-body ol,.markdown-body ul{margin-bottom:0;margin-top:0;padding-left:0}.markdown-body ol ol,.markdown-body ul ol{list-style-type:lower-roman}.markdown-body
      ol ol ol,.markdown-body ol ul ol,.markdown-body ul ol ol,.markdown-body ul ul ol{list-style-type:lower-alpha}.markdown-body dd{margin-left:0}.markdown-body code,.markdown-body pre{font-family:SFMono-Regular,Consolas,Liberation Mono,Menlo,Courier,monospace;font-size:12px}.markdown-body pre{margin-bottom:0;margin-top:0}.markdown-body input::-webkit-inner-spin-button,.markdown-body input::-webkit-outer-spin-button{-webkit-appearance:none;appearance:none;margin:0}.markdown-body .border{border:1px solid #e1e4e8!important}.markdown-body .border-0{border:0!important}.markdown-body .border-bottom{border-bottom:1px solid #e1e4e8!important}.markdown-body .rounded-1{border-radius:3px!important}.markdown-body .bg-white{background-color:#fff!important}.markdown-body .bg-gray-light{background-color:#fafbfc!important}.markdown-body .text-gray-light{color:#6a737d!important}.markdown-body .mb-0{margin-bottom:0!important}.markdown-body .my-2{margin-bottom:8px!important;margin-top:8px!important}.markdown-body .py-0{padding-bottom:0!important;padding-top:0!important}.markdown-body .py-2{padding-bottom:8px!important;padding-top:8px!important}.markdown-body .pl-3,.markdown-body .px-3{padding-left:16px!important}.markdown-body .px-3{padding-right:16px!important}.markdown-body .f6{font-size:12px!important}.markdown-body .lh-condensed{line-height:1.25!important}.markdown-body .text-bold{font-weight:600!important}.markdown-body:after,.markdown-body:before{content:"";display:table}.markdown-body:after{clear:both}.markdown-body>:first-child{margin-top:0!important}.markdown-body>:last-child{margin-bottom:0!important}.markdown-body a:not([href]){color:inherit;text-decoration:none}.markdown-body blockquote,.markdown-body dl,.markdown-body ol,.markdown-body p,.markdown-body pre,.markdown-body table,.markdown-body ul{margin-bottom:16px;margin-top:0}.markdown-body hr{background-color:#e1e4e8;border:0;height:.25em;margin:24px 0;padding:0}.markdown-body blockquote{border-left:.25em solid #dfe2e5;color:#6a737d;padding:0 1em}.markdown-body blockquote>:first-child{margin-top:0}.markdown-body blockquote>:last-child{margin-bottom:0}.markdown-body kbd{border:1px solid #c6cbd1;border-bottom-color:#959da5;box-shadow:inset 0 -1px 0 #959da5;font-size:11px}.markdown-body h1,.markdown-body h2,.markdown-body h3,.markdown-body h4,.markdown-body h5,.markdown-body h6{font-weight:600;line-height:1.25;margin-bottom:16px;margin-top:24px}.markdown-body h1{font-size:2em}.markdown-body h1,.markdown-body h2{border-bottom:1px solid #eaecef;padding-bottom:.3em}.markdown-body h2{font-size:1.5em}.markdown-body h3{font-size:1.25em}.markdown-body h4{font-size:1em}.markdown-body h5{font-size:.875em}.markdown-body h6{color:#6a737d;font-size:.85em}.markdown-body ol,.markdown-body ul{padding-left:2em}.markdown-body ol ol,.markdown-body ol ul,.markdown-body ul ol,.markdown-body ul ul{margin-bottom:0;margin-top:0}.markdown-body li{word-wrap:break-all}.markdown-body li>p{margin-top:16px}.markdown-body li+li{margin-top:.25em}.markdown-body dl{padding:0}.markdown-body dl dt{font-size:1em;font-style:italic;font-weight:600;margin-top:16px;padding:0}.markdown-body dl dd{margin-bottom:16px;padding:0 16px}.markdown-body table{display:block;overflow:auto;width:100%}.markdown-body table th{font-weight:600}.markdown-body table td,.markdown-body table th{border:1px solid #dfe2e5;padding:6px 13px}.markdown-body table tr{background-color:#fff;border-top:1px solid #c6cbd1}.markdown-body table tr:nth-child(2n){background-color:#f6f8fa}.markdown-body img{background-color:#fff;box-sizing:content-box;max-width:100%}.markdown-body img[align=right]{padding-left:20px}.markdown-body img[align=left]{padding-right:20px}.markdown-body code{background-color:rgba(27,31,35,.05);border-radius:3px;font-size:85%;margin:0;padding:.2em .4em}.markdown-body pre{word-wrap:normal}.markdown-body pre>code{background:transparent;border:0;font-size:100%;margin:0;padding:0;white-space:pre;word-break:normal}.markdown-body .highlight{margin-bottom:16px}.markdown-body .highlight pre{margin-bottom:0;word-break:normal}.markdown-body .highlight pre,.markdown-body pre{background-color:#f6f8fa;border-radius:3px;font-size:85%;line-height:1.45;overflow:auto;padding:16px}.markdown-body pre code{background-color:transparent;border:0;display:inline;line-height:inherit;margin:0;max-width:auto;overflow:visible;padding:0;word-wrap:normal}.markdown-body .commit-tease-sha{color:#444d56;display:inline-block;font-family:SFMono-Regular,Consolas,Liberation Mono,Menlo,Courier,monospace;font-size:90%}.markdown-body .blob-wrapper{border-bottom-left-radius:3px;border-bottom-right-radius:3px;overflow-x:auto;overflow-y:hidden}.markdown-body .blob-wrapper-embedded{max-height:240px;overflow-y:auto}.markdown-body .blob-num{-moz-user-select:none;-ms-user-select:none;-webkit-user-select:none;color:rgba(27,31,35,.3);cursor:pointer;font-family:SFMono-Regular,Consolas,Liberation Mono,Menlo,Courier,monospace;font-size:12px;line-height:20px;min-width:50px;padding-left:10px;padding-right:10px;text-align:right;user-select:none;vertical-align:top;white-space:nowrap;width:1%}.markdown-body .blob-num:hover{color:rgba(27,31,35,.6)}.markdown-body .blob-num:before{content:attr(data-line-number)}.markdown-body .blob-code{line-height:20px;padding-left:10px;padding-right:10px;position:relative;vertical-align:top}.markdown-body .blob-code-inner{color:#24292e;font-family:SFMono-Regular,Consolas,Liberation Mono,Menlo,Courier,monospace;font-size:12px;overflow:visible;white-space:pre;word-wrap:normal}.markdown-body .pl-token.active,.markdown-body .pl-token:hover{background:#ffea7f;cursor:pointer}.markdown-body kbd{background-color:#fafbfc;border:1px solid #d1d5da;border-bottom-color:#c6cbd1;border-radius:3px;box-shadow:inset 0 -1px 0 #c6cbd1;color:#444d56;display:inline-block;font:11px SFMono-Regular,Consolas,Liberation Mono,Menlo,Courier,monospace;line-height:10px;padding:3px 5px;vertical-align:middle}.markdown-body :checked+.radio-label{border-color:#0366d6;position:relative;z-index:1}.markdown-body .tab-size[data-tab-size="1"]{-moz-tab-size:1;-o-tab-size:1;tab-size:1}.markdown-body .tab-size[data-tab-size="2"]{-moz-tab-size:2;-o-tab-size:2;tab-size:2}.markdown-body .tab-size[data-tab-size="3"]{-moz-tab-size:3;-o-tab-size:3;tab-size:3}.markdown-body .tab-size[data-tab-size="4"]{-moz-tab-size:4;-o-tab-size:4;tab-size:4}.markdown-body .tab-size[data-tab-size="5"]{-moz-tab-size:5;-o-tab-size:5;tab-size:5}.markdown-body .tab-size[data-tab-size="6"]{-moz-tab-size:6;-o-tab-size:6;tab-size:6}.markdown-body .tab-size[data-tab-size="7"]{-moz-tab-size:7;-o-tab-size:7;tab-size:7}.markdown-body .tab-size[data-tab-size="8"]{-moz-tab-size:8;-o-tab-size:8;tab-size:8}.markdown-body .tab-size[data-tab-size="9"]{-moz-tab-size:9;-o-tab-size:9;tab-size:9}.markdown-body .tab-size[data-tab-size="10"]{-moz-tab-size:10;-o-tab-size:10;tab-size:10}.markdown-body .tab-size[data-tab-size="11"]{-moz-tab-size:11;-o-tab-size:11;tab-size:11}.markdown-body .tab-size[data-tab-size="12"]{-moz-tab-size:12;-o-tab-size:12;tab-size:12}.markdown-body
      .task-list-item{list-style-type:none}.markdown-body .task-list-item+.task-list-item{margin-top:3px}.markdown-body .task-list-item input{margin:0 .2em .25em -1.6em;vertical-align:middle}.markdown-body hr{border-bottom-color:#eee}.markdown-body .pl-0{padding-left:0!important}.markdown-body .pl-1{padding-left:4px!important}.markdown-body .pl-2{padding-left:8px!important}.markdown-body .pl-3{padding-left:16px!important}.markdown-body .pl-4{padding-left:24px!important}.markdown-body .pl-5{padding-left:32px!important}.markdown-body .pl-6{padding-left:40px!important}.markdown-body .pl-7{padding-left:48px!important}.markdown-body .pl-8{padding-left:64px!important}.markdown-body .pl-9{padding-left:80px!important}.markdown-body .pl-10{padding-left:96px!important}.markdown-body .pl-11{padding-left:112px!important}.markdown-body .pl-12{padding-left:128px!important}</style>
    <style type="text/css">.markdown-body.override{color:#fff}.markdown-body.override h1,.markdown-body.override h2{border-bottom:1px solid hsla(0,0%,100%,.4)}.markdown-body.override a{color:#fff;text-decoration:underline}.markdown-body.override code{background-color:hsla(0,0%,100%,.1)}.markdown-body.override blockquote{color:#fff}</style>
    <style type="text/css">.language-menu[data-v-7711f32a]{position:absolute;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none;top:15px;text-align:right;right:10px;list-style:none;cursor:pointer;background-color:#de335e;padding:0 2px}.language-menu .other-languages[data-v-7711f32a]{list-style:none;padding:0;margin:5px 0}.language-menu .other-languages li[data-v-7711f32a]{padding:3px 0}</style>
    <style type="text/css">.banner[data-v-4c410b5a]{margin:20px 0;max-width:500px;background-color:#f1045c;border-radius:20px;border:2px solid #f0f0f0;color:#fff;padding:20px;cursor:pointer}.banner .title[data-v-4c410b5a]{font-size:26px;font-weight:900}.banner .subtitle[data-v-4c410b5a],.banner .title[data-v-4c410b5a]{color:#fff;text-shadow:0 0 .5px #ff7b00}.banner .subtitle[data-v-4c410b5a]{font-size:14px;font-weight:700}.banner .button[data-v-4c410b5a]{display:inline-block;border-radius:2px;height:20px;color:#fff;text-align:right;font-weight:900;border:1px solid #fb8500;border-radius:20px;height:40px;line-height:40px;text-decoration:none;background:#ffb703;padding:0 20px;box-shadow:2px 4px 0 #fb8500}</style>
    <style type="text/css">body{background-color:#de335e;webkit-tap-highlight-color:transparent;padding:40px 0}#app,body{color:#fff}#app{font-family:Avenir,Helvetica,Arial,sans-serif;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale;width:100%;display:flex;flex-flow:column;align-items:center;justify-content:center}div.content{margin:0 auto;max-width:500px;padding:10px}svg{border:3px solid #fff;border-radius:150px;padding:4px;width:150px;height:150px}a{color:#fff}</style>
    <script charset="utf-8" src="/js/zh_CN.ebdfefe2.js">
    </script>
    <style type="text/css">.content[data-v-15d0b2f8]{position:relative}.content .button-wrapper[data-v-15d0b2f8]{position:absolute;top:30px;right:10px}</style>
  </head>
  
  <body>
    <script type="text/javascript" async="" src="https://www.google-analytics.com/analytics.js">
    </script>
    <script type="text/javascript" async="" src="https://www.googletagmanager.com/gtag/js?id=G-44799DDNP5&amp;l=dataLayer&amp;cx=c">
    </script>
    <script async="" src="https://www.googletagmanager.com/gtag/js?id=UA-132312622-2">
    </script>
    <script>window.dataLayer = window.dataLayer || [];

      function gtag() {
        dataLayer.push(arguments);
      }
      gtag('js', new Date());

      gtag('config', 'UA-132312622-2');</script>
    <script async="" defer="" src="https://buttons.github.io/buttons.js">
    </script>
    <div id="app">
      <div data-v-7711f32a="" class="language-menu">
        <div data-v-7711f32a="" class="current-language">简体中文</div>
        <ul data-v-7711f32a="" class="other-languages" style="display: none;">
          <!---->
          <li data-v-7711f32a="">English</li>
          <li data-v-7711f32a="">Español</li>
          <li data-v-7711f32a="">Deutsch</li>
          <li data-v-7711f32a="">Français</li>
          <li data-v-7711f32a="">Italiano</li>
          <li data-v-7711f32a="">日本語</li>
          <li data-v-7711f32a="">Русский</li>
        </ul>
      </div>
      <svg xmlns="http://www.w3.org/2000/svg" height="512px" viewBox="0 0 464 464" width="512px">
        <g>
          <path d="m24 144c-4.414062 0-8 3.585938-8 8v120h16v-120c0-4.414062-3.585938-8-8-8zm0 0" data-original="#000000" data-old_color="#ffffff" fill="#ffffff" class="active-path">
          </path>
          <path d="m104 256h-32c-10.414062 0-19.214844 6.710938-22.527344 16h77.046875c-3.304687-9.289062-12.105469-16-22.519531-16zm0 0" data-original="#000000" data-old_color="#ffffff" fill="#ffffff" class="active-path">
          </path>
          <path d="m56 417.472656v-97.472656h-16v97.472656c-9.304688 3.304688-16 12.09375-16 22.527344 0 13.257812 10.742188 24 24 24s24-10.742188 24-24c0-10.433594-6.695312-19.222656-16-22.527344zm0 0" data-original="#000000" data-old_color="#ffffff" fill="#ffffff" class="active-path">
          </path>
          <path d="m0 288h464v16h-464zm0 0" data-original="#000000" data-old_color="#ffffff" fill="#ffffff" class="active-path">
          </path>
          <path d="m48 248.207031c.089844-.070312.160156-.144531.246094-.207031-.085938-.0625-.15625-.136719-.246094-.207031zm0 0" data-original="#000000" data-old_color="#ffffff" fill="#ffffff" class="active-path">
          </path>
          <path d="m101.121094 192h-29.121094c-13.230469 0-24 10.769531-24 24s10.769531 24 24 24h29.121094c13.230468 0 24-10.769531 24-24s-10.769532-24-24-24zm0 0" data-original="#000000" data-old_color="#ffffff" fill="#ffffff" class="active-path">
          </path>
          <path d="m143.191406 272h304.335938c-3.992188-35.945312-34.527344-64-71.527344-64h-192c-11.128906 0-22.257812 2.625-32.191406 7.601562l-11.214844 5.605469c-1.363281 10.3125-6.609375 19.320313-14.289062 25.609375 8.542968 5.769532 14.757812 14.742188 16.886718 25.183594zm0 0" data-original="#000000" data-old_color="#ffffff" fill="#ffffff" class="active-path">
          </path>
          <path d="m413.273438 80-29.882813-69.734375-33.503906 92.140625-9.605469-14.40625h-52.28125v-72c0-8.824219-7.175781-16-16-16h-80c-8.824219 0-16 7.175781-16 16v40h-69.273438l-18.117187 42.265625-30.488281-83.859375-22.402344 33.59375h-35.71875v16h44.28125l9.597656-14.40625 33.503906 92.140625 29.890626-69.734375h58.726562v40c0 8.824219 7.175781 16 16 16h16v24h16v40h16v-40h16v-24h16c8.824219 0 16-7.175781 16-16v-8h43.71875l22.402344 33.59375 30.496094-83.859375 18.109374 42.265625h61.273438v-16zm-157.273438-16h-16v16h-16v-16h-16v-16h16v-16h16v16h16zm0 0" data-original="#000000" data-old_color="#ffffff" fill="#ffffff" class="active-path">
          </path>
          <path d="m424 417.472656v-97.472656h-16v97.472656c-9.304688 3.304688-16 12.09375-16 22.527344 0 13.257812 10.742188 24 24 24s24-10.742188 24-24c0-10.433594-6.695312-19.222656-16-22.527344zm0 0" data-original="#000000" data-old_color="#ffffff" fill="#ffffff" class="active-path">
          </path>
        </g>
      </svg>
      <div data-v-15d0b2f8="" class="content markdown-body override">
        <section data-v-15d0b2f8="">
          <h1>996.ICU</h1>
          <p>“996”工作制，即每天早 9 点到岗，一直工作到晚上 9 点，每周工作 6 天。</p>
          <p>“996”工作制的周工作时间为最低 12x6=72 小时。</p>
          <p>
            <strong>中国大陆工时规管现况（标准工时）：</strong>一天工作时间为 8 小时，平均每周工时不超过 40 小时；加班上限为一天 3 小时及一个月 36 小时，逾时工作薪金不低于平日工资的 150%。而一周最高工时则为 48 小时。平均每月计薪天数为 21.75 天。</p>
          <h2>相关法律法规</h2>
          <h3>
            <a href="http://www.npc.gov.cn/npc/xinwen/2018-03/22/content_2052489.htm">《中华人民共和国宪法》</a>
          </h3>
          <h4>第二章第四十三条：</h4>
          <blockquote>
            <p>中华人民共和国劳动者有休息的权利。
              <br>国家发展劳动者休息和休养的设施，规定职工的工作时间和休假制度。</p>
          </blockquote>
          <h3>
            <a href="http://www.npc.gov.cn/npc/xinwen/2019-01/07/content_2070261.htm">《中华人民共和国劳动法》</a>
          </h3>
          <h4>第一章第三条：</h4>
          <blockquote>
            <p>劳动者享有平等就业和选择职业的权利、
              <strong>取得劳动报酬的权利</strong>、
              <strong>休息休假的权利</strong>、获得劳动安全卫生保护的权利、接受职业技能培训的权利、享受社会保险和福利的权利、提请劳动争议处理的权利以及法律规定的其他劳动权利。</p>
          </blockquote>
          <h4>第四章第三十六条：</h4>
          <blockquote>
            <p>国家实行劳动者每日工作时间不超过八小时、平均每周工作时间不超过四十四小时的工时制度。</p>
          </blockquote>
          <h4>第四章第三十九条：</h4>
          <blockquote>
            <p>企业因生产特点不能实行本法第三十六条、第三十八条规定的，经劳动行政部门批准，可以实行其他工作和休息办法。</p>
          </blockquote>
          <h4>第四章第四十一条：</h4>
          <blockquote>
            <p>用人单位由于生产经营需要，经与工会和劳动者协商后可以延长工作时间，一般每日不得超过一小时；因特殊原因需要延长工作时间的，在保障劳动者身体健康的条件下延长工作时间每日不得超过三小时，但是每月不得超过三十六小时。</p>
          </blockquote>
          <h4>第四章第四十三条：</h4>
          <blockquote>
            <p>用人单位不得违反本法规定延长劳动者的工作时间。</p>
          </blockquote>
          <h4>第四章第四十四条：</h4>
          <blockquote>
            <p>有下列情形之一的，用人单位应当按照下列标准支付高于劳动者正常工作时间工资的工资报酬：
              <br>（一）安排劳动者延长工作时间的，支付不低于工资的百分之一百五十的工资报酬；
              <br>（二）休息日安排劳动者工作又不能安排补休的，支付不低于工资的百分之二百的工资报酬；
              <br>（三）法定休假日安排劳动者工作的，支付不低于工资的百分之三百的工资报酬。</p>
          </blockquote>
          <h4>第十二章第九十条：</h4>
          <blockquote>
            <p>用人单位违反本法规定，延长劳动者工作时间的，由劳动行政部门给予警告，责令改正，并可以处以罚款。</p>
          </blockquote>
          <h4>第十二章第九十一条：</h4>
          <blockquote>
            <p>用人单位有下列侵害劳动者合法权益情形之一的，由劳动行政部门责令支付劳动者的工资报酬、经济补偿，并可以责令支付赔偿金：
              <br>……
              <br>（二）拒不支付劳动者延长工作时间工资报酬的；
              <br>……</p>
          </blockquote>
          <h3>
            <a href="http://www.npc.gov.cn/wxzl/gongbao/2013-04/15/content_1811058.htm">《中华人民共和国劳动合同法》</a>
          </h3>
          <h4>第三章第三十一条：</h4>
          <blockquote>
            <p>用人单位应当严格执行劳动定额标准，不得强迫或者变相强迫劳动者加班。用人单位安排加班的，应当按照国家有关规定向劳动者支付加班费。</p>
          </blockquote>
          <h4>第五章第六十二条：</h4>
          <blockquote>
            <p>用工单位应当履行下列义务：
              <br>……
              <br>（三）支付加班费、绩效奖金，提供与工作岗位相关的福利待遇；
              <br>……</p>
          </blockquote>
          <h4>第七章第八十五条：</h4>
          <blockquote>
            <p>用人单位有下列情形之一的，由劳动行政部门责令限期支付劳动报酬、加班费或者经济补偿；劳动报酬低于当地最低工资标准的，应当支付其差额部分；逾期不支付的，责令用人单位按应付金额百分之五十以上百分之一百以下的标准向劳动者加付赔偿金：
              <br>（一）未按照劳动合同的约定或者国家规定及时足额支付劳动者劳动报酬的；
              <br>（二）低于当地最低工资标准支付劳动者工资的；
              <br>（三）安排加班不支付加班费的；
              <br>……</p>
          </blockquote>
          <h3>
            <a href="http://www.mohrss.gov.cn/SYrlzyhshbzb/zcfg/flfg/xzfg/201604/t20160412_237909.html">《国务院关于职工工作时间的规定》</a>
          </h3>
          <h4>第三条：</h4>
          <blockquote>
            <p>职工每日工作8小时、每周工作40小时。</p>
          </blockquote>
          <h4>第六条：</h4>
          <blockquote>
            <p>任何单位和个人不得擅自延长职工工作时间。因特殊情况和紧急任务确需延长工作时间的，按照国家有关规定执行。</p>
          </blockquote>
          <h3>
            <a href="https://duxiaofa.baidu.com/detail?cid=dd3870dde31884c992ce6c617b248e99_law&amp;searchType=statute">《劳动部贯彻〈国务院关于职工工作时间的规定〉的实施办法》</a>
          </h3>
          <h4>第三条：</h4>
          <blockquote>
            <p>职工每日工作8小时、每周工作40小时。实行这一工时制度，应保证完成生产和工作任务，不减少职工的收入。</p>
          </blockquote>
          <h4>第六条：</h4>
          <blockquote>
            <p>任何单位和个人不得擅自延长职工工作时间。企业由于生产经营需要而延长职工工作时间的，应按《中华人民共和国劳动法》第四十一条的规定执行。</p>
          </blockquote>
          <h4>第八条：</h4>
          <blockquote>
            <p>根据本办法第六条、第七条延长工作时间的，企业应当按照《中华人民共和国劳动法》第四十四条的规定，给职工支付工资报酬或安排补休。</p>
          </blockquote>
          <h2>相关事件报道</h2>
          <ul>
            <li>
              <p>2016 年 9 月初起，陆续有网友爆料称，
                <strong>58同城</strong>实行全员 996 工作制，且周末加班没有工资。公司方面回应称，为应对业务量高峰期，公司每年 9、10 月份都会有动员，属常规性活动，而本次“996 动员”并非强制。（
                <a href="http://finance.cnr.cn/gs/20160901/t20160901_523105136.shtml">58同城实行全员996工作制 被指意图逼员工主动辞职</a>. 央广网. 2016-09-01. ）</p>
            </li>
            <li>
              <p>2019 年 1 月，杭州电商公司
                <strong>有赞</strong>在公司年会宣布未来执行 996 工作制，CEO 白鸦回应“几年后回看，这次绝对是好事”。（
                <a href="http://www.linkshop.com.cn/web/archives/2019/418163.shtml">年会成了“鸿门宴”，这家公司“强制996”被员工举报</a>. 联商网. 2019-01-22. ）</p>
            </li>
            <li>
              <p>2019 年 3 月，曝
                <strong>京东</strong>开始实行分部门的 996 或 995 工作制，京东公关在脉脉平台上表示：“全情投入”。（
                <a href="http://tech.163.com/19/0312/13/EA2QGIOK00097U7R.html">京东回应995工作制：不会强制要求 但要全情投入</a>. 网易科技. 2019-03-12. ）</p>
            </li>
          </ul>
          <hr>
          <p>按照劳动法规定，996 工作制下只有拿到当前工资的
            <strong>2.275</strong>倍，才在经济账上不吃亏。</p>
          <p>什么是 996.ICU？工作 996，生病 ICU。</p>
          <p>
            <strong>Developers' lives matter.</strong>
          </p>
        </section>
      </div>
      <span>
      </span>
    </div>
    </script>
    <input type="hidden" value="chrome_extension" data-id="abcdefghijk" name="chrome_extension">
  </body>

</html>

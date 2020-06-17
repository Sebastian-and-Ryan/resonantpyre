<head>
<meta charset="utf-8">
<meta name="generator" content="hakyll">
<meta name="google-site-verification" content="BOhOQI1uMfsqu_DopVApovk1mJD5ZBLfan0s9go3phk">
<meta name="title" content="Gwern.net Index of Essays">
<meta name="author" content="gwern">
<meta name="description" content="">
<meta name="keywords" content="">

<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Title</title>



<style> /* index-specific: */
      @media only screen and (max-width:64.9ch) { body.siteIndex #markdownBody li { line-height: 1.65; } }

/*  Add some vertical padding for the introduction.
    */
body.siteIndex #markdownBody {
    padding-top: 1.5ch;
}

/*  Make the sections reflow; better than fixed-width tables.
    */
body.siteIndex article section {
    display: inline-block;
    vertical-align: top;
}

/*  No index self-link.
    */
body.siteIndex #sidebar a#logo {
    pointer-events: none;
}
/*  Abstract is not a real abstract.
    */
body.siteIndex #abstract {
    padding: 0;
    border: none;
    margin: 0;
    box-shadow: none;
}

/*  Less fancy headings.
    */
body.siteIndex section:not(.collapse) > h1:first-child {
    font-size: 1.5em;
    line-height: 1.125;
    box-shadow: none;
    text-align: left;
    font-weight: bold;
    margin-left: 0;
    padding: 0;
}

/*  Nice-looking bottom decoration.
    */
body.siteIndex article,
body.tags article {
    position: relative;
    padding-bottom: 4em;
}
body.siteIndex article::after,
body.tags article::after{
    content: "";
    background-color: #fff;
    background-image: url('/images/logo-smooth.svg');
    display: block;
    position: absolute;
    bottom: 0.75em;
    width: 22px;
    height: 30px;
    background-size: contain;
    background-position: center;
    background-repeat: no-repeat;
    left: 0;
    right: 0;
    margin: auto;
    padding: 0 10px 0 11px;
    z-index: 1;
}
body.siteIndex article::before,
body.tags article::before{
    content: "";
    display: block;
    position: absolute;
    bottom: calc(0.75em + 15px);
    height: 1px;
    border-bottom: 1px dotted #000;
    width: 100%;
    opacity: 0.5;
}

/*  Lists on the home page.
    */
body.siteIndex #markdownBody ul,
body.tags #markdownBody ul {
    margin: 1.25em 3em 0 0;
    padding: 0 0 0 1.375em;
}
body.siteIndex #markdownBody li > ul,
body.tags #markdownBody li > ul {
    margin: 0.25em 0 0.25em 0;
}
body.siteIndex #markdownBody li,
body.tags #markdownBody li {
    margin-top: 0;
}
body.siteIndex #markdownBody > section ~ p {
    border-top: 1px dotted #777;
    margin: 2em 0 0 0;
    padding: 1em 0 0 0;
    font-weight: bold;
}

/*  Internal links on the home page need no decoration.
    */
body.siteIndex #markdownBody a[href^="."]:not([href*="/docs/"]):not([href*="/images/"])::after,
body.siteIndex #markdownBody a[href^="https://www.gwern.net/"]:not([href$=".pdf"])::after {
    content: none;
}

@media only screen and (min-width: 120ch) {
    /*  Leave enough horizontal room to show multiple sections simultaneously,
        table-like
        */
    body.siteIndex #markdownBody {
        width: 135ch;
        max-width: calc(50vw + 42ch);
    }
    body.siteIndex p,
    body.siteIndex hr {
        max-width: 97ch;
    }
}
@media only screen and (max-width: 64.9ch) {
    body.siteIndex #sidebar #logo {
        border: 1px dotted transparent;
        align-self: flex-start;
        padding: 7px 5px 6px 5px;
    }
    body.siteIndex #markdownBody section {
        max-width: 100%;
    }
    body.siteIndex #markdownBody ul,
    body.tags #markdownBody ul {
        overflow-wrap: break-word;
        margin-right: 0;
    }
    body.siteIndex #markdownBody li,
    body.tags #markdownBody li {
        padding: 1px 0;
        margin: 2px 0 0 0;
    }
    body.siteIndex #markdownBody ul > li::before,
    body.tags #markdownBody ul > li::before {
        top: 0.25em;
    }
}

      


<style>
    @font-face {
        font-family: 'Source Serif Pro';
        font-weight: 400;
        font-style: normal;
        src: url('/static/font/SourceSerifPro-BASIC-Regular.ttf') format('truetype');
        unicode-range: U+0020-007E, U+2010, U+2013-2014, U+2018-2019, U+201C-201D;
        font-display: swap
    }
    @font-face {
        font-family: 'Source Serif Pro';
        font-weight: 400;
        font-style: italic;
        src: url('/static/font/SourceSerifPro-BASIC-RegularItalic.ttf') format('truetype');
        unicode-range: U+0020-007E, U+2010, U+2013-2014, U+2018-2019, U+201C-201D;
        font-display: swap;
    }
    @font-face {
        font-family: 'Source Serif Pro';
        font-weight: 600;
        font-style: normal;
        src: url('/static/font/SourceSerifPro-BASIC-Semibold.ttf') format('truetype');
        unicode-range: U+0020-007E, U+2010, U+2013-2014, U+2018-2019, U+201C-201D;
        font-display: swap
    }
    @font-face {
        font-family: 'Source Serif Pro';
        font-weight: 700;
        font-style: normal;
        src: url('/static/font/SourceSerifPro-BASIC-Bold.ttf') format('truetype');
        unicode-range: U+0020-007E, U+2010, U+2013-2014, U+2018-2019, U+201C-201D;
        font-display: swap
    }

    @font-face {
        font-family: 'Source Sans Pro';
        font-weight: 400;
        font-style: normal;
        src: url('/static/font/SourceSansPro-BASIC-Regular.ttf') format('truetype');
        unicode-range: U+0020-007E, U+2010, U+2013-2014, U+2018-2019, U+201C-201D;
        font-display: swap
    }
    @font-face {
        font-family: 'Source Sans Pro';
        font-weight: 400;
        font-style: italic;
        src: url('/static/font/SourceSansPro-BASIC-RegularItalic.ttf') format('truetype');
        unicode-range: U+0020-007E, U+2010, U+2013-2014, U+2018-2019, U+201C-201D;
        font-display: swap
    }
    @font-face {
        font-family: 'Source Sans Pro';
        font-weight: 700;
        font-style: normal;
        src: url('/static/font/SourceSansPro-BASIC-Bold.ttf') format('truetype');
        unicode-range: U+0020-007E, U+2010, U+2013-2014, U+2018-2019, U+201C-201D;
        font-display: swap
    }
    </style>

<link rel="preconnect" href="https://www.google-analytics.com">
<link rel="preconnect" href="https://cdnjs.cloudflare.com">
<link rel="preconnect" href="https://stats.g.doubleclick.net">
<link rel="shortcut icon" type="image/x-icon" href="./static/img/favicon.png">
<style id="popups-styles">
#popup-container {
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    pointer-events: none;
    z-index: 3;
}
#popup-container > * {
    pointer-events: auto;
}
@media not screen and (hover:hover) and (pointer:fine) {
    #popup-container.popup-visible::before {
        content: "";
        position: absolute;
        left: 0;
        right: 0;
        top: 0;
        bottom: 0;
        pointer-events: auto;
        background-color: #000;
        opacity: 0.4;
    }
}

#popupdiv {
    z-index: 10001;
    font-size: 0.8em;
    box-shadow: 0 0 0 2px #fff;
    position: absolute;
    opacity: 1.0;
    transition: none;
    touch-action: none;
    user-select: none;
}
#popupdiv.fading {
    opacity: 0.0;
    transition:
        opacity 0.75s ease-in 0.1s;
}
#popupdiv > div {
    background-color: #fff;
    padding: 12px 16px 14px 16px;
    border: 3px double #aaa;
    line-height: 1.45;
    overflow: auto;
    overscroll-behavior: none;
    touch-action: none;
    user-select: none;
    min-width: 360px;
    max-width: 640px;
    max-height: calc(100vh - 2 * 3px - 26px);
}
/* TODO: the popups should ideally inherit from the regular CSS once the #markdownBody class is rewritten, and the underlining can be removed */
#popupdiv a { text-decoration: underline; }
#popupdiv a:hover { color: #888; }
#popupdiv > div .data-field {
    text-align: left;
    text-indent: 0;
    hyphens: none;
}
#popupdiv > div .data-field + .data-field {
    margin-top: 0.25em;
}
#popupdiv > div .data-field:empty {
    display: none;
}
#popupdiv > div .data-field.title {
    font-weight: bold;
    font-size: 1.125em;
}
#popupdiv > div .data-field.author-plus-date {
    font-style: italic;
}
#popupdiv > div .data-field.abstract {
    text-align: justify;
    text-indent: 2em;
    hyphens: auto;
}
#popupdiv > div.popup-screenshot {
    padding: 0;
    max-width: unset;
}
#popupdiv > div.popup-screenshot img {
    display: block;
}
#popupdiv > div.popup-screenshot a::after {
    content: none;
}
#popupdiv > div.popup-section-embed,
#popupdiv > div.popup-citation-context {
    height: 100%;
    padding: 12px 24px 14px 24px;
    overflow-x: hidden;
}
#popupdiv > div.popup-section-embed > h1:first-child,
#popupdiv > div.popup-section-embed > h2:first-child,
#popupdiv > div.popup-section-embed > h3:first-child,
#popupdiv > div.popup-section-embed > h4:first-child  {
    margin-top: 0;
}
#popupdiv > div.popup-section-embed > :last-child {
    margin-bottom: 12px;
}
#popupdiv > div .icon {
    background-image: none !important;
    position: relative;
    top: 0.15em;
    font-size: 1.125em;
}
#popupdiv > div .icon::after {
    margin: 0 0.175em 0 0;
    width: 1em;
    height: 1em;
    font-size: 1em;
}
#popupdiv > div .icon:not([href*='.pdf'])::after {
    background-position: center center;
    background-size: 100%;
}
#popupdiv > div .title-link::after {
    content: none;
}

/*  Scroll bar styles (Webkit/Blink only).
    */
#popupdiv > div::-webkit-scrollbar {
    width: 14px;
}
#popupdiv > div::-webkit-scrollbar-thumb {
    background-color: #ccc;
    box-shadow:
        0 0 0 3px #fff inset;
}
#popupdiv > div::-webkit-scrollbar-thumb:hover {
    background-color: #999;
}

/*  Popups on mobile.
    */
@media only screen and (max-width: 64.9ch), not screen and (hover:hover) and (pointer:fine) {
    #popupdiv > div {
        max-width: 100%;
    }
}

/*  Image focus interaction.
    */
#markdownBody #popupdiv img {
    filter: none;
    cursor: initial;
    transform: none;
}
#markdownBody #popupdiv .popup-screenshot a img {
    cursor: pointer;
}

#popupdiv .originalURL {
  font-size: 75%;
}

</style><style id="mode-selector-styles">
    #mode-selector {
        position: absolute;
        right: 3px;
        top: 4px;
        display: flex;
        background-color: #fff;
        padding: 0.125em 0.25em;
        border: 3px solid transparent;
        opacity: 0.3;
        transition:
            opacity 2s ease;
    }
    #mode-selector.hidden {
        opacity: 0;
    }
    #mode-selector:hover {
        transition: none;
        opacity: 1.0;
        border: 3px double #aaa;
    }
    #mode-selector button {
        -moz-appearance: none;
        appearance: none;
        border: none;
        background-color: transparent;
        padding: 0.5em;
        margin: 0;
        line-height: 1;
        font-family: Lucida Sans Unicode, Source Sans Pro, Helvetica, Trebuchet MS, sans-serif;
        font-size: 0.75rem;
        text-align: center;
        color: #777;
        position: relative;
    }
    #mode-selector button:hover,
    #mode-selector button.selected {
        box-shadow:
            0 2px 0 6px #fff inset,
            0 1px 0 6px currentColor inset;
    }
    #mode-selector button:not(:disabled):hover {
        color: #000;
        cursor: pointer;
    }
    #mode-selector button:not(:disabled):active {
        transform: translateY(2px);
        box-shadow:
            0 0px 0 6px #fff inset,
            0 -1px 0 6px currentColor inset;
    }
    #mode-selector button.active:not(:hover)::after {
        content: "";
        position: absolute;
        bottom: 0.25em;
        left: 0;
        right: 0;
        border-bottom: 1px dotted currentColor;
        width: calc(100% - 12px);
        margin: auto;
    }
    </style><style id="mode-styles">@media (prefers-color-scheme:dark) {
    :root {
        --GW-blockquote-background-color: #ddd
    }
    body::before,
    body > * {
        filter: invert(90%)
    }
    body::before {
        content: '';
        width: 100vw;
        height: 100%;
        position: fixed;
        left: 0;
        top: 0;
        background-color: #fff;
        z-index: -1
    }
    img,
    video {
        filter: invert(100%);
    }
    #markdownBody, #mode-selector button {
        text-shadow: 0 0 0 #000
    }
    article > :not(#TOC) a:link {
        text-shadow:
                 0      0 #777,
             .03em      0 #fff,
            -.03em      0 #fff,
                 0  .03em #fff,
                 0 -.03em #fff,
             .06em      0 #fff,
            -.06em      0 #fff,
             .09em      0 #fff,
            -.09em      0 #fff,
             .12em      0 #fff,
            -.12em      0 #fff,
             .15em      0 #fff,
            -.15em      0 #fff
    }
    article > :not(#TOC) blockquote a:link {
        text-shadow:
                 0      0 #777,
             .03em      0 var(--GW-blockquote-background-color),
            -.03em      0 var(--GW-blockquote-background-color),
                 0  .03em var(--GW-blockquote-background-color),
                 0 -.03em var(--GW-blockquote-background-color),
             .06em      0 var(--GW-blockquote-background-color),
            -.06em      0 var(--GW-blockquote-background-color),
             .09em      0 var(--GW-blockquote-background-color),
            -.09em      0 var(--GW-blockquote-background-color),
             .12em      0 var(--GW-blockquote-background-color),
            -.12em      0 var(--GW-blockquote-background-color),
             .15em      0 var(--GW-blockquote-background-color),
            -.15em      0 var(--GW-blockquote-background-color)
    }
    #logo img {
        filter: none;
    }
    #mode-selector {
        opacity: 0.6;
    }
    #mode-selector:hover {
        background-color: #fff;
    }
}</style></head>

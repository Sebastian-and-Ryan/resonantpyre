<head>
<meta charset="utf-8">
<meta name="generator" content="hakyll">
<meta name="google-site-verification" content="BOhOQI1uMfsqu_DopVApovk1mJD5ZBLfan0s9go3phk">
<meta name="title" content="Gwern.net Index of Essays">
<meta name="author" content="gwern">
<meta name="description" content="Writer, self-experimenter, and programmer: psychology, statistics, and technology. This index page is a categorized list of gwern.net pages.">
<meta name="keywords" content="statistics, darknet markets, Bitcoin, blinded self-experiments, Quantified Self, dual n-back, spaced repetition, modafinil, literary criticism">
<meta name="dc.date.issued" content="27 January 2009">
<meta name="dcterms.modified" content="2 june 2020">
<link rel="canonical" href="https://www.gwern.net/index">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Essays - Gwern.net</title>

<link rel="preload" href="/images/logo-smooth.svg" as="image" type="image/svg+xml">


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

      /* general */
      :root{--GW-blockquote-background-color:#f5f5f5}html{padding:0;margin:0;background-color:#fff;color:#000;font-weight:400;font-family:'Source Serif Pro',Baskerville,'Libre Baskerville',serif}body{max-width:112ch}@media only screen and (max-width:64.9ch){html{font-size:18px}}@media only screen and (min-width:65ch){body{padding:0 1.5ch 0 .5ch;margin:0 auto}@media only screen and (min-width:118.5ch){body{padding:0 6ch 0 .5ch}}main{min-height:100vh;display:flex;flex-flow:column}@media only screen and (min-width:176.1ch){main{position:relative;right:4ch}}@supports (-moz-user-focus:normal){@media only screen and (min-width:176.1ch){main{right:0}}}article{flex:1 1 auto}#sidebar{position:absolute}article,header{margin-left:15ch}@media only screen and (max-width:120ch){article,header{margin-left:14.5ch}}@media only screen and (max-width:112ch){article,header{margin-left:14ch}}@media only screen and (max-width:104ch){article,header{margin-left:13.5ch}}@media only screen and (max-width:96ch){article,header{margin-left:13ch}}}@media only screen and (max-width:64.9ch){body{margin:0 1ch}}#sidebar code{border:none;background-color:transparent;padding:0}#sidebar a{display:block}@media only screen and (min-width:65ch){#sidebar{font-variant:small-caps;padding:0 4ch 0 1ch;width:10ch}#sidebar a#logo{margin:1em 0 2em 0}#sidebar a#logo img{width:64px}#sidebar a.patreon{border-top:1px dotted #aaa}#sidebar a.new{box-shadow:0 1.125em 0 0 #fff inset}#sidebar a.patreon{font-size:.9em;margin-top:1.375em;padding-top:1.25em;box-shadow:0 1.25em 0 0 #fff inset;white-space:nowrap}#sidebar a.mail,#sidebar a.r_gwern{line-height:1;padding-left:.25em;font-size:1.05em}#sidebar a.mail::before,#sidebar a.r_gwern::before{content:'°\2007';text-shadow:0 0 0 #000;position:relative;top:.25em}#sidebar code{font-variant:none;text-transform:uppercase;font-size:.7em}}@media only screen and (max-width:64.9ch){#sidebar{justify-content:center;margin:0 0 .5em 0}#sidebar a{border:1px dotted #000;padding:3px 10px;text-align:center;margin:1px}#sidebar a#logo{padding:8px 5px 3px 5px}#sidebar,#sidebar-links{display:flex}#sidebar-links{flex-flow:row wrap;margin:.5em 0 0 0}#sidebar a.links,#sidebar a.site{flex:1 1 20%}#sidebar a.mail,#sidebar a.new,#sidebar a.r_gwern{padding:3px 10px;flex:1 1 auto}#sidebar a.patreon{display:none}#sidebar #logo{margin:calc(.5em + 1px) 1px 1px 0}#sidebar #logo img{width:2.5rem}}header{overflow:auto}header h1{margin:.75em 0;text-align:center;text-transform:none;font-variant:small-caps;font-size:2.5em;line-height:1.15;font-weight:600;letter-spacing:-1px}@media only screen and (max-width:64.9ch){header h1{font-size:2em}}#page-metadata hr{display:none}#page-metadata{margin:0 0 2rem 0;overflow:auto;font-size:.95em;line-height:1.5}#page-metadata #page-description{display:block;margin:0 auto .5em auto}#page-metadata #page-description+br{display:none}#page-metadata span:nth-of-type(n+3){white-space:nowrap}#TOC{border:1px solid #ccc;background-color:#f9f9f9;font-family:'Lucida Sans Unicode','Source Sans Pro',Helvetica,'Trebuchet MS',sans-serif;margin:0 2rem 1.5rem 0;line-height:1.25;padding:10px 10px 2px 14px;position:relative;z-index:1}#TOC:empty{display:none}@media only screen and (max-width:128ch){#TOC{font-size:.95rem}}@media only screen and (max-width:120ch){#TOC{font-size:.9rem}}@media only screen and (max-width:112ch){#TOC{font-size:.85rem;margin:0 1.5rem 1.25rem 0}}@media only screen and (max-width:104ch){#TOC{font-size:.8rem;margin:0 1.25rem 1rem 0}}@media only screen and (max-width:96ch){#TOC{margin:0 1rem 1rem 0}}@media only screen and (min-width:90ch){#TOC{float:left;max-width:30ch}}@media only screen and (max-width:90ch){#TOC{float:none;margin:2em auto;font-size:1rem}#TOC>ul>li>ul{column-count:2}}@media only screen and (max-width:64.9ch){#TOC a{display:inline-block}#TOC>ul>li>ul{column-count:1}#TOC li li a{padding:0 0 1px 0}#TOC li li li a{padding:0 0 2px 0}#TOC li li li li a{padding:0 0 3px 0}#TOC li li li li a{padding:0 0 4px 0}}#TOC ul{list-style-type:none;padding-left:0;margin-bottom:0;margin-top:4px;padding-left:1.4em;text-indent:0;padding:0}#TOC ul ul{list-style-type:none;padding-left:.7em;margin-top:2px}#TOC li{font-weight:700;margin:5px 0 10px 0;padding-left:1.125em;position:relative;overflow-wrap:break-word}#TOC li li{margin-bottom:0;font-weight:400;font-size:.9em}#TOC p{margin-top:9px;margin-bottom:3px}#TOC a{border:0;display:block;position:relative}#TOC a:hover{background-color:rgba(0,0,0,.05);color:#000}#TOC a:hover::after{content:'';display:inline-block;position:absolute;left:100%;top:0;background-color:#ccc;width:.25em;height:100%}#TOC code{font-family:inherit;font-size:inherit;border:none;padding:0;background-color:inherit}#TOC>ul{counter-reset:htoc_1}#TOC>ul>li::before{counter-increment:htoc_1;content:counter(htoc_1) '\2006  '}#TOC>ul ul{counter-reset:htoc_2}#TOC>ul ul li::before{counter-increment:htoc_2;content:counter(htoc_1) '.' counter(htoc_2) '\2006  '}#TOC>ul ul ul{counter-reset:htoc_3}#TOC>ul ul ul li::before{counter-increment:htoc_3;content:counter(htoc_1) '.' counter(htoc_2) '.' counter(htoc_3) '\2006  '}#TOC>ul ul ul ul{counter-reset:htoc_4}#TOC>ul ul ul ul li::before{counter-increment:htoc_4;content:counter(htoc_1) '.' counter(htoc_2) '.' counter(htoc_3) '.' counter(htoc_4) '\2006  '}#TOC>ul ul ul ul ul{counter-reset:htoc_5}#TOC>ul ul ul ul ul li::before{counter-increment:htoc_5;content:counter(htoc_1) '.' counter(htoc_2) '.' counter(htoc_3) '.' counter(htoc_4) '.' counter(htoc_5) '\2006  '}#TOC>ul ul ul ul ul ul{counter-reset:htoc_6}#TOC>ul ul ul ul ul ul li::before{counter-increment:htoc_6;content:counter(htoc_1) '.' counter(htoc_2) '.' counter(htoc_3) '.' counter(htoc_4) '.' counter(htoc_5) '.' counter(htoc_6) '\2006  '}#TOC ul li::before{position:absolute;right:calc(100% - 1em);width:12ch;text-align:right;font-weight:400;opacity:.4;pointer-events:none}#TOC ul li:hover::before{opacity:.7}#markdownBody{overflow-wrap:break-word}@media only screen and (min-width:176.1ch){#markdownBody{position:relative}}@media only screen and (min-width:65ch){@media only screen and (max-width:100ch){#markdownBody{line-height:1.45}}@media only screen and (min-width:100.1ch) and (max-width:120ch){#markdownBody{line-height:1.5}}@media only screen and (min-width:120.1ch){#markdownBody{line-height:1.55}}}@supports (-webkit-hyphens:auto) or (-ms-hyphens:auto) or (hyphens:auto){#markdownBody li,#markdownBody p{text-align:justify;-webkit-hyphens:auto;-ms-hyphens:auto;hyphens:auto}}#markdownBody p{font-variant-numeric:oldstyle-nums}#abstract blockquote{margin:0 0 1.5em 0;box-shadow:0 0 0 5px #fff inset;border-color:#bbb;padding:.9rem 1.25rem .95rem 1.25rem}h1{margin:1.25em 0 .5em -.75rem;font-weight:700;position:relative}@media only screen and (max-width:65ch){h1{margin:1.25em 0 .5em 0}}h1{font-feature-settings:'smcp';font-size:1.75em;line-height:1.25;letter-spacing:-.75px}a{color:#3c3c3c;text-decoration:none}#markdownBody a{word-wrap:break-word}article>:not(#TOC) a:link{text-decoration:none;background-image:linear-gradient(#fff,#fff),linear-gradient(#fff,#fff),linear-gradient(#333,#333);background-size:.05em 1px,.05em 1px,1px 1px;background-repeat:no-repeat,no-repeat,repeat-x;background-position:0 90%,100% 90%,0 90%;text-shadow:.03em 0 #fff,-.03em 0 #fff,0 .03em #fff,0 -.03em #fff,.06em 0 #fff,-.06em 0 #fff,.09em 0 #fff,-.09em 0 #fff,.12em 0 #fff,-.12em 0 #fff,.15em 0 #fff,-.15em 0 #fff;font-variant-numeric:lining-nums}article>:not(#TOC) a:hover{background-image:linear-gradient(#fff,#fff),linear-gradient(#fff,#fff),linear-gradient(#999,#999)}#markdownBody ol,#markdownBody ul{list-style-type:none;margin:1.25em 0 1.5em 0;padding:0 0 0 2.5em;overflow:hidden}#markdownBody li>ol,#markdownBody li>ul{margin:.5em 0}#markdownBody ol>li,#markdownBody ul>li{position:relative;margin:0}#markdownBody ol>li:nth-of-type(n+2),#markdownBody ul>li:nth-of-type(n+2){margin:.5em 0 0 0}#markdownBody ol>li::before,#markdownBody ul>li::before{position:absolute;z-index:1}@media only screen and (max-width:64.9ch){#markdownBody ol,#markdownBody ul{padding:0 0 0 1.75em}}blockquote{margin:1.625em 0 1.75em 0;border:1px solid #ccc;font-size:.95em;padding:1em 1.25em}@media only screen and (min-width:65ch){blockquote{overflow:hidden}}@media only screen and (max-width:64.9ch){blockquote{margin:1.25em 0 1.5em 0}}blockquote,blockquote blockquote blockquote,blockquote blockquote blockquote blockquote blockquote{z-index:-2;background-color:var(--GW-blockquote-background-color)}blockquote blockquote,blockquote blockquote blockquote blockquote,blockquote blockquote blockquote blockquote blockquote blockquote{background-color:#e6e6e6}article>:not(#TOC) a:link q,article>:not(#TOC) blockquote a:link,article>:not(#TOC) blockquote blockquote blockquote a:link,article>:not(#TOC) blockquote blockquote blockquote blockquote blockquote a:link,article>:not(#TOC) q a:link,article>:not(#TOC) span.quote-mark.open+a:link{text-shadow:.03em 0 var(--GW-blockquote-background-color),-.03em 0 var(--GW-blockquote-background-color),0 .03em var(--GW-blockquote-background-color),0 -.03em var(--GW-blockquote-background-color),.06em 0 var(--GW-blockquote-background-color),-.06em 0 var(--GW-blockquote-background-color),.09em 0 var(--GW-blockquote-background-color),-.09em 0 var(--GW-blockquote-background-color),.12em 0 var(--GW-blockquote-background-color),-.12em 0 var(--GW-blockquote-background-color),.15em 0 var(--GW-blockquote-background-color),-.15em 0 var(--GW-blockquote-background-color)}article>:not(#TOC) blockquote blockquote a:link,article>:not(#TOC) blockquote blockquote blockquote blockquote a:link,article>:not(#TOC) blockquote blockquote blockquote blockquote blockquote blockquote a:link{text-shadow:.03em 0 #e6e6e6,-.03em 0 #e6e6e6,0 .03em #e6e6e6,0 -.03em #e6e6e6,.06em 0 #e6e6e6,-.06em 0 #e6e6e6,.09em 0 #e6e6e6,-.09em 0 #e6e6e6,.12em 0 #e6e6e6,-.12em 0 #e6e6e6,.15em 0 #e6e6e6,-.15em 0 #e6e6e6}blockquote blockquote{margin:1em 1px}#markdownBody blockquote blockquote:first-child{margin:.25em 1px 1em 1px}#markdownBody blockquote>:last-child,#markdownBody blockquote>:last-child>:last-child,#markdownBody blockquote>:last-child>:last-child>:last-child,#markdownBody blockquote>:last-child>:last-child>:last-child>:last-child{margin-bottom:0}#markdownBody blockquote>:first-child,#markdownBody blockquote>:first-child>:first-child,#markdownBody blockquote>:first-child>:first-child>:first-child,#markdownBody blockquote>:first-child>:first-child>:first-child>:first-child{margin-top:0}#markdownBody blockquote>:last-child>:last-child>:last-child>table:last-child,#markdownBody blockquote>:last-child>:last-child>table:last-child,#markdownBody blockquote>:last-child>table:last-child,#markdownBody blockquote>table:last-child{margin-bottom:.5em}#markdownBody blockquote>:first-child>:first-child>:first-child>table:first-child,#markdownBody blockquote>:first-child>:first-child>table:first-child,#markdownBody blockquote>:first-child>table:first-child,#markdownBody blockquote>table:first-child{margin-top:.5em}#markdownBody blockquote>ol:only-child,#markdownBody blockquote>ul:only-child{margin-left:1.5em}blockquote p>a:first-child code:first-child,blockquote p>code:first-child{border:none;background-color:transparent;font-weight:700;font-family:inherit;padding:0;font-size:inherit}blockquote table{font-size:.7em}p{margin:0}p+p{text-indent:2.5em}@media only screen and (max-width:64.9ch){p+p{text-indent:1em}}code{padding:0 4px;font-family:'Liberation Mono',Consolas,Courier,monospace;font-size:.9em;border:1px solid #c8c8c8;background-color:#fafafa}pre{overflow:auto;margin:1.75em auto;border:1px solid #c8c8c8;background-color:#fafafa;cursor:text;max-height:calc(100vh - 8em)}pre code{display:block;padding:8px 14px;margin:0;border:none;background-color:transparent}span.smallcaps{font-feature-settings:'smcp'}span.allcaps{text-transform:uppercase}hr{border:none;height:0;border-bottom:1px solid #aaa;margin:1em 0}#adsense{display:block;text-align:center;display:none}#adsense a img{max-width:100%}</style>
<link rel="preload" as="style" href="/static/css/default.css">
<link rel="preload" href="/static/font/SourceSansPro-BASIC-Regular.ttf" as="font" type="font/ttf" crossorigin="anonymous">
<link rel="preload" href="/static/font/SourceSansPro-BASIC-RegularItalic.ttf" as="font" type="font/ttf" crossorigin="anonymous">
<link rel="preload" href="/static/font/SourceSansPro-BASIC-Semibold.ttf" as="font" type="font/ttf" crossorigin="anonymous">
<link rel="preload" href="/static/font/SourceSerifPro-BASIC-Bold.ttf" as="font" type="font/ttf" crossorigin="anonymous">
<link rel="preload" href="/static/font/SourceSerifPro-BASIC-Regular.ttf" as="font" type="font/ttf" crossorigin="anonymous">
<link rel="preload" href="/static/font/SourceSerifPro-BASIC-Semibold.ttf" as="font" type="font/ttf" crossorigin="anonymous">
<link rel="preload" href="/static/font/SourceSerifPro-BASIC-SemiboldItalic.ttf" as="font" type="font/ttf" crossorigin="anonymous">
<link rel="preload" href="/static/font/SourceSerifPro-BASIC-RegularItalic.ttf" as="font" type="font/ttf" crossorigin="anonymous">


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

---
title: HackMD Medium Theme
description: Medium styled markdown css, to use this, add `{% hackmd @yukai/medium-theme %}` in your HackMD note
tags: theme
TODOs:
    - revisit heading from h1~h6
    - Screenshot
    - alternative blockquote style
    - tables
---

<style>
.markdown-body img + strong {
    display: block; 
    text-align: center;
    font-weight: normal;
    margin-top: 10px;
    color:  rgba(0, 0, 0, 0.54);
    font-size: 16px;
}

.markdown-body .alert.alert-info {
    background: rgba(0, 0, 0, 0.05);
    border: none;
    border-radius: 0px;
    font-size: 16px;
}

.markdown-body .alert.alert-info p {
    font-family: Menlo, Monaco, "Courier New", Courier, monospace;
    white-space: pre-wrap;
}

.markdown-body blockquote {
    font-family: medium-content-title-font, Georgia, Cambria, "Times New Roman", Times, serif;
    padding-left: 30px;
    border: none;
    font-size: 30px;
    font-weight: 400;
    letter-spacing: -0.014em;
    line-height: 1.48;
}

.markdown-body hr {
    background-color: transparent;
    height: auto;
    text-align: center;
    font-size: 28px;
    margin-left: auto;
    margin-right: auto;
    margin: 24px 0 32px;
}

.markdown-body hr:before {
    content: "...";
    line-height: 1.4;
    font-style: italic;
    text-indent: 0.6em;
    letter-spacing: 0.6em;
}


.markdown-body blockquote p {
    color: rgba(0, 0, 0, 0.54);
}

/* centered image */
.markdown-body img {
    display: block;
    margin-left: auto;
    margin-right: auto;
}

.markdown-body h1 {
    font-size: 40px;
    border: none;
}

.markdown-body h2 {
    border: none;
}

.markdown-body h1:first-child + h2 {
    color: rgba(0, 0, 0, 0.54);
    margin-top: -28px;
    font-weight: 300;
    font-size: 24px;
}

.markdown-body h6[id^="tags"] {
    font-size: 15px;
    margin-left: -42px;
    color: transparent;
}

.markdown-body h6[id^="tags"] > a {
    margin-right: -42px;
}

.markdown-body h6[id^="tags"] > a, 
.markdown-body h6[id^="tags"] > code { 
    color: rgba(0, 0, 0, 0.54) !important;
}
.markdown-body h6[id^="tags"] > code {
    font-family: medium-content-sans-serif-font, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
    padding: 5px 10px;
}

.markdown-body p {
    font-family: 'Noto Serif TC', medium-content-serif-font, Georgia, Cambria, "Times New Roman", Times, serif;
    line-height: 1.58;
    color: rgba(0, 0, 0, 0.84);
}

.markdown-body p, .markdown-body blockquote, .markdown-body ul, .markdown-body ol, .markdown-body dl, .markdown-body table, .markdown-body pre {
    margin-bottom: 2em;
}

.markdown-body > ol, .markdown-body > ul {
    font-family: 'Noto Serif TC', medium-content-serif-font, Georgia, Cambria, "Times New Roman", Times, serif;
    color: rgba(0, 0, 0, 0.84);
}

.markdown-body > table {
    font-size: 16px;
}

@media screen and (max-width: 727.98px) and (min-width: 552px) {
    .markdown-body {
        font-size: 18px;
    }
    
    .markdown-body h2 {
        font-size: 24px;
    }
    
    .markdown-body p > img {
        margin-top: 20px;
    }
}

@media screen and (max-width: 903.98px) and (min-width: 728px) {
    .markdown-body {
        font-size: 21px;
    }
    
    .markdown-body h2 {
        font-size: 26px;
    }

    .markdown-body p > img {
        margin-top: 36px;
    }
}

@media screen and (max-width: 1079.98px) and (min-width: 904px) {
    .markdown-body {
        font-size: 21px;
    }

    .markdown-body h2 {
        font-size: 26px;
    }

    .markdown-body p > img {
        margin-top: 36px;
    }
}

@media screen and (min-width: 1080px) {
    .markdown-body {
        font-size: 21px;
    }

    .markdown-body h2 {
        font-size: 26px;
    }

    .markdown-body p > img {
        margin-top: 36px;
    }
}

#doc.markdown-body {
    font-family: medium-content-sans-serif-font, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
    padding-left: 24px;
    padding-right: 24px;
    
    width: 100%;
}

.markdown-body pre > code {
    font-size: 15px;
}


.markdown-body > p > img {
    max-width: calc(1032px);
    position: relative;
    margin-left: 50%;
    transform: translateX(-50%);
}

@media screen and (max-width: 1079.98px) {
    .markdown-body > p > img {
        max-width: 100%;
        transform: unset;
        margin-left: auto;
        margin-right: auto;
    }
}

body > #ui-toc-affix {
    display: none !important;
}

.markdown-body a,  .markdown-body a:hover, .markdown-body a:active {
    text-decoration: underline;
    color: inherit;
}

</style>

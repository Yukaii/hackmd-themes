---
title: conversational theme
tags: theme
description: 使用方法：以 `---` 分隔線來區隔不同人的對話，分隔線後第一個段落會被當成講者。 `{%hackmd @yukai/conversational-theme %}`
image: https://i.imgur.com/wrDi84K.png
---

<style>


.markdown-body hr ~ p, 
.markdown-body hr ~ blockquote, 
.markdown-body hr ~ ul, 
.markdown-body hr ~ ol, 
.markdown-body hr ~ dl, 
.markdown-body hr ~ table, 
.markdown-body hr ~ pre {
    border-radius: 5px;
    background-color: #f3f3f3;
    margin-left: 1em;
    margin: 10px 0px !important;
    padding: 10px;
    border: 1px solid #dadada;
}

.markdown-body * {
    position: relative;
}

hr {
    visibility: hidden;
}

.markdown-body hr + p, 
.markdown-body hr + blockquote, 
.markdown-body hr + ul, 
.markdown-body hr + ol, 
.markdown-body hr + dl, 
.markdown-body hr + table, 
.markdown-body hr + pre {
    background-color: transparent;
    margin-left: 0px;
    margin-bottom: 20px !important;
    display: inline-block;
    border-style: solid;
    border-width: 1px;
    border-color: #c1c1c1;
}

.markdown-body hr + p:before, 
.markdown-body hr + blockquote:before, 
.markdown-body hr + ul:before, 
.markdown-body hr + ol:before, 
.markdown-body hr + dl:before, 
.markdown-body hr + table:before, 
.markdown-body hr + pre:before {
    content: '';
    position: absolute;
    bottom: -33px;
    left: 19px;
    width: 0;
    height: 0;
    border-style: solid;
    border-width: 0 22px 18px 22px;
    border-color: transparent transparent #c1c1c1 transparent;
}

.markdown-body hr + p:after, 
.markdown-body hr + blockquote:after, 
.markdown-body hr + ul:after, 
.markdown-body hr + ol:after, 
.markdown-body hr + dl:after, 
.markdown-body hr + table:after, 
.markdown-body hr + pre:after {
    content: '';
    position: absolute;
    bottom: -32px;
    left: 21px;
    width: 0;
    height: 0;
    border-style: solid;
    border-width: 0 20px 16px 20px;
    border-color: transparent transparent #f3f3f3 transparent;
}

.markdown-body hr + hr ~ p, 
.markdown-body hr + hr ~ blockquote, 
.markdown-body hr + hr ~ ul, 
.markdown-body hr + hr ~ ol, 
.markdown-body hr + hr ~ dl, 
.markdown-body hr + hr ~ table, 
.markdown-body hr + hr ~ pre {
    margin-top: 0 !important;
    margin-bottom: 16px !important;
    background-color: transparent;
    border: none;
    padding: initial;
}


.markdown-body hr + hr + p:before, 
.markdown-body hr + hr + blockquote:before, 
.markdown-body hr + hr + ul:before, 
.markdown-body hr + hr + ol:before, 
.markdown-body hr + hr + dl:before, 
.markdown-body hr + hr + table:before, 
.markdown-body hr + hr + pre:before {
    display: none;
}

</style>


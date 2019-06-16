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
    background-color: #e7e7e7;
    margin-left: 1em;
    margin: 10px 0px !important;
    padding: 10px;
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
    border-color: #4F4F4F;
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
    border-width: 0 20px 16px 20px;
    border-color: transparent transparent #E7E7E7 transparent;
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


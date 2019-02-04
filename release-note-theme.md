---
title: Release note theme
description: A release note style HackMD template theme
image: https://i.imgur.com/r2YLGhE.png
tags: theme
---

<style>
body > #doc.markdown-body span.date {
    float: right;
    font-size: 0.7em;
    margin-top: 0.7em;
    color: gray;
    font-weight: 100;
}

body > #doc.markdown-body ul {
    padding-left: 0;
}

body > #doc.markdown-body li {
    list-style-type: none;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    align-items: center;    
}

body > #doc.markdown-body span.block {
    text-transform: uppercase;
    font-family: "Source Code Pro", monospace;
    font-size: 0.9em;
    color: white;
    padding: 0.2em 0.6em;
    border-radius: 7px;
    min-width: 100px;
    margin-right: 1em;
    text-align: center;    

    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;    
}

body > #doc.markdown-body span.block.new {
  background-color: #5CC869;
}

body > #doc.markdown-body span.block.improve {
  background-color: #62BAEF;
}

body > #doc.markdown-body span.block.fix {
  background-color: #EF6C5A;
}
</style>
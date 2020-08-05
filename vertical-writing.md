---
title: HackMD 主題：中文直書 (Vertical writing theme)
tags: theme
description: 由於直書編輯不易，本主題僅顯示於發表後的靜態頁面，請使用 `{%hackmd theme-vertical-writing %}` 語法來使用此主題。This theme applies only to published static pages. It changes content layout to vertical writing common in many Asian languages. Use `{%hackmd theme-vertical-writing %}` syntax to include this theme.
---
 
<style>
body > .ui-infobar {
    max-width: 70vw !important;
}

body > #doc.markdown-body {
    writing-mode: vertical-rl;
    overflow-x: scroll !important;
    font-size: 18px;
    width: 100vw !important;
    padding: 1em 2em;
    max-width: 100vw;
    height: calc(100vh - 107px);
    max-width: calc(70vw) !important;
    letter-spacing: 0em !important;
}

body > #doc li.task-list-item {
    position: relative;
}

body > #doc li.task-list-item > input[type="checkbox"].task-list-item-checkbox {
    position: absolute;
    top: -1.3em;
    right: 7px;
}

body > #ui-toc-affix {
    position: fixed;
    right: 0px;
    left: unset !important;
}

/* scrollbar patch */


	/* customize scrollbar css */
	body > #doc::-webkit-scrollbar{
		width:6px;
		background-color:#cccccc;
	}
	body > #doc::-webkit-scrollbar:horizontal{
		height:6px;
	}
	body > #doc::-webkit-scrollbar-track{
		border:1px #ffffff solid;
		border-radius:2px;
		-webkit-box-shadow:0 0 6px #c8c8c8 inset;
	}
	body > #doc::-webkit-scrollbar-thumb{
		background-color:#5e5e5e;
		border:1px solid #ffffff;
		border-radius:3px;
	}
	body > #doc::-webkit-scrollbar-thumb:hover{
		background-color:#000000;
		border:1px solid #333333;
	}
	body > #doc::-webkit-scrollbar-thumb:active{
		background-color:#666666;
		border:1px solid #ffffff;
	}

/* end scrollbar patch */

body > #doc.markdown-body blockquote {
    margin: 0 16px;
    border-top: 0.25em solid #ddd;
    border-left: 0px;
    padding: 1em 0;
}

body > #doc.markdown-body p {
    margin: 0;
    text-align: justify;    
}

body > #doc.markdown-body p:before {
    content: '　　';
}

body > #doc.markdown-body h1,
body > #doc.markdown-body h2,
body > #doc.markdown-body h3,
body > #doc.markdown-body h4,
body > #doc.markdown-body h5,
body > #doc.markdown-body h6
{
    margin: 0px 24px 16px 16px;
}

body > #doc hr {
    height: 4em;
    background-color: transparent;
    width: 1.5em;
    margin: 0 1em;
    margin-top: calc(50% - 2em);
}

body > #doc hr:before {
    content: '§§§';
    color: black;
}

.ui-user-icon.small {
    background-size: cover;
}

@media (max-width: 768px) {
    body > .ui-infobar {
        max-width: 100vw !important;
        margin: 7px auto -25px auto;
    }
    
    body > .ui-infobar .ui-infobar__user-info li {
        white-space: nowrap;
        text-overflow: ellipsis;
        overflow-x: hidden;
        max-width: 140px;
        margin-top: 5px;
    }

    body > #doc.markdown-body {
        width: 100vw !important;
        max-width: 100vw !important;
        margin-top: 10px;
        height: calc(100vh - 91px);
    }
    
    .ui-toc {
        bottom: 5px;
        right: 60px !important;
    }
    
    .ui-toc .ui-toc-label, .ui-toc .ui-toc-label:hover, .ui-toc .ui-toc-label:active {
        background-color: transparent;
        color: #686868 !important;
        opacity: 1;
    }
}

</style>

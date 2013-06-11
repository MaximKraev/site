---
title: "HTML, CSS and JS Productivity Shortcuts"
class_name: docs
full_width: true
---

We have implemented lots of productivity shortcuts into the Codio IDE. These features let you saves loads of time when working with HTML, CSS and Javascript.

##Code Editor Keyboard Shortcuts
General code editor shortcuts can be [found here](/docs/ide/code-editor/kb-shortcuts/). All other productivty shortcuts are found in this chapter.

##Abbreviations
Thanks to our Emmet support, you get a large number of [HTML](/docs/ide/emmet/emmet-html/) and [CSS](/docs/ide/emmet/emmet-css/) abbreviations that expand to code, a bit like this

	div>ul>li*3

expands to 

	<div>
	    <ul>
	        <li></li>
	        <li></li>
	        <li></li>
	    </ul>
	</div>

Be sure to check out the [complete reference](/docs/ide/emmet/emmet-ref/) as there are an awful lot of abbreviations for you to take advantage of.


##Snippet Support
[Snippets](/docs/ide/emmet/snippets/) save you lots of typing and often save you having to look up detailed syntax for HTML, CSS and Javascript. You type abbreviated commands directly in the editor then, when you press the tab key, they expand into full HTML and CSS.

	for

then tab expands to 

	for (var i = 0; i < Things.length; i++) {
	    Things[i]
	}


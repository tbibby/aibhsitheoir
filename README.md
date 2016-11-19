# aibhsitheoir
A WordPress syntax highlighting plugin, based on Prism-JS
The word 'aibhsitheoir'. is Irish.

*Aibhsitheoir*, *n*, highlighter.
## Description
Aibsitheoir is a lightweight syntax highlighting plugin for WordPress, based on [Prism-JS](http://prismjs.com)
## Installation
Zip up the repo and install the zip file in your WordPress admin
## Usage
Aibhsitheoir modifies the default behaviour of Prism-JS slightly: it will only highlight code in the format:
```
<pre><code class="language-cpp">
//your code here
</code></pre>
```
Unlike the default Prism-JS behaviour, Aibhsitheoir does not add a class to the enclosing `<pre>` tag.
## Languages supported
* Any C-like language (use 'language-clike')
* Bash
* C
* C++
* C#
* CSS
* Java
* JavaScript
* Objective-C
* PHP
* Python
* Swift

## TODO
Syntax highlighting is working for now, need to add a button in TinyMCE now.

# Pygments Plugin for DocPad
This plugin enables [Pygments](http://pygments.org/) syntax highlighting for [DocPad](https://docpad.org)

**NOTE: Please try the [HighlightJS](http://docpad.org/plugin/highlightjs) plugin instead, it is way faster as it is coded in JavaScript, whereas for Pygments we have to start up new processes for each code block which is incredibly slow and sometimes unreliable.**


## Install

1. Install Python

	If you are on Linux or OSX, generally Python is already installed for you.

	1. Installing Python via Homebrew

		1. [Install Homebrew](http://mxcl.github.com/homebrew/)

		2. Install Python

			``` bash
			brew install python
			```

		3. Add the Python share directory to your path: `/usr/local/share/python`

		4. Now follow the generic installation instructions


2. Install Pip

	``` bash
	easy_install pip
	```


3. Install Pygments

	```
	pip install pygments
	```

4. Include your favourite [Pygments Stylesheet](https://github.com/richleland/pygments-css) into your website



## Usage

- With Github Flavored Markdown

		## Coffeescript with markdown backticks:

		``` coffeescript
		alert 'hello'
		```

		## Guessing with markdown backticks:

		```
		alert 'hello'
		```

		## Guessing with markdown standard:

			alert 'hello'


- With HTML

	``` html
	<h2>Coffeescript with html:</h2>

	<code class="highlight" lang="coffeescript">
		alert 'hello'
	</code>


	<h2>Guessing with html:</h2>

	<code class="highlight">
		alert 'hello'
	</code>
	```


## Deployment
If you are wanting to generate your DocPad website on your hosting provider, rather than deploying a static site. You will have to install pygments on the host as well. You're probably better off using the [HighlightJS](http://docpad.org/plugin/highlightjs) plugin instead.


## History
You can discover the history inside the `History.md` file


## License
Licensed under the incredibly [permissive](http://en.wikipedia.org/wiki/Permissive_free_software_licence) [MIT License](http://creativecommons.org/licenses/MIT/)
<br/>Copyright &copy; 2012 [Bevry Pty Ltd](http://bevry.me)

# {%= name %}

{%= description %}

## What is Punch?

[Punch](http://laktek.github.com/punch) is a framework for creating, managing and publishing web sites. 

## How to Use 

* Install the package

	`npm install {%= name %}`

* Open your Punch project's configurations (`config.json`) and add the following:

		"plugins": {

			_(Add appropriate config options)_

		}

## License

Copyright (c) {%= grunt.template.today('yyyy') %} {%= author_name %}  
Licensed under the {%= licenses.join(', ') %} license{%= licenses.length === 1 ? '' : 's' %}.

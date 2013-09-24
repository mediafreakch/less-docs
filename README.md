# lesscss.org

> Official website and documentation for LESS/Less.js

### [Visit the website](http://lesscss.org)

### [Visit Less.js](https://less/less.js)


## Libs

The documentation site is generated using [Assemble](http://assemble.io) and [Grunt.js](http://gruntjs.com). Please visit those respective projects to learn more about usage and customization.

## Todo

* Add grunt-github-api to sync changelog from main site
* Add grunt-readme


## Contributing

**Formatting Standards**

For _consistency and readability_ across all examples in the documentation, we ask that you please conform these guidelines when contributing:

* Two spaces for indentation, never tabs, and always use proper indentation
* Multiple-line formatting (one property and value per line)
* For multiple, comma-separated selectors, place each selector on it's own line
* Double quotes only, never single quotes
* Always a space after a property's colon (.e.g, `display: block;` and not `display:block;`)
* End _all_ lines with a semi-colon
* Attribute selectors, like `input[type="text"]` should always wrap the attribute's value in double quotes. This is important to do in your own code as well, for consistency and safety (see this [blog post on unquoted attribute values](http://mathiasbynens.be/notes/unquoted-attribute-values) that can lead to XSS attacks).
* When HTML is in your examples, use tags and elements appropriate for an HTML5 doctype (e.g., self-closing tags with no trailing slash)
* All page files should have globally unique names regardless of where they are located in the repository.

Examples:

**Good**

```css
body {
  padding-top: 80px;
  font-size: 12px;
}
```

**Bad**

```css
body {
padding-top: 80px;
font-size: 12px;
}
```

**Bad**

```css
body { padding-top: 80px; font-size: 12px }
```

### Feature Requests, Bugs and Pull Requests

* If you would like to request a feature, suggest an improvement, or report a bug, please [submit an Issue](https://github.com/cloudhead/less.js/issues?state=open).
* Feature requests are more likely to get attention if you include a clearly described use case.
* If you wish to submit a pull request, please [read this first](https://github.com/cloudhead/less.js/blob/master/CONTRIBUTING).md.

## Tools

### Assemble

* Visit [Assemble's documentation](http://assemble.io/docs/) site to learn more about customization and configuration.
* Markdown: [Markdown Cheatsheet](http://assemble.io/docs/Cheatsheet-Markdown.html)
* Handlebars


## Release History
_(Nothing yet)_

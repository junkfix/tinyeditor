### The simplest and smallest WYSIWYG text editor for web
No dependencies, minified gzipped js is 1926 bytes

* Attaches to an existing textarea,
* Added code toggle to manually insert own html or update
* Fixed font size bug
* Icon fonts dependency removed
* `textarea` is updated on change
* Uses css styles for html editor
* Sticky toolbar
* Added fonts preview in dropdown
* Added cleanup function to auto remove non matching tags and css
* Converts `font` to `span` tags
  
### Installation and Usage

```html
<textarea id="mytext" style="width:100%;height:400px">this &lt;b&gt;bold&lt;/b&gt;</textarea>
```
```js
spell('#mytext');
```

See demo.html

![tinyeditor](https://github.com/junkfix/tinyeditor/raw/master/screenshot.png)

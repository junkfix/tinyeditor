> spell is a fork of pell, the simplest and smallest WYSIWYG text editor for web, with no dependencies, minified js is 2044 bytes

* attaches to an existing textarea,
* added code toggle to manually insert own html or update
* fixed font size bug
* icon fonts removed, can be added back by updating css classes
* textarea is updated on change
* uses css styles for html editor
* sticky toolbar
* added fonts preview in dropdown
  
## Installation and Usage

```html
<textarea id="mytext" style="width:100%;height:400px">this &lt;b&gt;bold&lt;/b&gt;</textarea>
```
```js
spell('#mytext');
```

see demo.html

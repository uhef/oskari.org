# Development Tools

## Sequence Diagrams

Framework supports generating runtime Sequence Diagrams when debug mode is enabled. Run this in browser console to get a Sequence Diagram of requests and events:

```javascript
Oskari.getSandbox().popUpSeqDiagram();
```

## API documentation

The JavaScript API documentation is created from source comments/annotations using [​YUIDoc](http://yui.github.io/yuidoc/). The results can be seen in [here](http://demo.paikkatietoikkuna.fi/Oskari/latest/api/).

### Object type quick guide

* Text = `{String}`
* Boolean = `{Boolean}`
* Numeric values = `{Number}`
* Oskari class = `{Oskari.<mynamespace>.bundle.<mybundle>.MyClass}`
* Multiple possible values = for example `{Number/OpenLayers.Bounds}`
* JSON "configuration" = `{Object}`
* Try not to use Array or Object if you have any chance to be more specific. For example instead of `{Array}` you could use `{String[]}`

* Class documentation with `@class <class name>`
* Method documentation with `@method <method name>`
* Mark methods that are only used internally with `@private` and prefix method name _.
* Mark parameters with `@param {<Type>} <paramname>`
* Mark return value with `@return {<Type>}`

## Editors

* [Sublime Text](http://www.sublimetext.com/) is the Oskari team's editor of choice for JavaScript development
* [IntelliJ IDEA](http://www.jetbrains.com/idea/) has been found useful IDE for Oskari Java development.
* If you're developing on a Windows machine, we recommend using [Cygwin](http://cygwin.com/)
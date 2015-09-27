[Modernizr](http://modernizr.com/)

Modernizr detects features in the browser and creates a JavaScript object. It then adds classes to the `<html>` element depending on which features we have chosen to detect in your modernizr build. ie:

```
<html lang="en" class=" js flexbox canvas canvastext webgl no-touch geolocation postmessage websqldatabase indexeddb hashchange history draganddrop websockets rgba hsla multiplebgs backgroundsize borderimage borderradius boxshadow textshadow opacity cssanimations csscolumns cssgradients cssreflections csstransforms csstransforms3d csstransitions fontface generatedcontent video audio localstorage sessionstorage webworkers applicationcache svg inlinesvg smil svgclippaths">
```

_CSS simple example:_
```javascript
.no-js .glossy,
.no-cssgradients .glossy {
    background: url("images/glossybutton.png");
}

.cssgradients .glossy {
    background-image: linear-gradient(top, #555, #333);
}
```

[Modernizr.load()](http://modernizr.com/docs/#load) is a resource loader (CSS and JavaScript). 

```javascript
Modernizr.load({
  test: Modernizr.geolocation,
  yep : 'geo.js',
  nope: 'geo-polyfill.js'
});
```

[Modernizr.mq()](http://modernizr.com/docs/#mq) tests a given media query.

```javascript
Modernizr.mq('only screen and (max-width: 768px)') // true
```

 
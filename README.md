<p align="center"><a href="http://barbajs.org" target="_blank"><img width="300" src="http://barbajs.org/images/logo.svg"></a></p>

---

*barba.js* is a small *(4.4kb minified and gzipped)*, flexible and dependency free library that helps you creating fluid and smooth transitions between your website's pages.

It helps reducing the delay between your pages, minimizing browser HTTP requests and enhancing your user's web experience.

---
## Websites using Barba.js
<a href="https://www.stanleystella.com" target="_blank"><img src="http://v18.imgup.net/ezgif-2010437e.gif" width="288"></a>
<a href="http://www.poigneedemainvirile.com" target="_blank"><img src="http://u43.imgup.net/ezgif-324794c0.gif" width="288"></a>
<a href="http://www.budidiokojinedostaje.hr" target="_blank"><img src="http://k77.imgup.net/ezgif-1820c351.gif" width="288"></a>

[View demos](http://barbajs.org/demos.html)

## Features

- [Pjax](http://barbajs.org/how-it-works.html)
- [Transitions](http://barbajs.org/transition.html)
- [Views](http://barbajs.org/views.html)
- [Events](http://barbajs.org/events.html)
- [Cache](http://barbajs.org/cache.html)
- [Prefetch](http://barbajs.org/prefetch.html)

## Installation

**barba.js** supports AMD, CommonJS and Browser global (using UMD).  
You can install it using npm:   
```
npm install barba.js --save-dev
```
or just including the script in your page:   
```html
<script src="barba.min.js" type="text/javascript"></script>
```
barba.js needs to know a little bit about your DOM structure. By default uses this markup structure in your pages:

```html
<div id="barba-wrapper">
  <div class="barba-container">
    ...Put here the content you wish to change between pages...
  </div>
</div>
```

> Please note, all the selector (#barba-wrapper, .barba-container) are easily editable, see the API section.

After you've included barba.js in your project it's time to initialize it

```javascript
// Please note, the DOM should be ready
Barba.Pjax.start();
```

## Contribute

Barba.js is created in the spare time by [Luigi De Rosa](https://twitter.com/luruke) and released under MIT licence.  
Any help on the project is more than welcomed.  
For any problem/question do not hesitate to open an issue.  

## Other

For any other information, please visit the [website](http://barbajs.org)

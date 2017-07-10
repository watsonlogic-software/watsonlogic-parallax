# \<watsonlogic-parallax\>

Parallax scrolling effect [web component](https://www.webcomponents.org/element/watsonlogic-software/watsonlogic-parallax) made with Polymer 2.0. Import [Web Component polyfills](https://github.com/webcomponents/webcomponentsjs) if needed.

<!--
```
<custom-element-demo>
<template>
<link rel="import" href="watsonlogic-parallax.html">
<style>
  html{
    font-family: Arial, sans-serif;    
  }
  watsonlogic-parallax{
    color: white;
  }
  .demo{
    height: 300px;
	overflow-y:scroll
  }
</style>
<div class="demo">
<p>Use the scrollbar to view the parallax effect.</p>
<next-code-block>
</next-code-block>
<blockquote>
  Learn to enjoy every minute of your life. Be happy now. Don't wait
  for something outside of yourself to make you happy in the future.
  Think how really previous is the time you have to spend, whether
  it's at work or with your family. Every minute should be enjoyed and
  savored.
  <footer>&mdash; Earl Nightingale</footer>
</blockquote>
</div>
</template>
</custom-element-demo>
```
-->

```html
<watsonlogic-parallax
  parallax-image-height="200"
  parallax-text="You can pass text content into the <watsonlogic-parallax> component."
  parallax-image="https://static.pexels.com/photos/316874/pexels-photo-316874.jpeg">
</watsonlogic-parallax>
```

![Demo Preview](https://github.com/watsonlogic-software/watsonlogic-parallax/blob/master/preview.gif?raw=true)

## License

Apache License 2.0

# \<watsonlogic-parallax\>

Parallax scrolling effect [web component](https://www.webcomponents.org/element/watsonlogic-software/watsonlogic-parallax) made with Polymer 2.0. Import [Web Component polyfills](https://github.com/webcomponents/webcomponentsjs) if needed.


```html
<watsonlogic-parallax
  parallax-image-height="200"
  parallax-text="You can pass text content into the <watsonlogic-parallax> component."
  parallax-image="https://static.pexels.com/photos/316874/pexels-photo-316874.jpeg">
</watsonlogic-parallax>
```

![Demo Preview](https://github.com/watsonlogic-software/watsonlogic-parallax/blob/master/preview.gif?raw=true)

## Known Limitations

This component component currently uses background-attachment:fixed, which is not supported in all browsers (works on most desktop browsers, but has limited support on mobile browsers). According to Can I Use, the `fixed` CSS value is currently only partially supported on iOS Safari and Chrome for Android. We will work towards a more universal solution in the future.

## License

Apache License 2.0

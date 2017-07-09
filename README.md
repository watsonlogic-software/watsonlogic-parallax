# \<watsonlogic-parallax\>

Parallax scrolling effect web component for Polymer 2.0.

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
  <p>We deliberately placed more content in the demo so that you will scroll to view the parallax effect</p>
  <watsonlogic-parallax
    parallax-image-height="200"
    parallax-text="You can pass text content into the <watsonlogic-parallax> component."
    parallax-image="https://static.pexels.com/photos/316874/pexels-photo-316874.jpeg">
  </watsonlogic-parallax>
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

![preview](https://raw.githubusercontent.com/watsonlogic-software/watsonlogic-parallax/preview.gif)

```html
<watsonlogic-parallax
  parallax-image="images/your-image.png">
</watsonlogic-parallax>

<watsonlogic-parallax
  parallax-text="You can pass text content as well."
  parallax-image="images/your-image.png">
</watsonlogic-parallax>
```

## License
Apache License 2.0

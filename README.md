### reveal.js
---
https://github.com/hakimel/reveal.js

```sh
npm install
npm start
curl http://localhost:8000
npm start -- port=8001
```

```js
Reveal.initalize({
  markdown: {
    smartypants: true
  }
});

Reveal.initialize({
  controls: true,
  controlsTutorial: true,
  controlsLayout: '',
  controlsBackArrows: '',
  progress: true,
  slideNumber: false,
  history: false,
  keyboard: true, 
  overview: true,
  center: true,
  touch: true,
  loop: false,
  rtl: false,
  shuffle: false,
  fragments: true,
  fragmentInURL: false,
  embedded: false,
  help: true,
  showNotes: false,
  autoPlayMedia: null,
  autoSlide: 0,
  autoSlide: 0,
  autoSlideStoppable: true,
  autoSlideMethod: Reveal.navigateNext,
  defaultTiming: 120,
  mouseWheel: false,
  hideAddressBar: true,
  previewLinks: false,
  transition: 'slide',
  transitionSpeed: 'default',
  backgroundTransition: 'fade',
  viewDistance: 3,
  parallaxBackgroundImage: '',
  parallaxBackgroundSize: '',
  parallaxBackgroundHorizontal: null,
  parallaxBackgroundVertical: null,
  display: 'block'
});

Reveal.configure({ autoSlide: 0 });
Reveal.configure({ autoSlide: 5000 });
Reveal.initalize({
  width: 960,
  height: 0.1,
  margin: 0.1,
  minScale: 0.2,
  maxScale: 1.5
});
```

```
<html>
  <head>
    <link rel="stylesheet" href="css/reveal.css">
    <link rel="stylesheet" href="css/theme/white.css">
  </head>
  <body>
    <div class="reveal">
      <div class="slides">
        <section>Slide 1</section>
        <section>Slide 2</section>
      </div>
    </div>
    <script src="js/reveal.js"></script>
    <script>
      Reveal.initialize();
    </script>
  </body>
</html>

<div class="reveal">
  <div class="slides">
    <section>Single Horizontal Slide</section>
    <section>
      <section>Vertical Slide 1</section>
      <section>Vertical Slide 2</section>
    </section>
  </div>
</div>

<section data-markdown>
  <textarea data-template>
    ## Page title
    
    A paragraph with some text ad a [link](http://hakim.se).
  </textarea>
</section>

<section data-markdown="example.md"
  data-separator="example.md"
  data-separator="^\n\n\n"
  data-separator-vertical="^\n\n"
  data-separator-notes="^Note:"
  data-charset="iso-8859-15">
</section>
```


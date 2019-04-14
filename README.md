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

```js

```


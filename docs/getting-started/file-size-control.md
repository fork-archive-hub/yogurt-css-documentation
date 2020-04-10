> Installation

### File Size Control

Yogurt will generate thousand of CSS classes which leads to increasing the file size, in order to create a complete experience for the prototyping environment that your project not actually using them all. There are ways to either reducing the Yogurt file size or permanently caching it or adopting both.

### Purge Unused CSS

Implement the Node module from [PurgeCSS](https://purgecss.com/), which is the most recommended and effective way to strip down unused CSS classes in Yogurt and vastly reducing the CSS file size. With this, you can [configure](../customization/configuration.md) Yogurt to enable all utilities possible without worrying about the file size. Below is an example setting of [PurgeCSS using Gulp](https://purgecss.com/plugins/gulp.html) in `gulpfile.js`.

```js
// Example
const purgeCss = require('gulp-purgecss')
gulp.task('purge-css', () => {
  return gulp.src('src/assets/css/yogurt.css')
    .pipe(purgeCss({
        content: [
          'src/views/**/*.html'
        ],
        // make compatible for `Yogurt CSS`
        defaultExtractor: content => content.match(/[\w-/:]+(?<!:)/g) || [],
        whitelistPatterns: [/-webkit-scrollbar-thumb$/]
    }))
    .pipe(rename('style.css'))
    .pipe(gulp.dest('dist/assets/css'))
})
```

### On-demand Caching

Another modern method is using **in-browser on-demand-cache** to permanently store the Yogurt CSS with **PWA (Progress Web App)** feature. So that it only loads once maybe for its lifetime and also without the internet connection for the next load, this vastly improves load speed, reduce bandwidth and load time. (See example projects [FX-Filter Previewer](https://fx-filter-previewer.netlify.com/), [FX-Gradient Previewer](https://fx-gradient-previewer.netlify.com/)).

#### Experience Both Ways

To try it out in action that including all that above methods, create a new [Krugurt.js](https://github.com/loouislow81/krugurt) app and see it for yourself. The `Krugurt.js` boilerplate has already preloaded the `PurgeCSS` and `On-demand-caching mechanism`.

```bash
$ npx create-krugurt-app my-new-app
```



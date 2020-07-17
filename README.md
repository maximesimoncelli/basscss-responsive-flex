
# basscss-responsive-flex

Optional module to extend [Basscss](http://basscss.com), intended to offer responsive breakpoints (as determined by basscss own breakpoints) for flex utilities.

## Npm installation

```
npm i -D basscss-responsive-flex
```

To import it :

```js
import '~basscss/css/index.css'
import '~basscss-responsive-flex/css/responsive-flex.css'
```

or in css :

```css
@import '~basscss/css/index.css';
@import '~basscss-responsive-flex/css/responsive-flex.css'
```

(assuming you're using some sort of webpack aliasing, else import it with the relative node_modules path.)

## CDN Link

```
<link href="https://unpkg.com/basscss-responsive-flex@0.0.2/css/responsive-flex.css" rel="stylesheet">
```

## Usage

Each flex utility defined by basscss is augmented with *-sm-*, *-md-* and *-lg-* classes.

For example:

```html
<nav class='flex flex-wrap flex-sm-column flex-lg-wrap '>
    <a href="#">1</a>
    <a href="#">2</a>
    <a href="#">3</a>
    <a href="#">4</a>
    <a href="#">5</a>
</nav>
```

would wrap at the smallest possible size, column at sm size and wrap at lg size.

For a complete breakdown of all possible classes, see the compiled .css file located in css/responsive-flex.css

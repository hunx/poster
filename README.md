# Poster

Poster is a standalone JavaScript poster-generating micro-library. [Check out a Demo](https://overbool.github.io/poster/).

![screenshot](https://raw.githubusercontent.com/overbool/poster/master/images/screenshot.png)

## Quick start

Several quick start options are available:

* Clone the repo: git clone https://github.com/overbool/poster.git
* Install with npm: `npm i @overbool/poster`
* Use cdn service: `http://pghkcbw8p.bkt.clouddn.com/poster.min.js`

## What's included

```
./
├── LICENSE
├── README.md
├── dist
│   ├── poster.js
│   └── poster.min.js
├── gulpfile.babel.js
├── images
│   ├── dream.png
│   ├── home.jpg
│   └── mountain.jpg
├── index.html
├── package.json
└── src
    └── poster.js
```

## Usage

Using Poster is simple.

```js
// html
<div class="poster"></div>

// js
poster.init({
  banner: './images/dream.png',
  selector: '.poster',
  title: '...',
  content: '...',
  logo: '...',
  description: '...',
  callback: function(container) {...}
})
```

More config:

```js
// html
<div class="poster"></div>

// js
poster.init({
    banner: './images/mountain.jpg',
    selector: '.poster',
    title: '...',
    titleStyle: {
      font: 'bold italic 50px Arial',
      color: 'rgba(66, 66, 66, 1)'
    },
    content: '...',
    contentStyle: {
      font: 'italic 24px Arial',
      lineHeight: 1.2,
      position: 'center',
      color: 'rgba(88, 88, 88, 1)'
    },
    logo: '...',
    logoStyle: {
      color: 'rgba(0, 0, 120, 1)'
    },
    description: '...',
    callback: function(container) {...}
  })
```

## Documentation
### running locally
1. Run `npm install` to install the Node.js dependencies
2. Run `npm run dev` to rebuild Javascript files and start a local http server with port 8080.


## License
[MIT license](./LICENSE)



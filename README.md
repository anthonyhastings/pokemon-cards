# Pokemon Cards

## Introduction

![Demonstration](./.github/demo.avif)

This repository showcases using a variety of CSS techniques to recreate a Pokemon trading card. Some of the techniques are listed below:

- **Font Face**: This CSS at-rule specifies a custom font with which to display text. This is used to change the typography of all the text on the card.

- **Clip Path**: This CSS property creates a clipping region that sets what part of an element should be shown. Parts that are inside the region are shown, while those outside are hidden. This is used to create custom shapes for UI such as the stage badge, the biography, the weaknesses and restistances badges.

- **Filter Drop Shadow**: This CSS function applies a drop shadow effect to an element. This is used on parent elements whose children use clip-path because box shadows do not honor clip-path.

- **WebP**: WebP is a lossless and lossy compression image format developed by Google. It has better compression sizes than JPEG, PNG or GIF. This is used for card textures which originally were lossless PNG images.

- **AVIF**: AVIF is an image format that is even newer—than WebP. As with WebP, AVIF aims to address every conceivable use case for raster images on the web: GIF-like animation, PNG-like transparency, and file sizes smaller than JPEG or WebP. It is used for Pokemon portraits instead of JPEG images.

- **CSS Grid**: A two-dimensional layout system that lets you organize content into rows and columns and offers many features to simplify the creation of complex layouts. This is used for all aspects of layout in the cards.

## Instructions

These instructions assume you are running a version of NodeJS equal to or greater than the version mentioned in the `.nvmrc` file and have pnpm installed:

1. Install dependencies across all packages and applications in the monorepo

```bash
pnpm install
```

2. Start the dev server to see the UI

```bash
pnpm dev
```

## Further Reading

- [Learn CSS Grid by building a Pokemon Card](https://www.udemy.com/course/learn-css-grid-by-building-a-pokemon-card/)
- [CSS Grid Garden](https://cssgridgarden.com/)
- [Using Modern Image Formats: AVIF and WebP](https://www.smashingmagazine.com/2021/09/modern-image-formats-avif-webp/)
- [Using shadows and clip-path together](https://css-tricks.com/using-box-shadows-and-clip-path-together/)
- [Clippy: CSS clip-path maker](https://bennettfeely.com/clippy/)
- [MDN: clip-path](https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path)
- [MDN: @font-face](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face)
- [web.dev: AVIF](https://web.dev/learn/images/avif)
- [web.dev: WebP](https://web.dev/learn/images/webp)
- [web.dev: Grid](https://web.dev/learn/css/grid)

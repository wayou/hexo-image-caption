# hexo-image-caption

Auto adding caption for images with `alt` attribute.

[![npm package](https://img.shields.io/npm/v/hexo-image-caption.svg)](https://www.npmjs.com/package/hexo-image-caption)
[![npm package](https://img.shields.io/npm/dm/hexo-image-caption.svg)](https://www.npmjs.com/package/hexo-image-caption)


## Installation

```
npm install --save hexo-image-caption
```

## Usage
adding following section to your hexo site `_config.yml` file to enable and config plugin.
```yml
# add caption for iamges
image_caption:
  enable: true #false to disable
  class_name: #if you wanna customize the style for the caption,you can assign a class name, default is 'image-caption'
```

## How it works

This extension takes the `alt` attribe as the cation for images.

For example:

```md
![description](xxxx.jpg)
```
the result will be:

```html
<img src="xxxx.jpg" alt="description">
<span class="image-caption">description</span>
```

## Credits
[wayou](https://github.com/wayou/)

## License

MIT

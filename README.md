# hexo-image-caption

Auto adding caption for images with `alt` attribute.

[![build status](https://secure.travis-ci.org/wayou/hexo-image-caption.svg)](http://travis-ci.org/wayou/hexo-image-caption)
[![dependency status](https://david-dm.org/wayou/hexo-image-caption.svg)](https://david-dm.org/wayou/hexo-image-caption)

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

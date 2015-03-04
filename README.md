# hugo-lightslider-example

Hugo with lightSlider and lightGallery integration.

A generated version of this is available [here](http://hugo-lightslider.pc-dummy.net).

## Overview

This repo contains an example which combines these 3 great tools.

#### [Hugo](http://gohugo.io/) from [@spf13](https://github.com/spf13)

A new idea around making website creation simple again. Hugo flexibly works with many formats and is ideal for blogs, docs, portfolios and much more. Hugo’s speed fosters creativity and makes building a website fun again.

#### [lightSlider](https://sachinchoolur.github.io/lightslider/) from [@sachinchoolur](https://github.com/sachinchoolur)

A lightweight responsive Content slider with carousel thumbnails navigation.

#### [lightGallery](https://sachinchoolur.github.io/lightGallery/) from [@sachinchoolur](https://github.com/sachinchoolur)

A lightweight jQuery lightbox gallery for displaying image and video gallery.

## Demo usage

1. Follow this [quickstart](http://gohugo.io/overview/quickstart/) guide, if you don't have hugo yet.

3. Clone this repo with submodules:

        git clone --recursive https://github.com/pcdummy/hugo-lightslider-example

4. Change into the newly created directory and run hugo:

        cd hugo-lightslider-example
        hugo server -w -D -t purehugo

5. Open [your-local-copy](http://localhost:1313) - yes it runs from your computer :)

Wasn't that easy?

## For your site you need

- The contents of the [static](/static) folder (except `/static/content` of course).

- The lightslider shortcode [layouts/shortcodes/lightslider.html](/layouts/shortcodes/lightslider.html), its well documented.

- Your own [data/post/lightslider_example.json](data/post/lightslider_example.json), see lightSlider/lightGallery docs for the `settings`.

- The .css includes [here](layouts/partials/header.html#L19).


## License

[BSD 3-Clause](http://opensource.org/licenses/BSD-3-Clause)

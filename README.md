# hugo-lightslider-example

Hugo with lightSlider and lightGallery integration.

A generated version of this is available [here](http://hugo-lightslider.pc-dummy.net).

## Overview

This repo contains an example which combines these 3 great tools.

**Currently you need the hugo version from [@SchumacherFM](https://github.com/SchumacherFM) [SchumacherFM_SourceJSON](https://github.com/SchumacherFM/hugo/tree/SchumacherFM_SourceJSON)**

#### [Hugo](http://gohugo.io/) from [@spf13](https://github.com/spf13)

A new idea around making website creation simple again. Hugo flexibly works with many formats and is ideal for blogs, docs, portfolios and much more. Hugo’s speed fosters creativity and makes building a website fun again.

#### [lightSlider](https://sachinchoolur.github.io/lightslider/) from [@sachinchoolur](https://github.com/sachinchoolur)

A lightweight responsive Content slider with carousel thumbnails navigation.

#### [lightGallery](https://sachinchoolur.github.io/lightGallery/) from [@sachinchoolur](https://github.com/sachinchoolur)

A lightweight jQuery lightbox gallery for displaying image and video gallery.

## Install/usage

1. Follow this [quickstart](http://gohugo.io/overview/quickstart/) guide, if you don't have hugo yet.

2. Replace it with the extended one from Cyrill:

        pushd .
        cd $GOPATH/src/github.com/spf13/hugo
        git remote add schumacherfm https://github.com/SchumacherFM/hugo.git
        git fetch schumacherfm
        git checkout -b sourcejson schumacherfm/SchumacherFM_SourceJSON
        go get
        popd

2. Clone this repo with submodules:

        git clone --recursive https://github.com/pcdummy/hugo-lightslider-example

3. Change into the newly created directory and run hugo:

        cd hugo-lightgallery
        hugo server -w -D -t purehugo

4. Open [your-local-copy](http://localhost:1313) - yes it runs from your computer :)

Its save to ignore the `Symbolic links not supported, skipping` errors on the output.

Wasn't that easy?

## License

[BSD 3-Clause](http://opensource.org/licenses/BSD-3-Clause)

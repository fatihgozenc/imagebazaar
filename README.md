# imagebazaar

## A simple bash script to download all images in img tags from a web page.

I've created this script to save inspirations for my daily paintings. I am surfing on random websites everyday to gain some inspiration and saving images that I like. When I found a good collection I don't want to spend my time to download images one by one. I save more time for my creation process with this simple shell program.

## Usage

Just download the repo and run `./imagebazaar` in the repo folder. Then you can follow the instruction messages step by step. A new folder will be created by the url name in the repo folder and downloaded images will be inside.

### Using with Instagram

You can pass `-i` or `--instagram` flag to download images from public profiles of Instagram. Currently it's not possible to download all images of the profile. Because Instagram is rendered with Javascript and initially it loads only 12 images, then it partially renders 12 more images after user scrolls down. I will develop this feature more in the future. I know it's easier to do it Puppeteer but I am thinking a Shell way to do it.

## Dependencies and Compatibilty

It uses `curl`, `sed`, `grep` and some basic Linux commands to operate correctly. I haven't tested the usability on macOSX and Windows but it is working without any problems on CentOS 8 and Debian at the moment.

## Personal Thoughts

### How it does affect my daily routine?

It saves me a lot of time while downloading collection of images and causes me to broaden my imagination faster. If you want to see the outcome of this imagination, you can follow my daily paintings here: [Instagram](https://instagram.com/fatihgozenc)

### Thanks for interest.

It may needs more development but it is working enough for me now. I hope it may be useful for someone too. Especially for inspiration hunters.


Cheers...

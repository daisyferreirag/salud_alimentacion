# Particle Jekyll Theme

This is a simple and minimalist template for Jekyll designed for developers that want to show of their portfolio.

The Theme features:

- Gulp
- SASS
- Sweet Scroll
- Particle.js
- BrowserSync
- Font Awesome and Devicon icons
- Google Analytics
- Info Customization

## Basic Setup

1. [Install Jekyll](http://jekyllrb.com)
2. Clone the particle theme: `git clone https://github.com/nrandecker/particle.git`
3. Edit `_config.yml` to personalize your site.

## Site and User Settings

You have to fill some informations on `_config.yml` to customize your site.

```
# Site settings
description: A blog about lorem ipsum dolor sit amet
baseurl: "" # the subpath of your site, e.g. /blog/
url: "http://localhost:3000" # the base hostname & protocol for your site

# User settings
username: Lorem Ipsum
user_description: Anon Developer at Lorem Ipsum Dolor
user_title: Anon Developer
email: anon@anon.com
twitter_username: lorem_ipsum
github_username:  lorem_ipsum
gplus_username:  lorem_ipsum
```

### Pictures Information

|Type|Size|Extention|
|---|---|---|
|services|225x225|png|
|activities|800x800|png|

**Don't forget to change your url before you deploy your site!**

## Activities
The file name has to be named as YYYY-MM-DD-name.md

Add this header in each file

```yaml
\---
layout: default
title: "Title name"
photo: "photo file name without extention"
\---
```

## Color and Particle Customization
- Color Customization
  - Edit the sass variables
- Particle Customization
  - Edit the json data in particle function in app.js
  - Refer to [Particle.js](https://github.com/VincentGarreau/particles.js/) for help

## Running the blog in local

In order to compile the assets and run Jekyll on local you need to follow those steps:

- Install [NodeJS](https://nodejs.org/)
- Install [Jekyll](https://jekyllrb.com): `sudo gem install bundler jekyll`
- Install [Yarn](https://yarnpkg.com/): `npm install -g yarn`
- Install dependencies: `yarn`
- Run: `gulp`

## Questions

Having any issues file a [GitHub Issue](https://github.com/nrandecker/particle/issues/new).

## License

This theme is free and open source software, distributed under the The MIT License. So feel free to use this Jekyll theme anyway you want.

## Credits

This theme was partially designed with the inspiration from these fine folks
- [Willian Justen](https://github.com/willianjusten/will-jekyll-template)
- [Vincent Garreau](https://github.com/VincentGarreau/particles.js/)

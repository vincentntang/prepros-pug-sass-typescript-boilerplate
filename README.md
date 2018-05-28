<a><img src="https://i.imgur.com/xjgwEas.png" height="300" align="right"></a>

<style>
  img:hover {
    border: 2px solid red;
  }
</style>

## Prepros-pug-sass-typescript boilerplate

Prepros-pug-sass-typescript is a frontend web kit and boilerplate for building webapps or small sites using PUG (jade) and Sass.

It also supports typescript

## Inspiration

I just wanted a quick and dirty tool for laying out multipage HTML websites and/or prototyping. All the solutions I found out there were not to my liking. Either they have too many steps involved in installation, or don't work out on my windows 7 / windows 10 PCs. My goal is to have the following:

1. Painless setup that works 100% of the time
2. Fast feedback loop for frontend development
3. No reliance on external libraries unless specified
4. No dependencies
5. Scalable architecture

Inspiration is drawn from the following resources

- [Pug Sass Boilerplate with Gulp](https://github.com/Errec/pug-sass-boilerplate-starter-kit/blob/master/README.md) - An example boilerplate using gulp instead of prepros
- [Standard Folder Structure Conventions](https://github.com/kriasoft/Folder-Structure-Conventions) - For structuring source vs compiled folder
- [Codepens Multipage Site with PUG template](https://codepen.io/project/editor) - PUG templating layout
- [7-1 Sass Pattern](https://sass-guidelin.es/#architecture) - for organizing `scss` code and scalability. You can pick your own opinionated CSS styleguide framework (BEM, SMACSS, etc)

## Features

- Doesn't require nodeJs
- Doesn't require NPM, bower, yarn
- All the features of prepros
- Optimized prepros settings for compiling files
- Jquery and Bootstrap 4 are included from CDN web links. *You can comment these out*

## Requirements

- [Prepros](https://prepros.io/)

## Install

Install prepros

Fork this repo or download it

It includes optimized settings in `prepros.config` file

Run prepros

![](https://i.imgur.com/eYwvFcz.png)

Add your project

Change somethings
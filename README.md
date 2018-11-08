<a><img src="https://i.imgur.com/xjgwEas.png" height="300" align="right"></a>

## Prepros-pug-sass-typescript boilerplate

Prepros-pug-sass-typescript is a frontend web kit and boilerplate for building webapps or small sites using PUG (jade) and Sass.

It also supports typescript

Read [here](/src/README.md) if you don't know what typescript/pug/sass is

## Inspiration

I needed a quick way for laying out multipage HTML websites and/or prototyping. All the solutions I found out there were not to my liking. Either they have too many steps involved in installation, or don't work out on my windows 7 / windows 10 PCs. My goal is to have the following:

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
- Jquery, Bootstrap 4, and Font Awesome are included from CDN web links.
- [Uses the bootstrap 4 thumbnail gallery template](https://startbootstrap.com/template-overviews/thumbnail-gallery/) as a starting point.
- Only modifications to scss file are in `mixins.scss` and `body.scss`

## Features specific to prepros settings

- Check out the documents to see how the scss folder is structured [here](/src/sass/README.md)
- `src/pug` compiles to `dist/`
- `src/sass` compiles to `dist/css`
- `src/ts` compiles to `dist/ts`
- If you are using local images put them in `dist/img`

## Requirements

- [Prepros](https://prepros.io/)

## Install

1. Install prepros
2. Fork this repo or download it
3. It includes optimized settings in `prepros.config` file
4. Run prepros
5. Add your project
6. Compile Each File (right click → process) on following files `main.scss`, `index.pug`, `about.pug`, `contact.pug`, `script.ts`
7. http://localhost:7880/dist/index.html

Result:

![](https://i.imgur.com/FEol2cV.gif)

## Changelog

- version 1.0.0 >> supports bootstrap 4, jquery, pug, sass, typescript with prepros 

# Klipspringer

Klipspringer is a [Stylus](http://learnboost.github.com/stylus/) framework for
rapid CSS authoring. It provides functions that help perform common styling
tasks easily.

## Installation

Stylus can be installed through NPM. This will put klipspringer in
`node_modules/klipspringer`

```shell
npm install stylus
````

It can also be used from
[zip](https://github.com/naneau/klipspringer/archive/master.zip). You can unzip
Klipspringer into a location that is convenient to you.

## Usage

Klipspringer provides a single entry point into its library that can be
imported into your stylus files. Because Klipspringer is written in function
form, there is no overhead. Until you call a function no CSS will be generated.

```stylus
@import "klipspringer"
```

It is also possible to import subsets of Klipspringers functionality:

```stylus
@import "klipspringer/library/box"
```

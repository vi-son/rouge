# 🎨 rouge
### Stylesheet library for [vi • son/mixing senses](https://mixing-senses.art) related projects

Either use this project as submodule or use the `@vi.son/rouge` package from npm
via:

`npm install @vi.son/rouge`


#### Base style + ITCSS structure
You can use the following ITCSS oriented stylesheet structure as a starting point:

```sass
$font-root: "@vi.son/rouge/fonts"

/* 1. Settings - variables, config-switches
@import @vi.son/rouge/1-settings/_colors.sass
@import @vi.son/rouge/1-settings/_fonts.sass
@import @vi.son/rouge/1-settings/_variables.sass
@import @vi.son/rouge/1-settings/_breakpoints.sass
@import @vi.son/rouge/1-settings/_typograhpy.sass

/*** 2. Tools - mixins and functions
@import @vi.son/rouge/2-tools/_responsive-font-size.sass
@import @vi.son/rouge/2-tools/_media-queries.sass

/* 3. Generic - ground-zero styling (normalize, reset)
@import @vi.son/rouge/3-generic/_reset.sass

/* 4. Base - unclassed HTML element styles
@import @vi.son/rouge/4-base/_button.sass
@import @vi.son/rouge/4-base/_document.sass
@import @vi.son/rouge/4-base/_headings.sass
@import @vi.son/rouge/4-base/_images.sass
@import @vi.son/rouge/4-base/_input.range.sass
@import @vi.son/rouge/4-base/_input.text.sass
@import @vi.son/rouge/4-base/_input.text.sass
@import @vi.son/rouge/4-base/_links.sass
@import @vi.son/rouge/4-base/_text.sass

/* 5. Objects - cosmetic-free design patterns
@import @vi.son/rouge/5-objects/_button.send.sass
@import @vi.son/rouge/5-objects/_btn.sass
@import @vi.son/rouge/5-objects/_emoji.sass
```

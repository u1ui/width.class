# .u1-width - class
The main width of your layout


The **main width** of your layout.

This class has a max-width of `var(--width)`.

- horizontal centered
- default paddings left and right of `1rem`
- padding adds spacing of save area `env(safe-area-inset-left)`
- nested elements using `.u1-width` have no padding.
- box-sizing is explicit content-box to define the width without its padding.

## Demos

https://raw.githack.com/u1ui/width.class/main/tests/minimal.html  
https://raw.githack.com/u1ui/width.class/main/tests/test.html

## Ussage

```html
<div class="u1-width">
    content
    <div class="u1-width">nested (no padding)</div>
</div>
```

## Install

```html
<link href="https://cdn.jsdelivr.net/gh/u1ui/width.class@3.0.0/width.min.css" rel=stylesheet>
```

## Demo

https://raw.githack.com/u1ui/width.class/main/tests/minimal.html  
https://raw.githack.com/u1ui/width.class/main/tests/test.html  

## About

- MIT License, Copyright (c) 2022 <u1> (like all repositories in this organization) <br>
- Suggestions, ideas, finding bugs and making pull requests make us very happy. ♥



# Typed.js

Sebuah library yang disediakan javascript untuk membuat efek pengetikan sendiri didalam sebuah tampilan website




## Installation

Install type.js with CDN

```
<script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
```

## HTML
```
<h1 id="element"></h1>
```

## Script

```
var typed = new Typed('#element', {
    strings: [
        "Halo",
        "Hello",
        "Hola"
    ],
    shuffle: true,
    typeSpeed: 20,
    showCursor: true,
    cursorChar: '<h4>|</h4>',
    backSpeed: 20,
    backDelay: 1500,
    loop: true,
});
```
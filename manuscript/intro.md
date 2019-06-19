# Intro. Few words about the book

## A brief history of the book

Why another book on JavaScript? As much as I love "You don't know JS" and "Eloquent JavaScript" I feel there is the need for a book which takes the reader by hand. Everyone has a unique viewpoint on technical topics and my readers love my style of teaching. This book was originally released in italian but a lot of fellow devs asked for a translation. And here it is. The "Little JavaScript Book" aims to be a reference for the hard parts of JavaScript while being beginner friendly. I hope you'll appreciate. Enjoy the reading!

## Structure of the book

The "Little JavaScript Book" is organized in three parts. The first part covers the inner working of JavaScript engines and the "hard parts" of the language: closures, the prototype system, `this` and `new`. Every chapter ends with a self-assessment test which is useful for making the concepts stick. The second part of the book has a lot of practical exercises on the DOM with a lot of pages convering code organization and best practices. The third and last part contains solutions for the exercises and future additions to the book.

## Who this book is for?

While writing the book I had in mind web developers who always worked with jQuery or JavaScript without digging deeper into the language. The book is not a complete intro to programming. But with a little work you should be able to follow along even if you never programmed before. I highly suggest reading the book even if you're an experienced JavaScript programmer or you're coming from another language. You may be surprised how much you forgot about JavaScript.

## What should I know before reading this book?

The "Little JavaScript Book" is not a complete guide to ES6, the 2015 JavaScript release. I assume the reader has some familiarity with ES6 but I'll introduce it a bit in chapter 2. No worries though, I will explain ES6 syntax as we encounter it during the chapters.

## Typographic conventions

This book uses JavaScript and you will find examples written inside a block:

```js
function generateTableHead(table, data) {
  var thead = table.createTHead();
  var row = thead.insertRow();
  for (var i = 0; i < data.length; i++) {
    var th = document.createElement("th");
    var text = document.createTextNode(data[i]);
    th.appendChild(text);
    row.appendChild(th);
  }
}
```
or inline: `th.appendChild(text)`. You will find both ES5 and ES6 code in the book, the former used for not overwhelming the reader at first, the latter used for refactoring later during the exercises.

## What's the best way for following the examples?

I suggest experimenting hands-on with the code and not just copy-pasting. You can use whatever editor you prefer for writing HTML and JavaScript. Then you can run the pages in a browser. You can also use an online tool like [Jsbin](https://jsbin.com) or [Codesandbox](https://codesandbox.io/).

## Errata and other requests

This book is not a definitive guide to JavaScript and I might have missed something you'd like to read. The nice thing is that I can update the book whenever I want on Leanpub. If you want me to cover some topics in more depth feel free to drop me an email at valentino@valentinog.com.

## About the author

I've been in love with computers since my mother gave me the first PC when I was 6 years old. In 1999 I was creating the first HTML pages and from there the web became my life. Today I help busy companies to embrace this crazy modern JavaScript stuff. I do training and consulting on JavaScript, React, Redux. Besides JavaScript I'm also active in the Python community. I serve as a coach for [Django Girls](https://djangogirls.org/) and I've spoke at Pycon Italia. Check out [my talks here](https://www.valentinog.com/talks). In my spare time you can find me in the countryside near Siena. If you want to get in touch for a beer feel free to ping me up at valentino@valentinog.com. Fancy reading some stuff about JavaScript or Python? Head over [my blog](https://www.valentinog.com/blog/)!

## Acknowledgments

This book would not have been possibile without the clever questions I've got during the years from dozens of developers. A huge thanks goes also to all the people who helped shape the beta version of this book: Caterina Vicenti, Alessandro Muraro, Cristiano Bianchi, Irene Tomaini, Roberto Mossetto, Ricardo Antonio Piana, Alessio Forti, Valentino Pellegrino, Mauro De Falco, Sandro Cantagallo, Maurizio Zannoni.
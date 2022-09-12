# Fork of Gematro

This is a fork of the popular cryptography/gematria calculator called Gematro, hosted at [gematro.com](https://gematro.com).
This fork aims at adding new ciphers as fast as possible! In fact, it has been added the QWERTY set of ciphers. It also has no
google analytics tags, meaning that it's private, and free. Feel free to fork it and/or send pull requests.

## List of Modifications

In "calc/calc.js", row 25, I've setted the Extra Ciphers as always visible

```javascript
var optShowExtraCiphers = true // false // enable extra ciphers
```

In "calc/ciphers.js" I've added, at the end of the file, the QWERTY set of ciphers, notably the QWERTY (extended), the QWERTY ordinal and the QWERTY reduced, all with the respective reverse cipher.

## How to contribute

Just drop a pull request with your favorite cipher, the source and, possibly, make a YouTube video explaining why it is important.
The ciphers can be added in the "calc/ciphers.js" file, you can see how the other ones are being implemented.

## Licence

I don't own this code, and this is a fork of the software [gematro.com](https://gematro.com).


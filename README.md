# Anki theme
## Anki themes, cards, templates for programming

Want to learn how to code? This Anki programming theme will help make your Anki development decks a little more fun to work with. Inspired by the excellent [Janki method](#further-reading), it's perfect for front-end and back-end programmers, beginner to experienced.

The template is built in html and css, with [syntax highlighting](./dist/themes/assets/css/README.md) for inline code and code blocks using the beautiful `Monokai` and `Tomorrow` themes (I personally use these in [Sublime Text](http://www.sublimetext.com)). Supports developer languages such as **html**, **css**, **python**, **ruby**, **php**, **jquery**, **javascript** and whatever else you want to throw at it!

![Preview image](./preview.png)

*Anki theme card #01 preview image*


## Card Types
There are currently two types of card, a simple card and a complex card. Both share the `dist/themes/assets/css/main.css` file.

1. **[Simple](./dist/themes/README.md)**
  - What's the answer?
  - What does this syntax do?
2. **[Complex](./dist/themes/README.md#puzzle-field-template)**
  - Everything in **Simple** theme
  - **+** Puzzle question


## Styling fields, inline code fields and code blocks

I've included some nice default styles for code; some fields will be automatically wrapped in `<code>` so all you need to do is add the symbol, class or function. The main `(code blocks ..)` need to be wrapped in a `<pre><code>`.

- **[Anki syntax highlighting and themes](./dist/themes/assets/css/README.md)**


## Notes

### Further reading

Not sure what all the fuss is about Anki? Read on my friend ...

- [Anki essentials](http://alexvermeer.com/anki-essentials/)
- [Janki method](http://www.jackkinsella.ie/2011/12/05/janki-method.html)

### Versioning

This is a major overhaul from the original. In future I'll try to stick to [semantic versioning](http://semver.org), so updates don't break existing cards. Unfortunately with Anki this can be tricky, so view commits for any major changes to the card's structure or Anki fields. The easiest way to test the `dist/deck/*.apkg` is to import into a [new Anki profile](http://ankisrs.net/docs/manual.html#profiles-&-preferences).

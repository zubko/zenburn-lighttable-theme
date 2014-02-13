[Light Table](http://www.lighttable.com) theme based on [Emacs Zenburn theme](https://github.com/bbatsov/zenburn-emacs).

It my be a bit different from [original one for Vim](http://slinky.imukuppi.org/zenburnpage/). I just wanted to have the same _Zenburn_ theme that I have in _Emacs_. Anyways because _LightTable_ uses _CodeMirror_ and _CodeMirror_'s syntax highlight is different from the _Emacs_'s one the colors aren't exactly the same either. But generally I'm satisfied with the result for now. 

Copyright (c) 2014 by Alexander Zubko. [The MIT License (MIT)](LICENSE)

---

### Examples

#### - ClojureScript

<img src="https://github.com/wisenomad/zenburn-lighttable-theme/wiki/images/clojurescript.png" alt="ClojureScript Screenshot" width="524">

#### - Clojure

<img src="https://github.com/wisenomad/zenburn-lighttable-theme/wiki/images/clojure.png" alt="Clojure Screenshot" width="526">

#### - HTML

<img src="https://github.com/wisenomad/zenburn-lighttable-theme/wiki/images/html.png" alt="HTML Screenshot" width="532">

#### - CSS

<img src="https://github.com/wisenomad/zenburn-lighttable-theme/wiki/images/css.png" alt="CSS Screenshot" width="527">

#### - JavaScript

<img src="https://github.com/wisenomad/zenburn-lighttable-theme/wiki/images/javascript.png" alt="JavaScript Screenshot" width="525">

---

### Instalation

- Run `Plugins: Show plugin manager` command
- Find and install `Zenburn` plugin
- Run `Settings: User bahaviors` command
- Add or replace `set-theme` in `:editor` section to `(:lt.objs.style/set-theme "zenburn")`

---

### Source

Using [Less CSS pre-processor](http://lesscss.org) for making _CSS_ with support of variables. Everything is done in [zenburn.less](zenburn.less) file, [zenburn.css](zenburn.css) is compiled version of it.

---

### TODO

- Better colors for _JS_ code (if there is a way to set different colors for one kind of syntax element of _CodeMirror_ when it belong to different languages, for example `cm-property` should be orange for _CSS_ but cyan or blue for _JS_.

- Consider creating style suitable for Zenburn theme (currently we have a couple of modfications to UI just to make tabs visible).

- Add an option with rainbow brackets.

- Highlight active line.

- Consider using _CSS_ with _var_ params (without _Less_) if possible as can be found in skin files of _LightTable_.

- Add version with more contrast.

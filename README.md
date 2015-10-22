# Corpus
#### A collection of CSS things

Corpus is yet another CSS toolkit. It’s basically a collection of the things I find [myself](http://jamiewilson.io) returning to for each new project. It uses [Flexbox](http://tympanus.net/codrops/css_reference/flexbox/) for the grid system, [viewport-based heights and percentage-based widths](http://bitsofco.de/2015/viewport-vs-percentage-units/), is heavily influenced by Basscss’s [White Space](http://www.basscss.com/docs/white-space/) module, and has a few useful greyscale color utilities. For syntax highlighting I'm using [Prism.js](http://prismjs.com/) and my own [Predawn](https://packagecontrol.io/packages/Predawn) color scheme, with code set in [Office Code Pro](https://github.com/nathco/Office-Code-Pro). Styles are written in SCSS.

### Docs

The docs currently live here: https://github.com/jamiewilson/corpus-site, and is kept in a separate repo (rather than a branch) in order to make it possible to symlink the .scss files into other projects. This makes it easier to make revisions back into the Corpus source files within the context of the docs site and also requires less `git pull`ing to keep separate projects up to date.

### Alpha
Please note that Corpus is in an Alpha stage right now and hasn't been tested much. Feel free to leave feedback and requests on the Issues page.

### The MIT License (MIT)
Copyright (c) 2015 Jamie Wilson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

The software is provided "as is", without warranty of any kind, express or
implied, including but not limited to the warranties of merchantability,
fitness for a particular purpose and noninfringement. In no event shall the
authors or copyright holders be liable for any claim, damages or other
liability, whether in an action of contract, tort or otherwise, arising from,
out of or in connection with the software or the use or other dealings in
the software.

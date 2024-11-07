flymake-css.el
==============

An Emacs flymake handler for syntax-checking CSS source code
using [`csslint`](https://github.com/stubbornella/csslint).

Installation
=============

If you choose not to use one of the convenient packages in
[Melpa][melpa] and [Marmalade][marmalade], you'll need to add the
directory containing `flymake-css.el` to your `load-path`, and then
`(require 'flymake-css)`. You'll also need to install
[flymake-easy](https://github.com/purcell/flymake-easy).

Usage
=====

Add the following to your emacs init file:

    (require 'flymake-css)
    (add-hook 'css-mode-hook 'flymake-css-load)

Beware that csslint is quite slow, so there can be a significant lag
between editing and the highlighting of resulting errors.

[marmalade]: http://marmalade-repo.org
[melpa]: http://melpa.org

<hr>

[💝 Support this project and my other Open Source work via Patreon](https://www.patreon.com/sanityinc)

[💼 LinkedIn profile](https://uk.linkedin.com/in/stevepurcell)

[✍ sanityinc.com](http://www.sanityinc.com/)


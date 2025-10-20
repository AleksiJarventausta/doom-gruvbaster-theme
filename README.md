# doom-gruvbaster-theme
Stripped down version of gruvbox theme for Doom Emacs.

Shamelessly built on top of [doom-gruvbox-theme](https://github.com/doomemacs/themes/blob/master/themes/doom-gruvbox-theme.el). Inspired by [Alabaster theme](https://github.com/tonsky/sublime-scheme-alabaster) and [doom-alabaster](https://github.com/agraul/doom-alabaster-theme).

Like the idea of minimalist highlighting but also love the colors from original gruvbox theme.


## Installation

1. Add `doom-gruvbaster-theme` to `$DOOMDIR/packages.el`.

``` emacs-lisp
;; $DOOMDIR/packages.el
(package! doom-gruvbaster-theme :recipe (:host github :repo "AleksiJarventausta/doom-gruvbaster-theme"))
```
2. Run `doom sync`
3. Set `doom theme` to `doom-gruvbaster`
``` emacs-lisp
;; $DOOMDIR/config.el
(setq doom-theme 'doom-gruvbaster)
```

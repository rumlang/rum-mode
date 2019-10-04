# rum-mode
Emacs major mode for editing Rum

## Installation


`rum-mode` is available on the two major community maintained repositories -
[MELPA STABLE](http://melpa-stable.milkbox.net) and [MELPA](https://melpa.milkbox.net).

You can install `rum-mode` with the following command:

<kbd>M-x package-install [RET] rum-mode [RET]</kbd>


or by adding this bit of Emacs Lisp code to your Emacs initialization file
(`.emacs` or `init.el`):

```el
(unless (package-installed-p 'rum-mode)
  (package-install 'rum-mode))
```

### Manual

You can install `rum-mode` manually by placing `rum-mode` on your `load-path` and
`require` ing it. Many people favour the folder `~/.emacs.d/vendor`.

```el
(add-to-list 'load-path "path/to/rum-mode/dir")
(require 'rum-mode)
```

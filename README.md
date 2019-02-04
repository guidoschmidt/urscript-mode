# URScript-Mode
#### Emacs major mode for [URScript](https://s3-eu-west-1.amazonaws.com/ur-support-site/46196/scriptManual.pdf)

### Installation with `use-package`

**WARNING:** Not yet available via MELPA, you can use [straight.el](https://github.com/raxod502/straight.el)
or [quelpa](https://framagit.org/steckerhalter/quelpa)

```emacs-lisp
(use-package urscript-mode
    :ensure t
    :mode ("\\.urscript\\'" . urscript-mode))
```

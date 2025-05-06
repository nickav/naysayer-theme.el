# naysayer-theme.el

[![MELPA](http://melpa.org/packages/naysayer-theme-badge.svg)](http://melpa.org/#/naysayer-theme)

### _Emacs theme inspired by Jonathan Blow's compiler livestreams_

## Screenshots

![Naysayer Theme](/assets/naysayer_0.png)

Includes support for `rainbow-delimeters-mode`.

## Install

### With package.el

Naysayer is available on [MELPA](https://melpa.org).

You can install `naysayer-theme` with: `M-x package-install naysayer-theme`

Then add this to your init file:

```lisp
(load-theme 'naysayer t)
```

### Manual

Download `naysayer-theme.el` to the directory `~/.emacs.d/themes/`, then add this to your `.emacs`:

```lisp
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes/")
```

Now you can load the theme with: `M-x load-theme RET naysayer`

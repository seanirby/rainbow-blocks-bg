# rainbow-blocks-bg.el

rainbow-blocks-bg is an Emacs mode that highlights the background of code blocks delimited by
parenthesis, brackets, or braces.  The highlight color is determined by the blocks nesting level.

This package is a fork of the
[rainbow-blocks.el](https://github.com/istib/rainbow-blocks) package
and only applies minor patches such that the background is highlighted
rather than the foreground text.

This was just a quick hack. I'm not sure if this will be that useful
but I thought it was cool.

## Screenshots

### Light

![light-theme](/screenshots/light.png)

### Dark

![dark-theme](/screenshots/dark.png)

## Basic Installation

I'm not sure if I'll add this to MELPA but for now download the ```rainbow-blocks-bg.el``` file into your ```.emacs.d``` directory or wherever you keep external libraries.  Then add this to your init file.

```
(load-file "path/to/rainbow-blocks-bg.el")
(global-rainbow-blocks-bg-mode)
```

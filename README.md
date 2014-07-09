## Synopsis ##

toggle-quotes.el lets you toggle between single and double quotes
easily, it also does the necessary escape and automatically remove the
unnecessary unescape for you. See it in action:

![Toggle Quotes Screenshot](https://github.com/toctan/toggle-quotes.el/raw/master/screenshots/toggle-quotes.gif)

## Installation ##

### Manual ###

Clone this repository or download `toggle-quotes.el`, make sure that
this file is in Emacs load-path:

```lisp
(add-to-list 'load-path "/path/to/directory/or/file")
```

Then require toggle-quotes, and bind the command `toggle-quotes`:

```lisp
(require 'toggle-quotes)

(global-set-key (kbd "C-'") 'toggle-quotes)
```

## MELPA ##

If you're an Emacs 24 user or you have a recent version of package.el
you can install toggle-quotes.el from the [MELPA](http://melpa.milkbox.net/)
repository.

## Bugs & Improvements ##

Please, report any problems that you find on the projects integrated
issue tracker. If you've added some improvements and you want them
included upstream don't hesitate to send me a patch or even better - a
GitHub pull request.

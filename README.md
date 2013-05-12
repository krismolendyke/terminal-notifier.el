# `terminal-notifier.el`

A simple Emacs Lisp module for interfacing with
[`terminal-notifier`](https://github.com/alloy/terminal-notifier) for the OS X
Notification Center.

## Installation

Copy or clone `terminal-notifier.el` into a reasonable spot on your Emacs
`load-path`.

## Usage

```
(tn-notify "Ahoy, message!" "Whoa there, title!" "Yo, subtitle!")
```

Will display a notification like this:

![tn-notify](tn-notify.png)

That's about it.  I find it handy for notifying that a longer asynchronous
process has finished, e.g., `set-process-sentinel`.

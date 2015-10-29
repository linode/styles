**This is experimental, incomplete software**

# Linode Styles

These stylesheets are shared among Linode websites for a unified look & feel.
At a glance:

* Bootstrap 4 base
* Font Awesome icons
* Everything is SCSS
* Material inspired design

This repository is included in other projects as a git submodule.

*Note: this repository includes external javascript dependencies in addition to
our stylesheets.*

## Usage

Add this repository as a submodule, then to your sass path. Add this:

    @import "base";

To your scss.

## Hacking

Bootstrap is pulled in via the `bootstrap` directory, which includes our
variable overrides and a few other nifty things. The `components` directory
includes styles for specific components of the UI.

Bower components are checked into version control so that we can use them from
GitHub pages.

# useflags

(C) Martin Väth (martin at mvath.de).
This project is under the BSD license 2.0 (“3-clause BSD license”).
SPDX-License-Identifier: BSD-3-Clause

This is a utility for the Gentoo portage system.

With this perl script you can print or save the current setting of the
`USE` flags or compare it with a saved versions.
This is the most convenient way to keep track of the changes of the
`USE` flags in the portage tree (and of the defaults in your profile).

Since the auto-useflags of use.defaults are practically deprecated,
these files are ignored by this script.

If you have installed `app-portage/eix`, this script is faster
(with __eix-0.27.7__ or newer even considerably faster and more secure).

### Installation

For installation, copy the content of `bin/` with executable permission
in your `$PATH` (perhaps `/usr/bin`). To obtain support for __zsh completion__,
you can copy the content of `zsh/` to a directory of your zsh's `$fpath`
(perhaps `/usr/share/zsh/site-functions/`)
.
There is also an ebuild in the mv overlay (which is available over layman).

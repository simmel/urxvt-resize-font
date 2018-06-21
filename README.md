Install instructions
--------------------

1. Copy `resize-font` to where URxvt looks for Perl extensions, e.g:
   `$HOME/.urxvt/ext/`. For exact path see urxvt(1) man-page on perl-lib.

2. In your `~/.Xresources` add `resize-font` to the `urxvt.perl-ext-common`
   setting so URxvt loads the extension, e.g:

        urxvt.perl-ext-common: default,tabbed,matcher,resize-font,-tabbed

3. See header of `resize-font` for standard keybinds and how to change them.

_Note that this extension requires you to set your font size with urxvt.font.
   For more information, see header of `resize-font`._

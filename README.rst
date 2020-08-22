================
lean-unicode.vim
================

Unicode translation (of e.g. ``\l`` to ``←`` as in other Lean environments),
for (n)vim. These are suitable for use with `coc-snippets
<https://github.com/neoclide/coc-snippets>`_ (or directly with Ultisnips).

These translations are auto-generated via a script from the `vscode-lean
<https://github.com/leanprover/vscode-lean/blob/master/translations.json>`_
file.

Installation
------------

Install as a normal (n)vim plugin, via e.g.::

    Plug 'Julian/lean-unicode.vim'

Regenerating the Translations
-----------------------------

Run::

    $ bin/regenerate > Ultisnips/lean.snippets

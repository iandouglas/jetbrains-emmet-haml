jetbrains-emmet-haml
====================

Collection of emmet.io shortcuts for JetBrains editors for HAML documents.

For example, tyle this into a .haml file:

```
link:css
```

... then hit TAB, and it should turn into this:

```
%link(rel='stylesheet' type='text/css' href='.css')
```

... and place the cursor inside the href quotes for you to type in the CSS stylesheet filename.

Installation
------------

I've symlinked the "Zen HAML.xml" file under the following paths. I'll test more as I'm able.

| OS | Editor/Version | Location |
| --- | --- | --- |
| Ubuntu 13.10 | PyCharm 3.0x (Pro) | `~/.PyCharm30/config/templates/` |
| Mac OS X Mavericks | PyCharm 2.x | `~/Library/Preferences/PyCharm20/templates` |
| Mac OS X Mavericks | PyCharm 3.x | `~/Library/Preferences/PyCharm30/templates` |
| Mac OS X Mavericks | RubyMine 5.x | `~/Library/Preferences/RubyMine50/templates` |
| Mac OS X Mavericks | RubyMine 6.x | `~/Library/Preferences/RubyMine60/templates` |


If you find other file locations based on OS/editor/version, please add it to this README.

Cautions
--------
1. If you make edits to this Live Template within a JetBrains editor, it may remove your symlink.
1. Adding this file to RubyMine wants to remove the Python and Django flags on each element. Tips to fix this are welcome.

Contribute
----------
Contributions are more than welcome.



[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/iandouglas/jetbrains-emmet-haml/trend.png)](https://bitdeli.com/free "Bitdeli Badge")


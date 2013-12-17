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


If you've never looked at Live Templates in the JetBrains editors before, go into Settings > Live Templates, add a new Template Group and add a live template shortcut to that new group, then click OK to close the dialog, which should populate your respective /templates/ folder with things like "Zen HTML.xml" and "html_xml.xml" and such. At that point, symlink the "Zen HAML.xml" from where you checked out this repo to that templates folder. Restart your editor completely (changes don't auto-reload, only when the editor starts up fresh) and you'll be all set.

If you find other file locations based on OS/editor/version, please add it to this README.

Cautions
--------
1. If you make edits to this Live Template within a JetBrains editor, it may remove your symlink.
1. Adding this file to RubyMine wants to remove the Python and Django flags on each element. Tips to fix this are welcome. You can always "chmod 400 Zen\ HAML.xml" in the repo folder but then your editor will throw an error that the file is unwriteable (duh).

Contribute
----------
Contributions are more than welcome.



[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/iandouglas/jetbrains-emmet-haml/trend.png)](https://bitdeli.com/free "Bitdeli Badge")


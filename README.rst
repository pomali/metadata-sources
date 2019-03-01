================
metadata-sources
================
A collection of metadata source plugins for calibre. Some are based on calibre's
own plugins, others are new.


Plugins
-------

:Arxiv:
   Fetches metadata from arxiv.org.
   
:Mathscinet:
   Fetches metadata from Mathscinet. Requires subscription.
   
:Zentralblatt:
   Fetches metadata from Zentralblatt.
   

Installation
------------

Just go to the plugin subdirectory and type::
  
  make install

This makes a zip package with the code and installs it in the user's calibre
directory (``~/.config/calibre`` on Arch linux)


*[UPDATED] For OSX type*::
  ./calibre-customize -b <plugin_folder>

<plugin folder is the specific folder where you have the __init__.py file. In the arxiv 
case, it would be <repo>/arxiv/src

Usually in OSX, the command line tools are in the bundle:
`/Applications/calibre.app/Contents/console.app/Contents/MacOS/`


Links
-----
- http://calibre-ebook.com/
- http://www.arxiv.org/
- http://www.ams.org/mathscinet/
- http://www.zentralblatt-math.org/zmath/en/

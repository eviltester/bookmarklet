# Bookmarklet

A minimalist bookmarklet generator

- Click [Rename] and type in a name to rename the link.
- Click [Make BookMarkLet], copy in the code you want to convert and click OK
- Drag the link to bookmark toolbar
- Or copy and past into bookmark manager from the JavaScript Console

For a really minimal bookmarklet just type this into the console

~~~~~~~~
"javascript:(function(){" + encodeURI(window.prompt("")) + "})()"
~~~~~~~~

Currently live at [compendiumdev.co.uk/apps/eviltester/bookmarklets.html](http://compendiumdev.co.uk/apps/eviltester/bookmarklets.html)

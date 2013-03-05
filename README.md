Evernote Action Page
====================

Installation
------------

Installation now requires [sass](http://http://sass-lang.com/).  Clone the repo and run `sass ActionTemplate.scss ActionTemplate.css`.  Host both the index.html and ActionTemplate.css files somewhere (dropbox works well).  Go to the link online and use the Evernote clipper tool for the browser on the page.  Clip the entire page.  Add your check boxes to the action step columns and simply clone the note when you want to use it.

Alternatively you can simply get the link directly through Evernote [here](http://www.evernote.com/shard/s2/sh/0b7e8e8f-1445-4543-b377-34213568a2b3/ca31c2a7a950f9473538e7a3a055b152).  Please note that this Evernote link may lead to an out of date copy and generating your own copy is recommended.

Why tables for layout?
----------------------
Good question.  Unfortunately Evernote removes divs if there's no content in them automatically.  Regularly I'd suddenly find myself typing on top of the action step column.  It pained me to do it, but tables solved the problem incredibly well in this context.

Enjoy!
------
I highly recommend forking the repo and making changes to this to fit your needs.  I did not add a back burner area or any number of other things you may want.

moz-hocr-edit
=============

NB: This is a README created by @rdmpage based on [Jim Garrison's original description](http://jimgarrison.org/moz-hocr-edit/).

moz-hocr-edit provides a line-by-line interface for people to proofread the results of the Optical Character Recognition (OCR) process. OCR programs are not perfect at recognizing text, so human editing is often necessary.

Install
-------

Latest version: [moz-hocr-edit 0.4.3](https://addons.mozilla.org/en-US/firefox/addon/11067) (released 2010-09-16)

moz-hocr-edit is a Firefox extension, and as such it must be installed in the Firefox web browser. From the user's perspective, it operates like an ordinary web application, except it runs on your local machine and can save files anywhere you want.

License
-------

moz-hocr-edit is free software, available under the same tri-license as Mozilla itself.

Note: In 2011, Firefox switched to a (much criticized) six-week release cycle. I do not myself test this add-on with each version of Firefox, so please let me know if you experience any issues.

Getting Started
---------------

moz-hocr-edit can edit local hOCR files (as generated by [OCRopus](http://www.ocropus.org/)), and it can edit files over HTTP if the remote server supports HTTP PUT. To edit a document, browse to its location in Firefox; then click on "hOCR" in the add-on bar (bottom right corner of Firefox), and choose "Edit this hOCR document." This will launch the editing system in a new tab. In recent versions of Firefox, the add-on bar is hidden by default. If you do not see the add-on bar, click on the menu: View → Toolbars → Add-on Bar.

Sample Documents
----------------

moz-hocr-edit is being used to proofread Concerning Beards, a 1930 book by Edwin Valentine Mitchell. The hOCR file of this book makes excellent sample material for editing. You can open this document in moz-hocr-edit, but you can only save it to your local filesystem since you probably don't have write access to the subversion repository in which it is hosted.

If you are trying to set up your own subversion repository for remote editing, the key step is to enable autoversioning.

Feedback
--------

I am very interested in feedback or suggestions for the program. Is it easy to use? Does it increase your productivity? Have you found any bugs? What else should a future version of moz-hocr-edit do?

Please send any feedback to moz-hocr-edit@googlegroups.com. Although you need not subscribe to send a message, you are encouraged to [join the group](http://groups.google.com/group/moz-hocr-edit).


Links
-----

* [hOCR format ](http://docs.google.com/Doc?id=dfxcv4vc_67g844kf)– public specification of the hOCR file format
* [OCRopus](http://www.ocropus.org/) – OCR software
* [hocr-tools](http://code.google.com/p/hocr-tools/) – tools for manipulating hOCR documents
* [hOCR discussion group](http://groups.google.com/group/hocr) – also includes links to other hOCR software
* [BookLiberator](http://bookliberator.org/) – hardware + software for digitizing your books

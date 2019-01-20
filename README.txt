===============================================================================
OSUBDL                                                 Fetch subs, senprobleme!
===============================================================================

It's kind of annoying to visit OpenSubtitle's website.
First off, their site's shit.
Second off, it uses Javascript.

Let's get around that.
With `osubdl`, you can download subtitles for a given file in the
given language "automagically"~



----------------------------------------
PRE-REQUISITES
----------------------------------------
You'll need:
	* To compile "oshash.h" to "oshash" and put it in your $PATH
	* a POSIX-compatible shell (tested with `pdksh` and `bash`)
	* "unzip" installed
	* "curl" installed"
	* Some videos <3



----------------------------------------
USAGE
----------------------------------------
Just run "osubdl" like so:

	osubdl file [language] [destination]

The file should be, obviously, some TV episode or movie's video file.
The language defaults to "eng" (english), but you can choose any
three-char language code.
The destination defaults to the file's name, but with "srt" as the
file-extension.



----------------------------------------
BORING STUFF
----------------------------------------
License is CC-0
Author is Jenga Phoenix <jadedctrl@teknik.io>
Sauce is at https://git.eunichx.us/osubdl

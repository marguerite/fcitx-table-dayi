## fcitx-table-dayi

fcitx-table-dayi is a table input method for Da Yi.
It's based on the Dayi3 and Dayi4 tables from OXIM project. 

### Requirements:

You need Fcitx main package to get it running.

### About optimized tables 

There're so many of them on Taiwan local forums. (Google is your friend!)

Although they're all also freeware, permit everyone to use them without any
responsiblity, and even input faster than or have less redundant mappings than 
these tables I chose, they themselves may potentially violated the original 
agreement from [Dayi software corp](http://www.dayi.com) (See COPYING.Data).

You can take this one as a skeleton, it provides functionality to use Dayi
under Fcitx. You can still replace the .txt in tables folder to make a non-
distributable fcitx-table-dayi yourself.

#### Table conversion

It's quite easy.

The table you downloaded might be in .cin format (Mostly).

You can simply rename it to .txt.

And delete everything except those between `%chardef begin` and `%chardef end`.

Then add a `[Data]` before them.

Add a header, see the current ones as examples.



Tablet fixed-background hack
============================

Attempt to fix broken background-fixed &amp; background-cover on a tablets
It's not necessarily 'broken', as omitted for performance issues.

Initially, this script just resizes/repositions the background image once onscroll fires. Not ideal when using and image for a parallaxy background.

To be truly useful, this needs:

1. To use a position:fixed img, which might actually stay put (does it?). Do something clever to position/z-index it.
2. User agent detection :/ I mean... There aren't really any other options.

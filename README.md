# IVC - Introvert Version Control system

Tired of Git quirkiness?

Don't really need 99% of its features, as you're mostly developing alone?

Don't like Subversion / Mercurial / etc?

Try IVC!

## Features

* History consists of a linear sequence of versions, neatly stored in each instance of the repo (and on the server, of course)
* No branches!!! No more mess with rebases and multiple conflicts!
* No automatic merges - no more your code will be silently altered / corrupted by "automatic" three-way merge
* A "remote server" is nothing more than just a directory - therefore, any means of syncing dirs will work as a "transport protocol"
* Versions are deflated diffs, making history storage quite compact
* Friendly towards big binary blobs - it won't waste your time by trying to compress a high-entropy binary file (instead, ivc will detect that it's a binary and use signature-based block diffing instead)
* Easy-to-understand version storage - you can manipulate your history easily and without need for arcane knowledge

### This document (and in fact the tool itself) is WIP

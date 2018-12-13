# FMPReport2ncursesForSwift
XSLT 1.0 stylesheet to convert FileMaker DDR for ncurses for Swift 5

This is a stylesheet written to convert FileMaker's Data Design Report to Swift 5 in order to build a basic TUI( Textual User Interface ) from your FileMaker solution. The reason for mentioning the version number of Swift is that Swift 5 implements UTF-8 as its unicode default.

While DATA API represents marginally different( It's not really better or worse ) approach to retrieving data compared to FileMaker CWP.

This will run on any version of FileMaker that has CWP or Thrift; regardless of DATA API. Good for proof of concept, however for production I run FileMaker as editorial tool, postgres as datastore, elasticsearch as index, nginx as reverse proxy, and whatever is required as frontend. For booking systems ncurses and graphQL represents an opportunity with the lowest bandwidth distribution possible within reason; thrift is always an option if load is still too high.

FileMaker 5.5 Pro will do for this.

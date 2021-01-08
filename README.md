[![CI with Maven](https://github.com/x-stream/mxparser/workflows/CI%20with%20Maven/badge.svg)](https://github.com/x-stream/mxparser/actions?query=workflow%3A%22CI+with+Maven%22)

----
# MXParser
MXParser is a fork of xpp3_min 1.1.7 containing only the parser with merged changes of the Plexus fork.  It is an
implementation of the XMLPULL V1 API (parser only).

Xpp3 was once provided by the Extreme! Lab, Indiana University.  However, the project's website, repository and
documentation have been vanished from their servers long ago.  Although the original author did setup in the meanwhile
repositories at GitHub, he is no longer responding and maintained forks cannot publish their versions to Maven Central
using the existing Maven coordinates.

Xpp3 has been the default parser for XStream since beginning and due to some special behavior it cannot be simply
changed due to compatibility issues.  Several bugs have been fixed with the fork, some of them had been reported more
than a decade ago. 

## Binaries
The resulting Java library is available at Maven Central:
 io.github.x-stream:mxparser

## Documentation
Documentation can also be found at [GitHub](http://x-stream.github.io/mxparser).
This includes:
* JavaDoc
* Change log


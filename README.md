[![Build Status](https://travis-ci.org/x-stream/mxparser.svg?branch=master)](https://travis-ci.org/x-stream/mxparser)

----
# MXParser
MXParser is a fork of xpp3_min 1.1.7 containing only the parser with merged changes of the Plexus fork.
It is an implementation of the XMLPULL V1 API (parser only).

Xpp3 was once provided by the Extreme! Lab, Indiana University. However, the project's website, repository and
documentation has been vanished from their servers long ago. Although the original author did setup in the meanwhile
repositories at GitHub, he is no longer responding and maintained forks cannot publish their versions using the
existing Maven coordinates.

Xpp3 has been the default parser for XStream since beginning and due to some special behavior it cannot be simply
changed due to compatibility issues. With the for of the parser some bugs have been fixed, some of them had been
reported more than a decade ago. 

## Binaries
The resulting Java library is available at Maven Central:
 io.github.x-stream:mxparser

## Documentation
Documentation can also be found at [GitHub](http://x-stream.github.io/mxparser).
This includes:
* JavaDoc
* Change log


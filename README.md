# bug fixes and extensions

starting from version 0.11.3 of [debbuild](https://secure.deepnet.cx/trac/debbuild)
the commits of this project deal with

* handling tarballs compressed with various packers
* extracting specfiles from such tarballs
* improved handling of the `%setup` and `%patch` macros
* configuration and invocation of debbuild
* many more nuts and bolts under the hood

some – but unfortunately not all – of these improvements have already made it
back into [the original source
tree](https://secure.deepnet.cx/svn/debbuild/trunk/debbuild).

## result

after four months this effort resulted in the release of debbuild 0.15.11.

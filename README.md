sel4test-manifest-newlibs
=========================
This is a modification of the standard sel4test project for porting
the new libraries that make libsel4 no depend upon libc. See [sel4test-manifest](https://github.com/seL4/sel4test-manifest)
for the original manifest and my version [here](https://github.com/winksaville/sel4test-manifest).

For general instructions on using this repository, see [sel4.systems/Download/building](http://sel4.systems/Download/building)
and the Wiki.

Prerequisites, in addition to a standard development environment for your target(s) are:
* python tempita templating package
* realpath and which
* the libxml2 utilities.

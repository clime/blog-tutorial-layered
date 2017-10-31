Hello, this is a subdirectory of a layered repository.

Content of this directory is flat and unpacked.

**Flat** means there are no subpackages in the directory the "root one".
In other words, there are no subdirectories that would themselves contain a spec file.

**Unpacked** means the application source files are not packed into a tarball
that would be referenced by a Source directive in the spec file. Instead
the sources are kept as developer made them and they will be packed into
the tarball later during the build process. We need to get the sources
packed at some point to be able to build an RPM from them.

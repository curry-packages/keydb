keydb: Database access for entities stored with unique keys
===========================================================

This package contains a library to provide a general interface
for accessing databases where each entry consists of a key and an info
part. The key is an integer and the info is arbitrary. All
functions are parameterized with a dynamic predicate that takes an
integer key as a first parameter.

This current library is based on the
[SQLite](http://sqlite.org/) database engine.
In order to use it you need to have `sqlite3` in your
`PATH` environment variable or adjust the value of the
constant `path'to'sqlite3` in the library.

--------------------------------------------------------------------------

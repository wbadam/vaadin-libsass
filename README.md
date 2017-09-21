test.libsass
==============

Test application for compiling Vaadin themes with libsass.

* Uses maven-dependency-plugin  `unpack-dependencies` to scan jars for .scss files.
* Uses libsass-maven-plugin for sass file compilation.
* Uses fizzed-watcher-maven-plugin for on-the-fly-compilation.

`mvn jetty:run` localhost:8080/

`mvn fizzed-watcher:run` for on-the-fly-compilation

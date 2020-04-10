# Introduction

This is a template of a minimum maven archetype to create CUI application.

# Features

* maven-compiler-plugin is compatible with Java 9 or later versions.
* the build-in plugins
    * exec-maven-plugin is that We can execute the compiled sources quickly.
* dependencies
    * Junit 5 

# Instalattion

```
$ cd maven-cui-archetype
$ mvn install
```

# Usage

```
$ mvn archetype:generate -DarchetypeCatalog=local
1: local -> ..
...
#: local -> io.github.yossan:maven-cui-archetype (maven-cui-archetype)
Choose a number or apply filter (format: [groupId:]artifactId, case sensitive contains): #:
```

→ Select #, which is the number of `io.github.yossan:maven-cui-archetype`


# License

MIT




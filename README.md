# IntelliJ Tooling

Author: Andrew McNamee


This project contains tooling for IntelliJ.

## Live Templates

This project contains IntelliJ live templates. To install a given XML file, copy it to your IntelliJ `.../config/templates` directory.

### Guava

[Guava](https://github.com/google/guava) is a set of core libraries for Java built by Google.

These [IntelliJ live templates](https://www.jetbrains.com/help/idea/2017.1/live-templates.html) for Guava serve as quick shorthands for some of the most common operations on Guava types such as `ImmutableList`, `ImmutableSet`, `Preconditions`, etc.

Example: if you type `CTRL-J` `i`-`l`-`o`-`f`, IntelliJ will expand that to `ImmutableList.of(...)` and also auto-import ImmutableList.

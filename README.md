#  Keep your architecture clean with Gradle [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

## :clipboard: Introduction

[ArhUnit](https://www.archunit.org/userguide/html/000_Index.html) is a free, simple and extensible library for checking the architecture of your Java code. That is, ArchUnit can check dependencies between packages and classes, layers and slices, check for cyclic dependencies and more. It does so by analyzing given Java bytecode, importing all classes into a Java code structure. ArchUnit’s main focus is to automatically test architecture and coding rules, using any plain Java unit testing framework.

## :cloud: Getting Started

Follow along this notes. You will need to have at least [Java 8](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html) installed or some openJDK distribution, and [Gradle](https://gradle.org/) on the PATH. 

You can use some package management tool for windows. E.g. [Chocolatey](https://chocolatey.org/)

*	[OpenJDK8 Zulu](https://azul.com) - Java Development Kits (OpenJDK build)

```
choco install zulu8 -y
```

*	[Gradle](https://gradle.org/) - Constructor and manager dependencies

```
choco install gradle --version 5.6.4 -y
```

Clone this repository, and fire up a command-line tool.

> To know a check dependencies between packages and classes, layers and slices, check for cyclic dependencies...

## :computer: Steps

To execute the next command line:

```
gradle build
```

## :octocat: Can you support me?

I will continue to do things and expose notes, but existing many ways to support what I do:
* Pull requests are welcome a :dizzy:
* Don't forget to give this Repository a :star2:
* <a href="https://www.buymeacoffee.com/pedringcoding" title="Donate to this content using BuyMeACoffee">Buy me a :coffee:</a>

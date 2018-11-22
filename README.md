# robocode-gp

Table of contents
=================

   * [Description](Description)
   * [Table of contents](Table_of_contents)
   * [Instalation](Instalation)
   * [Usage](Usage)
   * [Credits](Credits)



Description
===========

A forked project for **homebrewed** genetic programming application for evolving Robocode robots.

Video: http://www.youtube.com/watch?v=1o9pwrTEgN0

This project evolves java source code using genetic programming.
A copy of Robocode (free) is required for this application to work.


Instalation
===========

Robocode
--------

It's needed to install robocode at [Robocode](https://robocode.sourceforge.io/)

Usage
=====

 You'll need to update the file paths in RunGP and BattleRunner.
There are tons of Robots on Robocode's website you can use to train yours against.

It assumes that Robocode is installed at C:\robocode,
 * and writes all files to the "C:\robocode\robots\sampleex" directory.
 * The robocode.jar library must be included in the build path (C:\robocode\libs\robocode.jar by default)


If you are using Linux or installed robocode in another diretory you need to change these variables:

```java
  public class BattleRunner {
    engine = new RobocodeEngine(new java.io.File(<ROBOCODE PATH>));
  }
  
  public class MetaBot {
		String PATH = new String("<ROBOCODE PATH>sampleex");
		String PACKAGE = new String("sampleex");
		String JARS = new String("<ROBOCODE PATH>robocode.jar");
  }
```

Credits
=======

All credits to the creator 
[tbh1](https://github.com/tbh1)


I remade this readMe to explore github .md possibilities. 






# SimpleScala
This project is an example of a simple scala project.  It is a simple [SBT](https://github.com/sbt/sbt) project. SBT is basically a build tool for Scala, Java and more. Have a look at this [Getting Started](https://www.scala-sbt.org/1.x/docs/Getting-Started.html).

Have a look at `build.sbt` file. This file is used by SBT to understand the project (library dependancies, sub projects, common settings, etc.). The project also shows the required [folder structure](https://www.scala-sbt.org/1.x/docs/Directories.html) for sbt.

To get started, navigate to the root of the project, and do the following:
```bash
sbt
```

| SBT Commands              | Description                                                                      |
| ------------              | -----------                                                                      |
| reload                    | when you make changes to `build.sbt`, and you want to reparse/reload the changes |
| compile                   | compile your src                                                                 |
| test                      | compile your tests                                                               |
| test:compile              | compile src and tests                                                            |
| procect <subproject name> | switch to a subproject                                                           |
| runMain                   | run your project (you can also specify which project by passing it as a param)   |
| testOnly                  | run your test (you can also specify which test by passing it as a param)         |


This will start the parsing of the project's `*.sbt*` files, as well as getting all the dependancies. Whenever you change `build.sbt`, execute `reload`.


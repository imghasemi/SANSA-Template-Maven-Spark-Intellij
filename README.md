Maven Template Project for SANSA using Spark - Intellij Configuration
=============================
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Twitter](https://img.shields.io/twitter/follow/SANSA_Stack.svg?style=social)](https://twitter.com/SANSA_Stack)

This is a [Maven](https://maven.apache.org/) template to generate a [SANSA](https://github.com/SANSA-Stack) project using [Apache Spark](http://spark.apache.org/).

How to use it in IntelliJ IDE
----------
**Step 1**: First open your terminal and follow the terminal command-lines:

```
cd $HOME/IdeaProjects/
git clone https://github.com/imghasemi/SANSA-Template-Maven-Spark-Intellij.git

````
----------

**Step 2**: The subsequent steps depend on your IDE which we specifically explain the intelliJ IDE way to get run the project. Therefore Open IntelliJ application.

----------

**Step 3**: In the third step you must select the root directory in the project with is `SANSA-Template-Maven-Spark`. Then as maven plugins are installed inside the IDE you see that the project automatically starts to include all the dependencies in the `pom.xml` file which is located in the root.

![alt text](https://raw.githubusercontent.com/imghasemi/SANSA-Template-Maven-Spark-Intellij/master/img/img1.png)

----------

**Step 4**: While it is checking the dependencies just click on the `Maven Projects` -> `SANSA-Template-Maven-Spark`-> `Lifecycle` -> `install`:

![alt text](https://raw.githubusercontent.com/imghasemi/SANSA-Template-Maven-Spark-Intellij/master/img/img2.png)

----------

**Step 5**: Download `rdf.nt` from [Here](https://raw.githubusercontent.com/SANSA-Stack/SANSA-Examples/develop/sansa-examples-spark/src/main/resources/rdf.nt) then put the file inside the `resources` folder if it does not exists there. Then add the `--input=src/main/resources/rdf.nt` in the arguments as below:
![alt text](https://raw.githubusercontent.com/imghasemi/SANSA-Template-Maven-Spark-Intellij/master/img/img3.png)

----------

**Step 6**: Then click on the GREEN PLAY button to make it run:

![alt text](https://raw.githubusercontent.com/imghasemi/SANSA-Template-Maven-Spark-Intellij/master/img/img4.png)

----------

Expected output if the configuration is correct:
----------
This template get run the `TripleReader.scala` example. The app read the `RDF` data then takes first 5 inputs and return. Here is an example of the output:

![alt text](https://raw.githubusercontent.com/imghasemi/SANSA-Template-Maven-Spark-Intellij/master/img/img5.png)




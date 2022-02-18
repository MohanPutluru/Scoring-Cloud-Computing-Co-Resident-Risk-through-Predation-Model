# Scoring-Cloud-Computing-Co-Resident-Risk-through-Predation-Model
## Damon Alsup, Mohan Putluru, Dr.Suxia Cui, Dr.Yunpeng Zhang
### Abstract:

The utility of the cloud results from amassing computation resources while being able to distribute workload.
The backbone of this ability is the virtual machine. This means of interface is also a primary vehicle and target
for attackers. Those remedies proposed and implemented to counter this threat consider the costs and benefits
to the cloud’s essential functions. Where the future development of the cloud is also considered, this
competition between attackers and benign users is analogous to those modeled in extended game theory. This
paper examines the game as a predator-prey contest played out on a data-center environment. A range of
contestant parameters are applied through the threshold of a viable model to the recognizable boundaries.
System health is compared to a baseline model in relief with individual cost and benefit

### Table of Contents
---------------------------------------------------
Directory structure of the CloudSim Toolkit

Software requirements: Java version 1.6 or newer

Installation and running the CloudSim Toolkit

Running the CloudSim examples

Learning CloudSim

Compiling CloudSim: using Ant

Directory structure of the CloudSim Toolkit

cloudsim/ -- top level CloudSim directory docs/ -- CloudSim API Documentation examples/ -- CloudSim examples jars/ -- CloudSim jar archives sources/ -- CloudSim source code tests/ -- CloudSim unit tests

Software requirements: Java version 1.6 or newer
CloudSim has been tested and ran on Sun's Java version 1.6.0 or newer. Older versions of Java are not compatible. If you have non-Sun Java version, such as gcj or J++, they may not be compatible. You also need to install Ant to compile CloudSim (explained in more details later).

Installation and running the CloudSim Toolkit
You just need to unpack the CloudSim file to install. If you want to remove CloudSim, then remove the whole cloudsim directory. You do not need to compile CloudSim source code. The JAR files are provided to compile and to run CloudSim applications:

jars/cloudsim-.jar -- contains the CloudSim class files
jars/cloudsim--sources.jar -- contains the CloudSim source code files
jars/cloudsim-examples-.jar -- contains the CloudSim examples class files
jars/cloudsim-examples--sources.jar -- contains the CloudSim examples source code files
Running the CloudSim examples
Please read how to run the CloudSim examples in examples.txt

Learning CloudSim
To understand how to use CloudSim, please go through the examples provided in the examples/ directory.

Compiling CloudSim: using Ant
This release contains a simple buildfile for compiling CloudSim classes. You need to have ant installed (http://ant.apache.org/). Ant can be used in both Windows and Unix/Linux environment.

Usage:

Being in the CloudSim root directory (cloudsim/), type 'ant' to compile all cloudsim source files, put them into the classes/ directory and to create a cloudsim-new.jar file in the jars/ directory

Being in the CloudSim root directory (cloudsim/), type 'ant clean' to delete all the compiled classes and the classes/ directory itself. The generated cloudsim-new.jar is not deleted.

Note:

You need to set up PATH for ant in Windows and/or Unix.

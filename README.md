Hands-on Lab on Sparkling Water
===============================

Requirements
------------

- Basic knowledge of Spark
- Knowing H2O helps but not important

Dependencies
------------

- Java 8
- Python 2.7 + with virtualenv installed
- Clone this repo as ``git clone https://github.com/jakubhava/ukraine-sparkling-water-workshop.git``

We will go through the rest of the environment setup together during the all hands

The Topic
---------

Sparkling Water provides access to H2O algorithms and publishes API to integrate them as part of regular Spark pipelines. This feature allows for seamless training and deployment of H2O algorithms in the Spark environment. Furthermore, trained pipelines do not require H2O runtime anymore (thanks to MOJO representation of trained H2O models) which enables variety of deployment scenarios. Moreover, by supporting Python and Scala environment, we enable a simple transfer of modeling results between data scientists (Python land) and production (JVM land). The goal of this hands-on is to show integration of H2O models into Spark pipelines using PySpark and PySparkling and demonstrate deployment of the trained pipeline in the context of JVM and Spark streaming.

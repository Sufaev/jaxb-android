Android JAXB 2.3.1
==================

Description
-----------
This project creates an Android compatible JAXB 2.3.1 jar.
Conflicting classes in java.awt and javax.activation have been
removed from the baseline. An uber-jar containing jaxb-api, jaxb-core,
and jaxb-impl is packaged using the Maven shade plugin.


Usage
-----
mvn install

# log4jconverter

mvn install, then java -jar target/log4jconverter-0.0.1-SNAPSHOT.jar your-input-log4j.xml

The conversion will not work without a comment after the DOCTYPE and before the log4j:configuration tag. If a comment does not exist in the log4j1x configuration, formatted similar to the example ahead, it must be added before running the application:
```
<!--
############################################################################
##
##  This is the log configuration for production.
##
############################################################################
-->
```

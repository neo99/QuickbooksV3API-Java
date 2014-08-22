QuickbooksV3API-Java
====================

QuickbooksV3API-Java Sample App
The instruction to set up sample app is available at https://developer.intuit.com/docs/0025_quickbooksapi/0055_devkits/sample_code/spring_sample_app_for_quickbooksapi/0002_creating_the_app

Please note
1. Eclipse EE version should be used; not the default Standard version
2. error at step 5
mvn install:install-file -DgroupId=com.intuit.code.devkit.v3 -DartifactId=ipp-v3-java-devkit -Dversion=1.0.7 -Dpackaging=jar -Dfile=JarFilePath\ipp-v3-java-devkit-2.2.1-jar-with-dependencies.jar

The "-Dversion=1.0.7" should be changed to the version of the jar.
For example, it should be 2.3.2 for the latest version 2.3.2
mvn install:install-file -DgroupId=com.intuit.code.devkit.v3 -DartifactId=ipp-v3-java-devkit -Dversion=2.3.2 -Dpackaging=jar -Dfile=JarFilePath\ipp-v3-java-devkit-2.3.2-jar-with-dependencies.jar

Command used to install vboxws.jar version 4.1.8 to local repository:

mvn deploy:deploy-file
    -DgroupId=org.virtualbox
    -DartifactId=vboxws-41
    -Dversion=4.1.8
    -Dpackaging=jar
    -Dfile=/PATH_TO_DOWNLOADED_JAR/vboxjws-4.1.8.jar
    -Durl=file:/PATH_TO_PLUGIN_SOURCES/virtualbox-plugin/plugin/../lib
    -DrepositoryId=virtualbox-libs


Command used to install vboxws.jar version 4.2.0 to local repository:

mvn deploy:deploy-file
    -DgroupId=org.virtualbox
    -DartifactId=vboxws-42
    -Dversion=4.2.0
    -Dpackaging=jar
    -Dfile=/PATH_TO_DOWNLOADED_JAR/vboxjws-4.2.0.jar
    -Durl=file:/PATH_TO_PLUGIN_SOURCES/virtualbox-plugin/plugin/../lib
    -DrepositoryId=virtualbox-libs

Command used to install vboxws.jar version 4.3.0 to local repository:

mvn deploy:deploy-file
    -DgroupId=org.virtualbox
    -DartifactId=vboxws-43
    -Dversion=4.3.0
    -Dpackaging=jar
    -Dfile=/PATH_TO_DOWNLOADED_JAR/vboxjws-4.3.0.jar
    -Durl=file:/PATH_TO_PLUGIN_SOURCES/virtualbox-plugin/plugin/../lib
    -DrepositoryId=virtualbox-libs



Command used to install vboxws.jar version 5.0.16 to local repository:

mvn deploy:deploy-file
    -DgroupId=org.virtualbox
    -DartifactId=vboxws-50
    -Dversion=5.0.16
    -Dpackaging=jar
    -Dfile=/PATH_TO_DOWNLOADED_JAR/vboxjws-5.0.16.jar
    -Durl=file:/PATH_TO_PLUGIN_SOURCES/virtualbox-plugin/plugin/../lib
    -DrepositoryId=virtualbox-libs



Command used to install vboxjws.jar version 6.0.12 to local repository:

mvn deploy:deploy-file
    -DgroupId=org.virtualbox
    -DartifactId=vboxws-60
    -Dversion=6.0.12
    -Dpackaging=jar
    -Dfile=/PATH_TO_DOWNLOADED_JAR/vboxjws-6.0.12.jar
    -Durl=file:/PATH_TO_PLUGIN_SOURCES/virtualbox-plugin/plugin/../lib
    -DrepositoryId=virtualbox-libs

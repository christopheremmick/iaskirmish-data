
# Building Java Library

To build the skirmsh-data jar.

    cd skirmish-data
    ../mvnw clean install

The output for the generated jar will be in the target folder.   You will need
to add the dependencies for jackson-core, jackson-databind, and jackson-annotation to your project as well.


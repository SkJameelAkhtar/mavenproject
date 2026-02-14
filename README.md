Task 3


The Clean Lifecycle is responsible for cleaning the project by removing files generated during previous builds. Its main purpose is to ensure that the project starts from a fresh state before a new build begins. It primarily deletes the target directory, which contains compiled classes, packaged files such as JAR or WAR files.

In contrast, the Default Lifecycle is responsible for building and deploying the project. It manages the complete build process, including compiling the source code, running tests, packaging the application, and installing or deploying it. The Default Lifecycle includes several important phases such as validate, compile, test, package, verify, install, and deploy. When a phase like mvn install is executed, Maven automatically runs all the preceding phases in sequence.

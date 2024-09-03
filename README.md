# Swtkal

This repository contains the Maven migration of the SWTKal projekt from SWT 1. You can use IntelliJ for loading the modules into the an existing project.

## Steps:
1. Install Maven command line tool (mvn --version should work)
2. Clone this repo
3. Execute 'mvn install' in the base directory to install all required remote plugins (dependencies)
4. Execute 'mvn clean package' at the root level of this repo (same directory as this Readme.MD file)
5. Use 'java -jar SwtKal.SwingGui/target/SwtKal.SwingGui-1.0-SNAPSHOT-jar-with-dependencies.jar' for starting the application. You should see the Calendar app now.

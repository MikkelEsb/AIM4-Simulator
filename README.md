# AIM4-Simulator
The open source code behind the Autonomous Intersection Management simulator from University of Texas.

AIM4 is a traffic simulator for the study of innovative design of intersection control protocol.
This program is based on the source code of AIM3, which is written by Kurt Dresner.
AIM4 is currently maintained by Tsz-Chiu Au <chiu@cs.utexas.edu>.

## Running the Simulation

**For more information on the simulation, view the documentation located in the `docs/` directory.**

Install Apache Maven (version >= 2.2.1):

To compile with testing, type

`mvn assembly:assembly`

To compile without testing, type

`mvn -Dmaven.test.skip=true assembly:assembly`

To run the jar file, type

`java -jar target/AIM4-1.0-SNAPSHOT-jar-with-dependencies.jar`

To execute a particular main function, type

`java -cp target/AIM4-1.0-SNAPSHOT-jar-with-dependencies.jar <YOUR_MAIN_FUNCTION>`

To check the coding style, type

`mvn checkstyle:checkstyle`

`view target/checkstyle-result.xml`

To clean up, type

`mvn clean`

## Release Notes

Version 1.0.3
- Fixed a bug in TiledArea.java.

Version 1.0.2
- Updated the user guide and the installation guide.

Version 1.0.1
- Added copyright statement.
- Fixed a bug in the traffic signal mode in the standalone executable.

Version 1.0.0
- Initial release

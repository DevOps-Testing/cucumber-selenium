# cucumber-selenium


mvn test -Dcucumber.options="–help"

Run one scenario:
mvn test -Dcucumber.options=”feature file path” + “line number of the scenario”

Run using tags:
mvn test -Dcucumber.options="–tags @tag Name"


mvn test -Dcucumber.options="–plugin junit:target/cucumber-reports/report.xml"

mvn test -Dcucumber.options="src/test/resources/functionalTests/End2End_Tests.feature"

mvn test -Dcucumber.options="src/test/resources/functionalTests/End2End_Tests.feature" -Dcucumber.options="–tags @Smoke"


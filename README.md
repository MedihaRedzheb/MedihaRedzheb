*Execute all tests:*
mvn test

*Execute all tests from specific test class:*
mvn test -Dtest=testclassName

*Execute single test from specific test class:*
mvn test -Dtest=TestClassName#nameOfMethod

*Run tests using Edge browser:*
mvn test -Dbrowser=edge

*Run tests using Chrome browser:*
mvn test -Dbrowser=chrome

*Path to html report -->* \SwagLabsTests\target\surefire-reports\index.html
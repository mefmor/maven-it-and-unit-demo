# maven-it-and-unit-demo
This repository demonstrate ability to run UnitTests on the Test phase and IntegrationTests on the Integration Test phase

By default **mvn test** run all classes in _src/test/java_, that contains "_Test_".
But in case we need to run Integration Tests only in the _Integration Test phase_, we can configure maven-surefire-plugin.
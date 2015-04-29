Maven Cargo Wildfly commands:

Simple command:
mvn clean install

Use cargo run goal to keep the server running:
mvn clean install -Dcargo.goal=run

Start server in port offset of 1000:
mvn clean install -Dwildfly1.http.port=9080 -Dwildfly1.management.port=10990 -Dwildfly1.port.offset=1000 -Dwildfly1.debug.port=9787
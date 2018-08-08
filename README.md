Build

`mvn package`

Run

`java -javaagent:newrelic.jar -Dnewrelic.config.file=newrelic.yml -Dnewrelic.config.transaction_events.max_samples_stored=100 -jar target/demo-0.0.1-SNAPSHOT.jar`

or

``
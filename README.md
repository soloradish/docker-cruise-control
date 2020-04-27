kafka-cruise-control
====================

LinkedIn Cruise Control manager for Kafka. This image includes the Cruise Control application.
It includes the metrics reporter jar at `/opt/cruise-control/cruise-control/build/dependant-libs/cruise-control-metrics-reporter.jar`.

Compose file example:

https://github.com/soloradish/docker-cruise-control/tree/master/compose-example

Customize `cruisecontrol.properties` file under `compose-example/configs` folder. and run

    docker-compose up
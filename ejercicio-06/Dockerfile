FROM registry.access.redhat.com/redhat-openjdk-18/openjdk18-openshift:1.12-1.1661378017
ADD passwordapi.jar .
ENTRYPOINT ["java", "-jar", "passwordapi.jar"]
# service-foo

`Mirco Service`

This application was generated using Duiker.

## Development

To start your application in the dev profile, simply run:

    ./gradlew

## Building for production

To optimize the platform application for production, run:

    ./gradlew -Pprod clean bootRepackage

To ensure everything worked, run:

    java -jar build/libs/*.jar

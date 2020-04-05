# SPI event listener

An example of a custom event listener that simply logs the events.

## Keycloak config

Copy the jar in the target folder to the `/opt/jboss/keycloak/standalone/deployments/` folder.
Or when using Docker mount the file `./jar-name.jar:/opt/jboss/keycloak/standalone/deployments/jar-name.jar`

## Keycloak admin console configuration

* Open up Keycloak administration console and select your realm
* Go to events in the left side bar under Manage
* Open the config [tab]
* click in the input box next to event listeners, a dropdown with all available event listeners is shown
* select our pl_event_listener

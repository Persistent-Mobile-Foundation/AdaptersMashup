Persistent Mobile Foundation
===
## Adapter Mashup
A sample that demonstrates adapters mashup (passing requests between different adapters paths/procedures).
This sample demonstrates a specific scenario where an SQL adapter collects data from a database, passes the data to an HTTP adapter that calls a Webservice and returns the data accepted from the Webservice.
The demonstration is presented in 3 possible combinations:

1. JavaScript adapter -> JavaScript adapter.
2. Java adapter -> JavaScript adapter.
3. Java adapter -> Java adapter.

### Tutorials
https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/adapters/advanced-adapter-usage-mashup

### Usage

#### SQL setup
An example of city list in SQL is available in the provided adapter maven project (located inside the Cordova project), under `Utils/mobilefirstTraining.sql`. 

1. Run the .sql script in your SQL database.
2. Use either Maven or MobileFirst Developer CLI to [build and deploy the adapters](https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/adapters/creating-adapters/).
3. Open the MobileFirst Console
    - Click on the **getCitiesListJS** adapter and update the database connectivity properties.
    - Click on the **getCitiesListJava** adapter and update the database connectivity properties.

#### Application setup

1. From the command line, navigate to the project's root folder.
2. Add a platform by running the `cordova platform add` command.
3. Run the Cordova application by running the `cordova run` command.



## 9.3.0

#### Project


#### OAP Server

* Add component ID(133) for impala JDBC Java agent plugin and component ID(134) for impala server
* Use prepareStatement in H2SQLExecutor#getByIDs.(No function change).
* Bump up snakeyaml to 1.31 for fixing CVE-2022-25857
* Fix `DurationUtils.convertToTimeBucket` missed verify date format.
* [**Breaking Change**] Change the LAL script format(Add layer property).

#### UI

* Fix: tab active incorrectly, when click tab space
* Add impala icon for impala JDBC Java agent plugin.
* (Webapp)Bump up snakeyaml to 1.31 for fixing CVE-2022-25857
* [Breaking Change]: migrate from Spring Web to Armeria, now you should use the environment variable name `SW_OAP_ADDRESS`
  to change the OAP backend service addresses, like `SW_OAP_ADDRESS=localhost:12800,localhost:12801`, and use environment
  variable `SW_SERVER_PORT` to change the port. Other Spring-related configurations don't take effect anymore.


#### Documentation


All issues and pull requests are [here](https://github.com/apache/skywalking/milestone/149?closed=1)

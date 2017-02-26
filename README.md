[maven]: http://maven.apache.org/
[git]: http://git-scm.com/

## Allure TestNG Example

### Getting Started

To run tests you need to install [maven][maven], [git][git].

To generate Allure Report you should perform following steps:

```bash
$ git clone https://github.com/Mictim/allure_testng.git
$ mvn clean test
$ mvn site
```

To see a report, run `mvn jetty:run` and open `http://localhost:8080` in your browser

**NOTE: required maven version 3.1.1 or above**

### More

* [Documentation](https://github.com/allure-framework/allure-core/wiki)
* [Issue Tracking](https://github.com/allure-framework/allure-core/issues?labels=&milestone=&page=1&state=open)


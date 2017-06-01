# arquillian-example
arquillian example project


```sh
$ bin/standalone.sh -b 10.0.1.6 -bmanagement 10.0.1.6
$ bin/standalone.sh -b 0.0.0.0 -bmanagement 0.0.0.0
```

```sh
$ mvn clean test -Parq-wildfly-remote
$ mvn clean test -Parq-wildfly-managed
```

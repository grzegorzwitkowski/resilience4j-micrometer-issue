# A demo project showing an issue with Resilience4j and micrometer-core

## show the issue

```shell
./gradlew bootRun
```

It fails with `java.lang.ClassNotFoundException: org.springframework.boot.actuate.autoconfigure.metrics.MetricsAutoConfiguration`

## fix

Uncomment `spring-boot-actuator-autoconfigure` dependency in `build.gradle` and run again

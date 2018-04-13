When applied at the command line, the property `org.gradle.caching` appears to be ignored

example:
```
➜  build-cache-sample gradle clean build --build-cache

BUILD SUCCESSFUL in 1s
5 actionable tasks: 5 executed
➜  build-cache-sample gradle clean build --build-cache

BUILD SUCCESSFUL in 0s
5 actionable tasks: 2 executed, 3 from cache
➜  build-cache-sample gradle clean build -Porg.gradle.caching=true

BUILD SUCCESSFUL in 0s
5 actionable tasks: 5 executed
```

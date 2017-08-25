# Guide for Testing Apps

This library implements simple caching methods that can be used in your apps. See documentation
here: https://enonic-docs.s3.amazonaws.com/com.enonic.guide/guide-testing-apps/index.html

## Building

To build this project, execute the following:

```
./gradlew clean build
```

## Documentation

Building the documentation is done executing the following:

```
./gradlew buildDoc
```

And publishing the docs to S3:

```
./gradlew publishDoc
```

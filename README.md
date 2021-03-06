# Starter Service

To create this service locally on your machine:

```
serverless create --template-url https://github.com/cnktech/serviceStarterTemplate
```

### Overview

There are 5 parts to this service:

-   domain
-   infra
-   triggers
-   io
-   interfaces

![Overview](https://design-autrpctplz.now.sh/arch-overview.png)

### Testing

We test the following:

-   100% of the domain with unit tests
-   100% of the real adaptors in infra with integration tests
-   100% of the triggers with integration tests
-   100% of the io with contract tests (maybe)

We use interfaces to insure that each part of the system is following contract between layers.

### Flow of execution

![Drivers](https://design-autrpctplz.now.sh/arch-drivers.png)

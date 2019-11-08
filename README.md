# logs-analytics-events
Log analytics events to a log file.

## Usage

Step1: Set the below config in the config file:
```xml
  <Analytics>
    <Enabled>true</Enabled>
    <SkipWorkflowEventPublisher>true</SkipWorkflowEventPublisher>
    <PublisherClass>com.rukspot.samples.analytics.publisher. FilePublisher</PublisherClass>
  </Analytics>
```

Setp2: Add the following to the log4j.properties:

```
log4j.category.com.rukspot.samples.analytics.publisher=INFO
```

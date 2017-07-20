## Go

### Wizard

[Wizard](https://github.com/evalphobia/wizard) is the database connection library, which supports sharding and multiple instances.  
[xorm](https://github.com/go-xorm/xorm) is used in wizard. (thanks [lunny](https://github.com/lunny))  

[See the summary deck](https://www.slideshare.net/TakumaMorikawa/golangtokyo-7-wizard-database-sharding-library-for-golang)

### aws-sdk-go-wrapper

[aws-sdk-go-wrapper](https://github.com/evalphobia/aws-sdk-go-wrapper) is wrapper library of [aws-sdk-go](https://github.com/aws/aws-sdk-go).  
This enables to use AWS SDK in golang with easy syntax.  

Supported services below,

- DynamoDB
- Kinesis
- S3
- SNS
- SQS

### google-api-go-wrapper

[google-api-go-wrapper](https://github.com/evalphobia/google-api-go-wrapper) is wrapper library for Google services.

Supported services below,

- Google Analytics
- BigQuery
- Stackdriver Logging
- Stackdrriver monitoring
- Google Cloud Vision

### google-vision-ocr

[google-vision-ocr](https://github.com/evalphobia/google-vision-ocr) extracts text from a bunch of images and save it to CSV.

### eurekache

[eurekache](https://github.com/evalphobia/eurekache) is cache library, which supports multiple fallbacking cache chains.

### go-paypal-classic

[go-paypal-classic](https://github.com/evalphobia/go-paypal-classic) is PayPal library for Classic API.

### go-iap

[go-iap](https://github.com/evalphobia/go-iap) is forked from [dogenzaka/go-iap](https://github.com/dogenzaka/go-iap), golang library for iOS IAP and Android IAB.  
This version supports old version IAP receipts(iOS6 style receipt).  

### go-yml2sql

[go-yml2sql](https://github.com/evalphobia/go-yml2sql) is library to create SQL statement from YAML file.  
This supports CLI and import code.  

### kinesis-tail

[kinesis-tail](https://github.com/evalphobia/kinesis-tail) is tailing tool from Amazon Kinesis Stream.

### Logrus hooks

These are plugins to sends log data to external services for [logrus](https://github.com/Sirupsen/logrus).


- [logrus_appneta](https://github.com/evalphobia/logrus_appneta)
    - [TraceView](https://traceview.solarwinds.com/) hook
- [logrus_kinesis](https://github.com/evalphobia/logrus_kinesis)
    - [AWS Kinesis](https://aws.amazon.com/kinesis/) hook
- [logrus_sentry](https://github.com/evalphobia/logrus_sentry)
    - [Sentry](https://sentry.io/) hook
- [logrus_fluent](https://github.com/evalphobia/logrus_fluent)
    - [fluentd](http://www.fluentd.org/) hook

### go-simple-proxy

[go-simple-proxy](https://github.com/evalphobia/go-simple-proxy) is TCP proxy to forwarding port for unit testing.

### github-branch-pr-number

[github-branch-pr-number](https://github.com/evalphobia/github-branch-pr-number) is CLI tool to get PullRequest number from branch name.

### go-datarobot

[go-datarobot](https://github.com/evalphobia/go-datarobot) is [DataRobot](https://www.datarobot.com/) API client for golang.


----

## JS

### Hydranger

[Hydranger](https://github.com/evalphobia/hydranger) is frontend page for Google Spread Sheet.   
See [demo](http://evalphobia.github.io/hydranger/demo/)

### github2slack-lambda

[github2slack-lambda](https://github.com/evalphobia/github2slack-lambda) is forked from [kawahara/github2slack-lambda](https://github.com/kawahara/github2slack-lambda), sending Github repository event to Slack channel via SNS and lambda.  

This version supports multi channels, custom icons and attachment message.

### jira2slack-lambda

[jira2slack-lambda](https://github.com/evalphobia/jira2slack-lambda) is sending JIRA event to Slack channel via API Gateway and lambda.


### google-search-comparer (* deprecated)

Yo can use [google-search-comparer](https://github.com/evalphobia/google-search-comparer) to compare the search result to change keyword order.  
You might think "for what?"  
Oh, I'm serious.  

See [demo](http://evalphobia.github.io/google-search-comparer/) (* Google's API is already deprecated now)

----

## Support or Contact

[see my profile page](https://github.com/evalphobia)

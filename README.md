# crypto-volume-tracker
Based on binance pairs 

## Features
MVP
- Track volume change of crypto future pairs from binance 
- Recommendation pair that should deep analysis on  1Hr and 4Hr
- Fake call statistic 

Phase 2
- Send alert to discord channel

## High level design

### Technology stack
- React (UI)
- NodeJs (Lambda)
- Terraform (IaC)
- AWS DynamoDB (DB)

### Sequence diagram
![](crypto-volume-tracker.png)

### Deployment view

#### Application
![](deployment-view.png)

#### Metadata Service
![](metadatservices-deploymentview.png)

### Cost projection
Total cost [36](https://calculator.aws/#/estimate?id=f459b6bf1912a37586cb3b79dd4981c920262f4d) USD /month

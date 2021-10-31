# Solution
## Solution Overview

TBA

- Serverless for custom components using API Gateway and Lambda ( Pay per Requests)
- Cheap Analytics solution using AWS Glue and AWS Athena 
- Use existing system like AWS Cognito and AWS Dynamo DB for Storage to avoid an addtional operational cost

## Constrains

....

## Risks

...

## Data Model

![data-model](diagrams/data_model.png)

...

## Components Diagram 

![component_diagram](diagrams/component_diagram.png)

...

### Security

- Integrate with existing AWS Cognito solution - User Pool as It is part of original solution   
- Manage user account for Dietitian and Medical Provider
- Provide Authentication  & Authorisation 

### Cutomer Profile

- Configure Profile Attributes 

- Configure Medical tests

- Create and View Customer Profiles

- Customer can set Profile Privacy

  

### eDietian

- Send Advice
- Monitor Customer

### Notification

- Emails
- Newsletter Subscriptions

### Analytics

- Geographical trend analysis
- Medical Profile analysis
- Customers Segmant analysis

### Reports

- View analysis Result by Medical Profile, Marketing

### Community

- forum (localized, temporal)

- Survey

- Direct Messaging

- in person / virtual events (localized, temporal)

- classes (localized, temporal) and general wellness education (global, reference)

- interactive media library (global, reference)

  

## Sequence Diagrams

### Onboarding

![](diagrams/onboarding_flow.png)

....

### Customer Segmentation

![](diagrams/customer_segmentation.png)

### Analytics

![](diagrams/analytics.png)

...

### Medical Test

...

## Physical Architecture

...

## Design Decisions 

### Data Storage

Dynamo DB vs RDS

### Customer Segmantion

Scheduled  job vs immediate calculation 

### Custom Modules

Serverless vs Monolithic 

## Quality Of Service (QoS)

- Security
- Extendability 
- Scalability 
- Performance
- Reliability

<br>
<hr style="height:2px;border-width:0;color:gray;background-color:gray">

##  [<-- Back](2_Requirements.md) | [Home](README.md) | [Next -->](4_Team.md)
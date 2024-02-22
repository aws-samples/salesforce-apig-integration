# Salesforce APIG Integration

This solution demonstrates how to implement a secure private integration between Salesforce and a private [Amazon API Gateway](https://aws.amazon.com/api-gateway/) using [AWS PrivateLink](https://aws.amazon.com/privatelink/) technology to support a synchronous user experience while meeting security and performance requirements. The integration can be leveraged in a Salesforce Flow.

## AWS Blog post
The AWS blog post explaining how this solution works, and how to deploy the Amazon CloudFormation templates.

**NEED TO UPDATE** https://aws.amazon.com/blogs/

## Amazon CloudFormation templates
This repository provides the following Amazon CloudFormation template used to provision the demo environment:

- `template.yaml`
  - Provisions a stack housing the AWS Services required to demonstrate and test the integration with Salesforce. This can be used standalone to test the solution.

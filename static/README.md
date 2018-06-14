# Stack

Static Website

# Overview

This repo is a demonstration of Continuous Delivery of a static website to S3 via CodeBuild and CodePipeline. To launch, you'll need to specify a unique S3 bucket name for the website bucket that will be created. Ensure you've configured the [Prerequisites](https://github.com/telemundo/cloudformation-stacks/wiki/Prerequisites) before launching the stack below.

# Launch Stack

[![Launch CFN stack](https://s3.amazonaws.com/telemundo-cloudformation-stacks/cloudformation-launch-stack.svg)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=telemundo-cloudformation-stack-static&templateURL=https://s3.amazonaws.com/telemundo-cloudformation-stacks/static/static.template)

# Design Stack

![alt text](https://raw.githubusercontent.com/telemundo/cloudformation-stacks/master/static/template-designer.png)

# Configure Solution

1.  Once the CloudFormation stack is successful, select the checkbox next to the stack and click the **Outputs** tab.
1.  From **Outputs**, click on the **PipelineUrl** output.
1.  Once the pipeline is complete, go to your CloudFormation Outputs and click on the **SiteUrl** Output

# Resources

1.  The CloudFormation template is available [here](https://s3.amazonaws.com/telemundo-cloudformation-stacks/static/static.template).

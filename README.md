# spacestack

## AWS CDK and cloudFormation intro

1. Basic understanding of AWS CDK with a small project
   1. Installation
   2. Configuration
   3. Talk about CDK version
2. Basic understanding of AWS cloudFormation
3. Deployment to AWS
   1. Outputs
   2. Deployment parameters



## understanding AWS CDK 

1. Definition: Abstraction of AWS resources
   Abstraction: reusable component capable of hiding complex implementation. 
2. Use AWS CDK to:
   1. Create and deploy AWS resources 
   2. Configure those resources
   3. Link together resources into constructs


## CDK is for all developers

1. Multiple language support: `Java`, `C#`, `Python`, `Go`, `JavaScript`, `TypeScript`
2. JavaScript Interop Interface -`JSII`

[TypeScript] -----> [JSII] ----> [Java], [C#], [Python], ...



## Installing CDK 

```bash

sudo npm i -g aws-cdk

cdk --version


cdk init app --language typescript

cdk synth


# cloud formation Stack
cdk bootstrap

# for deploy
cdk deploy 

```
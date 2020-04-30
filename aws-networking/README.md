

Overview
========

In this workshop you will learn how to set-up most of the AWS Networking Resources


The workshop is broken up into the five modules below:

1.	[Core AWS Networking](ModuleOneCore.md)
2.	[Elastic Load Balancers](ModuleTwoELB.md)
3.	[VPN Gateway](ModuleThreeVPN.md)
4.	[VPC Peering](ModuleFourPeering.md)
5.	[TransitGateway](ModuleFiveTransit.md)


-	*Level*: Beginner - Intermediate

-	*Duration*: 30 min - 3:00 hour


Prerequisites
=============

1.	You will need an AWS account for this workshop and administrative credentials.
2.	The instructions are written with the understanding that the account is new or clean. We strongly recommend that you do not do these workshops in work or "production" accounts.
3.	You will incur charges for the AWS resources used in this workshop.   The charges for some of the resources may be covered through the [AWS Free Tier](https://aws.amazon.com/free/).  The demo uses free tier choices wherever possible.
4.	If you are using an existing account with resources already deployed in a region, be aware of the soft limit of five VPCs per region.
6.	You can run this workshop in any region. In our example we are using the *eu-west-1* region.

CloudFormation Templates
========================

Each Module comes with one or multiple Cloudformation templates which can be used to quickly build or rebuild the lab environment.

1. [Module One - Core Networking Template](./cloudformation/module-one-core.yml)
2. [Module One - Security groups Template](./cloudformation/module-one-security-group.yml)  
This module rely on the Core Networking Templates.  
3. [Module Two - Load Balancer Template](./cloudformation/module-two-elb.yml)
This module rely on the Core Networking and the security group templates.

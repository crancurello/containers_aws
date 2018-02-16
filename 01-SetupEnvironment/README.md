# Setup Environment

This section describes the hardware and software needed for this workshop, and how to configure them. This workshop is designed for a BYOL (Brying Your Own Laptop) style hands-on-lab.

##########################################################################################
## IF USING A CLOUD9 ENVIRONMENT:
##########################################################################################

Using a Cloud9 environment allows you to interact directly with an cloud-native IDE

## Creating a Cloud9 environment

Sign in on your AWS Console

Select Virigina as REGION

Choose Cloud9 from the Services menu

Clic "Create environment"

Give the environment a name (any name you want)

On Environment Type, select "Create a new instance for environment"

On Instance Type, select t2.small

Clic "Next" 

Clic "Create environment"

You can have more information about launching a Cloud9 IDE on AWS here: https://docs.aws.amazon.com/cloud9/latest/user-guide/create-environment.html

The creation of a cloud9 environment can take up to 5 minutes. Please wait

Once you are on the cloud9 environment, verify the following:

## Install Docker

issue "docker --version"

if no output is detected, please refer to this guide to install it:

http://docs.aws.amazon.com/es_es/AmazonECS/latest/developerguide/docker-basics.html

## Install git

issue the following command: 

sudo yum install git -y

You can have more information about git here: https://git-scm.com/book/en/v1/Getting-Started

## Verify AWS Credentials

issue the following command:

aws ec2 describe-regions

If you get any error message, please attach an role with admin policies to the cloud9 ec2 instance

## Proceed to the next stage of the workshop:

https://github.com/crancurello/containers_aws/tree/master/02-CreatingDockerImage

##########################################################################################
## IF USING YOUR OWN LAPTOP AS YOUR ENVIRONMENT:
##########################################################################################

## Hardware & Software

- Memory: At least 4 GB+, strongly preferred 8 GB
- Operating System: Mac OS X (10.10.3+), Windows 10 Pro+ 64-bit, Ubuntu 12+, CentOS 7+.

> NOTE: An older version of the operating system may be used.

## Install Docker

Docker runs natively on Mac, Windows and Linux. This lab will use https://www.docker.com/community-edition#/download (Docker Community Edition - CE). Download the Docker CE edition for your machine from the https://store.docker.com/search?type=edition&offering=community (Docker Store).

Install Docker: http://docs.aws.amazon.com/es_es/AmazonECS/latest/developerguide/docker-basics.html

> NOTE: Docker CE requires a fairly recent operating system version. If your machine does not meet the requirements, then you need to install https://www.docker.com/products/docker-toolbox (Docker Toolbox).

## Install AWS CLI

During this workshop we will interact with some AWS API's. Having the latest version of the AWS CLI in your computer is appropriated.

Instructions to install the AWS CLI are available here: http://docs.aws.amazon.com/cli/latest/userguide/installing.html

## Install git

Download and install here: https://git-scm.com/downloads

## Proceed to the next stage of the workshop:

https://github.com/crancurello/containers_aws/tree/master/02-CreatingDockerImage


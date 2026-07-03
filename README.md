# jrr-udagram-iac-project
Project for Udacity course "Deploy Infrastructure As Code", part of the CloudDevOps NanoDegree

To create the CloudFormation Stacks in AWS, run the following commands from the aws cli:

`$ ./run.sh deploy us-east-1 udagram-project-jrr network.yml network-parameters.json`

`$./run.sh deploy us-east-1 webapp-udagram-project-jrr udagram.yml udagram-parameters.json`

To delete the stacks from AWS, run : 

`$./run.sh delete us-east-1 udagram-project-jrr`

`$./run.sh delete us-east-1 webapp-udagram-project-jrr`


To preview changes made to the templates:

`$./run.sh preview us-east-1 udagram-project-jrr network.yml network-parameters.json`

`$./run.sh preview us-east-1 webapp-udagram-project-jrr udagram.yml udagram-parameters.json`


Or alternatively, use the CloudFormation console for creating the stacks (recommended).

A live URL of the deployed stack can be reached at the [DNS URL](http://webapp-webap-bpyhjzffecs8-1915047134.us-east-1.elb.amazonaws.com/)

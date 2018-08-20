# snapshotanalyzer-3000

Demo project to manage AWS EC2 instances snapshots

## About

This is a demo, and uses boto3 to manage AWS EC2 instances snapshots

## Confgiuration

shotty uses the configuration file created by the AWS CLI

`aws configure`

## Running

`pipenv run "python shotty\shotty.py <command> <--project=PROJECT>"`

*command* is to list, stop and Start
*project* is optional 

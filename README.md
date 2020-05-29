# snapshotalyser
Project to manage AWS EC2 instance snapshots


## About

This project uses boto3 to manage AWS EC2 instances snapshots.


## Configuring

shotty uses the configuration file created by the AWS cli. e.g.

'aws configure --profile shotty'

## Running

pipenv run python shotty/shotty.py <command> <--project=PROJECT>

*command* is a list, start, or stop
*project* is optional

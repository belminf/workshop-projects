# Setup
Configure a server with Mongo. For instructions:

### AWS + Amazon Linux
You must first create an AWS instance with Amazon Linux. See [AWS docs](https://aws.amazon.com/premiumsupport/knowledge-center/create-linux-instance/). You could also create it via [CloudFormation stack](cfn-template.yaml):

```bash
$ pip install awscli
$ aws cloudformation create-stack --template-body file://cfn-template.yaml --stack-name mongo-workshop-stack --parameters ParameterKey=KeyName,ParameterValue=belminf@gmail.com ParameterKey=AMIID,ParameterValue=ami-5583d42f
```

Then, follow [MongoDB instructions](https://docs.mongodb.com/v3.0/tutorial/install-mongodb-on-amazon/).

### DigitalOcean + Ubuntu
 
 See [DigitalOcean docs](https://www.digitalocean.com/community/tutorials/how-to-install-mongodb-on-ubuntu-16-04).

# Workshop

https://github.com/goinggo/MongoDB-Workshop/blob/master/README.md

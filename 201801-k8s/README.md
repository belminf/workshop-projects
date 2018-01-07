# Setup
Need `awscli` installed:

    pip install -r requirements.txt

# Example run

    aws cloudformation create-stack --stack-name my-project --template-body file://cfn-template.yaml --parameters ParameterKey=ProjectName,ParameterValue=my-project

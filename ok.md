<details><summary>DEV</summary><br/>
<details><summary>Create gh-actions-user</summary><br/>
aws cloudformation create-stack --stack-name quoddud-gql-beta-gh-actions-user \
  --template-body file://main.yml \
  --parameters ParameterKey=AssetsEcrRepository,ParameterValue=cloud-unigql-beta \
  ParameterKey=LambdaService,ParameterValue=unigql-beta \
  ParameterKey=HostedZoneId,ParameterValue=Z0445463G44KW7B1YUXX \
  ParameterKey=ExternalId,ParameterValue=dev-unigql-beta \
  ParameterKey=ProjectName,ParameterValue=unigql-beta\
  --tags Key=project,Value=unigql-beta \
  --region us-east-2 \
  --capabilities CAPABILITY_NAMED_IAM \
</details>

<details><summary>Update gh-actions-user</summary><br/>
aws cloudformation update-stack --stack-name quoddud-gql-beta-gh-actions-user \
  --template-body file://main.yml \
  --parameters ParameterKey=AssetsEcrRepository,ParameterValue=cloud-unigql-beta \
  ParameterKey=LambdaService,ParameterValue=unigql-beta \
  ParameterKey=HostedZoneId,ParameterValue=Z0445463G44KW7B1YUXX \
  ParameterKey=ExternalId,ParameterValue=dev-unigql-beta \
  ParameterKey=ProjectName,ParameterValue=unigql-beta\
  --tags Key=project,Value=unigql-beta \
  --region us-east-2 \
  --capabilities CAPABILITY_NAMED_IAM \
</details>

<details><summary>Delete</summary><br/>
aws cloudformation delete-stack --stack-name quoddud-gql-beta-gh-actions-user --region us-east-2
</details>

</details>


<details><summary>STG</summary><br/>
<details><summary>Create gh-actions-user</summary><br/>
aws cloudformation create-stack --stack-name quoddud-gql-beta-gh-actions-user \
  --template-body file://main.yml \
  --parameters ParameterKey=AssetsEcrRepository,ParameterValue=cloud-unigql-beta \
  ParameterKey=LambdaService,ParameterValue=unigql-beta \
  ParameterKey=HostedZoneId,ParameterValue=Z0445463G44KW7B1YUXX \
  ParameterKey=ExternalId,ParameterValue=dev-unigql-beta \
  ParameterKey=ProjectName,ParameterValue=unigql-beta\
  --tags Key=project,Value=unigql-beta \
  --region us-east-2 \
  --capabilities CAPABILITY_NAMED_IAM \
</details>

<details><summary>Update gh-actions-user</summary><br/>
aws cloudformation update-stack --stack-name quoddud-gql-beta-gh-actions-user \
  --template-body file://main.yml \
  --parameters ParameterKey=AssetsEcrRepository,ParameterValue=cloud-unigql-beta \
  ParameterKey=LambdaService,ParameterValue=unigql-beta \
  ParameterKey=HostedZoneId,ParameterValue=Z0445463G44KW7B1YUXX \
  ParameterKey=ExternalId,ParameterValue=dev-unigql-beta \
  ParameterKey=ProjectName,ParameterValue=unigql-beta\
  --tags Key=project,Value=unigql-beta \
  --region us-east-2 \
  --capabilities CAPABILITY_NAMED_IAM \
</details>

<details><summary>Delete</summary><br/>
aws cloudformation delete-stack --stack-name quoddud-gql-beta-gh-actions-user --region us-east-2
</details>

</details>

<details><summary>PROD</summary><br/>
<details><summary>Create gh-actions-user</summary><br/>
aws cloudformation create-stack --stack-name quoddud-gql-beta-gh-actions-user \
  --template-body file://main.yml \
  --parameters ParameterKey=AssetsEcrRepository,ParameterValue=cloud-unigql-beta \
  ParameterKey=LambdaService,ParameterValue=unigql-beta \
  ParameterKey=HostedZoneId,ParameterValue=Z0445463G44KW7B1YUXX \
  ParameterKey=ExternalId,ParameterValue=dev-unigql-beta \
  ParameterKey=ProjectName,ParameterValue=unigql-beta\
  --tags Key=project,Value=unigql-beta \
  --region us-east-2 \
  --capabilities CAPABILITY_NAMED_IAM \
</details>

<details><summary>Update gh-actions-user</summary><br/>
aws cloudformation update-stack --stack-name quoddud-gql-beta-gh-actions-user \
  --template-body file://main.yml \
  --parameters ParameterKey=AssetsEcrRepository,ParameterValue=cloud-unigql-beta \
  ParameterKey=LambdaService,ParameterValue=unigql-beta \
  ParameterKey=HostedZoneId,ParameterValue=Z0445463G44KW7B1YUXX \
  ParameterKey=ExternalId,ParameterValue=dev-unigql-beta \
  ParameterKey=ProjectName,ParameterValue=unigql-beta\
  --tags Key=project,Value=unigql-beta \
  --region us-east-2 \
  --capabilities CAPABILITY_NAMED_IAM \
</details>

<details><summary>Delete</summary><br/>
aws cloudformation delete-stack --stack-name quoddud-gql-beta-gh-actions-user --region us-east-2
</details>

</details>



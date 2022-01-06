# GitHub Actions User Template
This cloudformation template is used to create and maintain the aws user and permissions needed by this repo's github action workflows. This template is only applied manually as a one-time step or as needed for updates.

## Usage Examples:

<details><summary>Create aws user</summary><br/>

<details><summary>DEV</summary><br/>

  ```sh
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
 ```

</details>

<details><summary>STG</summary><br/>

  ```sh
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
 ```
</details>
<details><summary>PROD</summary><br/>

  ```sh
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
 ```
</details>
</details>
<details><summary>Update aws user</summary><br/>

<details><summary>DEV</summary><br/>

  ```sh
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
 ```
</details>

<details><summary>STG</summary><br/>

  ```sh
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
 ```
</details>
<details><summary>PROD</summary><br/>

  ```sh
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
 ```
</details>
</details>
  
<details><summary>Delete aws user</summary><br/>

<details><summary>DEV</summary><br/>

  ```sh
  aws cloudformation delete-stack --stack-name quoddud-gql-beta-gh-actions-user --region us-east-2
 ```
</details>


<details><summary>STG</summary><br/>

  ```sh
  aws cloudformation delete-stack --stack-name quoddud-gql-beta-gh-actions-user --region us-east-2
 ```
</details>
<details><summary>PROD</summary><br/>

  ```sh
  aws cloudformation delete-stack --stack-name quoddud-gql-beta-gh-actions-user --region us-east-2
 ```
</details>

</details>

---

NOTE: This github action user pattern and cloudformation template is based on:
- https://medium.com/cloud-recipes/configuring-github-actions-to-access-aws-efb9fe13d722
- https://github.com/antklim/gh-actions-user
- https://github.com/aws-actions/configure-aws-credentials


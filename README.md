# AWS AMPLIFY GUIDE

## CLI
Install CLI `$ npm i -g @aws-amplify/cli`

Configure amplify with AWS account `$ amplify configure`

- Log into AWS account
- Select region
- Select username (to be configured in IAM)
- Set user credentials
- Set profile name (default)

Initialize amplify `$ amplify init`

- Enter project name
- Enter name for environment
- Choose default editor
- Choose language
- Choose framework
- Complete accordingly

Create backend API `$ amplify add api`

- Select service (REST, GraphQL)
- Provide API name
- Choose authorization type
- Complete accordingly
- Create schema

Upload changes to the cloud `$ amplify push`

- Generate code for GraphQL API
- Choose language target
- Complete accordingly

*Note: in case of error due to node version 8, change the runtime to nodejs12.x in amplify-react-cloudformation-template.yaml

Open amplify console `$ amplify console`

Upload project to S3 `$ amplify add hosting`

- Choose between DEV (http) or PROD (cloudfront and https)
- Set bucket name
- Complete accordingly
- Upload changes to cloud `$ amplify push`

Get status of current amplify project `$ amplify status`

## React

Create new project `npx create-react-app [project]` or with yarn `yarn create react-app [project]`

Install these dependencies `npm i aws-amplify aws-amplify-react`




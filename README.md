# miso-api

## Local dev

Install dependencies and serverless:
```
npm i
npm i -g serverless
```

Local query using `query.json`:
```
serverless invoke local -f graphql -p query.json
```

## Deploy

Configure AWS credentials for an IAM user with the following permissions:
* TODO

If you use a non-default profile, prefix the command with `AWS_PROFILE=your-profile`.

Deploy the API:
```
serverless deploy
```

Deploy a custom domain for API gateway:
```
serverless create_domain
```

## Links
* [Apollo Studio Explorer](https://studio.apollographql.com/sandbox/explorer)
* [Apollo: Deploying with AWS Lambda](https://www.apollographql.com/docs/apollo-server/deployment/lambda/)
* [How to set up a custom domain name for Lambda & API Gateway with Serverless](https://www.serverless.com/blog/serverless-api-gateway-domain/)

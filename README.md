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

Deploy:
```
serverless deploy
```

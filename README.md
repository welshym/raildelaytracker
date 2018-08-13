# nationalrailtracker application

**Tracks national rail train services.**

## Prerequisites
You must have node and npm installed, then install the webpack development server:

```bash
$ npm install webpack-dev-server -g
```

Then install the local dependencies

```bash
$ npm install
```

Requires a local dynamoDB instance up and running on port 8000 with a "delays" table. Local version run using ddb - defined in bash profile:

alias ddb="cd ~/Personal/AWS/Externals/dynamodb_local_latest && java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb"

## Dev build + livereload webserver
```bash
$ npm start
```

## Dev build
```bash
$ npm run build
```

## Prod build
```bash
$ npm run build-prod
```

## Linting

Stage 0 features of JavaScript.

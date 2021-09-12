# Cyclic - Koa Hello World

This is a basic starter Koa app

## Local Quick Start

If you want to setup your dev account and deploy with `git push`

- Fork this repo (or deploy above)
- Clone to your local
- Install dependencies `npm install`
- Run locally `npm serve`
- Make requests
  - Browser: `http://localhost:3000/some/path?q=query+one&q=second+query&single=value`
  - Command line: `curl -i -XGET "http://localhost:3000/cmd/line-curl"`
- Deploy on Cyclic
  - https://app.cyclic.sh/api/app/deploy/cyclic-software/koa-hello-world

## Cyclic Runtime

- Cyclic hosts your app on serverless infrastructure. That means there is no guarantee of memory or file system persistence between requests.
- The runtime expects a nodejs entry point defined as:
  - package.json "main" field defines the entry point file (if missing uses index.js)
  - Entry point starts a server on `process.env.PORT`

## Say Hi

Ask a question or give us a shout out:

- 💌 hello@cyclic.sh
- 🐣 https://twitter.com/cyclicsoftware

# Develop, Test, and Deploy Serverless Functions with Netlify

## Talk Recordings

- You can view this talk at <https://www.swyx.io/talks> ([direct link](https://www.swyx.io/speaking/netlify-functions-lunchnlearn))

## JAMstack 😍 Serverless

- Dramatically reduce the cost of creating APIs
- Your APIs don't _have_ to be serverless, you can also create a stateful microservice

![https://cdn-images-1.medium.com/max/1600/1*uD1IkSE1cwF1Yr_njKu9qA.png](https://cdn-images-1.medium.com/max/1600/1*uD1IkSE1cwF1Yr_njKu9qA.png)

## Why Serverless

- Pay per execution pricing
- Never pay for idle servers
- Auto scales for you
- **Event driven workflows**
- Leverage third party services

![https://cdn-images-1.medium.com/max/1200/1*R65rmc0x432_s9EmAbGlOA.png](https://cdn-images-1.medium.com/max/1200/1*R65rmc0x432_s9EmAbGlOA.png)

![https://cdn-images-1.medium.com/max/1600/1*TdRFV0LAG7TG3US2YJMALA.jpeg](https://cdn-images-1.medium.com/max/1600/1*TdRFV0LAG7TG3US2YJMALA.jpeg)

## What can Functions do

Very basic Functions Tutorial: https://functions-playground.netlify.com/

Featured Use Cases

- [Hiding Tokens](https://community.netlify.com/t/handling-api-keys-in-a-proxy-redirect/857/2)
- [Post Scheduler](https://github.com/serverless/post-scheduler)
- [Oauth Flows](github.com/netlify-labs/oauth-example)
- [URL shortener](https://github.com/kentcdodds/netlify-shortener) - [Livestream with Airtable](https://www.youtube.com/watch?v=Xs-qvWqoi2U)

Scheduled Function Execution

- https://cron-job.org/en/
- IFTTT
- Zapier
- https://cronless.com/
- https://www.setcronjob.com/
- https://cronless.com/
- https://cronnomy.com/
- etc.

Authenticated Functions

- Netlify Identity + Netlify Functions
- [Livestream: How to use Gatsby + Netlify Identity + Netlify Functions](https://www.youtube.com/watch?v=vrSoLMmQ46k)
- https://github.com/sw-yx/jamstack-hackathon-starter
- https://identity.netlify.com/ ([react version](https://react-netlify-identity-widget.netlify.com))
- [JWT](https://jwt.io/) vs Sessions vs [Paseto](https://github.com/paragonie/paseto)
- Okta
- Auth0

Open source list of Function Examples

- <https://functions.netlify.com/examples>
- <https://github.com/netlify/functions>

Learn More

- Netlify Functions Workshop <https://github.com/DavidWells/netlify-functions-workshop>
- [Livestream: Building async serverless business logic for your GraphQL API with Hasura and @Netlify](https://www.youtube.com/watch?v=Sz9M5vTAAUk)
- Flaviocopes: [Netlify Lambda Functions Tutorial](https://flaviocopes.com/netlify-functions/)
- raymondcamden Camden: [Adding Serverless Functions to Your Netlify Static Site ](https://www.raymondcamden.com/2019/01/08/adding-serverless-functions-to-your-netlify-static-site)

Pricing:

- [details](https://www.netlify.com/pricing/?utm_source=conf&utm_medium=smashingconf&utm_campaign=devex)
- Free: 125k
- Level 1: 2 million

## Netlify Functions:Create

- Token-Hider
- GraphQL API
- Fauna GraphQL

more templates here: https://github.com/netlify/netlify-dev-plugin/tree/master/src/functions-templates/js/

## Netlify Dev

- <https://github.com/netlify/netlify-dev-plugin/>
- The difference between [Netlify-Lambda vs Netlify Dev](https://github.com/netlify/netlify-lambda/blob/master/README.md#netlify-lambda)
- https://www.netlify.com/products/dev/

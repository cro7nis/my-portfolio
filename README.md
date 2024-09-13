# My Portoflio

A portfolio website written entirely in HTML and CSS. It is designed to be fast and easy to maintain

Currently hosted on Akash in the following link [fbjao4n16hen791jih8lptdk1k.ingress.d3akash.cloud](fbjao4n16hen791jih8lptdk1k.ingress.d3akash.cloud)

## Deploy on Akash guide <img src="./assets/akash-logo.png" alt="drawing" width=20 height=20/>


https://github.com/user-attachments/assets/6b05b8d7-4a0b-4caa-ae04-070b7055d193



- Create and fund a Keplr or Leap wallet
  - [Keplr wallet](https://akash.network/docs/getting-started/token-and-wallets/#keplr-wallet)
  - [Leap wallet](https://akash.network/docs/getting-started/token-and-wallets/#leap-cosmos-wallet)
- Visit https://deploy.cloudmos.io/
- Connect your wallet
  - You need to have at least 0.5 AKT in your wallet
- Press the deploy button
- Select "Build your template"
- (Optional) Name your deployment
- Select YAML and paste the [deploy.yaml](deploy.yaml) contents
- Press "Create Deployment"
- Accept wallet transaction
- Review bids and select provider
- Accept provider transaction
- Go to LEASES and press the URI
- Check the [Akash docs](https://akash.network/docs/deployments/cloudmos-deploy/) if you have and questions
- Done

<br />

## Run this site locally using Docker

Note that Docker must already be installed to your local machine. ([Docker install instructions](https://docs.docker.com/get-docker/)).

>1. docker build -t portfolio .
>1. docker run --name portfolio_container -d -p 8080:80 portfolio

The website is now reachable at http://localhost:8080 in your browser.

<br />

# Desktop Page Layouts

- About
- Portfolio
- Blog

<br />



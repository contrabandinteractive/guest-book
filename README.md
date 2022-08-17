
Sonata
===========

Sonata takes the business model of music streaming services such as Spotify and turns it on its head! Listeners will pay artists in NEAR tokens. Play counts will be tracked by the blockchain. And songs will be stored on decentralized networks!


Quick Start
===========

To run this project locally:

1. Prerequisites: Make sure you have Node.js ≥ 12 installed (https://nodejs.org), then use it to install [yarn]: `npm install --global yarn` (or just `npm i -g yarn`)
2. Run the local development server: `yarn && yarn dev` (see `package.json` for a
   full list of `scripts` you can run with `yarn`)

Now you'll have a local development environment backed by the NEAR TestNet! Running `yarn dev` will tell you the URL you can visit in your browser to see the app.

Under the Hood
===========

Sonata uses the **IPFS HTTP Client Library** to upload song files to IPFS. This project previously used Crust, but now uses IPFS exclusively. More info here: https://github.com/ipfs/js-ipfs/tree/master/packages/ipfs-http-client#readme

## Permanent File Storage with Bundlr Network and Next.js Route Handlers

This is a reference architecture showing how to upload files and images to Arweave permanent storage with Bundlr Network and Next.js

### Prerequisites

This project assumes you have an EVM compatible wallet with "Matic" tokens.

If you do not have Matic, you can choose any of the [supported tokens here](https://docs.bundlr.network/overview/supported-tokens) instead, and swap out the references to `matic` in the route handlers with the token of your choice.

### Project setup

For this project to run, you need to have an environment variable set as `BNDLR_KEY` to be accessed as `process.env.BNDLR_KEY`. You can do this many ways, one being having a `.env.local` file (see `.example.env.local`). __BE SURE TO NEVER SEND ANY PRIVATE KEYS TO ANY CODE REPOSITORIES, IT'S BEST TO SET THEM LOCALLY IN YOUR SESSION__.

## Running the app

1. Clone the repo

```sh
git clone git@github.com:dabit3/nextjs-route-handlers-permanent-file-storage.git
```

2. Install depdenencies

```sh
npm install

# or yarn, pnpm, etc...
```

3. Run the app

```sh
npm start
```

> Be sure you have your environment variable set as referenced above.
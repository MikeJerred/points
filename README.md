# Points

## Installation

Install dependencies:

```bash
npm install
```

Fill out the environment variables in `points-api-server` according to `.env.example`.

## Usage

Start the API server:

```bash
cd points-api-server
npm start
```

Start the frontend:

```bash
cd points-demo
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

A new campaign can be created with the button on the left. This will generate an API key for you and store it in your browser's `localStorage`.
Points can then be distributed & viewed using the forms in the middle of the page.

## Project Structure

### points-api-server
A REST API that can register clients and allow them to make updates to their points data.

### points-demo
A web app utility that allows people to view & insert points for an address.

### points-sdk
An `npm` package that provides a client for interacting with the REST API. The package is deployed [here](https://www.npmjs.com/package/@mikejerred/points-sdk).

## Docs

View documentation [here](https://mikes-organization-20.gitbook.io/absinthe-demo).

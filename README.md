# apod-api
A TypeScript port of [nasa/apod-api](https://github.com/nasa/apod-api) made for Deno.

## Quick Start

### Running locally

Clone this repo and:

```
deno run --allow-net .\server.ts
```

To use the API, go to `http://localhost:8000/`

### Deployment

Using [Deno Deploy](https://deno.com/deploy), you can deploy the API for free.

Create a new project, then set the deploy URL to:

```
https://github.com/johfee/deno_apod/blob/main/server.ts
``` 

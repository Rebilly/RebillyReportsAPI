# Rebilly Experimental Reports REST API Specification
[![Build Status](https://travis-ci.org/Rebilly/RebillyReportsAPI.svg?branch=master)](https://travis-ci.org/Rebilly/RebillyReportsAPI)

## Installing

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and `cd`
    + Run `npm install`

## Usage

- Run `npm start`
- Look full spec:
    + JSON [http://localhost:3000/swagger.json](http://localhost:3000/swagger.json)
    + YAML [http://localhost:3000/swagger.yaml](http://localhost:3000/swagger.yaml)  (may not be fully functional)
- Browse Swagger UI:
    + JSON [http://localhost:3000/swagger-ui/?url=http://localhost:3000/swagger.json](http://localhost:3000/?url=http://localhost:3000/swagger.json)
    + YAML [http://localhost:3000/swagger-ui/?url=http://localhost:3000/swagger.yaml](http://localhost:3000/?url=http://localhost:3000/swagger.yaml)  (may not be fully functional)
- Browse ReDoc: [http://localhost:3000/](http://localhost:3000/)
- Preview spec version for branch `<branch>` (**doesn't work locally**): [http://rebilly.github.io/RebillyAPI/preview/&lt;branch&gt;](http://rebilly.github.io/RebillyAPI/preview/branch)
**!** Branch preview is not available until Travis CI deploys it
- Import spec by URL in editor, online or local (you should uncheck "Use CORS proxy" in the model)

## Tests

Run command from project root directory:

```bash
npm test
```

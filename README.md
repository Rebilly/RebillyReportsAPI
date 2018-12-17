# Rebilly Experimental Reports OpenAPI Specification
[![Build Status](https://travis-ci.org/Rebilly/RebillyReportsAPI.svg?branch=master)](https://travis-ci.org/Rebilly/RebillyReportsAPI)

## Links

- [Reference Documentation (ReDoc)](https://rebilly.github.io/RebillyReportsAPI/)
- OpenAPI Raw Files: [JSON](https://rebilly.github.io/RebillyReportsAPI/openapi.json) [YAML](https://rebilly.github.io/RebillyReportsAPI/openapi.yaml)

**Warning:** All above links are updated only after Travis CI finishes deployment

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and run `npm install` in the repo root

### Usage

#### `npm start`
Starts the development server.

#### `npm run build`
Bundles the spec and prepares web_deploy folder with static assets.

#### `npm test`
Validates the spec.

#### `npm run gh-pages`
Deploys docs to GitHub Pages. You don't need to run it manually if you have Travis CI configured.

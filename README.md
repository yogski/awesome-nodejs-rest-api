# Node.js REST API Reference
So, you want to create REST API using Node.js? This is the reference you need to build the right recipe.

## Table of Contents
- [Frameworks](README.md)
- Libraries
  - `.env` variable
  - CORS
  - Auth
  - Router
  - Database Driver
  - ORM
  - SQL Migration
  - Request validation
  - Request throttling
  - File upload
  - Multimedia file
  - HTTP request
  - Middleware
  - Logging
  - Testing
  - Documentation
  - Process Manager
- Other Libraries
  - Template engine
  - Websocket
  - Email
- Recipes

## Framework

Framework is the backbone of REST API.
| Name | Description | Paradigm | Documentation | Github |
| --- | ------ | ----- | ---- | ----|
| Express | Most well-known Node.js framework (50K+ github stars) that it has its own stack name.  | Unopinionated | [docs](https://expressjs.com/en/starter/installing.html) | [Github Repo](https://github.com/expressjs/express) |
| Koa | Developed by Express.js creator. Lightweight and middleware-centric. Perhaps the most unopinionated Node.js framework. [Middlewares available](https://github.com/orgs/koajs/repositories) for various use cases. | Unopinionated | [docs](https://koajs.com/)| [Github Repo](https://github.com/koajs/koa) |
| Fastify | Fast and low overhead web framework, for Node.js. It's slim in size with many [plugins](https://www.fastify.io/ecosystem/) available. Similar approach to Koa.js, although bit more opinionated.| Moderate | [docs](https://www.fastify.io/docs/latest/)| [Github Repo](https://github.com/fastify/fastify) |
| Nest | Text | [docs]()| [Github Repo](https://github.com/balderdashy/sails) |
| Meteor | Text | [docs]()| [Github Repo](https://github.com/balderdashy/sails) |
| Hapi | Text | [docs]()| [Github Repo](https://github.com/balderdashy/sails) |
| Sails | A complete MVC Node.js framework. On par with Laravel, Ruby on Rails, and Django. 20K+ stars on Github | [sailsjs.com](https://sailsjs.com/documentation/reference) | [Github Repo](https://github.com/balderdashy/sails) |
| Adonis | Text | [docs]()| [Github Repo](https://github.com/balderdashy/sails) |
| Restify | Text | [docs]()| [Github Repo](https://github.com/balderdashy/sails) |
| Feathers | Text | [docs]()| [Github Repo](https://github.com/balderdashy/sails) |

The following table shows built-in features included in each framework.

✅ = fully available 🟡 = partially available

PUT TABLE HERE

## Libraries for REST API
### `.env` variable
- [dotenv]()
- [env-cmd]()
- [cross-env]()
### CORS
- [cors]()
### Auth
- [firebase]() : 
- 
### Router
- [koa-router](https://www.npmjs.com/package/koa-router) : router middleware for Koa framework
- 
### Database Driver
- [mongodb](https://www.npmjs.com/package/mongodb) : The official MongoDB driver for Node.js
- [pg](https://www.npmjs.com/package/pg) : Most popular PostgreSQL client for Node.js. Pure JavaScript and optional native libpq bindings.
- [pg-promise](https://www.npmjs.com/package/pg-promise) : Promise-based PostgreSQL client for Node.js, built on top of node-postgres
- [redis](https://www.npmjs.com/package/redis) : A high performance Node.js Redis client.
### ORM
- [mongoose](https://www.npmjs.com/package/mongoose) : A MongoDB object modeling tool designed to work in an asynchronous environment. Mongoose supports both promises and callbacks.
- [sequelize](https://www.npmjs.com/package/sequelize) : A promise-based Node.js ORM tool for Postgres, MySQL, MariaDB, SQLite and Microsoft SQL Server. 
- [waterline](https://www.npmjs.com/package/waterline) : Next-generation storage and retrieval engine, and the default ORM used in the Sails framework. Supports MySQL, MongoDB, neDB, and PostgreSQL.
### SQL Migration
### Request validation
### Rate Limit
- [fastify-rate-limit](https://github.com/fastify/fastify-rate-limit) : rate limit middleware for Fastify Framework
- [koa-ratelimit](https://github.com/koajs/ratelimit) : rate limit middleware for Koa framework.
### Serve static files
- [koa-static](https://www.npmjs.com/package/koa-static) : Static file serving middleware for Koa framework.
### File upload
### Multimedia file
### HTTP client
REST API receives request and send response through HTTP/HTTPS protocol. But what if the server needs to talk to other services while processing request? HTTP client is the answer. Here is the list of well-known packages.
- [axios](https://www.npmjs.com/package/axios) : Promise based HTTP client for the browser and node.js
- [bent](https://www.npmjs.com/package/bent) : Functional HTTP client for Node.js and Browsers with async/await. Incredibly small browser version built on fetch with no external dependencies or polyfills.
- [node-fetch](https://www.npmjs.com/package/node-fetch) : A light-weight module that brings window.fetch to Node.js
- [superagent](https://www.npmjs.com/package/superagent) : Small progressive client-side HTTP request library, and Node.js module with the same API, supporting many high-level HTTP client features.
### Middleware
### Logging
- [pino](https://www.npmjs.com/package/pino) : Very low overhead Node.js logger.
### Testing
- [jest](https://www.npmjs.com/package/jest) : 🃏 Delightful JavaScript Testing, for all-round app types
- [mocha](https://www.npmjs.com/package/mocha) : ☕️ Simple, flexible, fun JavaScript test framework for Node.js & The Browser ☕️
- [supertest](https://www.npmjs.com/package/supertest) : HTTP assertions made easy via superagent.
- [ava](https://www.npmjs.com/package/ava) : Test runner for Node.js with a concise API, detailed error output, embrace of new language features and process isolation that lets you develop with confidence 🚀
### Documentation
REST API is useless when no one knows how to access it. That's where documentation library comes in. It usually requires REST API definitions, then magically convert it to accessible HTML page. 
- [@nestjs/swagger](https://www.npmjs.com/package/@nestjs/swagger) : OpenAPI (Swagger) module for Nest framework
- [apidoc](https://www.npmjs.com/package/apidoc) : Generate a documentation from API descriptions in your source code. See [live demo](https://apidocjs.com/example/).
- [redoc](https://www.npmjs.com/package/redoc) : React-based documentation generator compliant with OpenAPI. See [live demo](http://redocly.github.io/redoc/?).
- [swagger-ui-express](https://www.npmjs.com/package/swagger-ui-express) : Generate swagger-ui API docs in Express framework, based on a swagger.json file.
- [typedoc](https://www.npmjs.com/package/typedoc) : Documentation generator for TypeScript projects as CLI or npm package.
### Process Manager
- [forever](https://www.npmjs.com/package/forever) : A simple CLI tool for ensuring that a given script runs continuously (i.e. forever).
- [nodemon](https://www.npmjs.com/package/nodemon) : A tool that helps develop node.js based applications by automatically restarting the node application when file changes in the directory are detected.
- [pm2](https://www.npmjs.com/package/pm2) : Production process manager for Node.js applications with a built-in load balancer. It allows you to keep applications alive forever, to reload them without downtime and to facilitate common system admin tasks.
- [supervisor](https://www.npmjs.com/package/supervisor) : A little supervisor script for nodejs. It runs your program and watches for code changes without worrying about memory leaks and making sure you clean up all the inter-module references.

## Other Libraries
### Template Engine
Template engine is not essential since most REST APIs return JSON data. But in any case it is needed, here is the list:
- [](https://www.npmjs.com/package/)
### Email
### Websocket
### Encryption 
## Recipes
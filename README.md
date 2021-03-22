# Rocket Seat Ignite - Repo Manager

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Endpoints](#endpoints)
- [Resources](#resources)

## About <a name = "about"></a>

A repo management backend made with NodeJS and Express.

## Getting Started <a name = "getting_started"></a>

### Prerequisites

- `node >= 12.0.0`
- `yarn >= 1.22.0`

### Installing

1. Clone this repo locally and install the required packages:

```bash
$ git clone https://github.com/librity/ignite_repo_manager.git
$ cd ignite_repo_manager
$ yarn install
```

2. Start a dev server:

```bash
$ yarn dev
```

3. Import the Insomnia workspace from `./insomnia/workspace.json`
   and run some requests.

### Testing

Run tests with jest:

```bash
$ yarn test
```

## Endpoints <a name = "endpoints"></a>

`Repositories`

- `GET` http://localhost:3333/repositories
- `POST` http://localhost:3333/repositories
- `PUT` http://localhost:3333/repositories/:id
- `DELETE` http://localhost:3333/repositories/:id
- `POST` http://localhost:3333/repositories/:id/like

## Resources <a name = "resources"></a>

- https://rapidapi.com/blog/put-vs-patch/
- https://github.com/uuidjs/uuid#quickstart
- https://stackoverflow.com/questions/18875292/passing-variables-to-the-next-middleware-using-next-in-express-js
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
- https://en.wikipedia.org/wiki/List_of_HTTP_status_codes#2xx_success
- https://stackoverflow.com/questions/10865025/merge-flatten-an-array-of-arrays
- https://www.w3schools.com/howto/howto_js_remove_property_object.asp

# Working With Databases in Node.js

A page hit counter service which saves data to a MySQL database using the Sequelize ORM.

This is an example project for the purposes of demonstration only. It is not recommended for production use!

## Requirements

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Installation Steps

1. Clone repo
2. Run `docker-compose build`
3. Run `docker-compose up` to launch MongoDB, NGINX, and Node.js development containers.
4. Once started, [load any page](http://localhost:8888/) to test four methods of adding a hit counter:
   * <http://localhost:8888/page-svg.html>
   * <http://localhost:8888/page-jswrite.html>
   * <http://localhost:8888/page-jsdefer.html>
   * <http://localhost:8888/page-jsajax.html>

*If any Docker command fails, run `docker system prune` to remove all stopped containers and dangling images to ensure there are no conflicts with other versions of the page hit counter.*

*If you get an `address already in use` error, the chances are that you already have a MongoDB service running on the port in question. Try stopping the service and re-running the `docker` command.*

## License

SitePoint's code archives and code examples are licensed under the MIT license.

Copyright © 2020 SitePoint

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

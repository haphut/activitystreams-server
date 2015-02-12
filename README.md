activitystreams-server
======================

Reference implementation of an ActivityStreams 2.0 server

We use Grunt, npm, and mongodb.  Mongo needs to be running for ActivityStreams 2.0 server to work.

## Development setup

Run in one terminal:
```sh
mkdir 'mongodata' && mongod --dbpath './mongodata' --port 27017
```

And in another:
```sh
npm install
npm install -g grunt jasmine-node
npm test
npm start
```

The server will be available at `http://localhost:8080/`.

Or see it running live on Bluemix at http://activitystreams-server.mybluemix.net/.

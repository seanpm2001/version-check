# 4minitz update check

A small rest service that returns the current stable 4minitz version.

## Installation

Install dependencies with `npm` or `yarn`

    $ yarn install

and start the service with

    $ yarn start

to connect to the end2end mongodb server or set the `MONGO_URL` env variable to point to another installation

    $ MONGO_URL=mongodb://user:password@server:port/database yarn start


## Usage
You may manually check the service like so:

    $ curl localhost:8080/updatecheck/MyClientsUniqueID/0.10.0

This should return the current officially released master version like so:
 
    {"tag":"0.11.0"}


## License

This software is licensed under the terms of the MIT License.

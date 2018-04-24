Node.js Transfers Dashboard implementation for testing purposes

##### Sample config.js

Requires config.js to be added to project root. Sample format/contents:

```

var config = {};

///port -> what port the application should listen on
config.port = 3200;

///config.api settings -> configures the commitment api accessed by the application
config.api_bearer_token = "THIS_IS_THE_COMMITMENTS_API_BEARER_TOKEN";
config.api_hostname = "127.0.0.1";
config.api_port = 44380;

module.exports = config;

```


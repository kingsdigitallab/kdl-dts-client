# KDL Distributed Text Services Client API

Library of helper functions to send request to a DTS API. Supports dynamic (kdl-dts-server) and static (kdl-dts-static) APIs.

The functions can be called from the browser or from the server side (node).

# Usage

## Server

`npm i git@github.com:kingsdigitallab/kdl-dts-client.git`

```javascript
const dtsutils = require("kdl-dts-client");

dtsutils.fetchDTS(...)

dtsutils.getDTSUrl(...)

dtsutils.getFormatFromRequest(...)
```

## Browser


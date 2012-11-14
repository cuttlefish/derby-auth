# Derby.js Authentication

Provides authentication middleware for use in your Derby projects. Currently supports Facebook, LinkedIn, and Github integration; but more integration is on the way. Please do scratch your own itch with other Everyauth implementations and provide pull requests. See [Everyauth's sample code](https://github.com/bnoguchi/everyauth/tree/express3/example) for details. For usage details, see [lefnire/derby-examples/authentication](https://github.com/lefnire/derby-examples/blob/master/authentication); specifically, [server/index.js](https://github.com/lefnire/derby-examples/blob/master/authentication/src/server/index.coffee).

Note: currently uses [Everyauth](https://github.com/bnoguchi/everyauth/tree/express3), which is incompatible with password-authentication (see [this issue](https://groups.google.com/d/msg/derbyjs/JuUqUNd9Rls/MgHOXuYwDMgJ)); therefore, derby-auth will likely be moving to Passport in the near future.
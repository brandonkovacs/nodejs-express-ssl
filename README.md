# nodejs-express-ssl
Boiler Plate Template for NodeJS &amp; Express Apps w/ SSL Support

Use this as a starting point for your NodeJS Express Apps.

**Requirements**
1. SSL Certificate ([LetsEncrypt](http://letsencrypt.com/))

**Installation**
1. ``git clone https://github.com/brandonkovacs/nodejs-express-ssl``
2. ``npm install``

**Usage**
1. Set Environment Variables (See Below)
2) ``node index.js``

**Environment Variables**
* ``export PORT=8080``
* ``export SSL_KEY=/path/to/privkey.pem``
* ``export SSL_CERT=/path/to/certificate.pem``
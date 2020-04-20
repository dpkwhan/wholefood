## Installation
Under the root directory of the project, run the following:

```bash
npm install
```

## Amazon Credentials
A file named ``credentials.js`` in the project root directory is not committed. It should have the following contents:

```javascript
module.exports = {
  email: 'your email to login Amazon',
  password: 'your password to login Amazon',
};
```

## Run the script
```bash
node app.js
```

## A few nuances
- Sometimes clicking the ``Continue`` button on the substitute preference selection does not work. In this case, you can manually click the ``Continue`` button and the script will continue.
- The element id for ``Checkout Whole Foods Market Cart`` might be different in your case. Update it with the correct id on line 52 in ``app.js``.
- The system bell will ring when a delivery window is available.

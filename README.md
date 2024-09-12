# @beyond-js/log

A simple logging utility for BeyondJs applications.

## Installation

```bash
npm install @beyond-js/log
```

## Usage

This package provides a simple logging function that can be used to log messages and errors in your Beyond.js
applications.

```javascript
const log = require('@beyond-js/log');

// Log a simple message
log('Hello, world!');

// Log a message with an error
try {
	// Some code that might throw an error
} catch (error) {
	log('An error occurred', error);
}
```

## API

### `log(message, [error])`

-   `message` (string): The message to log.
-   `error` (Error, optional): An error object to log along with the message.

This function logs the provided message to the console. If an error object is provided, it will also log the error stack
trace.

## License

MIT © [[BeyondJS](https://beyondjs)]

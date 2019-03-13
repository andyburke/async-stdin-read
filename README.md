# async-stdin-read

A very simple asynchronous stdin reader.

## Installation

```bash
npm install -P async-stdin-read
```

## Usage

```js
const read_stdin = require( 'async-stdin-read' );

async function some_async_function() {
    const input = await read_stdin();
    console.log( "here is what we read from stdin:" );
    console.log( input );
}
```

## License

The MIT License (MIT)

## Thanks

This module was developed at Oportun, Inc.
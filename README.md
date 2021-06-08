# ASCII helper

## Features

ASCII helper for encoding and decoding strings:

- Encode string to ASCII hex string
- Decode ASCII hex string to string

## Installation

```bash
npm install ascii-helper
```

## Usage

```JavaScript
import { decode, encode } from 'ascii-helper';

// 537472696e6720746f20656e636f6465
encode('String to encode');

// String to decode
decode('537472696e6720746f206465636f6465');

```

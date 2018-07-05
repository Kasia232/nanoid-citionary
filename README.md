# nanoid-dictionary
Predefined character sets to use with [nanoid](https://github.com/ai/nanoid)

## Usage

Install nanoid and dictionary

`npm i nanoid nanoid-dictionary`

Require a generator and pass a string from the dictionary

```javascript
const generate = require('nanoid/generate');
const dictionary = require('nanoid-dictionary');

const safeFileName = generate(dictionary.filename, 10);
```

##Character sets

###`filename`

Provides a cross-platform character set for safe filename generation.
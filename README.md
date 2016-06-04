# text-encoding.d.ts

An Typescript definition for [text-encoding](https://www.npmjs.com/package/text-encoding).

### Installation

Using [typings](https://github.com/typings/typings):

```bash
typings install github:nozzlegear/text-encoding.d.ts --save
```

### Usage

```js
import * as encoding from "text-encoding";

const array: Uint8Array = new encoding.TextEncoder().encode(string);
const string: String = new encoding.TextDecoder("utf-8").decode(array);
```

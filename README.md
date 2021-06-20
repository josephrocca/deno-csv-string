# deno-csv-string

A version of npm's csv-string package that works in the browser and in Deno. It's just a browserified v3.2.0 of this: https://github.com/Inist-CNRS/node-csv-string

Here's the README of v3.2.0: https://github.com/Inist-CNRS/node-csv-string/blob/e0cb5fbffee2ee48a34b36401f6cd3fc6e2e2247/README.md

Also, it's >6k lines 😳 probably due to all the node.js polyfills. It suits my purposes but might not make sense for yours, so it's probably worth you seeing if there are other libs that suit you better.

```js
import CSV from "https://deno.land/x/deno_csv_string@v0.0.2/mod.js";
const arr = CSV.parse('a,b,c\na,b,c', ','); // second argument is the separator. CSV.parse returns an array or rows
const str = CSV.stringify(arr);
```


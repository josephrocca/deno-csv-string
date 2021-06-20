# deno-csv-string

A version of npm's csv-string package that works in the browser and in Deno. It's just a browserified v3.2.0 of this: https://github.com/Inist-CNRS/node-csv-string

Here's the README of v3.2.0: https://github.com/Inist-CNRS/node-csv-string/blob/e0cb5fbffee2ee48a34b36401f6cd3fc6e2e2247/README.md


```js
import CSV from "https://deno.land/x/deno_csv_string@v0.0.2/mod.js";
const arr = CSV.parse('a,b,c\na,b,c');
const str = CSV.stringify(arr);
```


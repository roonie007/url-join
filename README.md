# url-join

A simple port of the NodeJS module [url-join](https://github.com/jfromaniello/url-join) to Deno with typescript

Join all arguments together and normalize the resulting url.

## Usage

```javascript
import { urlJoin } from "https://deno.land/x/url-join@master/join.ts";

const fullUrl = urlJoin("http://www.google.com", "a", "/b/cd", "?foo=123");

console.log(fullUrl);
// http://www.google.com/a/b/cd?foo=123
```

## License

MIT

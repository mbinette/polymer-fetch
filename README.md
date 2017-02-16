`polymer-fetch` is a simple html wrapper for polymerlabs/promise-polyfill and github/fetch. 

```
bower install --save mbinette/polymer-fetch
```

Include it at the top of each Polymer element that needs fetch to make sure it is available as a global.

```
<link rel="import" href="/bower_components/polymer-fetch/polymer-fetch.html">
```

There is no element. Call `fetch` from any code within the file.

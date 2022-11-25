# cors-now 

> reverse proxy with CORS headers.


## Usage:

__Just do a `fetch` on the below:__

```
https://4rr0w.my.id/<url>
```

__Example:__

```js
// The XKCD URL below doesn't allow CORS.
fetch('https://4rr0w.my.id/http://xkcd.com/info.0.json')
.then(console.log)
.catch(console.error)
```

P.S: Make sure you give the absolute URL, or else you will see an error like:

```js
{
  "error": "Only absolute urls are supported"
}
```

## WHY?

* For reverse proxies.

* For crawlers, spiders and what not! 

## License

MIT © [4RR0W](https://4rr0w.my.id)

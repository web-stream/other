
# [other.webstream.dev]()


## [Highland.js](https://caolan.github.io/highland/)


[Node.js streams 101 - slides.com/michalczukm/nodejs-streams-101#/9/1](https://slides.com/michalczukm/nodejs-streams-101#/9/1)

[caolan/highland: High-level streams library for Node.js and the browser](https://github.com/caolan/highland)

With Highland, we really can have one language to work with both synchronous and asynchronous data, whether it's from a Node Stream, an EventEmitter, a callback or an Array. You can even wrap ES6 or jQuery promises:

```js
var foo = _($.getJSON('/api/foo'));
```

Piping in data from Node Streams

```js
function isBlogPost(doc) {
    return doc.type === 'blogpost';
}

var output = fs.createWriteStream('output');
var docs = new db.createReadStream();

// Wrap a node stream and pipe to file
_(docs).filter(isBlogpost).pipe(output);

// or, pipe in a node stream directly:
// useful if you need a TransformStream-like object for external APIs.
var transformStream = _.pipeline(_.filter(isBlogpost));
docs.pipe(transformStream).pipe(output);
```




[Rehydration.md](Rehydration.md)





## About Webstream

+  Website about Webstreaming on github - [web-stream/www](https://github.com/web-stream/www)

## About Tom Sapletta

+ [Contact on linkedin](https://www.linkedin.com/in/tom-sapletta-com/)
+ [Tom Sapletta Blog - Embedded System Software & Hardware Developer](https://tom.sapletta.com/)
+ [Softreck Company - Leadership Through Software Development](https://softreck.com/)


## Devops supported by [Api Foundation](https://www.apifoundation.com)

+ [.apicra](https://www.apicra.com) - bash scripts to prepare environment
+ [.apifunc](https://www.apifunc.com) - funkcje, implementacja apiunit
+ [.apiunit](https://www.apiunit.com) - metadane potrzebne do stworzenia aplikacji
+ [.apibuild](https://www.apibuild.com) - budowanie plaikacji, deployment
+ [.apiterminal](https://www.apiterminal.com) - devops terminal by web


## Substantively supported by: 

+ [SaaS is King .com](https://www.saasisking.com/)
+ [hyper Modularity .com](https://www.hypermodularity.com/)


## Sponsored by:

+ [Softreck - Leadership Through Software Development](https://softreck.com/)



---
+ [edit](https://github.com/web-stream/other/edit/main/README.md)
```
https://github.com/web-stream/other.git
```

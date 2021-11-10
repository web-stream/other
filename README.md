
# [other.webstream.dev](https://other.webstream.dev/)



Static site generators

We love static sites and have plugins are secure, simple and reliable. 
They withstand high traffic and require little upkeep.


## Middleman

The static site generator [Middleman](https://middlemanapp.com/) is a command-line tool that uses Ruby and Ruby Gems. It’s one of the most-used static tools for large companies. This plugin will help you manage your Contentful content
Static site generators

We love static sites and have plugins to support four of our favorites. Static sites are secure, simple and reliable. They withstand high traffic and require little upkeep.
Middleman

The static site generator Middleman is a command-line tool that uses Ruby and Ruby Gems. It’s one of the most-used static tools for large companies. This plugin will help you manage your Contentful content

View on GitHub

View examples
Jekyll

Jekyll is a Ruby based static site generator. It’s simple and blog-aware, a great option for small projects and personal sites. This plugin pulls content from Contentful.

View on GitHub

View examples
Gatsby

Gatsby is a static site generator based on React. Gatsby and Contentful work together well—you can install the Gatsby app, which lets you see updates. Gatsby also has a package that enables Contentful to be a data source for a Gatsby project.

View on GitHub
Metalsmith

Metalsmith is a JavaScript based static-site generator, and this plugin fetches and renders data from Contentful.

View on GitHub

View examples
Tutorials
Automated rebuild and deployment with CircleCI and Webhooks

This tutorial shows you how to setup and automatically deploy static sites using Jekyll or Middleman with CircleCI.
Other tools

While the below tools are not officially supported by our static site CMS, they can help extend the functionality of Contentful
Roots

Roots is a JavaScript based static site generator. It doesn’t have an extensive ecosystem, but it’s great if you’re using Node.js-based front-end tools. This plugin helps you manage content from Contentful.

View on GitHub
Textalk

Textalk is a simple static site generator, a command-line interface (CLI) tool to generate a site from templates and data in a Contentful space.

View on GitHub
AWS Lambda

Here’s an example static site using Amazon web services (AWS) Lambda.






[Static site generators | Contentful](https://www.contentful.com/developers/docs/tools/staticsitegenerators/)

## Middleman

The static site generator [Middleman](https://middlemanapp.com/) is a command-line tool that uses Ruby and Ruby Gems. It’s one of the most-used static tools for large companies. This plugin will help you manage your Contentful content

[View on GitHub](https://github.com/contentful/contentful_middleman)

[View examples](https://github.com/contentful/contentful_middleman_examples)

## Jekyll

[Jekyll](https://jekyllrb.com/) is a Ruby based static site generator. It’s simple and blog-aware, a great option for small projects and personal sites. This plugin pulls content from Contentful.

[View on GitHub](https://github.com/contentful/jekyll-contentful-data-import)

[View examples](https://github.com/contentful/contentful_jekyll_examples)

## Gatsby

[Gatsby](https://www.gatsbyjs.org/) is a static site generator based on React. Gatsby and Contentful work together well—you can install the Gatsby app, which lets you see updates. Gatsby also has a package that enables Contentful to be a data source for a Gatsby project.

[View on GitHub](https://github.com/gatsbyjs/gatsby/tree/master/packages/gatsby-source-contentful)

## Metalsmith

[Metalsmith](http://www.metalsmith.io/) is a JavaScript based static-site generator, and this plugin fetches and renders data from Contentful.

[View on GitHub](https://github.com/contentful-labs/contentful-metalsmith)

[View examples](https://github.com/contentful-labs/contentful-metalsmith-example)






## Jekyll

[Jekyll](https://jekyllrb.com/) is a Ruby based static site generator. It’s simple and blog-aware, a great option for small projects and personal sites. This plugin pulls content from Contentful.

[View on GitHub](https://github.com/contentful/jekyll-contentful-data-import)

[View examples](https://github.com/contentful/contentful_jekyll_examples)


## Gatsby

[Gatsby](https://www.gatsbyjs.org/) is a static site generator based on React. Gatsby and Contentful work together well—you can install the Gatsby app, which lets you see updates. Gatsby also has a package that enables Contentful to be a data source for a Gatsby project.

[View on GitHub](https://github.com/gatsbyjs/gatsby/tree/master/packages/gatsby-source-contentful)

## Metalsmith

[Metalsmith](http://www.metalsmith.io/) is a JavaScript based static-site generator, and this plugin fetches and renders data from Contentful.

[View on GitHub](https://github.com/contentful-labs/contentful-metalsmith)

[View examples](https://github.com/contentful-labs/contentful-metalsmith-example)

## Tutorials


### Automated rebuild and deployment with CircleCI and Webhooks

[This tutorial](https://www.contentful.com/developers/docs/ruby/tutorials/automated-rebuild-and-deploy-with-circleci-and-webhooks/) shows you how to setup and automatically deploy static sites using Jekyll or Middleman with CircleCI.

## Other tools

While the below tools are not officially supported by our static site CMS, they can help extend the functionality of Contentful


### Roots

[Roots](https://roots.cx/) is a JavaScript based static site generator. It doesn’t have an extensive ecosystem, but it’s great if you’re using Node.js-based front-end tools. This plugin helps you manage content from Contentful.

[View on GitHub](https://github.com/carrot/roots-contentful)


### Textalk

Textalk is a simple static site generator, a command-line interface (CLI) tool to generate a site from templates and data in a Contentful space.

[View on GitHub](https://github.com/Textalk/contentful-static)

### AWS Lambda

Here’s an example static site using Amazon web services (AWS) Lambda.

[View example](https://github.com/contentful-labs/contentful-aws-lambda-static)



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





### Forge FaaS

Forge to FaaS od Atlassiana do tworzenia rozszerzeń do Jiry czy Confluence. 
Spoiler alert - kod JavaScript który jest tam uruchamiany również działa w sandbox'ie.
Pzyjrzymy się na przykładzie Forge'a jak możemy stworzyć bezpieczny sandbox w V8.



### next.js

Build your app with web components!

Web components have matured significantly over the last several year and are definitely ready for prime time. 

Writing a full blown web application with web components is now a wonderful experience.

+    CSS style isolation out of the box with Shadow DOM
+    Component based architecture
+    Supports ESM
+    Bundled (if you want)
+    Minified (if you want)
+    Documentation - Best on the web!
+    Supported by all major browsers (And IE11 with some polyfills)
+    Data binding - a little help from lit-html will go a long way!






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

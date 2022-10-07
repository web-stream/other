
![logo webstream](https://logo.webstream.dev/3/cover.png)

<img alt="open collective badge" src="https://opencollective.com/webstream/tiers/backer/badge.svg?label=backer&color=brightgreen" />
<img alt="open collective badge" src="https://opencollective.com/webstream/tiers/sponsor/badge.svg?label=sponsor&color=brightgreen" />
<object type="image/svg+xml" data="https://opencollective.com/webstream/tiers/backer.svg?avatarHeight=36&width=600"></object>

---

# [docs.webstream.dev](https://docs.webstream.dev/#/)

+ [www.webstream.dev](https://www.webstream.dev/#/)
+ [roadmap.webstream.dev](https://roadmap.webstream.dev/#/)
+ [other.webstream.dev](https://other.webstream.dev/#/)
+ [other.webstream.dev](https://other.webstream.dev/#/)
+ [modules.webstream.dev](https://modules.webstream.dev/#/)

## About Webstream [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/web-stream/other/edit/main/DOCS/ABOUT.md)

## About Webstream

+  Website about Webstreaming on github - [web-stream/www](https://github.com/web-stream/www)


# [other.webstream.dev](https://other.webstream.dev/)


# Frameworks and libraries

Static site generators

We love static sites and have plugins are secure, simple and reliable.
They withstand high traffic and require little upkeep.


[Static site generators - Contentful](https://www.contentful.com/developers/docs/tools/staticsitegenerators/)





## Tutorials


### Automated rebuild and deployment with CircleCI and Webhooks

[This tutorial](https://www.contentful.com/developers/docs/ruby/tutorials/automated-rebuild-and-deploy-with-circleci-and-webhooks/) shows you how to setup and automatically deploy static sites using Jekyll or Middleman with CircleCI.

## Other tools

While the below tools are not officially supported by our static site CMS, they can help extend the functionality of Contentful






### ASCIIFlow

[website ASCIIFlow](https://asciiflow.com/#/)
[github lewish/asciiflow: ASCIIFlow](https://github.com/lewish/asciiflow)


### AWS Lambda

Here’s an example static site using Amazon web services (AWS) Lambda.

[View example](https://github.com/contentful-labs/contentful-aws-lambda-static)


## Gatsby

[Gatsby](https://www.gatsbyjs.org/) is a static site generator based on React. Gatsby and Contentful work together well—you can install the Gatsby app, which lets you see updates. Gatsby also has a package that enables Contentful to be a data source for a Gatsby project.

[View on GitHub](https://github.com/gatsbyjs/gatsby/tree/master/packages/gatsby-source-contentful)


## [Highland.js](https://caolan.github.io/highland/)

[Node.js streams 101 - slides.com/michalczukm/nodejs-streams-101#/9/1](https://slides.com/michalczukm/nodejs-streams-101#/9/1)

[caolan/highland: High-level streams library for Node.js and the browser](https://github.com/caolan/highland)

[Highland.js](https://caolan.github.io/highland/)

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



## Jekyll

[Jekyll](https://jekyllrb.com/) is a Ruby based static site generator. It’s simple and blog-aware, a great option for small projects and personal sites. This plugin pulls content from Contentful.

[View on GitHub](https://github.com/contentful/jekyll-contentful-data-import)

[View examples](https://github.com/contentful/contentful_jekyll_examples)




## Metalsmith

[Metalsmith](http://www.metalsmith.io/) is a JavaScript based static-site generator, and this plugin fetches and renders data from Contentful.

[View on GitHub](https://github.com/contentful-labs/contentful-metalsmith)

[View examples](https://github.com/contentful-labs/contentful-metalsmith-example)


## Middleman

The static site generator [Middleman](https://middlemanapp.com/) is a command-line tool that uses Ruby and Ruby Gems. It’s one of the most-used static tools for large companies. This plugin will help you manage your Contentful content

[View on GitHub](https://github.com/contentful/contentful_middleman)

[View examples](https://github.com/contentful/contentful_middleman_examples)



# SaaS

## [Modellution, tool for EventStorming and EventModeling](https://www.modellution.com/#step-1)


> Modelling platform that improves velocity of your dev-team by 80% Modelling platform that improves velocity of your dev-team by 80%
>
> 1
>
> # Visual Collaboration Realtime collaboration experience for EventStorming and EventModeling Visual Collaboration \- Realtime board collaboration experience. \- Event Modeling and Event Storming support : Building blocks: Commands, Events, Views, UI, Processors and Policies, Business Rules, Users, Aggregates and more.... \- Schema register: Supports input for test example data and schema types. \- Swim lanes
>

> 2
>
> # Estimate software complexity Estimate software complexity with one click!
>
> # Transparent estimates \- Estimate information complexity with a click. \- Configure estimation formula based on team experience. \- From now on - never hide any complexity
>

> 3
>
> # Jira integration We make EventStorming and EventModeling play nicely with Jira and ClickUp.
>
> # Jira integration \- Create or assign new user stories straight from Modellution \- See statuses of stories directly from Modellution. \- Always have links to up-to-date specs from Jira. \- If you are not using Jira but other project- management software - no worries - let us know.
>

> 4
>
> # IDE assist Do you want a better refactor? Generate code based on spec directly in your fav. IDE
>
> IDE assist & CI/CD integration \- Significantly improve code-writing experience to your team: Let your team automatically apply theirs conventions with IDE assist based on specs. \- Generate BDD scenarios or contracts from CLI.




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




### Roots

[Roots](https://roots.cx/) is a JavaScript based static site generator. It doesn’t have an extensive ecosystem, but it’s great if you’re using Node.js-based front-end tools. This plugin helps you manage content from Contentful.

[View on GitHub](https://github.com/carrot/roots-contentful)



### Textalk

Textalk is a simple static site generator, a command-line interface (CLI) tool to generate a site from templates and data in a Contentful space.

[View on GitHub](https://github.com/Textalk/contentful-static)


### Textik

[website Textik - ASCII diagrams editor](https://textik.com/)
[github flatedit/tixi: Ascii charts editor](https://github.com/flatedit/tixi)


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


## About Tom Sapletta

+ [Contact on linkedin](https://www.linkedin.com/in/tom-sapletta-com/)
+ [Tom Sapletta Blog - Embedded System Software & Hardware Developer](https://tom.sapletta.com/)
+ [Softreck Company - Leadership Through Software Development](https://softreck.com/)



---
+ [edit](https://github.com/web-stream/other/edit/main/README.md)
```
https://github.com/web-stream/other.git
```


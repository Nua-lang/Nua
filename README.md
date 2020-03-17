 <img src="https://github.com/Nua-lang/Images/blob/master/uhunua.png"></img>


A Production ready implementation of the Lua C Librairy

![](https://img.shields.io/badge/build-passing-brightgreen)
![](https://img.shields.io/badge/circleci-passing-brightgreen)
![](https://img.shields.io/badge/chat-on%20googleGroups-dodgerblue)
![](https://img.shields.io/badge/Self--host-passing-dodgerblue)

Nua is a language with the following goals:
* Virtual Machine
  * C VM transpiled to node.js for web-commitment
  * Small but compact byte-code interpreter (similar to LuaJIT - Joff) 
  * Much more speed than the Lua-C
* Syntax
  * Using couroutines
  * Lightweight fibers
  * nil value
* Api
  * Js-api similar to the LuaC-api
  * Useful rest-api
  
  Sounds great? So get started. You even can try it out in your <a href="http://freezyjs.github.io">Browser</a>.
  
  Medium: <a href="https://medium.com/p/90cd532ac09/edit">article</a>

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

The Nua language is built on top of node.js so simply do install the deps from npm:

```
npm install -g nua-node-cli
npm install nua-node-cli
npm install -g nua-test
npm install nua-test
npm init
```

### Installing

To keep up with clean deps simply do:

```
npm install && npm init
```
<hr>

### Cli options

To fire up an Interactive Interpreter Mode do so:

```
$ nua
```


To run external .Nua scripts please type:

```
$ nua <script.nua>
```

Show the current version of Nua using this command:

```
nua -v
```

You want to learn the Nua lang? So fire up the official syntax guide<a href=""> on Nua.io</a>


## Running the tests

The test section for Nua is written itselfes in Nua!

### Nua

Run these commands in your local shell.

```
npm run nua-test
```

### Nua-C


```
npm run nuac-test
```



## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com//) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Timo Sarkar** - *Initial work* - [Nua](https://github.com/Nua-lang)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## work in progress

* Book for Nua
* Blog
* better Modules
* Rewrite Nua.io in Nua


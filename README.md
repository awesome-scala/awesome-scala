
Awesome Scala [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/awesome-scala/awesome-scala.svg?branch=master)](https://travis-ci.org/awesome-scala/awesome-scala)
=============

A community driven list of useful Scala libraries, frameworks and software. This is not a catalog of all the libraries, just a starting point for your explorations. Inspired by [awesome-python](https://github.com/vinta/awesome-python). Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

Also awesome is [Scaladex](https://index.scala-lang.org/), the searchable, tagged, and centralized index of Scala libraries.

Projects with over 500 stargazers are in bold.

## Table of Contents

- [Learning Scala](#learning-scala)
- [Projects](#projects)
    - [Android](#android)
    - [Artificial Intelligence](#artificial-intelligence)
    - [Authentication](#authentication)
    - [Authorization](#authorization)
    - [Big Data](#big-data)
    - [Cryptography](#cryptography)
    - [CSV](#csv)
    - [Data Binding and Validation](#data-binding-and-validation)
    - [Databases](#databases)
    - [Database Access](#database-access)
    - [DevOps](#devops)
    - [Distributed Systems](#distributed-systems)
    - [Extensions](#extensions)
    - [Functional Reactive Programming](#functional-reactive-programming)
    - [Geospatial](#geospatial)
    - [Graphical User Interfaces](#graphical-user-interfaces)
    - [HTTP](#http)
    - [i18n](#i18n)
    - [Image processing and image analysis](#image-processing-and-image-analysis)
    - [JavaScript](#javascript)
    - [JSON](#json)
    - [Markdown](#markdown)
    - [Metrics and Monitoring](#metrics-and-monitoring)
    - [Misc](#misc)
    - [Modularization and Dependency Injection](#modularization-and-dependency-injection)
    - [Parsing](#parsing)
    - [Reactive Web Frameworks](#reactive-web-frameworks)
    - [Sbt plugins](#sbt-plugins)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Scheduling](#scheduling)
    - [Semantic Web](#semantic-web)
    - [Serialization](#serialization)
    - [Templating](#templating)
    - [Testing](#testing)
    - [Tools](#tools)
    - [Web Frameworks](#web-frameworks)
    - [XML / HTML](#xml--html)
    - [YAML](#yaml)
- [Resources](#resources)
    - [Newsletters](#newsletters)
    - [Podcasts](#podcasts)
- [Contributing](#contributing)

## Artificial Intelligence

* [CIlib ★ 82](https://github.com/cirg-up/cilib) - Typesafe, purely functional Computational Intelligence.


## Databases

*Databases implemented in Scala.*

* **[Atlas ★ 2790 ⧗ 1](https://github.com/Netflix/atlas)** - In-memory dimensional time series database built by Netflix.
* **[FiloDB ★ 1251 ⧗ 0](https://github.com/filodb/FiloDB)** - Prometheus-compatible distributed time series database.
* [L-space ★ 3 ⧗ 35](https://github.com/L-space/L-space) - A pure Scala (and Scala.js) Linked Data graph computing framework, database (both in-memory and persistent) and rest-APIs (support for Json-ld).
* [SwayDB](http://www.swaydb.io/) - A Type-safe & non-blocking key-value storage library for single/multiple disks and in-memory storage.

## Database Access

*Database access libraries in Scala.*

* [Anorm ★ 206 ⧗ 6](https://github.com/playframework/anorm) - Simple SQL data access.
* [Casbah](http://mongodb.github.io/casbah/) ([repo](https://github.com/mongodb/casbah)) - Officially supported Scala driver for MongoDB
* **[doobie ★ 1750 ⧗ 1](https://github.com/tpolecat/doobie)** - Pure functional JDBC layer for Scala.
* **[Elastic4s ★ 1527 ⧗ 0](https://github.com/sksamuel/elastic4s)** - A scala DSL / reactive client for Elasticsearch
* [Finagle ★ 71 ⧗ 53](https://github.com/finagle/finagle-postgres) - PostgreSQL protocol support for Finagle
* [longevity ★ 101 ⧗ 59](https://github.com/longevityframework/longevity) - A Persistence Framework for Scala and NoSQL with a Domain Driven Design Orientation
* [lucene4s ★ 41 ⧗ 38](https://github.com/outr/lucene4s) - Light-weight convenience wrapper around Lucene to simplify complex tasks and add Scala sugar.
* [Memcontinuationed ★ 50 ⧗ 59](https://github.com/Atry/memcontinuationed) - Memcached client for Scala.
* [Morpheus ★ 102 ⧗ 276](https://github.com/outworkers/morpheus) - Reactive type safe Scala Driver for MySQL/Postgres.
* **[Phantom ★ 1044 ⧗ 16](https://github.com/outworkers/phantom)** - Reactive typed Scala driver for Apache Cassandra.
* **[PostgreSQL and MySQL async ★ 1441 ⧗ 4](https://github.com/mauricio/postgresql-async)** - Async database drivers to talk to PostgreSQL and MySQL in Scala.
* [Pulsar4s ★ 169 ⧗ 6](https://github.com/sksamuel/pulsar4s) - Scala client for Apache Pulsar.
* **[Quill ★ 1774 ⧗ 2](https://github.com/getquill/quill)** - Compile-time Language Integrated Query for Scala
* [ReactiveCouchbase](http://reactivecouchbase.org/) - Reactive Scala Driver for Couchbase. Also includes a Play plug-in. An official plug-in is also in development.
* **[ReactiveMongo ★ 824 ⧗ 6](https://github.com/ReactiveMongo/ReactiveMongo)** - Reactive Scala Driver for MongoDB.
* **[rediscala ★ 793 ⧗ 2](https://github.com/etaty/rediscala)** - Non-blocking, Reactive Redis driver for Scala (with Sentinel support)
* [Relate ★ 163 ⧗ 135](https://github.com/lucidsoftware/relate) - Lightweight, blazing-fast database access layer for Scala that abstracts the idiosyncricies of the JDBC while keeping complete control over the SQL.
* [Salat ★ 488 ⧗ 28](https://github.com/salat/salat/) - ORM for MongoDB. A related Play-plugin is also available.
* [Scala ActiveRecord ★ 319 ⧗ 51](https://github.com/aselab/scala-activerecord) - ORM library for scala, inspired by ActiveRecord of Ruby on Rails.
* [Scala-Forklift ★ 179 ⧗ 58](https://github.com/lastland/scala-forklift) - Type-safe database migration for Slick, Git, etc.
* **[scala-redis ★ 979 ⧗ 4](https://github.com/debasishg/scala-redis)** - A Scala library for connecting to a redis server, with clustering support
* [scala-sql ★ 71 ⧗ 123](https://github.com/wangzaixiang/scala-sql) - Yet another SQL-based DB access library for scala language
* [ScalaRelational ★ 55 ⧗ 163](https://github.com/outr/scalarelational) - Type-Safe framework for defining, modifying, and querying SQL databases.
* **[ScalikeJDBC ★ 1128 ⧗ 0](https://github.com/scalikejdbc/scalikejdbc)** - A tidy SQL-based DB access library for Scala developers.
* [Scanamo ★ 276 ⧗ 1](https://github.com/guardian/scanamo) - A library to make using DynamoDB with Scala simpler and less error-prone.
* [scredis ★ 154 ⧗ 337](https://github.com/Livestream/scredis) - Non-blocking Redis client built on top of Akka IO (used by Livestream)
* [Shade ★ 106 ⧗ 59](https://github.com/alexandru/shade) - Memcached client for Scala, based on Spymemcached
* **[Slick ★ 2404 ⧗ 0](https://github.com/slick/slick)** - Modern database query and access library for Scala.
* [Sorm ★ 238 ⧗ 34](https://github.com/sorm/sorm) - A functional boilerplate-free Scala ORM.
* **[Squeryl ★ 550 ⧗ 5](https://github.com/squeryl/squeryl)** - A Scala DSL for talking with databases with minimum verbosity and maximum type safety.
* [Tepkin ★ 82 ⧗ 59](https://github.com/fehmicansaglam/tepkin) - Reactive MongoDB Driver for Scala built on top of Akka IO and Akka Streams.

## Messaging

* [Op-Rabbit ★ 236 ⧗ 22](https://github.com/SpinGo/op-rabbit) - High-level messaging library for Akka and Op-Rabbit.

## Graphical User Interfaces

*Libraries for creation of graphical user interfaces*

* [ScalaFX](http://www.scalafx.org/) - Scala DSL for creating Graphical User Interfaces that sits on top of JavaFX.

## Web Frameworks

*Scala frameworks for web development.*

* [Analogweb ★ 11 ⧗ 24](https://github.com/analogweb/analogweb-scala) - Tiny, simple, and pluggable web framework in Scala.
* [Chaos ★ 245 ⧗ 24](https://github.com/mesosphere/chaos) - A lightweight framework for writing REST services in Scala.
* **[Colossus ★ 811 ⧗ 70](http://tumblr.github.io/colossus/)** - lightweight framework for building high-performance applications in Scala that require non-blocking network I/O.
* **[Finatra ★ 2044 ⧗ 1](https://github.com/twitter/finatra)** - A sinatra-inspired web framework for scala, running on top of Finagle.
* **[Lift ★ 1222 ⧗ 2](https://github.com/lift/framework)** - Secure and powerful full stack web framework ([discussion](https://github.com/lauris/awesome-scala/pull/19)).
* [peregine ★ 13 ⧗ 24](https://github.com/dvarelap/peregrine) - A simple and async lightweight Scala web framework.
* **[Play ★ 11759 ⧗ 1](https://github.com/playframework/playframework)** - Makes it easy to build scalable, fast and real-time web applications with Java & Scala.
* [Play Pagelets ★ 75 ⧗ 24](https://github.com/splink/pagelets) - A Module for the Play Framework to build resilient and modular Play applications in an elegant and concise manner.
* [Reactive ★ 213 ⧗ 3](https://github.com/nafg/reactive) - FRP and web abstractions, which can be plugged into any web framework (currently only has bindings for Lift).
* **[Scalatra ★ 2482 ⧗ 0](https://github.com/scalatra/scalatra)** - Tiny Scala high-performance, async web framework, inspired by Sinatra.
* **[Skinny Framework ★ 717 ⧗ 6](https://github.com/skinny-framework/skinny-framework)** - A full-stack web app framework upon Scalatra for rapid Development in Scala.
* [suzaku ★ 108 ⧗ 24](https://github.com/suzaku-io/suzaku) - Suzaku web UI framework for Scala
* **[Unfiltered ★ 709 ⧗ 2](https://github.com/unfiltered/unfiltered)** - A modular set of unopinionated primitives for servicing HTTP and WebSocket requests in Scala.
* [Xitrum](http://xitrum-framework.github.io/) - An async and clustered Scala web framework and HTTP(S) server fusion on top of Netty, Akka, and Hazelcast.
* [youi ★ 183 ⧗ 9](https://github.com/outr/youi) - Next generation user interface framework and server engine for Scala and Scala.js.

## Reactive Web Frameworks

*Scala libraries for Reactive Web development*

* **[Binding.scala ★ 1513 ⧗ 3](https://github.com/ThoughtWorksInc/Binding.scala)** - A reactive web framework. It enables you use native XML literal syntax to create reactive DOM nodes, which are able to automatically change whenever the data source changes.
* **[Korolev ★ 935 ⧗ 0](http://github.com/fomkin/korolev/)** - Modern single-page applications running on the server side
* [Udash](http://udash.io/) - a web framework based on Scala.js with support for property bindings, frontend routing, i18n and much more. It also provides strongly typed client<->server RPC system based on WebSockets.
* [Vert.x Web](http://vertx.io/docs/vertx-web/scala/) - Toolkit to build Reactive web applications..
* [Widok](https://widok.github.io/) - Reactive web framework for the JVM and Scala.js

## Data Binding and Validation

*Scala libraries for data binding and validation*

* **[Accord ★ 515 ⧗ 4](https://github.com/wix/accord)** - A sane validation library for Scala
* [Monkeytail ★ 87 ⧗ 59](https://github.com/sksamuel/monkeytail) - A set of validation macros and helpers for cats.Validated
* [Octopus ★ 136 ⧗ 21](https://github.com/krzemin/octopus) - Scala library for boilerplate-free validation

## i18n

*Scala libraries for i18n.*

* [Scaposer ★ 36 ⧗ 120](https://github.com/xitrum-framework/scaposer) - GNU Gettext .po file loader for Scala.

## Authentication

*Libraries for implementing authentications schemes.*

* [akka-http-session ★ 429 ⧗ 9](https://github.com/softwaremill/akka-http-session) - Web&mobile client-side sessions for akka-http based applications, with optional JWT support
* [AWS Request Signer ★ 20 ⧗ 256](https://github.com/ticofab/aws-request-signer) - Helper to evaluate the signing headers for HTTP requests to Amazon Web Services.
* [Play Google Auth Module ★ 33 ⧗ 17](https://github.com/guardian/play-googleauth) - A very simple implementation of Google OpenID Connect authentication for Play 2 applications.
* [play-pac4j ★ 373 ⧗ 4](https://github.com/pac4j/play-pac4j) - Security library managing authentication (CAS, OAuth, OpenID, SAML, LDAP, SQL, JWT...), authorizations and logout for Play 2.x in Java and Scala.
* **[play-silhouette ★ 822 ⧗ 2](https://github.com/mohiva/play-silhouette)** - Authentication library for Play Framework applications that supports several authentication methods, including OAuth1, OAuth2, OpenID, Credentials or custom authentication schemes.
* **[play2-auth ★ 622 ⧗ 5](https://github.com/t2v/play2-auth)** - Play2.x Authentication and Authorization module.
* **[scala-oauth2-provider ★ 515 ⧗ 2](https://github.com/nulab/scala-oauth2-provider)** - OAuth 2.0 server-side implementation written in Scala.
* **[SecureSocial ★ 1195 ⧗ 11](https://github.com/jaliss/securesocial)** - A module that provides OAuth, OAuth2 and OpenID authentication for Play Framework applications.

## Authorization

*Libraries for implementing authorization strategies.*

* [deadbolt-2 ★ 495 ⧗ 2](https://github.com/schaloner/deadbolt-2) - A Play 2.x module supporting role-based and proprietary authorization; idiomatic APIs for Scala and Java APIs are provided.

## Cryptography

*Cryptography and Encryption Libraries.*

* [Scrypto ★ 171 ⧗ 26](https://github.com/ScorexProject/scrypto) - All-purpose cryptographic framework.
* [TSec ★ 332 ⧗ 1](https://github.com/jmcardon/tsec) - Type-safe, functional, general-cryptography library

## Testing

*Libraries for code testing.*

* [cornichon ★ 212 ⧗ 1](https://github.com/agourlay/cornichon) - Scala DSL for testing HTTP JSON API.
* [Gatling](http://gatling.io) - Async Scala-Akka-Netty based Stress Tool.
* [Minitest ★ 165 ⧗ 6](https://github.com/monix/minitest) - A testing framework with a focus on simplicity.
* **[ScalaCheck ★ 1676 ⧗ 0](https://github.com/rickynils/scalacheck)** - Property-based testing for Scala.
* [ScalaMeter](https://scalameter.github.io/) - Performance &  memory footprint measuring, regression testing.
* [ScalaMock](http://scalamock.org) - Scala native mocking framework
* [scalaprops ★ 260 ⧗ 2](https://github.com/scalaprops/scalaprops) - Another property based testing library for Scala
* **[ScalaTest ★ 930 ⧗ 0](https://github.com/scalatest/scalatest)** - A testing tool for Scala and Java developers.
* [Scalive ★ 203 ⧗ 143](https://github.com/xitrum-framework/scalive) - Connect a Scala REPL to running JVM processes without any prior setup; this library is used for inspecting systems in production mode.
* **[Specs2 ★ 685 ⧗ 8](https://github.com/etorreborre/specs2)** - Software Specifications for Scala.
* [Stryker4s ★ 107 ⧗ 1](https://github.com/stryker-mutator/stryker4s) - Test your tests with mutation testing.
* [testcontainers-scala ★ 386 ⧗ 1](https://github.com/testcontainers/testcontainers-scala) - Docker containers for testing in Scala.
* [µTest ★ 416 ⧗ 2](https://github.com/lihaoyi/utest) - A tiny, portable testing library for Scala.

## JSON

*Libraries for work with json.*

* [argonaut](http://argonaut.io/) - Purely Functional JSON in Scala.
* **[circe ★ 2062 ⧗ 0](https://github.com/travisbrown/circe)** - JSON library based on Argonaut, depends on Cats
* [diffson ★ 252 ⧗ 4](https://github.com/gnieh/diffson) - A scala diff/patch library for Json
* [jackson-module-scala ★ 424 ⧗ 0](https://github.com/FasterXML/jackson-module-scala) - Add-on module for Jackson to support Scala-specific datatypes.
* [jawn ★ 390 ⧗ 2](https://github.com/non/jawn) - Fast json parser (According to them, competetive with java gson/jackson speed).
* **[json4s ★ 1334 ⧗ 2](https://github.com/json4s/json4s)** - Project aims to provide a single AST to be used by other scala json libraries.
* [jsoniter-scala ★ 388 ⧗ 1](https://github.com/plokhotnyuk/jsoniter-scala) - Scala macros for compile-time generation of ultra-fast JSON codecs.
* [play-json ★ 251 ⧗ 20](https://github.com/playframework/play-json) - Flexible and powerful JSON manipulation, validation and serialization, with no reflection at runtime.
* [Pushka ★ 74 ⧗ 109](https://github.com/fomkin/pushka) - Scala JSON serialization library with annotations.
* [qbproject](https://github.com/qb-project/qbproject) - Scala Libs around JSON and API developement for Play Framework.
* [rapture-json](https://github.com/propensive/rapture/blob/dev/doc/json.md) - Clean, intuitive, unintrusive, boilerplate-free Scala API
* [scala-jsonapi ★ 106 ⧗ 59](https://github.com/scala-jsonapi/scala-jsonapi) - Support library for integrating the JSON API spec with Scala and Spray JSON, Play! JSON or Circe.
* [scalajack ★ 100 ⧗ 16](https://github.com/gzoller/ScalaJack) - Fast 'n easy JSON serialization with optional MongoDB support.  Uses Jackson under the hood.
* **[spray-json ★ 906 ⧗ 5](https://github.com/spray/spray-json)** - Lightweight, clean and efficient JSON implementation in Scala.
* [uJson](http://www.lihaoyi.com/upickle/#uJson) - fast, flexible and intuitive JSON for Scala

## YAML

*Libraries for work with YAML.*

* [MoultingYAML ★ 87 ⧗ 48](https://github.com/jcazevedo/moultingyaml) - Type-class based YAML serialization and deserialization on top of SnakeYAML.

## CSV

*Libraries for work with CSV.*

* [fm-flatfile ★ 9 ⧗ 131](https://github.com/frugalmechanic/fm-flatfile) - Very flexible, Flat File (CSV, TSV, Excel, etc) Reader for Scala.
* [kantan.csv ★ 300 ⧗ 5](https://github.com/nrinaudo/kantan.csv) - CSV handling library for Scala with multiple backends.
* **[Scala-CSV ★ 588 ⧗ 2](https://github.com/tototoshi/scala-csv)** - CSV Reader/Writer for Scala.

## Serialization

*Libraries for serializing and deserializing data for storage or transport.*

* [avro-codegen](https://github.com/Nitro/avro-codegen) - Code generation from avro schemas to serialize/deserialize avro messages, no runtime reflection.
* **[Chill ★ 559 ⧗ 5](https://github.com/twitter/chill)** - Extensions for the Kryo serialization library to ease configuration in systems like Hadoop and Storm.
* [msgpack ★ 90 ⧗ 74](https://github.com/msgpack/msgpack-scala) - A efficient binary serialization library.
* **[Pickling ★ 853 ⧗ 90](https://github.com/scala/pickling)** - Fast, customizable, boilerplate-free pickling support.
* [ScalaBuff ★ 222 ⧗ 182](https://github.com/SandroGrzicic/ScalaBuff) - a Scala Protocol Buffers (protobuf) compiler
* **[ScalaPB ★ 705 ⧗ 51](https://scalapb.github.io/)** - Protocol Buffers and gRPC support for Scala
* **[scodec ★ 705 ⧗ 0](https://github.com/scodec/scodec)** - A combinator library for working with binary data.
* [Scrooge](http://twitter.github.io/scrooge/) - An Apache Thrift code generator for Scala.
* [validation ★ 195 ⧗ 11](https://github.com/jto/validation) - Advanced validation & serialization for JSON, HTML form data, etc, with no reflection at runtime.
* [µPickle](http://lihaoyi.github.io/upickle/) - A lightweight serialization library for Scala that works in ScalaJS, allowing transfer of structured data between the JVM and JavaScript.

## Science and Data Analysis

*Libraries for scientific computing, data analysis and numerical processing.*

* **[Algebird ★ 2022 ⧗ 2](https://github.com/twitter/algebird)** - Abstract Algebra for Scala.
* [Axle ★ 62 ⧗ 19](https://github.com/axlelang/axle) - A Spire-based DSL for scientific cloud computing.
* **[BigDL ★ 3680 ⧗ 1](https://github.com/intel-analytics/BigDL)** - BigDL is a distributed deep learning library for Apache Spark.
* **[Breeze ★ 3189 ⧗ 0](https://github.com/scalanlp/breeze)** - Breeze is a numerical processing library for Scala.
* [Chalk ★ 262 ⧗ 130](https://github.com/scalanlp/chalk) - Chalk is a natural language processing library.
* [doddle-model ★ 142 ⧗ 37](https://github.com/picnicml/doddle-model) - An in-memory machine learning library built on top of Breeze. It provides immutable objects and exposes its functionality through a scikit-learn-like API.
* **[FACTORIE ★ 556 ⧗ 7](https://github.com/factorie/factorie)** - A toolkit for deployable probabilistic modeling, implemented as a software library in Scala.
* **[Figaro ★ 721 ⧗ 4](https://github.com/p2t2/figaro)** - Figaro is a probabilistic programming language that supports development of very rich probabilistic models.
* [Libra ★ 195 ⧗ 16](https://github.com/to-ithaca/libra) - Libra is a dimensional analysis library based on shapeless, spire and singleton-ops. It contains out of the box support for SI units for all numeric types.
* [MGO ★ 62 ⧗ 49](https://github.com/openmole/mgo) - Modular multi-objective evolutionary algorithm optimization library enforcing immutability.
* [MLLib](https://spark.apache.org/mllib/) - Machine Learning framework for Spark
* [ND4S ★ 297 ⧗ 3](https://github.com/deeplearning4j/nd4s) - N-Dimensional arrays and linear algebra for Scala with an API similar to Numpy.  ND4S is a scala wrapper around [ND4J](http://nd4j.org/).
* [Numsca ★ 157 ⧗ 11](https://github.com/botkop/numsca) - Numsca is Numpy for Scala.
* [OpenMOLE ★ 118 ⧗ 3](https://github.com/openmole/openmole) - OpenMOLE (Open MOdeL Experiment) is a workflow engine designed to leverage the computing power of distributed execution environments for naturally parallel processes.
* [OscaR](https://bitbucket.org/oscarlib/oscar/wiki/Home) - a Scala toolkit for solving Operations Research problems
* **[PredictionIO ★ 12467 ⧗ 0](https://github.com/PredictionIO/PredictionIO)** - machine learning server for developers and data scientists. Built on Apache Spark, HBase and Spray
* [Rings ★ 50 ⧗ 28](https://github.com/PoslavskySV/rings) - An efficient library for polynomial rings. Commutative algebra, polynomial GCDs, polynomial factorization and other sci things at a really high speed.
* **[Saddle ★ 510 ⧗ 98](https://github.com/saddle/saddle)** - A minimalist port of Pandas to Scala
* [Smile](http://haifengl.github.io/smile/) - Statistical Machine Intelligence and Learning Engine. Smile is a fast and comprehensive machine learning system.
* **[Spark Notebook ★ 2992 ⧗ 1](https://github.com/andypetrella/spark-notebook)** - Scalable and stable Scala and Spark focused notebook bridging the gap between JVM and Data Scientists (incl. extendable, typesafe and reactive charts).
* **[Spire ★ 1601 ⧗ 0](https://github.com/non/spire)** - Powerful new number types and numeric abstractions for Scala.
* **[Squants ★ 751 ⧗ 2](https://github.com/garyKeorkunian/squants)** - The Scala API for Quantities, Units of Measure and Dimensional Analysis.
* [SwiftLearner ★ 38 ⧗ 42](https://github.com/valdanylchuk/swiftlearner) - Simply written algorithms to help study Machine Learning or write your own implementations.
* **[Tensorflow_scala ★ 829 ⧗ 2](https://github.com/eaplatanios/tensorflow_scala)** - TensorFlow API for the Scala Programming Language
* [Tyche ★ 97 ⧗ 196](https://github.com/neysofu/tyche) - Probability distributions, stochastic & Markov processes, lattice walks, simple random sampling. A simple yet robust Scala library.
* [Zeppelin](http://zeppelin-project.org/) - Scala and Spark Notebook (like IPython Notebook)

## Big Data

* **[BIDMach ★ 907 ⧗ 104](https://github.com/BIDData/BIDMach)** - CPU and GPU machine learning library, using JNI for GPU computation.
* **[Flink ★ 14980 ⧗ 0](https://github.com/apache/flink)** - Processing framework with powerful stream- and batch-processing capabilities.
* [Gearpump ★ 300 ⧗ 36](https://github.com/apache/incubator-gearpump) - Lightweight real-time big data streaming engine
* [GridScale ★ 22 ⧗ 17](https://github.com/openmole/gridscale) - A Scala API for computing clusters and grids.
* **[Kafka ★ 17603 ⧗ 0](https://github.com/apache/kafka)** - Kafka is a message broker project and aims to provide a unified, high-throughput, low-latency platform for handling real-time data feeds.
* **[Reactive-kafka ★ 1274 ⧗ 3](https://github.com/akka/reactive-kafka)** - Reactive Streams API for Apache Kafka.
* **[Scalding ★ 3272 ⧗ 0](https://github.com/twitter/scalding)** - A Scala binding for the Cascading abstraction of Hadoop MapReduce.
* [Schemer ★ 95 ⧗ 19](https://github.com/indix/schemer) - Schema registry for CSV, TSV, JSON, AVRO and Parquet schema. Supports schema inference and GraphQL API.
* [Scio](https://github.com/spotify/scio) - A Scala API for [Apache Beam](https://beam.apache.org/) and [Google Cloud Dataflow](https://cloud.google.com/dataflow/) - None
* [Scrunch](http://crunch.apache.org/scrunch.html) - A Scala wrapper for [Apache Crunch](http://crunch.apache.org/index.html) which provides a framework for writing, testing, and running MapReduce pipelines.
* [Spark](http://spark.apache.org/) - Lightning fast cluster computing — up to 100x faster than Hadoop for iterative algorithms (memory caching) and up to 10x faster than Hadoop for single-pass MapReduce jobs. Compatible with YARN-enabled Hadoop clusters, can run on Mesos and in stand-alone mode as well.
* [spark-deployer ★ 76 ⧗ 109](https://github.com/KKBOX/spark-deployer) - A sbt plugin which helps deploying Apache Spark stand-alone cluster and submitting job on cloud system like AWS EC2.
* [Sparkplug ★ 23 ⧗ 97](https://github.com/indix/sparkplug) - Spark package to "plug" holes in data using SQL based rules
* **[Sparkta ★ 513 ⧗ 18](https://github.com/Stratio/sparkta)** - Real Time Aggregation based on Spark Streaming.
* **[Summingbird ★ 2089 ⧗ 11](https://github.com/twitter/summingbird)** - An implementation of the “lambda architecture” as a software abstraction — a single API for Hadoop and Storm.
* **[Vegas ★ 704 ⧗ 3](https://github.com/vegas-viz/Vegas)** - The missing MatPlotLib for Scala + Spark

## Image processing and image analysis

*2D and 3D image processing and image analysis*

* [scalismo ★ 180 ⧗ 3](https://github.com/unibas-gravis/scalismo) - Shape modelling and  model-based image analysis.
* **[scrimage ★ 777 ⧗ 0](https://github.com/sksamuel/scrimage)** - Image io, resize, manipulation and thumbnails.

## Sound processing and music

* [ScalaCollider ★ 169 ⧗ 16](https://github.com/Sciss/ScalaCollider) - Sound synthesis and signal processing client for SuperCollider.

## Functional Reactive Programming

*Event streams, signals, observables, etc.*

* **[Monix ★ 1738 ⧗ 1](https://github.com/monifu/monix)** - Extensions to Scala’s standard library for multi-threading primitives and functional reactive programming. Scala.js compatible.
* [REScala](http://www.rescala-lang.com/) - REScala is a library for functional reactive programming on the JVM and the Web. It provides a rich API for event stream transformations and signal composition with managed consistent up-to-date state and minimal syntactic overhead.
* **[RxScala ★ 882 ⧗ 5](https://github.com/ReactiveX/RxScala)** - Reactive Extensions for Scala – a library for composing asynchronous and event-based programs using observable sequences
* **[Scala.Rx ★ 960 ⧗ 3](https://github.com/lihaoyi/scala.rx)** - An experimental library for Functional Reactive Programming in Scala (reactive variables). Scala.js compatible.
* [SynapseGrid ★ 122 ⧗ 131](https://github.com/Primetalk/SynapseGrid) - an FRP framework for constructing reactive real-time immutable data flow systems. It implements an original way of running and organizing event-driven systems based on Petri nets. The topology can be viewed as a .dot graph. The library is compatible with Akka and can seamlessly communicate with other actors.
* [Vert.x](http://vertx.io/) - A polyglot reactive application platform for the JVM which aims to be an alternative to node.js. Its concurrency model resembles actors. It supports [Scala](http://vertx.io/docs/vertx-core/scala/), Clojure, Java, Javascript, Ruby, Groovy and Python.

## Modularization and Dependency Injection

*Modularization of applications, dependency injection, etc.*

* [Airframe ★ 434 ⧗ 0](https://github.com/wvlet/airframe) - Dependency injection library tailored to Scala.
* [DIStage ★ 377 ⧗ 0](https://github.com/pshirshov/izumi-r2) - Staged Dependency Injection with higher-kinded polymorphism.
* [Grafter ★ 240 ⧗ 88](https://github.com/zalando/grafter) - Grafter is a library to configure and wire Scala applications.
* **[MacWire ★ 1090 ⧗ 0](https://github.com/adamw/macwire)** - Scala Macro to generate wiring code for class instantiation. DI container replacement.
* [Scala-Guice ★ 321 ⧗ 0](https://github.com/codingwell/scala-guice) - Scala extensions for Google Guice
* [Scaldi ★ 282 ⧗ 2](https://github.com/scaldi/scaldi) - Lightweight Scala Dependency Injection Library.
* [SubCut ★ 393 ⧗ 10](https://github.com/dickwall/subcut) - Scala Uniquely Bound Classes Under Traits.

## Distributed Systems

*Libraries and frameworks for writing distributed applications.*

* [Akka](http://akka.io/) - A toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications.
* [Akka-tracing ★ 316 ⧗ 22](https://github.com/levkhomich/akka-tracing) - A distributed tracing extension for Akka. Provides integration with Play framework, Spray and Akka HTTP.
* [Clump](http://getclump.io) - A library for expressive and efficient service composition
* **[CurioDB ★ 511 ⧗ 24](https://github.com/stephenmcd/curiodb)** - Distributed & Persistent Redis Clone built with Scala & Akka.
* [Finagle](https://twitter.github.io/finagle/) - An extensible, protocol-agnostic RPC system designed for high performance and concurrency.
* [Glokka ★ 54 ⧗ 92](https://github.com/xitrum-framework/glokka) - Library to register and lookup actors by names in an Akka cluster.
* [Lagom](https://www.lightbend.com/lagom) - Framework for creating microservice-based systems.
* [Reactors](http://reactors.io/) - Foundational framework for distributed computing that fuses functional reactive programming and traditional actors.

## Extensions

*Scala extensions.*

* [Ammonite-Ops](http://lihaoyi.github.io/Ammonite/#Ammonite-Ops) - Safe, easy, filesystem operations in Scala as convenient as in the Bash shell.
* **[better-files ★ 1392 ⧗ 0](https://github.com/pathikrit/better-files)** - Simple, safe and intuitive Scala I/O. better-files is a dependency-free pragmatic thin Scala wrapper around Java NIO.
* **[Cassovary ★ 987 ⧗ 0](https://github.com/twitter/cassovary)** - A Scala library that is designed from the ground up for space efficiency, handling graphs with billions of nodes and edges.
* **[cats ★ 4150 ⧗ 1](https://github.com/typelevel/cats)** - Lightweight, modular, and extensible library for functional programming.
* **[Chimney ★ 698 ⧗ 1](https://github.com/scalalandio/chimney)** - Scala library for boilerplate-free data transformations.
* [chronoscala ★ 61 ⧗ 12](https://github.com/opt-tech/chronoscala) - Scala wrapper for Java Date/Time API.
* [Each ★ 239 ⧗ 53](https://github.com/ThoughtWorksInc/each) - A macro library that converts native imperative syntax to [Scalaz](https://github.com/scalaz/scalaz)'s monadic expressions.
* [Eff ★ 471 ⧗ 1](https://github.com/atnos-org/eff) - Extensible effects are an alternative to monad transformers for computing with effects in a functional way.
* [enableIf.scala ★ 57 ⧗ 19](https://github.com/ThoughtWorksInc/enableIf.scala) - A library that switches Scala code at compile-time, like `#if` in C/C++.
* **[Enumeratum ★ 993 ⧗ 1](https://github.com/lloydmeta/enumeratum)** - A macro to replace Scala enumerations with a sealed family of case objects. This allows additional checks for the compiler, e.g. for missing cases in a match statement. Has additinal support for Json libraries and the Play framework.
* [Freasy-Monad ★ 112 ⧗ 47](https://github.com/Thangiee/Freasy-Monad) - Easy way to create Free Monad for Cats and Scalaz using Scala macros with first-class Intellij support.
* **[Freestyle ★ 623 ⧗ 22](https://github.com/frees-io/freestyle)** - A cohesive & pragmatic framework of FP centric Scala libraries.
* [Hamsters ★ 293 ⧗ 29](https://github.com/scala-hamsters/hamsters) - A mini Scala utility library. Compatible with functional programming beginners. Featuring validation, monad transformers, HLists, Union types.
* [idid ★ 14 ⧗ 194](https://github.com/lucastorri/idid) - A library to define common interfaces for different Id types.
* [Lamma ★ 87 ⧗ 187](https://github.com/maxcellent/lamma) - A Scala date library for date and schedule generation.
* [LArray ★ 364 ⧗ 14](https://github.com/xerial/larray) - Large off-heap arrays (> 2GB) and mmap files.
* [Log4s](http://www.log4s.org/) - Fast, Scala-friendly logging bindings on top of [SLF4J](http://slf4j.org/). Uses macros for extreme performance.
* [LogStage ★ 377 ⧗ 0](https://github.com/pshirshov/izumi-r2) - Zero-cost structural logger for Scala with [SLF4J] integration.
* **[Monocle ★ 1311 ⧗ 2](https://github.com/julien-truffaut/Monocle)** - An Optics/Lens library for purely functional manipulation of immutable objects.
* **[n-scala ★ 830 ⧗ 2](https://github.com/nscala-time/nscala-time)** - Scala wrapper for Joda Time.
* [Persist-Logging ★ 38 ⧗ 307](https://github.com/nestorpersist/logging) - Comprehensive logging library for Scala.
* **[Quicklens ★ 634 ⧗ 4](https://github.com/adamw/quicklens)** - modify deeply nested case class fields with an elegant API
* [Rapture](http://rapture.io/) ([repo](https://github.com/propensive/rapture)) - a collection of libraries for common, everyday programming tasks (I/O, JSON, i18n, etc.)
* [Records for Scala ★ 159 ⧗ 59](https://github.com/scala-records/scala-records) - Labeled records for Scala based on structural refinement types and macros.
* **[refined ★ 1264 ⧗ 0](https://github.com/fthomas/refined)** - Simple refinement types with compile- and runtime checking
* **[Scala Async ★ 1074 ⧗ 5](https://github.com/scala/async)** - An asynchronous programming facility for Scala.
* [Scala Graph](http://www.scala-graph.org/) - A Scala library with basic graph functionality that seamlessly fits into the Scala standard collections library.
* [scala.meta](http://scalameta.org/) - A clean-room implementation of a metaprogramming toolkit for Scala.
* [Scalactic](http://www.scalactic.org/) - Small library of utilities related to quality that helps keeping code clear and correct.
* **[Scalaz ★ 4412 ⧗ 1](https://github.com/scalaz/scalaz)** - An extension to the core Scala library for functional programming.
* [scribe ★ 277 ⧗ 3](https://github.com/outr/scribe) - Practical logging framework that doesn't depend on any other logging framework and can be completely configured programmatically.
* **[Shapeless ★ 3103 ⧗ 1](https://github.com/milessabin/shapeless)** - A type class and dependent type based generic programming library for Scala.
* **[Simulacrum ★ 905 ⧗ 7](https://github.com/mpilquist/simulacrum)** - First class syntax support for type classes in Scala.
* [Squid ★ 172 ⧗ 25](https://github.com/epfldata/squid) - Type-safe metaprogramming framework with typed, hygienic quasiquotes.
* [Stateless Future ★ 178 ⧗ 185](https://github.com/qifun/stateless-future) - Asynchronous programming in fully featured Scala syntax.
* **[Twitter Util ★ 2415 ⧗ 0](https://github.com/twitter/util)** - General-purpose Scala libraries, including a future implementation and other concurrency tools.

## Misc

*Projects that don't fit into any specific category.*

* [Agora](https://gitlab.com/aossie/Agora/) - Library of vote-counting algorithms for elections.
* [Ammonite-REPL](http://lihaoyi.github.io/Ammonite/#Ammonite-REPL) - An improved Scala REPL: syntax highlighting, output formatting, multi-line input, and more.
* [ApiBuilder ★ 432 ⧗ 1](https://github.com/apicollective/apibuilder) - Simple, Comprehensive Tooling for Modern APIs 
* **[BootZooka ★ 577 ⧗ 0](https://github.com/softwaremill/bootzooka)** - Simple project to quickly start developing a web application using AngularJS and Akka HTTP, without the need to write login, user registration etc.
* **[Eclair ★ 871 ⧗ 2](https://github.com/ACINQ/eclair)** - ACINQ's Lightning Network implementation written in Scala.  Lightning Network is a second layer protocol built on top of bitcoin to address scalability, privacy, confirmation time and many other issues.
* [Fansi ★ 172 ⧗ 15](https://github.com/lihaoyi/fansi) - Scala/Scala.js library for manipulating Fancy Ansi colored strings
* [GoogleApiScala ★ 18 ⧗ 123](https://github.com/EckerdCollege/google-api-scala) - A simple scala library offering control of Google Drive, Calendar, and the Admin SDK.
* [mailgun4s ★ 14 ⧗ 13](https://github.com/outr/mailgun4s) - Scala wrapper around the Mailgun API
* [media4s ★ 23 ⧗ 10](https://github.com/outr/media4s) - Scala command-line wrapper around ffmpeg, ffprobe, ImageMagick, and other tools relating to media.
* [Miniboxing](https://github.com/miniboxing/miniboxing-plugin) - A Scala compiler plugin that improves program performance -- [see the project web site](http://scala-miniboxing.org) - Less boxes
* [Openquant ★ 73 ⧗ 0](https://github.com/openquant) - A Scala open source quantitative trading platform
* [Ostinato ★ 41 ⧗ 6](https://github.com/marianogappa/ostinato) - A chess library that runs on the server (Scala) and on the browser (ScalaJS)
* [Play Swagger ★ 371 ⧗ 9](https://github.com/iheartradio/play-swagger) - Automatically create Swagger documentation for your Play REST API
* [pprint ★ 124 ⧗ 24](https://github.com/lihaoyi/pprint) - Pretty-printer for Scala values and types for easier reading and debugging
* **[Prisma ★ 6930 ⧗ 0](https://github.com/prisma/prisma)** - Prisma turns your database into a realtime GraphQL API 
* **[PureConfig ★ 1067 ⧗ 0](https://github.com/melrief/pureconfig)** - A boilerplate-free Scala library for loading configuration files.
* [REPLesent ★ 405 ⧗ 2](https://github.com/marconilanna/REPLesent) - A presentation tool built inside the Scala REPL. Runs code straight from your slides with a single keystroke.
* [scala-debugger ★ 100 ⧗ 162](https://github.com/ensime/scala-debugger) - Scala libraries and tooling utilizing the Java Debugger Interface.
* [scala-ssh ★ 229 ⧗ 10](https://github.com/sirthias/scala-ssh) - Remote shell access via SSH for your Scala applications
* [Scalan ★ 93 ⧗ 4](https://github.com/scalan/scalan) - A framework for development of domain-specific compilers in Scala
* [ScalaSTM](https://nbronson.github.io/scala-stm/) - Software Transaction Memory for Scala
* [Scavenger](https://gitlab.com/aossie/Scavenger) - An experimental automated theorem prover.
* [Simple Scala Config ★ 46 ⧗ 259](https://github.com/ElderResearch/ssc) - Thin, idiomatic Scala wrapper around [Typesafe Config](https://github.com/typesafehub/config) with custom `Reader[T]` suppport.

## Android

*Scala libraries and wrappers for Android development.*

* **[Android SDK Plugin for SBT ★ 747 ⧗ 15](https://github.com/pfn/android-sdk-plugin)** - An sbt plugin that adds tasks for developing Android applications.
* [Gradle Android Scala Plugin ★ 344 ⧗ 117](https://github.com/saturday06/gradle-android-scala-plugin) - A gradle plugin that allows you to use Scala with Android
* **[Macroid ★ 538 ⧗ 11](https://github.com/47deg/macroid)** - A modular functional UI language for Android.
* **[Scaloid ★ 2104 ⧗ 4](https://github.com/pocorall/scaloid)** - Less painful Android development with Scala.

## HTTP

*Scala libraries and wrappers for HTTP clients.*

* **[Akka HTTP ★ 1137 ⧗ 0](https://github.com/akka/akka-http)** - The Streaming-first HTTP server/module of [Akka](https://github.com/akka/akka).
* [Dispatch ★ 435 ⧗ 68](https://github.com/dispatch/reboot) - Library for asynchronous HTTP interaction. It provides a Scala vocabulary for Java’s [async-http-client](https://github.com/AsyncHttpClient/async-http-client).
* **[Finch.io ★ 1509 ⧗ 18](https://github.com/finagle/finch)** - Purely Functional REST API atop of [Finagle](https://github.com/twitter/finagle).
* [Fintrospect ★ 37 ⧗ 0](http://fintrospect.io) - Implement fast, type-safe HTTP webservices for [Finagle](https://github.com/twitter/finagle).
* **[Http4s ★ 1938 ⧗ 1](https://github.com/http4s/http4s)** - A minimal, idiomatic Scala interface for HTTP.
* [jefe ★ 5 ⧗ 123](https://github.com/outr/jefe) - Manages installation, updating, downloading, launching, error reporting, proxying, multi-server management, and much more for your stand-alone and web applications.
* [lolhttp ★ 89 ⧗ 189](https://github.com/criteo/lolhttp) - An HTTP & HTTP/2 Server and Client library for Scala.
* [RösHTTP ★ 122 ⧗ 19](https://github.com/hmil/RosHTTP) - A lightweight asynchronous HTTP API built with Scala.js in mind. Supports the JVM and Node.js runtimes as well as most browsers.
* **[scalaj-http ★ 955 ⧗ 19](https://github.com/scalaj/scalaj-http)** - Simple scala wrapper for HttpURLConnection (including OAuth support).
* [Scalaxb ★ 297 ⧗ 11](https://github.com/eed3si9n/scalaxb) - An XML data-binding tool for Scala that supports W3C XML Schema (xsd) and Web Services Description Language (wsdl) as the input file.
* [Spray](http://spray.io/) - Actor-based library for http interaction.
* **[sttp ★ 1025 ⧗ 1](https://github.com/softwaremill/sttp)** - The Scala HTTP client you always wanted!

## Semantic Web

*Scala libraries for interactions with the Web of Data, and other RDF tools.*

* [Banana-RDF ★ 261 ⧗ 7](https://github.com/banana-rdf/banana-rdf) - Scala-friendly abstractions for RDF and Linked Data technologies. Supports Jena, Sesame and native Scala.
* [Scowl ★ 43 ⧗ 32](https://github.com/phenoscape/scowl) - Scala DSL allowing a declarative approach to composing OWL expressions and axioms using the OWL API.

## Metrics and Monitoring

*Scala libraries for gathering metrics and monitoring applications.*

* [Kamon](http://kamon.io) - Gathering metrics from applications built with Akka, Spray and Play! with support for user metrics as well.
* [Metrics-Scala ★ 417 ⧗ 3](https://github.com/erikvanoosten/metrics-scala) - Scala API for Dropwizard's Metrics library.

## Parsing

*Scala libraries for creating parsers.*

* [atto ★ 337 ⧗ 21](https://github.com/tpolecat/atto) - Pure functional incremental text parsing library for Scala, based on Attoparsec.
* [CLIST ★ 100 ⧗ 51](https://github.com/backuity/clist) - Command Line Interface Scala Toolkit
* [decline ★ 429 ⧗ 5](https://github.com/bkirwi/decline) - composable command-line parser for Scala, built on Cats
* **[Fast Parse ★ 923 ⧗ 0](https://github.com/lihaoyi/fastparse)** - Fast to write, Fast running Parsers in Scala
* **[Parboiled2 ★ 656 ⧗ 2](https://github.com/sirthias/parboiled2)** - A Fast Parser Generator for Scala 2.10.3+.
* **[Scala Parser Combinators ★ 505 ⧗ 0](https://github.com/scala/scala-parser-combinators)** - Scala Standard Parser Combinator Library.
* **[Scopt ★ 1248 ⧗ 0](https://github.com/scopt/scopt)** - Simple scala command line options parsing.

## Sbt plugins

*Sbt plugins to make your life easier.*

* [coursier ★ 2 ⧗ 74](https://github.com/alexarchambault/coursier) - A Scala library to fetch dependencies from Maven / Ivy repositories
* [sbt-api-mappings ★ 76 ⧗ 118](https://github.com/ThoughtWorksInc/sbt-api-mappings) - A Sbt plugin that resolves external API links to common Scala libraries.
* [sbt-buildinfo ★ 476 ⧗ 1](https://github.com/sbt/sbt-buildinfo) - Generates Scala source from build definition.
* **[sbt-dependency-graph ★ 1214 ⧗ 8](https://github.com/jrudolph/sbt-dependency-graph)** - Create a dependency graph for your project.
* **[sbt-docker ★ 683 ⧗ 1](https://github.com/marcuslonnberg/sbt-docker)** - Create Docker images directly from sbt
* [sbt-doctest ★ 168 ⧗ 2](https://github.com/tkawachi/sbt-doctest) - Plugin for sbt that generates tests from examples in ScalaDoc.
* [sbt-ensime ★ 242 ⧗ 35](https://github.com/ensime/ensime-sbt) - Generates .ensime config files for SBT projects [http://ensime.org/build_tools/sbt](http://ensime.org/build_tools/sbt)
* [sbt-groll ★ 129 ⧗ 101](https://github.com/sbt/sbt-groll) - sbt plugin to roll the Git history.
* [sbt-hepek ★ 16 ⧗ 276](https://github.com/sake92/sbt-hepek) - Make static websites in Scala code (render `object` to file!).
* [sbt-ide-settings ★ 45 ⧗ 4](https://github.com/Jetbrains/sbt-ide-settings) - SBT plugin for tweaking various IDE settings
* **[sbt-native-packager ★ 1410 ⧗ 0](https://github.com/sbt/sbt-native-packager)** - Bundle up Scala software for native packaging systems, like deb, rpm, homebrew, msi..
* [sbt-pack ★ 435 ⧗ 8](https://github.com/xerial/sbt-pack) - A sbt plugin for creating distributable Scala packages.
* **[sbt-revolver ★ 757 ⧗ 8](https://github.com/spray/sbt-revolver)** - Fork & Stop processes from sbt.
* [sbt-robovm ★ 108 ⧗ 92](https://github.com/roboscala/sbt-robovm) - An sbt plugin for iOS development in Scala
* [sbt-scala-js-map ★ 26 ⧗ 58](https://github.com/ThoughtWorksInc/sbt-scala-js-map) - A sbt plugin that configures source mapping for Scala.js projects hosted on Github
* [sbt-sublime ★ 139 ⧗ 182](https://github.com/orrsella/sbt-sublime) - Create Sublime Text projects with library dependencies sources
* **[sbt-updates ★ 644 ⧗ 12](https://github.com/rtimush/sbt-updates)** - Shows sbt project's dependency updates.
* **[sbteclipse ★ 727 ⧗ 45](https://github.com/typesafehub/sbteclipse)** - Create Eclipse project definitions from sbt builds.
* [scala-clippy ★ 310 ⧗ 1](https://github.com/softwaremill/scala-clippy) - Good advice and coloring for Scala compiler errors
* [ScalaKata2 ★ 99 ⧗ 100](https://github.com/MasseGuillaume/ScalaKata2) - Scala playground & Documentation tool.
* [splain ★ 350 ⧗ 10](https://github.com/tek/splain) - Better implicit errors for Scala.
* **[tut ★ 595 ⧗ 6](https://github.com/tpolecat/tut)** - Tool for writing documentation with typechecked examples.
* [xsbt-web-plugin ★ 380 ⧗ 6](https://github.com/earldouglas/xsbt-web-plugin) - Build enterprise J2EE Web applications in Scala.

## XML / HTML

*XML and HTML generation and processing*

* **[scala-scraper ★ 616 ⧗ 4](https://github.com/ruippeixotog/scala-scraper)** - A library for scraping content from HTML pages.

## Markdown

* [Laika ★ 161](https://github.com/planet42/Laika) - Text Markup Transformer for sbt and Scala applications, transforming Markdown and reStructuredText to HTML and PDF.


## Learning Scala

*Nice books, blogs and other resources to learn Scala*

* [A Tour of Scala](http://docs.scala-lang.org/tour/tour-of-scala.html) - Bite-sized introductions to some of the core language concepts.
* **[Demos and Examples in Scala (Chinese) ★ 1064 ⧗ 3](https://github.com/jacksu/utils4s)** - repo of sample Scala library usage, written in Chinese
* [Essential Scala](https://underscore.io/books/essential-scala/) - None
* [Exercism - Scala Exercises](http://exercism.io/languages/scala/exercises) - Community-driven Scala exercises.
* [Functional Programming for Mortals](https://leanpub.com/fpmortals/read) - None
* [Functional Programming in Scala](https://www.coursera.org/specializations/scala) - Coursera Specialization (5 courses) created by  Martin Odersky et al. at the EPFL (Ecole polytechnique fédérale de Lausanne).
* [Functional Works / Learn](https://functional.works-hub.com/learn/) - Quality resources maintained by functional works
* [Get Programming with Scala](https://www.manning.com/books/get-programming-with-scala) - Tutorial-driven introduction to Scala
* [Introduction to programming with dependent types in Scala](https://stepik.org/course/2294/) - Video Course by Dmytro Mitin
* **[Learn-by-doing functional programming course on Scala ★ 531 ⧗ 24](https://github.com/dehun/learn-fp/)** - Covers type classes, functors, applicatives, monads, monad transformers, free monad
* [Programming Community Curated Resources for Learning Scala](https://hackr.io/tutorials/learn-scala) - None
* [Reactive Programming with Scala and Akka](http://www.foxebook.net/reactive-programming-with-scala-and-akka/) - Use the concepts of reactive programming to build distributed systems running on multiple nodes
* [Resources by [Dr. Mark Lewis](http://www.cs.trinity.edu/~mlewis/) >> [Website](http://www.programmingusingscala.net/) | [Youtube Playlists](https://www.youtube.com/user/DrMarkCLewis/playlists) - None
* [Scala Collections Cookbook](http://colobu.com/ScalaCollectionsCookbook/) - Scala collections introduction. written in Chinese.
* [Scala Exercises](http://scala-exercises.47deg.com/) - Brings the popular Scala Koans to the web. Offering hundreds of solvable exercises organized into 42 categories covering the basics of the Scala language.
* [Scala for the Impatient 2nd Edition](https://horstmann.com/scala/) - Covers most Scala features with short and easy to understand explainations.
* [Scala in Depth](https://www.manning.com/books/scala-in-depth) - None
* [Scala school](https://twitter.github.io/scala_school/) - Scala school started as a series of lectures at Twitter to prepare experienced engineers to be productive Scala programmers.
* [Scala With Cats](https://underscore.io/books/scala-with-cats/) - Learn system architecture and design using the techniques of modern functional programming with [Cats](https://typelevel.org/cats/) - None
* [Scalera Blog](http://www.scalera.es) - Blog about Scala language and its environment (howto's, good practices, tips,...). Weekly posts written in both spanish and english
* [The Neophyte's Guide to Scala](http://danielwestheide.com/scala/neophytes.html) - None
* [The Type Astronaut's Guide to Shapeless](https://underscore.io/books/shapeless-guide/) - None

## JavaScript

*JavaScript generation and interop libraries.*

* [scala-js-fiddle](http://www.scala-js-fiddle.com/) ([repo](https://github.com/lihaoyi/scala-js-fiddle)) - Browser-based Scala.js playground
* [Scala.js](http://www.scala-js.org/) ([repo](https://github.com/scala-js/scala-js)) - Scala to JavaScript compiler

## Scheduling

* [akka-quartz-scheduler ★ 365](https://github.com/enragedginger/akka-quartz-scheduler) - Quartz Extension and utilities for cron-style scheduling in Akka.


## Templating

*Web templating engines.*

* [Beard ★ 113 ⧗ 19](https://github.com/zalando/beard) - lightweight logicless templating engine inspired by Mustache
* **[Scalatags ★ 659 ⧗ 11](https://github.com/lihaoyi/scalatags)** - Write html as scala code and have your IDE syntax check it.
* **[Scalate ★ 560 ⧗ 1](https://github.com/scalate/scalate)** - Scala based template engine which supports HAML, Mustache and JSP, Erb and Velocity style syntaxes
* [Twirl ★ 495 ⧗ 11](https://github.com/playframework/twirl) - The Play Scala Template Compiler

## Tools

* [Scalafix]https://github.com/scalacenter/scalafix) - Refactoring and linting tool

* [Codacy](https://www.codacy.com/) - Automated Code Reviews for Scala
* [fast-string-interpolator ★ 63 ⧗ 6](https://github.com/Sizmek/fast-string-interpolator) - Scala macro that generates ultra-fast string interpolators
* [Fastring ★ 123 ⧗ 78](https://github.com/Atry/fastring) - Extremely fast string formatting
* **[Gitbucket ★ 8220 ⧗ 0](https://github.com/gitbucket/gitbucket)** - The easily installable GitHub clone powered by Scala
* [Giter8](http://www.foundweekends.org/giter8/) - command line tool to generate files and directories from templates published on Github
* [Hepek ★ 75 ⧗ 3](https://github.com/sake92/hepek) - Static content generator for developers. Intuitive, scalable, powerful. 
* [Mill](http://www.lihaoyi.com/mill/) - A better Scala build tool
* [sbt](http://www.scala-sbt.org/) ([repo](https://github.com/sbt/sbt)) - The interactive build tool for Scala
* [Scala @LibHunt](https://scala.libhunt.com) - The go-to Scala Toolbox.
* [scala-trace-debug ★ 110 ⧗ 33](https://github.com/JohnReedLOL/scala-trace-debug) - Multithreaded print debug tool
* [Scalariform ★ 114 ⧗ 11](https://github.com/daniel-trinh/scalariform) - Scala source code formatter
* **[Scalastyle ★ 680 ⧗ 11](https://github.com/scalastyle/scalastyle)** - Scala style checker.
* [Scalatex ★ 285 ⧗ 17](https://github.com/lihaoyi/Scalatex) - Programmable, Typesafe Document Generation
* [Scapegoat ★ 398 ⧗ 1](https://github.com/sksamuel/scapegoat) - Scala compiler plugin for static code analysis
* [Scaps](http://scala-search.org/) ([repo](https://github.com/scala-search/scaps)) - A search engine for Scala libraries
* [Scoverage](https://github.com/scoverage) - Scala Code Coverage tool
* **[Wartremover ★ 944 ⧗ 0](https://github.com/puffnfresh/wartremover)** - Wartremover a flexible Scala code linting tool

## Geospatial

*Libraries to aid with geospatial calculations and artifacts.*

* **[Geotrellis ★ 1105 ⧗ 0](https://github.com/locationtech/geotrellis)** - Scalable raster toolkit for GIS processing
* [osm4scala ★ 46 ⧗ 12](https://github.com/angelcervera/osm4scala) - OpenStreetMap PBF2 file parser
* [rtree2d ★ 91 ⧗ 2](https://github.com/Sizmek/rtree2d) - RTree2D is a 2D immutable R-tree with STR (Sort-Tile-Recursive) packing for ultra-fast nearest and intersection queries on plane and spherical surfaces
* [sfcurve ★ 63 ⧗ 5](https://github.com/locationtech/sfcurve) - Space filling curves in Scala for geospatial indexing and query

## Devops

*DevOps related tools and libraries.*

* [Orkestra ★ 104 ⧗ 28](https://github.com/Orkestra-Tech/orkestra) - Functional DevOps with Scala and Kubernetes
* [Skuber ★ 280 ⧗ 9](https://github.com/doriordan/skuber) - Kubernetes client in Scala

# Resources

Where to discover new Scala libraries.

## Podcasts

* [CoRecursive Interviews](https://corecursive.com/) - In-depth Interviews with software developers, often on the subject of scala libraries and functional programming.

## Newsletters

* [Scala Times](https://scalatimes.com/) - Weekly newsletter about scala

# Contributing

Your contributions are always welcome! Please submit a pull request or create an issue to add a new framework, library or software to the list. Do not submit a project that hasn’t been updated in the past 6 months or is not awesome.

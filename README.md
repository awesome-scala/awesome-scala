
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

* [CIlibtutorial ★ 4 ⧗ 247](https://github.com/cirg-up/cilib-tutorial) - A tutorial book for cilib.

## Databases

*Databases implemented in Scala.*

* **[Atlas ★ 2413 ⧗ 0](https://github.com/Netflix/atlas)** - In-memory dimensional time series database built by Netflix.
* **[FiloDB ★ 1121 ⧗ 1](https://github.com/filodb/FiloDB)** - Prometheus-compatible distributed time series database.
* [L-space ★ 3 ⧗ 18](https://github.com/L-space/L-space) - A pure Scala (and Scala.js) Linked Data graph computing framework, database (both in-memory and persistent) and rest-APIs (support for Json-ld).
* [SwayDB](http://www.swaydb.io/) - A Type-safe & non-blocking key-value storage library for single/multiple disks and in-memory storage.

## Database Access

*Database access libraries in Scala.*

* [Anorm ★ 177 ⧗ 3](https://github.com/playframework/anorm) - Simple SQL data access.
* [Casbah](http://mongodb.github.io/casbah/) ([repo](https://github.com/mongodb/casbah)) - Officially supported Scala driver for MongoDB
* [CouchDB-Scala ★ 63 ⧗ 15](https://github.com/beloglazov/couchdb-scala) - Purely functional Scala client for CouchDB
* **[doobie ★ 1461 ⧗ 0](https://github.com/tpolecat/doobie)** - Pure functional JDBC layer for Scala.
* **[Elastic4s ★ 1367 ⧗ 1](https://github.com/sksamuel/elastic4s)** - A scala DSL / reactive client for Elasticsearch
* [Finagle ★ 64 ⧗ 38](https://github.com/finagle/finagle-postgres) - PostgreSQL protocol support for Finagle
* [longevity ★ 99 ⧗ 14](https://github.com/longevityframework/longevity) - A Persistence Framework for Scala and NoSQL with a Domain Driven Design Orientation
* [lucene4s ★ 33 ⧗ 17](https://github.com/outr/lucene4s) - Light-weight convenience wrapper around Lucene to simplify complex tasks and add Scala sugar.
* [Memcontinuationed ★ 52 ⧗ 95](https://github.com/Atry/memcontinuationed) - Memcached client for Scala.
* [Morpheus ★ 100 ⧗ 38](https://github.com/outworkers/morpheus) - Reactive type safe Scala Driver for MySQL/Postgres.
* [neo4akka ★ 16 ⧗ 50](https://github.com/outr/neo4akka) - Neo4j Scala client using Akka HTTP with compile-time query interpolation, case class support, true non-blocking IO, and much more.
* **[Phantom ★ 1021 ⧗ 3](https://github.com/outworkers/phantom)** - Reactive typed Scala driver for Apache Cassandra.
* **[PostgreSQL and MySQL async ★ 1399 ⧗ 3](https://github.com/mauricio/postgresql-async)** - Async database drivers to talk to PostgreSQL and MySQL in Scala.
* [Pulsar4s ★ 102 ⧗ 2](https://github.com/sksamuel/pulsar4s) - Scala client for Apache Pulsar.
* **[Quill ★ 1455 ⧗ 1](https://github.com/getquill/quill)** - Compile-time Language Integrated Query for Scala
* [ReactiveCouchbase](http://reactivecouchbase.org/) - Reactive Scala Driver for Couchbase. Also includes a Play plug-in. An official plug-in is also in development.
* **[ReactiveMongo ★ 797 ⧗ 2](https://github.com/ReactiveMongo/ReactiveMongo)** - Reactive Scala Driver for MongoDB.
* **[rediscala ★ 761 ⧗ 6](https://github.com/etaty/rediscala)** - Non-blocking, Reactive Redis driver for Scala (with Sentinel support)
* [Relate ★ 158 ⧗ 5](https://github.com/lucidsoftware/relate) - Lightweight, blazing-fast database access layer for Scala that abstracts the idiosyncricies of the JDBC while keeping complete control over the SQL.
* [Salat ★ 492 ⧗ 1](https://github.com/salat/salat/) - ORM for MongoDB. A related Play-plugin is also available.
* [Scala ActiveRecord ★ 317 ⧗ 31](https://github.com/aselab/scala-activerecord) - ORM library for scala, inspired by ActiveRecord of Ruby on Rails.
* [Scala-Forklift ★ 159 ⧗ 5](https://github.com/lastland/scala-forklift) - Type-safe database migration for Slick, Git, etc.
* **[scala-redis ★ 926 ⧗ 1](https://github.com/debasishg/scala-redis)** - A Scala library for connecting to a redis server, with clustering support
* [scala-sql ★ 55 ⧗ 29](https://github.com/wangzaixiang/scala-sql) - Yet another SQL-based DB access library for scala language
* [ScalaRelational ★ 53 ⧗ 99](https://github.com/outr/scalarelational) - Type-Safe framework for defining, modifying, and querying SQL databases.
* **[ScalikeJDBC ★ 1015 ⧗ 2](https://github.com/scalikejdbc/scalikejdbc)** - A tidy SQL-based DB access library for Scala developers.
* [Scanamo ★ 225 ⧗ 6](https://github.com/guardian/scanamo) - A library to make using DynamoDB with Scala simpler and less error-prone.
* [scredis ★ 154 ⧗ 131](https://github.com/Livestream/scredis) - Non-blocking Redis client built on top of Akka IO (used by Livestream)
* [Shade ★ 104 ⧗ 4](https://github.com/alexandru/shade) - Memcached client for Scala, based on Spymemcached
* **[Slick ★ 2251 ⧗ 0](https://github.com/slick/slick)** - Modern database query and access library for Scala.
* [Sorm ★ 237 ⧗ 45](https://github.com/sorm/sorm) - A functional boilerplate-free Scala ORM.
* **[Squeryl ★ 531 ⧗ 4](https://github.com/squeryl/squeryl)** - A Scala DSL for talking with databases with minimum verbosity and maximum type safety.
* [Tepkin ★ 83 ⧗ 231](https://github.com/fehmicansaglam/tepkin) - Reactive MongoDB Driver for Scala built on top of Akka IO and Akka Streams.

## Messaging

* [Op-Rabbit ★ 228 ⧗ 18](https://github.com/SpinGo/op-rabbit) - High-level messaging library for Akka and Op-Rabbit.

## Graphical User Interfaces

*Libraries for creation of graphical user interfaces*

* [ScalaFX](http://www.scalafx.org/) - Scala DSL for creating Graphical User Interfaces that sits on top of JavaFX.

## Web Frameworks

*Scala frameworks for web development.*

* [Analogweb ★ 11 ⧗ 56](https://github.com/analogweb/analogweb-scala) - Tiny, simple, and pluggable web framework in Scala.
* [Chaos ★ 238 ⧗ 33](https://github.com/mesosphere/chaos) - A lightweight framework for writing REST services in Scala.
* **[Colossus ★ 811 ⧗ 70](http://tumblr.github.io/colossus/)** - lightweight framework for building high-performance applications in Scala that require non-blocking network I/O.
* **[Finatra ★ 1932 ⧗ 0](https://github.com/twitter/finatra)** - A sinatra-inspired web framework for scala, running on top of Finagle.
* **[Lift ★ 1191 ⧗ 1](https://github.com/lift/framework)** - Secure and powerful full stack web framework ([discussion](https://github.com/lauris/awesome-scala/pull/19)).
* [peregine ★ 11 ⧗ 155](https://github.com/dvarelap/peregrine) - A simple and async lightweight Scala web framework.
* **[Play ★ 11239 ⧗ 0](https://github.com/playframework/playframework)** - Makes it easy to build scalable, fast and real-time web applications with Java & Scala.
* [Play Pagelets ★ 72 ⧗ 42](https://github.com/splink/pagelets) - A Module for the Play Framework to build resilient and modular Play applications in an elegant and concise manner.
* [Reactive ★ 206 ⧗ 18](https://github.com/nafg/reactive) - FRP and web abstractions, which can be plugged into any web framework (currently only has bindings for Lift).
* **[Scalatra ★ 2398 ⧗ 1](https://github.com/scalatra/scalatra)** - Tiny Scala high-performance, async web framework, inspired by Sinatra.
* **[Skinny Framework ★ 702 ⧗ 8](https://github.com/skinny-framework/skinny-framework)** - A full-stack web app framework upon Scalatra for rapid Development in Scala.
* [suzaku ★ 105 ⧗ 74](https://github.com/suzaku-io/suzaku) - Suzaku web UI framework for Scala
* **[Unfiltered ★ 704 ⧗ 10](https://github.com/unfiltered/unfiltered)** - A modular set of unopinionated primitives for servicing HTTP and WebSocket requests in Scala.
* [Xitrum](http://xitrum-framework.github.io/) - An async and clustered Scala web framework and HTTP(S) server fusion on top of Netty, Akka, and Hazelcast.
* [youi ★ 163 ⧗ 0](https://github.com/outr/youi) - Next generation user interface framework and server engine for Scala and Scala.js.

## Reactive Web Frameworks

*Scala libraries for Reactive Web development*

* **[Binding.scala ★ 1416 ⧗ 4](https://github.com/ThoughtWorksInc/Binding.scala)** - A reactive web framework. It enables you use native XML literal syntax to create reactive DOM nodes, which are able to automatically change whenever the data source changes.
* **[Korolev ★ 935 ⧗ 0](http://github.com/fomkin/korolev/)** - Modern single-page applications running on the server side
* [Udash](http://udash.io/) - a web framework based on Scala.js with support for property bindings, frontend routing, i18n and much more. It also provides strongly typed client<->server RPC system based on WebSockets.
* [Vert.x Web](http://vertx.io/docs/vertx-web/scala/) - Toolkit to build Reactive web applications..
* [Widok](https://widok.github.io/) - Reactive web framework for the JVM and Scala.js

## Data Binding and Validation

*Scala libraries for data binding and validation*

* [Accord ★ 482 ⧗ 0](https://github.com/wix/accord) - A sane validation library for Scala
* [Monkeytail ★ 84 ⧗ 60](https://github.com/sksamuel/monkeytail) - A set of validation macros and helpers for cats.Validated
* [Octopus ★ 74 ⧗ 1](https://github.com/krzemin/octopus) - Scala library for boilerplate-free validation

## i18n

*Scala libraries for i18n.*

* [scala-xgettext ★ 23 ⧗ 52](https://github.com/xitrum-framework/scala-xgettext) - A compiler plugin that acts like GNU xgettext command to extract i18n strings in Scala source code files to Gettext .po file.
* [Scaposer ★ 34 ⧗ 16](https://github.com/xitrum-framework/scaposer) - GNU Gettext .po file loader for Scala.

## Authentication

*Libraries for implementing authentications schemes.*

* [akka-http-session ★ 391 ⧗ 2](https://github.com/softwaremill/akka-http-session) - Web&mobile client-side sessions for akka-http based applications, with optional JWT support
* [AWS Request Signer ★ 18 ⧗ 16](https://github.com/ticofab/aws-request-signer) - Helper to evaluate the signing headers for HTTP requests to Amazon Web Services.
* [OAuth2-mock-play ★ 21 ⧗ 295](https://github.com/zalando/OAuth2-mock-play) - Implementation of an OAuth2 server designed for mocking/testing and configurable by environment variables (by use of the Typesafe config).
* [Play Google Auth Module ★ 30 ⧗ 17](https://github.com/guardian/play-googleauth) - A very simple implementation of Google OpenID Connect authentication for Play 2 applications.
* [play-pac4j ★ 345 ⧗ 7](https://github.com/pac4j/play-pac4j) - Security library managing authentication (CAS, OAuth, OpenID, SAML, LDAP, SQL, JWT...), authorizations and logout for Play 2.x in Java and Scala.
* **[play-silhouette ★ 780 ⧗ 2](https://github.com/mohiva/play-silhouette)** - Authentication library for Play Framework applications that supports several authentication methods, including OAuth1, OAuth2, OpenID, Credentials or custom authentication schemes.
* **[play2-auth ★ 624 ⧗ 1](https://github.com/t2v/play2-auth)** - Play2.x Authentication and Authorization module.
* [scala-oauth2-provider ★ 499 ⧗ 5](https://github.com/nulab/scala-oauth2-provider) - OAuth 2.0 server-side implementation written in Scala.
* **[SecureSocial ★ 1205 ⧗ 0](https://github.com/jaliss/securesocial)** - A module that provides OAuth, OAuth2 and OpenID authentication for Play Framework applications.

## Authorization

*Libraries for implementing authorization strategies.*

* **[deadbolt-2 ★ 500 ⧗ 31](https://github.com/schaloner/deadbolt-2)** - A Play 2.x module supporting role-based and proprietary authorization; idiomatic APIs for Scala and Java APIs are provided.

## Cryptography

*Cryptography and Encryption Libraries.*

* [Scrypto ★ 156 ⧗ 5](https://github.com/ScorexProject/scrypto) - All-purpose cryptographic framework.
* [TSec ★ 265 ⧗ 0](https://github.com/jmcardon/tsec) - Type-safe, functional, general-cryptography library

## Testing

*Libraries for code testing.*

* [cornichon ★ 173 ⧗ 2](https://github.com/agourlay/cornichon) - Scala DSL for testing HTTP JSON API.
* [Gatling](http://gatling.io) - Async Scala-Akka-Netty based Stress Tool.
* [Minitest ★ 132 ⧗ 4](https://github.com/monix/minitest) - A testing framework with a focus on simplicity.
* **[ScalaCheck ★ 1533 ⧗ 0](https://github.com/rickynils/scalacheck)** - Property-based testing for Scala.
* [ScalaMeter](https://scalameter.github.io/) - Performance &  memory footprint measuring, regression testing.
* [ScalaMock](http://scalamock.org) - Scala native mocking framework
* [scalaprops ★ 248 ⧗ 8](https://github.com/scalaprops/scalaprops) - Another property based testing library for Scala
* **[ScalaTest ★ 836 ⧗ 0](https://github.com/scalatest/scalatest)** - A testing tool for Scala and Java developers.
* [Scalive ★ 201 ⧗ 120](https://github.com/xitrum-framework/scalive) - Connect a Scala REPL to running JVM processes without any prior setup; this library is used for inspecting systems in production mode.
* **[Specs2 ★ 655 ⧗ 4](https://github.com/etorreborre/specs2)** - Software Specifications for Scala.
* [Stryker4s ★ 75 ⧗ 1](https://github.com/stryker-mutator/stryker4s) - Test your tests with mutation testing.
* [testcontainers-scala ★ 209 ⧗ 0](https://github.com/testcontainers/testcontainers-scala) - Docker containers for testing in Scala.
* [µTest ★ 376 ⧗ 0](https://github.com/lihaoyi/utest) - A tiny, portable testing library for Scala.

## JSON

*Libraries for work with json.*

* [argonaut](http://argonaut.io/) - Purely Functional JSON in Scala.
* **[circe ★ 1721 ⧗ 1](https://github.com/travisbrown/circe)** - JSON library based on Argonaut, depends on Cats
* [diffson ★ 201 ⧗ 0](https://github.com/gnieh/diffson) - A scala diff/patch library for Json
* [jackson-module-scala ★ 388 ⧗ 1](https://github.com/FasterXML/jackson-module-scala) - Add-on module for Jackson to support Scala-specific datatypes.
* [jawn ★ 353 ⧗ 6](https://github.com/non/jawn) - Fast json parser (According to them, competetive with java gson/jackson speed).
* **[json4s ★ 1198 ⧗ 0](https://github.com/json4s/json4s)** - Project aims to provide a single AST to be used by other scala json libraries.
* [jsoniter-scala ★ 245 ⧗ 0](https://github.com/plokhotnyuk/jsoniter-scala) - Scala macros for compile-time generation of ultra-fast JSON codecs.
* [play-json ★ 204 ⧗ 4](https://github.com/playframework/play-json) - Flexible and powerful JSON manipulation, validation and serialization, with no reflection at runtime.
* [Pushka ★ 76 ⧗ 37](https://github.com/fomkin/pushka) - Scala JSON serialization library with annotations.
* [qbproject](https://github.com/qb-project/qbproject) - Scala Libs around JSON and API developement for Play Framework.
* [rapture-json](https://github.com/propensive/rapture/blob/dev/doc/json.md) - Clean, intuitive, unintrusive, boilerplate-free Scala API
* [sbt-json ★ 29 ⧗ 28](https://github.com/battermann/sbt-json) - sbt plugin that generates Scala case classes for easy, statically typed and implicit access of JSON documents
* [scala-jsonapi ★ 108 ⧗ 43](https://github.com/scala-jsonapi/scala-jsonapi) - Support library for integrating the JSON API spec with Scala and Spray JSON, Play! JSON or Circe.
* [scalajack ★ 92 ⧗ 29](https://github.com/gzoller/ScalaJack) - Fast 'n easy JSON serialization with optional MongoDB support.  Uses Jackson under the hood.
* **[spray-json ★ 842 ⧗ 5](https://github.com/spray/spray-json)** - Lightweight, clean and efficient JSON implementation in Scala.
* [uJson](http://www.lihaoyi.com/upickle/#uJson) - fast, flexible and intuitive JSON for Scala

## YAML

*Libraries for work with YAML.*

* [MoultingYAML ★ 71 ⧗ 2](https://github.com/jcazevedo/moultingyaml) - Type-class based YAML serialization and deserialization on top of SnakeYAML.

## CSV

*Libraries for work with CSV.*

* [fm-flatfile ★ 8 ⧗ 95](https://github.com/frugalmechanic/fm-flatfile) - Very flexible, Flat File (CSV, TSV, Excel, etc) Reader for Scala.
* [kantan.csv ★ 262 ⧗ 37](https://github.com/nrinaudo/kantan.csv) - CSV handling library for Scala with multiple backends.
* **[Scala-CSV ★ 538 ⧗ 1](https://github.com/tototoshi/scala-csv)** - CSV Reader/Writer for Scala.

## Serialization

*Libraries for serializing and deserializing data for storage or transport.*

* [avro-codegen](https://github.com/Nitro/avro-codegen) - Code generation from avro schemas to serialize/deserialize avro messages, no runtime reflection.
* **[Chill ★ 509 ⧗ 0](https://github.com/twitter/chill)** - Extensions for the Kryo serialization library to ease configuration in systems like Hadoop and Storm.
* [msgpack ★ 87 ⧗ 45](https://github.com/msgpack/msgpack-scala) - A efficient binary serialization library.
* **[Pickling ★ 855 ⧗ 1](https://github.com/scala/pickling)** - Fast, customizable, boilerplate-free pickling support.
* [ScalaBuff ★ 223 ⧗ 8](https://github.com/SandroGrzicic/ScalaBuff) - a Scala Protocol Buffers (protobuf) compiler
* **[ScalaPB ★ 705 ⧗ 51](https://scalapb.github.io/)** - Protocol Buffers and gRPC support for Scala
* **[scodec ★ 629 ⧗ 0](https://github.com/scodec/scodec)** - A combinator library for working with binary data.
* [Scrooge](http://twitter.github.io/scrooge/) - An Apache Thrift code generator for Scala.
* [validation ★ 193 ⧗ 3](https://github.com/jto/validation) - Advanced validation & serialization for JSON, HTML form data, etc, with no reflection at runtime.
* [µPickle](http://lihaoyi.github.io/upickle/) - A lightweight serialization library for Scala that works in ScalaJS, allowing transfer of structured data between the JVM and JavaScript.

## Science and Data Analysis

*Libraries for scientific computing, data analysis and numerical processing.*

* **[Algebird ★ 1873 ⧗ 0](https://github.com/twitter/algebird)** - Abstract Algebra for Scala.
* [Axle ★ 62 ⧗ 57](https://github.com/axlelang/axle) - A Spire-based DSL for scientific cloud computing.
* **[BigDL ★ 3100 ⧗ 1](https://github.com/intel-analytics/BigDL)** - BigDL is a distributed deep learning library for Apache Spark.
* **[Breeze ★ 2919 ⧗ 0](https://github.com/scalanlp/breeze)** - Breeze is a numerical processing library for Scala.
* [Chalk ★ 265 ⧗ 41](https://github.com/scalanlp/chalk) - Chalk is a natural language processing library.
* [doddle-model ★ 110 ⧗ 2](https://github.com/picnicml/doddle-model) - An in-memory machine learning library built on top of Breeze. It provides immutable objects and exposes its functionality through a scikit-learn-like API.
* **[FACTORIE ★ 552 ⧗ 16](https://github.com/factorie/factorie)** - A toolkit for deployable probabilistic modeling, implemented as a software library in Scala.
* **[Figaro ★ 683 ⧗ 1](https://github.com/p2t2/figaro)** - Figaro is a probabilistic programming language that supports development of very rich probabilistic models.
* [Libra ★ 176 ⧗ 5](https://github.com/to-ithaca/libra) - Libra is a dimensional analysis library based on shapeless, spire and singleton-ops. It contains out of the box support for SI units for all numeric types.
* [MGO ★ 59 ⧗ 0](https://github.com/openmole/mgo) - Modular multi-objective evolutionary algorithm optimization library enforcing immutability.
* [MLLib](https://spark.apache.org/mllib/) - Machine Learning framework for Spark
* [ND4S ★ 299 ⧗ 15](https://github.com/deeplearning4j/nd4s) - N-Dimensional arrays and linear algebra for Scala with an API similar to Numpy.  ND4S is a scala wrapper around [ND4J](http://nd4j.org/).
* [Numsca ★ 82 ⧗ 28](https://github.com/botkop/numsca) - Numsca is Numpy for Scala.
* [OpenMOLE ★ 106 ⧗ 1](https://github.com/openmole/openmole) - OpenMOLE (Open MOdeL Experiment) is a workflow engine designed to leverage the computing power of distributed execution environments for naturally parallel processes.
* [OscaR](https://bitbucket.org/oscarlib/oscar/wiki/Home) - a Scala toolkit for solving Operations Research problems
* **[PredictionIO ★ 11851 ⧗ 0](https://github.com/PredictionIO/PredictionIO)** - machine learning server for developers and data scientists. Built on Apache Spark, HBase and Spray
* [Rings ★ 39 ⧗ 2](https://github.com/PoslavskySV/rings) - An efficient library for polynomial rings. Commutative algebra, polynomial GCDs, polynomial factorization and other sci things at a really high speed.
* **[Saddle ★ 502 ⧗ 10](https://github.com/saddle/saddle)** - A minimalist port of Pandas to Scala
* [Smile](http://haifengl.github.io/smile/) - Statistical Machine Intelligence and Learning Engine. Smile is a fast and comprehensive machine learning system.
* **[Spark Notebook ★ 2806 ⧗ 5](https://github.com/andypetrella/spark-notebook)** - Scalable and stable Scala and Spark focused notebook bridging the gap between JVM and Data Scientists (incl. extendable, typesafe and reactive charts).
* **[Spire ★ 1513 ⧗ 0](https://github.com/non/spire)** - Powerful new number types and numeric abstractions for Scala.
* **[Squants ★ 630 ⧗ 3](https://github.com/garyKeorkunian/squants)** - The Scala API for Quantities, Units of Measure and Dimensional Analysis.
* [SwiftLearner ★ 33 ⧗ 20](https://github.com/valdanylchuk/swiftlearner) - Simply written algorithms to help study Machine Learning or write your own implementations.
* **[Tensorflow_scala ★ 675 ⧗ 1](https://github.com/eaplatanios/tensorflow_scala)** - TensorFlow API for the Scala Programming Language
* [Tyche ★ 96 ⧗ 37](https://github.com/neysofu/tyche) - Probability distributions, stochastic & Markov processes, lattice walks, simple random sampling. A simple yet robust Scala library.
* [Zeppelin](http://zeppelin-project.org/) - Scala and Spark Notebook (like IPython Notebook)

## Big Data

* **[BIDMach ★ 898 ⧗ 14](https://github.com/BIDData/BIDMach)** - CPU and GPU machine learning library, using JNI for GPU computation.
* **[Flink ★ 9520 ⧗ 0](https://github.com/apache/flink)** - Processing framework with powerful stream- and batch-processing capabilities.
* [Gearpump ★ 305 ⧗ 9](https://github.com/apache/incubator-gearpump) - Lightweight real-time big data streaming engine
* [GridScale ★ 19 ⧗ 1](https://github.com/openmole/gridscale) - A Scala API for computing clusters and grids.
* **[Kafka ★ 12918 ⧗ 0](https://github.com/apache/kafka)** - Kafka is a message broker project and aims to provide a unified, high-throughput, low-latency platform for handling real-time data feeds.
* **[Reactive-kafka ★ 1177 ⧗ 5](https://github.com/akka/reactive-kafka)** - Reactive Streams API for Apache Kafka.
* **[Scalding ★ 3150 ⧗ 1](https://github.com/twitter/scalding)** - A Scala binding for the Cascading abstraction of Hadoop MapReduce.
* [Schemer ★ 68 ⧗ 9](https://github.com/indix/schemer) - Schema registry for CSV, TSV, JSON, AVRO and Parquet schema. Supports schema inference and GraphQL API.
* [Scio](https://github.com/spotify/scio) - A Scala API for [Apache Beam](https://beam.apache.org/) and [Google Cloud Dataflow](https://cloud.google.com/dataflow/) - None
* [Scrunch](http://crunch.apache.org/scrunch.html) - A Scala wrapper for [Apache Crunch](http://crunch.apache.org/index.html) which provides a framework for writing, testing, and running MapReduce pipelines.
* [Spark](http://spark.apache.org/) - Lightning fast cluster computing — up to 100x faster than Hadoop for iterative algorithms (memory caching) and up to 10x faster than Hadoop for single-pass MapReduce jobs. Compatible with YARN-enabled Hadoop clusters, can run on Mesos and in stand-alone mode as well.
* [spark-deployer ★ 77 ⧗ 280](https://github.com/KKBOX/spark-deployer) - A sbt plugin which helps deploying Apache Spark stand-alone cluster and submitting job on cloud system like AWS EC2.
* [Sparkplug ★ 20 ⧗ 5](https://github.com/indix/sparkplug) - Spark package to "plug" holes in data using SQL based rules
* [Sparkta ★ 480 ⧗ 1](https://github.com/Stratio/sparkta) - Real Time Aggregation based on Spark Streaming.
* **[Summingbird ★ 2036 ⧗ 0](https://github.com/twitter/summingbird)** - An implementation of the “lambda architecture” as a software abstraction — a single API for Hadoop and Storm.
* **[Vegas ★ 598 ⧗ 1](https://github.com/vegas-viz/Vegas)** - The missing MatPlotLib for Scala + Spark

## Image processing and image analysis

*2D and 3D image processing and image analysis*

* [scalismo ★ 144 ⧗ 1](https://github.com/unibas-gravis/scalismo) - Shape modelling and  model-based image analysis.
* **[scrimage ★ 670 ⧗ 0](https://github.com/sksamuel/scrimage)** - Image io, resize, manipulation and thumbnails.

## Sound processing and music

* [ScalaCollider ★ 156 ⧗ 35](https://github.com/Sciss/ScalaCollider) - Sound synthesis and signal processing client for SuperCollider.

## Functional Reactive Programming

*Event streams, signals, observables, etc.*

* **[Monix ★ 1535 ⧗ 1](https://github.com/monifu/monix)** - Extensions to Scala’s standard library for multi-threading primitives and functional reactive programming. Scala.js compatible.
* [Reactive Collections ★ 3 ⧗ 312](https://github.com/storm-enroute/reactors) - A library that incorporates event streams and signals with specialized collections called reactive containers, and expresses concurrency using isolates and channels.
* [REScala](http://www.rescala-lang.com/) - REScala is a library for functional reactive programming on the JVM and the Web. It provides a rich API for event stream transformations and signal composition with managed consistent up-to-date state and minimal syntactic overhead.
* **[RxScala ★ 852 ⧗ 3](https://github.com/ReactiveX/RxScala)** - Reactive Extensions for Scala – a library for composing asynchronous and event-based programs using observable sequences
* [scala.frp ★ 22 ⧗ 312](https://github.com/dylemma/scala.frp) - Functional Reactive Programming for Scala (event streams).
* **[Scala.Rx ★ 911 ⧗ 0](https://github.com/lihaoyi/scala.rx)** - An experimental library for Functional Reactive Programming in Scala (reactive variables). Scala.js compatible.
* [SynapseGrid ★ 123 ⧗ 38](https://github.com/Primetalk/SynapseGrid) - an FRP framework for constructing reactive real-time immutable data flow systems. It implements an original way of running and organizing event-driven systems based on Petri nets. The topology can be viewed as a .dot graph. The library is compatible with Akka and can seamlessly communicate with other actors.
* [Vert.x](http://vertx.io/) - A polyglot reactive application platform for the JVM which aims to be an alternative to node.js. Its concurrency model resembles actors. It supports [Scala](http://vertx.io/docs/vertx-core/scala/), Clojure, Java, Javascript, Ruby, Groovy and Python.

## Modularization and Dependency Injection

*Modularization of applications, dependency injection, etc.*

* [Airframe ★ 308 ⧗ 0](https://github.com/wvlet/airframe) - Dependency injection library tailored to Scala.
* [DIStage ★ 99 ⧗ 2](https://github.com/pshirshov/izumi-r2) - Staged Dependency Injection with higher-kinded polymorphism.
* [Grafter ★ 242 ⧗ 34](https://github.com/zalando/grafter) - Grafter is a library to configure and wire Scala applications.
* **[MacWire ★ 998 ⧗ 1](https://github.com/adamw/macwire)** - Scala Macro to generate wiring code for class instantiation. DI container replacement.
* [Scala-Guice ★ 296 ⧗ 4](https://github.com/codingwell/scala-guice) - Scala extensions for Google Guice
* [Scaldi ★ 274 ⧗ 8](https://github.com/scaldi/scaldi) - Lightweight Scala Dependency Injection Library.
* [SubCut ★ 399 ⧗ 53](https://github.com/dickwall/subcut) - Scala Uniquely Bound Classes Under Traits.

## Distributed Systems

*Libraries and frameworks for writing distributed applications.*

* [Akka](http://akka.io/) - A toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications.
* [Akka-tracing ★ 310 ⧗ 5](https://github.com/levkhomich/akka-tracing) - A distributed tracing extension for Akka. Provides integration with Play framework, Spray and Akka HTTP.
* [autobreaker ★ 10 ⧗ 160](https://github.com/lucastorri/autobreaker) - Automatically wrap classes that return Futures with a [Circuit Breaker](http://martinfowler.com/bliki/CircuitBreaker.html).
* [Clump](http://getclump.io) - A library for expressive and efficient service composition
* **[CurioDB ★ 500 ⧗ 1](https://github.com/stephenmcd/curiodb)** - Distributed & Persistent Redis Clone built with Scala & Akka.
* [Finagle](https://twitter.github.io/finagle/) - An extensible, protocol-agnostic RPC system designed for high performance and concurrency.
* [Glokka ★ 54 ⧗ 11](https://github.com/xitrum-framework/glokka) - Library to register and lookup actors by names in an Akka cluster.
* [Lagom](https://www.lightbend.com/lagom) - Framework for creating microservice-based systems.
* [Reactors](http://reactors.io/) - Foundational framework for distributed computing that fuses functional reactive programming and traditional actors.

## Extensions

*Scala extensions.*

* [Ammonite-Ops](http://lihaoyi.github.io/Ammonite/#Ammonite-Ops) - Safe, easy, filesystem operations in Scala as convenient as in the Bash shell.
* **[better-files ★ 1266 ⧗ 1](https://github.com/pathikrit/better-files)** - Simple, safe and intuitive Scala I/O. better-files is a dependency-free pragmatic thin Scala wrapper around Java NIO.
* **[Cassovary ★ 967 ⧗ 2](https://github.com/twitter/cassovary)** - A Scala library that is designed from the ground up for space efficiency, handling graphs with billions of nodes and edges.
* **[cats ★ 3336 ⧗ 0](https://github.com/typelevel/cats)** - Lightweight, modular, and extensible library for functional programming.
* [Chimney ★ 412 ⧗ 9](https://github.com/scalalandio/chimney) - Scala library for boilerplate-free data transformations.
* [chronoscala ★ 56 ⧗ 2](https://github.com/opt-tech/chronoscala) - Scala wrapper for Java Date/Time API.
* [Each ★ 225 ⧗ 19](https://github.com/ThoughtWorksInc/each) - A macro library that converts native imperative syntax to [Scalaz](https://github.com/scalaz/scalaz)'s monadic expressions.
* [Eff ★ 415 ⧗ 4](https://github.com/atnos-org/eff) - Extensible effects are an alternative to monad transformers for computing with effects in a functional way.
* [enableIf.scala ★ 55 ⧗ 24](https://github.com/ThoughtWorksInc/enableIf.scala) - A library that switches Scala code at compile-time, like `#if` in C/C++.
* **[Enumeratum ★ 807 ⧗ 2](https://github.com/lloydmeta/enumeratum)** - A macro to replace Scala enumerations with a sealed family of case objects. This allows additional checks for the compiler, e.g. for missing cases in a match statement. Has additinal support for Json libraries and the Play framework.
* [Freasy-Monad ★ 114 ⧗ 77](https://github.com/Thangiee/Freasy-Monad) - Easy way to create Free Monad for Cats and Scalaz using Scala macros with first-class Intellij support.
* [Freedsl ★ 34 ⧗ 150](https://github.com/ISCPIF/freedsl) - A library to implement composable side effects, weaving typeclasses on a wrapping type and the free monad.
* **[Freestyle ★ 592 ⧗ 5](https://github.com/frees-io/freestyle)** - A cohesive & pragmatic framework of FP centric Scala libraries.
* [Hamsters ★ 285 ⧗ 1](https://github.com/scala-hamsters/hamsters) - A mini Scala utility library. Compatible with functional programming beginners. Featuring validation, monad transformers, HLists, Union types.
* [idid ★ 13 ⧗ 33](https://github.com/lucastorri/idid) - A library to define common interfaces for different Id types.
* [Lamma ★ 85 ⧗ 5](https://github.com/maxcellent/lamma) - A Scala date library for date and schedule generation.
* [LArray ★ 325 ⧗ 4](https://github.com/xerial/larray) - Large off-heap arrays (> 2GB) and mmap files.
* [Log4s](http://www.log4s.org/) - Fast, Scala-friendly logging bindings on top of [SLF4J](http://slf4j.org/). Uses macros for extreme performance.
* [LogStage ★ 99 ⧗ 2](https://github.com/pshirshov/izumi-r2) - Zero-cost structural logger for Scala with [SLF4J] integration.
* **[Monocle ★ 1109 ⧗ 4](https://github.com/julien-truffaut/Monocle)** - An Optics/Lens library for purely functional manipulation of immutable objects.
* **[n-scala ★ 811 ⧗ 8](https://github.com/nscala-time/nscala-time)** - Scala wrapper for Joda Time.
* [Persist-Logging ★ 37 ⧗ 10](https://github.com/nestorpersist/logging) - Comprehensive logging library for Scala.
* **[Quicklens ★ 508 ⧗ 5](https://github.com/adamw/quicklens)** - modify deeply nested case class fields with an elegant API
* [Rapture](http://rapture.io/) ([repo](https://github.com/propensive/rapture)) - a collection of libraries for common, everyday programming tasks (I/O, JSON, i18n, etc.)
* [Records for Scala ★ 153 ⧗ 16](https://github.com/scala-records/scala-records) - Labeled records for Scala based on structural refinement types and macros.
* **[refined ★ 954 ⧗ 0](https://github.com/fthomas/refined)** - Simple refinement types with compile- and runtime checking
* **[Scala Async ★ 968 ⧗ 3](https://github.com/scala/async)** - An asynchronous programming facility for Scala.
* [Scala Graph](http://www.scala-graph.org/) - A Scala library with basic graph functionality that seamlessly fits into the Scala standard collections library.
* [scala.meta](http://scalameta.org/) - A clean-room implementation of a metaprogramming toolkit for Scala.
* [Scalactic](http://www.scalactic.org/) - Small library of utilities related to quality that helps keeping code clear and correct.
* **[Scalaz ★ 4190 ⧗ 0](https://github.com/scalaz/scalaz)** - An extension to the core Scala library for functional programming.
* [scribe ★ 224 ⧗ 0](https://github.com/outr/scribe) - Practical logging framework that doesn't depend on any other logging framework and can be completely configured programmatically.
* **[Shapeless ★ 2827 ⧗ 0](https://github.com/milessabin/shapeless)** - A type class and dependent type based generic programming library for Scala.
* **[Simulacrum ★ 814 ⧗ 8](https://github.com/mpilquist/simulacrum)** - First class syntax support for type classes in Scala.
* [Squid ★ 148 ⧗ 2](https://github.com/epfldata/squid) - Type-safe metaprogramming framework with typed, hygienic quasiquotes.
* [Stateless Future ★ 179 ⧗ 40](https://github.com/qifun/stateless-future) - Asynchronous programming in fully featured Scala syntax.
* **[Twitter Util ★ 2283 ⧗ 1](https://github.com/twitter/util)** - General-purpose Scala libraries, including a future implementation and other concurrency tools.
* [wvlet-log ★ 58 ⧗ 220](https://github.com/wvlet/log) - A library for enhancing your application logs with colors and source code locations.

## Misc

*Projects that don't fit into any specific category.*

* [Agora](https://gitlab.com/aossie/Agora/) - Library of vote-counting algorithms for elections.
* [Ammonite-REPL](http://lihaoyi.github.io/Ammonite/#Ammonite-REPL) - An improved Scala REPL: syntax highlighting, output formatting, multi-line input, and more.
* [ApiBuilder ★ 340 ⧗ 2](https://github.com/apicollective/apibuilder) - Simple, Comprehensive Tooling for Modern APIs 
* [BootZooka ★ 394 ⧗ 3](https://github.com/softwaremill/bootzooka) - Simple project to quickly start developing a web application using AngularJS and Akka HTTP, without the need to write login, user registration etc.
* **[Eclair ★ 788 ⧗ 0](https://github.com/ACINQ/eclair)** - ACINQ's Lightning Network implementation written in Scala.  Lightning Network is a second layer protocol built on top of bitcoin to address scalability, privacy, confirmation time and many other issues.
* [Fansi ★ 159 ⧗ 0](https://github.com/lihaoyi/fansi) - Scala/Scala.js library for manipulating Fancy Ansi colored strings
* [GoogleApiScala ★ 16 ⧗ 265](https://github.com/EckerdCollege/google-api-scala) - A simple scala library offering control of Google Drive, Calendar, and the Admin SDK.
* [mailgun4s ★ 11 ⧗ 20](https://github.com/outr/mailgun4s) - Scala wrapper around the Mailgun API
* [media4s ★ 17 ⧗ 8](https://github.com/outr/media4s) - Scala command-line wrapper around ffmpeg, ffprobe, ImageMagick, and other tools relating to media.
* [Miniboxing](https://github.com/miniboxing/miniboxing-plugin) - A Scala compiler plugin that improves program performance -- [see the project web site](http://scala-miniboxing.org) - Less boxes
* [Openquant ★ 73 ⧗ 0](https://github.com/openquant) - A Scala open source quantitative trading platform
* [Ostinato ★ 33 ⧗ 23](https://github.com/marianogappa/ostinato) - A chess library that runs on the server (Scala) and on the browser (ScalaJS)
* [Play Swagger ★ 319 ⧗ 7](https://github.com/iheartradio/play-swagger) - Automatically create Swagger documentation for your Play REST API
* [pprint ★ 90 ⧗ 0](https://github.com/lihaoyi/pprint) - Pretty-printer for Scala values and types for easier reading and debugging
* **[Prisma ★ 15007 ⧗ 0](https://github.com/prisma/prisma)** - Prisma turns your database into a realtime GraphQL API 
* **[PureConfig ★ 832 ⧗ 0](https://github.com/melrief/pureconfig)** - A boilerplate-free Scala library for loading configuration files.
* [REPLesent ★ 381 ⧗ 14](https://github.com/marconilanna/REPLesent) - A presentation tool built inside the Scala REPL. Runs code straight from your slides with a single keystroke.
* [scala-debugger ★ 93 ⧗ 1](https://github.com/ensime/scala-debugger) - Scala libraries and tooling utilizing the Java Debugger Interface.
* [scala-ssh ★ 222 ⧗ 11](https://github.com/sirthias/scala-ssh) - Remote shell access via SSH for your Scala applications
* [Scalan ★ 89 ⧗ 75](https://github.com/scalan/scalan) - A framework for development of domain-specific compilers in Scala
* [ScalaSTM](https://nbronson.github.io/scala-stm/) - Software Transaction Memory for Scala
* [Scavenger](https://gitlab.com/aossie/Scavenger) - An experimental automated theorem prover.
* [settler ★ 6 ⧗ 94](https://github.com/lucastorri/settler) - Boilerplate-free typed settings generation in Scala.
* [Simple Scala Config ★ 48 ⧗ 32](https://github.com/ElderResearch/ssc) - Thin, idiomatic Scala wrapper around [Typesafe Config](https://github.com/typesafehub/config) with custom `Reader[T]` suppport.

## Android

*Scala libraries and wrappers for Android development.*

* **[Android SDK Plugin for SBT ★ 731 ⧗ 4](https://github.com/pfn/android-sdk-plugin)** - An sbt plugin that adds tasks for developing Android applications.
* [Gradle Android Scala Plugin ★ 338 ⧗ 17](https://github.com/saturday06/gradle-android-scala-plugin) - A gradle plugin that allows you to use Scala with Android
* **[Macroid ★ 541 ⧗ 19](https://github.com/47deg/macroid)** - A modular functional UI language for Android.
* **[Scaloid ★ 2114 ⧗ 6](https://github.com/pocorall/scaloid)** - Less painful Android development with Scala.

## HTTP

*Scala libraries and wrappers for HTTP clients.*

* **[Akka HTTP ★ 940 ⧗ 2](https://github.com/akka/akka-http)** - The Streaming-first HTTP server/module of [Akka](https://github.com/akka/akka).
* [Dispatch ★ 426 ⧗ 25](https://github.com/dispatch/reboot) - Library for asynchronous HTTP interaction. It provides a Scala vocabulary for Java’s [async-http-client](https://github.com/AsyncHttpClient/async-http-client).
* **[Finch.io ★ 1382 ⧗ 4](https://github.com/finagle/finch)** - Purely Functional REST API atop of [Finagle](https://github.com/twitter/finagle).
* [Fintrospect ★ 37 ⧗ 0](http://fintrospect.io) - Implement fast, type-safe HTTP webservices for [Finagle](https://github.com/twitter/finagle).
* **[Http4s ★ 1594 ⧗ 0](https://github.com/http4s/http4s)** - A minimal, idiomatic Scala interface for HTTP.
* [jefe ★ 4 ⧗ 72](https://github.com/outr/jefe) - Manages installation, updating, downloading, launching, error reporting, proxying, multi-server management, and much more for your stand-alone and web applications.
* [lolhttp ★ 88 ⧗ 9](https://github.com/criteo/lolhttp) - An HTTP & HTTP/2 Server and Client library for Scala.
* [RösHTTP ★ 120 ⧗ 1](https://github.com/hmil/RosHTTP) - A lightweight asynchronous HTTP API built with Scala.js in mind. Supports the JVM and Node.js runtimes as well as most browsers.
* **[scalaj-http ★ 881 ⧗ 3](https://github.com/scalaj/scalaj-http)** - Simple scala wrapper for HttpURLConnection (including OAuth support).
* [Scalaxb ★ 281 ⧗ 3](https://github.com/eed3si9n/scalaxb) - An XML data-binding tool for Scala that supports W3C XML Schema (xsd) and Web Services Description Language (wsdl) as the input file.
* [Spray](http://spray.io/) - Actor-based library for http interaction.
* **[sttp ★ 737 ⧗ 0](https://github.com/softwaremill/sttp)** - The Scala HTTP client you always wanted!

## Semantic Web

*Scala libraries for interactions with the Web of Data, and other RDF tools.*

* [Banana-RDF ★ 249 ⧗ 18](https://github.com/banana-rdf/banana-rdf) - Scala-friendly abstractions for RDF and Linked Data technologies. Supports Jena, Sesame and native Scala.
* [Scowl ★ 35 ⧗ 40](https://github.com/phenoscape/scowl) - Scala DSL allowing a declarative approach to composing OWL expressions and axioms using the OWL API.

## Metrics and Monitoring

*Scala libraries for gathering metrics and monitoring applications.*

* [Kamon](http://kamon.io) - Gathering metrics from applications built with Akka, Spray and Play! with support for user metrics as well.
* [Metrics-Scala ★ 394 ⧗ 3](https://github.com/erikvanoosten/metrics-scala) - Scala API for Dropwizard's Metrics library.

## Parsing

*Scala libraries for creating parsers.*

* [atto ★ 282 ⧗ 8](https://github.com/tpolecat/atto) - Pure functional incremental text parsing library for Scala, based on Attoparsec.
* [CLIST ★ 90 ⧗ 39](https://github.com/backuity/clist) - Command Line Interface Scala Toolkit
* [decline ★ 238 ⧗ 2](https://github.com/bkirwi/decline) - composable command-line parser for Scala, built on Cats
* **[Fast Parse ★ 789 ⧗ 0](https://github.com/lihaoyi/fastparse)** - Fast to write, Fast running Parsers in Scala
* **[Parboiled2 ★ 613 ⧗ 4](https://github.com/sirthias/parboiled2)** - A Fast Parser Generator for Scala 2.10.3+.
* [Scala Parser Combinators ★ 408 ⧗ 1](https://github.com/scala/scala-parser-combinators) - Scala Standard Parser Combinator Library.
* **[Scopt ★ 1114 ⧗ 1](https://github.com/scopt/scopt)** - Simple scala command line options parsing.

## Sbt plugins

*Sbt plugins to make your life easier.*

* [coursier ★ 1 ⧗ 8](https://github.com/alexarchambault/coursier) - A Scala library to fetch dependencies from Maven / Ivy repositories
* [sbt-api-mappings ★ 67 ⧗ 11](https://github.com/ThoughtWorksInc/sbt-api-mappings) - A Sbt plugin that resolves external API links to common Scala libraries.
* [sbt-buildinfo ★ 428 ⧗ 17](https://github.com/sbt/sbt-buildinfo) - Generates Scala source from build definition.
* **[sbt-dependency-graph ★ 1093 ⧗ 3](https://github.com/jrudolph/sbt-dependency-graph)** - Create a dependency graph for your project.
* **[sbt-docker ★ 637 ⧗ 6](https://github.com/marcuslonnberg/sbt-docker)** - Create Docker images directly from sbt
* [sbt-doctest ★ 160 ⧗ 41](https://github.com/tkawachi/sbt-doctest) - Plugin for sbt that generates tests from examples in ScalaDoc.
* [sbt-ensime ★ 250 ⧗ 4](https://github.com/ensime/ensime-sbt) - Generates .ensime config files for SBT projects [http://ensime.org/build_tools/sbt](http://ensime.org/build_tools/sbt)
* [sbt-groll ★ 124 ⧗ 133](https://github.com/sbt/sbt-groll) - sbt plugin to roll the Git history.
* [sbt-hepek ★ 14 ⧗ 26](https://github.com/sake92/sbt-hepek) - Make static websites in Scala code (render `object` to file!).
* [sbt-ide-settings ★ 42 ⧗ 127](https://github.com/Jetbrains/sbt-ide-settings) - SBT plugin for tweaking various IDE settings
* **[sbt-native-packager ★ 1244 ⧗ 0](https://github.com/sbt/sbt-native-packager)** - Bundle up Scala software for native packaging systems, like deb, rpm, homebrew, msi..
* [sbt-pack ★ 386 ⧗ 2](https://github.com/xerial/sbt-pack) - A sbt plugin for creating distributable Scala packages.
* **[sbt-revolver ★ 698 ⧗ 0](https://github.com/spray/sbt-revolver)** - Fork & Stop processes from sbt.
* [sbt-robovm ★ 111 ⧗ 304](https://github.com/roboscala/sbt-robovm) - An sbt plugin for iOS development in Scala
* [sbt-scala-js-map ★ 22 ⧗ 29](https://github.com/ThoughtWorksInc/sbt-scala-js-map) - A sbt plugin that configures source mapping for Scala.js projects hosted on Github
* [sbt-sublime ★ 139 ⧗ 91](https://github.com/orrsella/sbt-sublime) - Create Sublime Text projects with library dependencies sources
* **[sbt-updates ★ 561 ⧗ 1](https://github.com/rtimush/sbt-updates)** - Shows sbt project's dependency updates.
* **[sbteclipse ★ 716 ⧗ 0](https://github.com/typesafehub/sbteclipse)** - Create Eclipse project definitions from sbt builds.
* [scala-clippy ★ 291 ⧗ 65](https://github.com/softwaremill/scala-clippy) - Good advice and coloring for Scala compiler errors
* [ScalaKata2 ★ 92 ⧗ 5](https://github.com/MasseGuillaume/ScalaKata2) - Scala playground & Documentation tool.
* [splain ★ 288 ⧗ 22](https://github.com/tek/splain) - Better implicit errors for Scala.
* **[tut ★ 576 ⧗ 4](https://github.com/tpolecat/tut)** - Tool for writing documentation with typechecked examples.
* [xsbt-web-plugin ★ 370 ⧗ 0](https://github.com/earldouglas/xsbt-web-plugin) - Build enterprise J2EE Web applications in Scala.

## XML / HTML

*XML and HTML generation and processing*

* **[scala-scraper ★ 532 ⧗ 0](https://github.com/ruippeixotog/scala-scraper)** - A library for scraping content from HTML pages.
* [xs4s ★ 34 ⧗ 126](https://github.com/ScalaWilliam/xs4s) - XML Streaming for Scala for processing large (gigabytes and over) XML files.

## Markdown

* [Laika ★ 161](https://github.com/planet42/Laika) - Text Markup Transformer for sbt and Scala applications, transforming Markdown and reStructuredText to HTML and PDF.


## Learning Scala

*Nice books, blogs and other resources to learn Scala*

* [A Tour of Scala](http://docs.scala-lang.org/tour/tour-of-scala.html) - Bite-sized introductions to some of the core language concepts.
* **[Demos and Examples in Scala (Chinese) ★ 979 ⧗ 0](https://github.com/jacksu/utils4s)** - repo of sample Scala library usage, written in Chinese
* [Essential Scala](https://underscore.io/books/essential-scala/) - None
* [Exercism - Scala Exercises](http://exercism.io/languages/scala/exercises) - Community-driven Scala exercises.
* [Functional Programming for Mortals](https://leanpub.com/fpmortals/read) - None
* [Functional Programming in Scala](https://www.coursera.org/specializations/scala) - Coursera Specialization (5 courses) created by  Martin Odersky et al. at the EPFL (Ecole polytechnique fédérale de Lausanne).
* [Functional Works / Learn](https://functional.works-hub.com/learn/) - Quality resources maintained by functional works
* [Get Programming with Scala](https://www.manning.com/books/get-programming-with-scala) - Tutorial-driven introduction to Scala
* [Introduction to programming with dependent types in Scala](https://stepik.org/course/2294/) - Video Course by Dmytro Mitin
* [Learn-by-doing functional programming course on Scala ★ 488 ⧗ 1](https://github.com/dehun/learn-fp/) - Covers type classes, functors, applicatives, monads, monad transformers, free monad
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

* [Beard ★ 100 ⧗ 6](https://github.com/zalando/beard) - lightweight logicless templating engine inspired by Mustache
* **[Scalatags ★ 584 ⧗ 0](https://github.com/lihaoyi/scalatags)** - Write html as scala code and have your IDE syntax check it.
* **[Scalate ★ 549 ⧗ 0](https://github.com/scalate/scalate)** - Scala based template engine which supports HAML, Mustache and JSP, Erb and Velocity style syntaxes
* [Twirl ★ 452 ⧗ 1](https://github.com/playframework/twirl) - The Play Scala Template Compiler

## Tools

* [Scalafix]https://github.com/scalacenter/scalafix) - Refactoring and linting tool

* [Codacy](https://www.codacy.com/) - Automated Code Reviews for Scala
* [fast-string-interpolator ★ 54 ⧗ 0](https://github.com/Sizmek/fast-string-interpolator) - Scala macro that generates ultra-fast string interpolators
* [Fastring ★ 115 ⧗ 9](https://github.com/Atry/fastring) - Extremely fast string formatting
* **[Gitbucket ★ 7744 ⧗ 1](https://github.com/gitbucket/gitbucket)** - The easily installable GitHub clone powered by Scala
* [Giter8](http://www.foundweekends.org/giter8/) - command line tool to generate files and directories from templates published on Github
* [Hepek ★ 54 ⧗ 4](https://github.com/sake92/hepek) - Static content generator for developers. Intuitive, scalable, powerful. 
* [Mill](http://www.lihaoyi.com/mill/) - A better Scala build tool
* [sbt](http://www.scala-sbt.org/) ([repo](https://github.com/sbt/sbt)) - The interactive build tool for Scala
* [Scala @LibHunt](https://scala.libhunt.com) - The go-to Scala Toolbox.
* [scala-trace-debug ★ 113 ⧗ 165](https://github.com/JohnReedLOL/scala-trace-debug) - Multithreaded print debug tool
* [Scalariform ★ 117 ⧗ 77](https://github.com/daniel-trinh/scalariform) - Scala source code formatter
* **[Scalastyle ★ 623 ⧗ 2](https://github.com/scalastyle/scalastyle)** - Scala style checker.
* [Scalatex ★ 278 ⧗ 26](https://github.com/lihaoyi/Scalatex) - Programmable, Typesafe Document Generation
* [Scapegoat ★ 320 ⧗ 4](https://github.com/sksamuel/scapegoat) - Scala compiler plugin for static code analysis
* [Scaps](http://scala-search.org/) ([repo](https://github.com/scala-search/scaps)) - A search engine for Scala libraries
* [Scoverage](https://github.com/scoverage) - Scala Code Coverage tool
* **[Wartremover ★ 874 ⧗ 0](https://github.com/puffnfresh/wartremover)** - Wartremover a flexible Scala code linting tool

## Geospatial

*Libraries to aid with geospatial calculations and artifacts.*

* **[Geotrellis ★ 875 ⧗ 1](https://github.com/locationtech/geotrellis)** - Scalable raster toolkit for GIS processing
* [osm4scala ★ 28 ⧗ 2](https://github.com/angelcervera/osm4scala) - OpenStreetMap PBF2 file parser
* [rtree2d ★ 53 ⧗ 2](https://github.com/Sizmek/rtree2d) - RTree2D is a 2D immutable R-tree with STR (Sort-Tile-Recursive) packing for ultra-fast nearest and intersection queries on plane and spherical surfaces
* [sfcurve ★ 47 ⧗ 21](https://github.com/locationtech/sfcurve) - Space filling curves in Scala for geospatial indexing and query

## Devops

*DevOps related tools and libraries.*

* [Orkestra ★ 91 ⧗ 22](https://github.com/Orkestra-Tech/orkestra) - Functional DevOps with Scala and Kubernetes
* [Skuber ★ 212 ⧗ 4](https://github.com/doriordan/skuber) - Kubernetes client in Scala

# Resources

Where to discover new Scala libraries.

## Podcasts

* [CoRecursive Interviews](https://corecursive.com/) - In-depth Interviews with software developers, often on the subject of scala libraries and functional programming.

## Newsletters

* [Scala Times](https://scalatimes.com/) - Weekly newsletter about scala

# Contributing

Your contributions are always welcome! Please submit a pull request or create an issue to add a new framework, library or software to the list. Do not submit a project that hasn’t been updated in the past 6 months or is not awesome.

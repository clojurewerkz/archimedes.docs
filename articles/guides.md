---
title: "Archimedes: all documentation guides"
layout: article
---

## Guide list

[Archimedes documentation](https://github.com/clojurewerkz/archimedes.docs) is organized as a number of guides, covering all kinds of topics.

We recommend that you read these guides, if possible, in this order:

#### [Transaction Management](/articles/transactions.html)

An in depth look into how Archimedes handles transaction management.
Covers the basics and shows how to easily implement geometric backing
off for retrying transactions.

#### [Working with Vertices](/articles/vertices.html)

Vertices are the pillars upon which your graph empire will rest. This
guide will go through how to create, remove, modify, and retrieve
vertices with Archimedes.

#### [Working with Edges](/articles/edges.html) 

What would a graph library be if it didn't have a great cadre of
features for working with edges? This guide goes through the various
functions that Archimedes provides to make working with edges as
graceful as possible.

#### [Simple Queries](/articles/query.html) 

Archimedes provides a very simple DSL for working with Blueprints
queries.

#### [IO Operations](/articles/io.html) 

Archimedes has several useful features for reading and writing various
graph file formats, like gml, graphml and GraphSON.

#### [Ogre Integration](/articles/ogre.html)    

[Ogre](http://ogre.clojurewerkz.org/) is a Clojure wrapper around the
[Gremlin traversal library](https://github.com/tinkerpop/gremlin/wiki).
Archimeds is built on top of Ogre and both libraries were developed in
parallel. This guide explores exactly how delightfully well these two
libraries play with each other.

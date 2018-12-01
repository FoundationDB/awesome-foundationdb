# awesome-foundationdb

## General

Important links:

- [GitHub repo](https://github.com/apple/foundationdb/)
- [Documentation](https://apple.github.io/foundationdb/contents.html)
  - [Downloads](https://apple.github.io/foundationdb/downloads.html)
- [Community Forum](https://forums.foundationdb.org/)
- [Blog](https://www.foundationdb.org/blog/)

## Bindings

Official bindings:

- [Python](https://apple.github.io/foundationdb/api-python.html)
  - [Class Scheduling tutorial](https://apple.github.io/foundationdb/class-scheduling.html#class-scheduling-application)
  - [Recipes](https://github.com/apple/foundationdb/tree/master/recipes/python-recipes)
- [Ruby](https://apple.github.io/foundationdb/api-ruby.html)
  - [Class Scheduling tutorial](https://apple.github.io/foundationdb/class-scheduling-ruby.html)
  - [Recipes](https://github.com/apple/foundationdb/tree/master/recipes/ruby-recipes)
- [Java](https://apple.github.io/foundationdb/javadoc/index.html)
  - [Class Scheduling tutorial](https://apple.github.io/foundationdb/class-scheduling-java.html)
  - [Recipes](https://github.com/apple/foundationdb/tree/master/recipes/java-recipes)
- [Go](https://godoc.org/github.com/apple/foundationdb/bindings/go/src/fdb)
  - [Class Scheduling tutorial](https://apple.github.io/foundationdb/class-scheduling-go.html)
  - [Recipes](https://github.com/apple/foundationdb/tree/master/recipes/go-recipes)
- [C](https://apple.github.io/foundationdb/api-c.html)
  - No tutorial yet :(

Community (varying levels of production-readiness):

- [Rust](https://github.com/bluejekyll/foundationdb-rs) (@bluejekyll)
- [C#/.NET](https://github.com/Doxense/foundationdb-dotnet-client) (@Doxense)
- [NodeJS](https://www.npmjs.com/package/foundationdb) (@josephg)
  - [Example repo](https://github.com/bbonnin/foundationdb-examples) (@bbonnin)
- [PHP](https://github.com/viest/PHP-FoundationDB) (@viest)
- [Clojure](https://github.com/vedang/clj_fdb) (@vedang)
- [Clojure](https://github.com/tirkarthi/clj-foundationdb) (@tirkarthi)
- [Clojure](https://github.com/alex-dixon/clj-foundationdb) (@alex-dixon)
- [Julia](https://github.com/tanmaykm/FoundationDB.jl) (@tanmaykm)
- [Python asyncio](https://github.com/amirouche/found) (@amirouche)
- [Haskell](https://github.com/crclark/foundationdb-haskell) (@crclark)

## Layers

Experimental/Proof of Concept:

- [FoundationDB's original SQL layer](https://github.com/jaytaylor/sql-layer) (no longer developed)
- [FoundationDB's example Python layers](https://github.com/apple/foundationdb/tree/master/layers)
  - [simpledoc.py](https://github.com/AydinSakar/python-layers/blob/master/lib/simpledoc.py) (missing from main repo)
- [Simple object store](https://fabianlindfors.se/blog/building-an-object-store-with-foundation-db/) (@Fabianlindfors)
- [JanusGraph adapter](https://github.com/twilmes/janusgraph/tree/foundationdb-storage) (@twilmes)
- [Python NBD server](https://github.com/dividuum/fdb-nbd) (@dividuum)
- [Java NBD server](https://github.com/spullara/nbd) (@spullara)
- [Hashicorp Vault](https://github.com/hashicorp/vault/pull/4900)

Production:

- [FoundationDB document layer](https://foundationdb.github.io/fdb-document-layer)

## Operations

- [Terraform deployment PoC](https://github.com/bitgn/fdb-cloud-test) (@bitgn)
- [Database benchmark that includes FDB](https://github.com/pingcap/go-ycsb/) (@pingcap)
- [Prometheus exporter](https://github.com/leoluk/fdb_exporter) (@leoluk)

## Technical

- [FoundationDB's high contention allocator](https://www.activesphere.com/blog/2018/08/05/high-contention-allocator) (activesphere.com)

## Production Experience

- [Snowflake](https://www.snowflake.net/how-foundationdb-powers-snowflake-metadata-forward/) - data warehouse for the cloud
- [Wavefront](https://www.wavefront.com/wavefront-foundationdb-open-source-project/) - cloud monitoring and analytics by VMWare
- [SkuVault](https://abdullin.com/sku-vault/foundationdb-layers/) - online warehouse management system


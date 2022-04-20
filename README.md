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

Community bindings (varying levels of production-readiness):

- [Rust](https://github.com/foundationdb-rs/foundationdb-rs) (@fdb-rs's community)
- [Tokio/Rust](https://fdb-rs.github.io/) (@rajivr)
- [C#/.NET](https://github.com/Doxense/foundationdb-dotnet-client) (@Doxense)
- [NodeJS](https://www.npmjs.com/package/foundationdb) (@josephg)
  - [Example repo](https://github.com/bbonnin/foundationdb-examples) (@bbonnin)
- [PHP](https://github.com/viest/PHP-FoundationDB) (@viest)
- [Clojure](https://github.com/vedang/clj_fdb) (@vedang)
- [Clojure](https://github.com/tirkarthi/clj-foundationdb) (@tirkarthi)
- [Clojure](https://github.com/alex-dixon/clj-foundationdb) (@alex-dixon)
- [Clojure Record-Layer](https://github.com/exoscale/vinyl) (@exoscale)
- [Julia](https://github.com/tanmaykm/FoundationDB.jl) (@tanmaykm)
- [Python asyncio](https://github.com/amirouche/found) (@amirouche)
- [Haskell](https://github.com/crclark/foundationdb-haskell) (@crclark)
- [TypeScript](https://github.com/openland/foundationdb) (@openland)
- [Elixir](https://github.com/ananthakumaran/fdb) (@ananthakumaran)
- [Swift](https://github.com/kirilltitov/FDBSwift) (@kirilltitov)
- [Erlang](https://github.com/apache/couchdb-erlfdb) (@apache)
- [Scala](https://github.com/pwliwanow/foundationdb4s) (@pwliwanow)

## Layers

Experimental/Proof of Concept:

- [FoundationDB's original SQL layer](https://github.com/jaytaylor/sql-layer) (no longer developed)
- [FoundationDB's example Python layers](https://github.com/apple/foundationdb/tree/master/layers)
  - [simpledoc.py](https://github.com/AydinSakar/python-layers/blob/master/lib/simpledoc.py) (missing from main repo)
- [Simple object store](https://fabianlindfors.se/blog/building-an-object-store-with-foundation-db/) (@Fabianlindfors)
- [JanusGraph adapter](https://github.com/twilmes/janusgraph/tree/foundationdb-storage) (@twilmes)
- [Python NBD server](https://github.com/dividuum/fdb-nbd) (@dividuum)
- [Java NBD server](https://github.com/spullara/nbd) (@spullara)
- [FoundationDB Block Device](https://github.com/meln1k/foundationdb-block-device) (@meln1k)
- [Hashicorp Vault](https://github.com/hashicorp/vault/pull/4900)
- [OpenTick](https://github.com/opentradesolutions/opentick) (@opentradesolutions)
- [STORED document layer](https://github.com/capturetechnologies/stored) (@capturetechnologies)
- [Nomure graph database](https://github.com/OkamiIO/Nomure) (@OkamiIO)
- [Lucene layer](https://github.com/AydinSakar/lucene-layer)
- [Zookeeper layer](https://github.com/pH14/fdb-zk) (@pH14)
- [Redis protocol FDB Gateway](https://github.com/ryanworl/fdb-gateway) (@ryanworl)
- [Copernic: versioned structured data, with change-request mechanic](https://github.com/amirouche/copernic) (@amirouche)
- [ETCD layer](https://github.com/PierreZ/fdb-etcd) (@PierreZ)
- [Record-Store](https://github.com/PierreZ/record-store) (@PierreZ)

Production:

- [FoundationDB document layer](https://foundationdb.github.io/fdb-document-layer)
- [FoundationDB record layer](https://www.github.com/foundationdb/fdb-record-layer)

## Operations

- [Terraform deployment PoC](https://github.com/bitgn/fdb-cloud-test) (@bitgn)
- [Database benchmark that includes FDB](https://github.com/pingcap/go-ycsb/) (@pingcap)
- [Prometheus exporter](https://github.com/leoluk/fdb_exporter) (@leoluk)
- [Wavefront FDB Tailer](https://github.com/wavefrontHQ/wavefront-fdb-tailer) (@wavefrontHQ)

## Technical

### Papers

- [Cloudkit: structured storage for mobile applications (2018)](https://www.vldb.org/pvldb/vol11/p540-shraer.pdf)
- [Towards a General Framework for ML-based Self-tuning Databases (2020)](https://arxiv.org/abs/2011.07921)
- [QuiCK: A Queuing System in CloudKit (2021)](https://www.foundationdb.org/files/QuiCK.pdf)
- [FoundationDB: A Distributed, Unbundled, Transactional Key Value Store (2021)](https://www.foundationdb.org/files/fdb-paper.pdf)

### Blogposts

- [FoundationDB Layers (2018)](https://abdullin.com/sku-vault/foundationdb-layers/) (abdullin.com)
- [FoundationDB's high contention allocator](https://www.activesphere.com/blog/2018/08/05/high-contention-allocator) (activesphere.com)
- [BUGGIFY](https://transactional.blog/simulation/buggify.html) (transactional.blog)
- [Building a FoundationDB Cluster: Roles, Classes, and Processes](https://nikita.melkozerov.dev/posts/2019/06/building-a-foundationdb-cluster-roles-classes-and-processes/) (nikita.melkozerov.dev)
- [Time Series and FoundationDB: Millions of writes/s and 10x compression in under 2,000 lines of Go](https://github.com/richardartoul/tsdb-layer/blob/master/README.md) (github.com/richardartoul)
- [FoundationDB Record Layer](https://smalldatum.blogspot.com/2019/09/foundationdb-record-layer.html) (smalldatum.blogspot.com)
- [Notes about FoundationDB](https://pierrezemb.fr/posts/notes-about-foundationdb/) (pierrezemb.fr)
- [Crafting row keys in FoundationDB](https://pierrezemb.fr/posts/crafting-keys-in-fdb/) (pierrezemb.fr)
- [FoundationDB: A Distributed Unbundled Transactional Key Value Store](https://www.micahlerner.com/2021/06/12/foundationdb-a-distributed-unbundled-transactional-key-value-store.html) (www.micahlerner.com)
- [Reading Group. FoundationDB: A Distributed Unbundled Transactional Key Value Store](http://charap.co/reading-group-foundationdb-a-distributed-unbundled-transactional-key-value-store/) (charap.co)
- Migrating Snowflake’s Metadata series:
  - [Part 1: Migrating Snowflake’s Metadata Part with No Downtime](https://medium.com/snowflake/migrating-snowflakes-metadata-with-no-downtime-ca90604b677c) (medium.com)
  - [Part 2: Migrating Snowflake’s Metadata with FDB Replication Service](https://medium.com/snowflake/part-2-migrating-snowflakes-metadata-with-fdb-replication-service-c3a3bee79904) (medium.com)
- [Bigblue’s multi-model database on FoundationDB](https://medium.com/bigblue-engineering/bigblues-multi-model-database-on-foundationdb-5c54b8d61942) (medium.com)

### Talks

- ["Testing Distributed Systems w/ Deterministic Simulation" by Will Wilson (2014)](https://www.youtube.com/watch?v=4fFDFbi3toc)
- [Playlist FoundationDB Summit 2018](https://www.youtube.com/playlist?list=PLbzoR-pLrL6q7uYN-94-p_-Q3hyAmpI7o)
- [Solving Everyday Data Problems with FoundationDB](https://www.youtube.com/watch?v=f6Ni30Q4Tg)
- [Playlist FoundationDB Summit 2019](https://www.youtube.com/playlist?list=PLbzoR-pLrL6oWYrC950yAhbLk8FRRB_Bt)
- [FoundationDB or: How I Learned to Stop Worrying and Trust the Database (Markus Pilman, Snowflake) (2020)](https://www.youtube.com/watch?v=OJb8A6h9jQQ)
- [Novel Design Choices in Apache CouchDB (Adam Kocoloski) (2021)](https://www.youtube.com/watch?v=FCs7Dz8hgjQ)
- [SIGMOD 568 QuiCK: a Queuing System in CloudKit (2021)](https://www.youtube.com/watch?v=I9mNENkZT90)
- [SIGMOD 538 FoundationDB: A Distributed Unbundled Transactional KeyValue Store (2021)](https://www.youtube.com/watch?v=st0VjQdpZL4)
- [Paper #65. FoundationDB: A Distributed Unbundled Transactional Key Value Store (2021)](https://www.youtube.com/watch?v=A6Ob1lebIzQ)
- [Markus Pilman (Snowflake) - FoundationDB at Snowflake: Architecture and Internals (2021)](https://www.youtube.com/watch?v=4yH4r8ZCt8M)

### Podcasts

- [Data Engineering Podcast episode 80: Using FoundationDB As The Bedrock For Your Distributed Systems (2019)](https://www.dataengineeringpodcast.com/foundationdb-distributed-systems-episode-80/)
- [Softwar Engineering Daily: FoundationDB with Ryan Worl (2019)](https://softwareengineeringdaily.com/2019/07/01/foundationdb-with-ryan-worl/)
- [Big data Hebdo 93: FoundationDB (2019 🇫🇷)](https://www.spreaker.com/user/vhe74/episode-93-foundation-db)

## Production Experience

- [Snowflake](https://www.snowflake.com/how-foundationdb-powers-snowflake-metadata-forward/) - data warehouse for the cloud
- [Wavefront](https://www.wavefront.com/wavefront-foundationdb-open-source-project/) - cloud monitoring and analytics by VMWare
- [SkuVault](https://abdullin.com/sku-vault/foundationdb-layers/) - online warehouse management system

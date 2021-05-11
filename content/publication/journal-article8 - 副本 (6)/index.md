---
title: Efficient Graph Query Processing over Geo-Distributed Datacenters
publication_types:
  - "2"
authors:
  - Y. Yuan
  - D. Ma
  - Z. Wen
  - Y. Ma
  - G. Wang and L. Chen
publication_short: 43rd International ACM SIGIR Conference on Research and
  Development in Information Retrieval (SIGIR'20). [CCF A; Core A*]
abstract: >-
  Graph queries have emerged as one of the fundamental

  techniques to support modern search services, such as PageRank web search, social networking search and knowledge

  graph search. As such graphs are maintained globally and

  very huge (e.g., billions of nodes), we need to efficiently

  process graph queries across multiple geographically distributed datacenters, running geo-distributed graph queries.

  Existing graph computing frameworks may not work well

  for geographically distributed datacenters, because they

  implement a Bulk Synchronous Parallel model that requires

  excessive inter-datacenter transfers, thereby introducing extremely large latency for query processing. In this paper,

  we propose GeoGraph–a universal framework to support

  efficient geo-distributed graph query processing based on

  clustering datacenters and meta-graph, while reducing the

  inter-datacenter communication. Our new framework can

  be applied to many types of graph algorithms without

  any modification. The framework is developed on the top

  of Apache Giraph. The experiments were conducted by

  applying four important graph queries, i.e., shortest path,

  graph keyword search, subgraph isomorphism and PageRank.

  The evaluation results show that our proposed framework

  can achieve up to 82% faster convergence, 42% lower WAN

  bandwidth usage, and 45% less total monetary cost for the

  four graph queries, with input graphs stored across ten geodistributed datacenters.
draft: false
featured: false
tags:
  - 期刊
slides: null
url_pdf: http://www.zhenyu.info/papers/Efficient%20Graph%20Query%20Processing%20over%20Geo-Distributed%20Datacenters.pdf
image:
  caption: ""
  focal_point: ""
  preview_only: false
summary: ""
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
author_notes: []
doi: ""
publication: "43rd International ACM SIGIR Conference on Research and
  Development in Information Retrieval (SIGIR'20). [CCF A; Core A*]  "
projects: []
date: 2020-10-10T11:55:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---
---
title: Performance-aware Speculative Resource Oversubscription for Large-scale
  Clusters.
publication_types:
  - "2"
authors:
  - R. Yang
  - C. Hu
  - X. Sun
  - P. Garraghan
  - T. Wo
  - Z. Wen H. Peng
  - J
  - Xu
  - C. Li.
publication_short: IEEE Transactions On Parallel and Distributed Systems. [CCF A; Core A*]
abstract: >-
  It is a long-standing challenge to achieve a high degree of resource
  utilization in cluster scheduling. Resource

  oversubscription has become a common practice in improving resource utilization and cost reduction. However, current centralized

  approaches to oversubscription suffer from the issue with resource mismatch and fail to take into account other performance

  requirements, e.g., tail latency. In this paper we present ROSE, a new resource management platform capable of conducting

  performance-aware resource oversubscription. ROSE allows latency-sensitive long-running applications (LRAs) to co-exist with

  computation-intensive batch jobs. Instead of waiting for resource allocation to be confirmed by the centralized scheduler, job managers

  in ROSE can independently request to launch speculative tasks within specific machines according to their suitability for

  oversubscription. Node agents of those machines can however avoid any excessive resource oversubscription by means of a

  mechanism for admission control using multi-resource threshold control and performance-aware resource throttle. Experiments show

  that in case of mixed co-location of batch jobs and latency-sensitive LRAs, the CPU utilization and the disk utilization can reach

  56.34% and 43.49%, respectively, but the 95th percentile of read latency in YCSB workloads only increases by 5.4% against the case

  of executing the LRAs alone.
draft: false
featured: false
tags:
  - 期刊
slides: null
url_pdf: https://www.dropbox.com/s/s88pi2kks87d81o/tpds2020-rose.pdf?dl=0
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
publication: "IEEE Transactions On Parallel and Distributed Systems. [CCF A; Core A*]  "
projects: []
date: 2020-10-10T11:55:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---
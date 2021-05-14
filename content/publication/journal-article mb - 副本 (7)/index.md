---
title: "PBUF: Sharing Buffer to Mitigate Flooding Attacks"
publication_types:
  - "2"
authors:
  - Changting Lin; Chunming Wu; Yifei Tian; Zhenyu Wen; Shouling Ji
publication_short: The 23rd IEEE International Conference on Parallel and
  Distributed Systems (ICPADS'17). [CCF C; Core B]
abstract: Software defined networking (SDN) is a promising network architecture,
  which decouples the control plane and data plane of a network. However, SDN
  opens some security challenges, such as man-in-the-middle attacks, spoofing
  attacks, flooding attacks and so on. In this paper, we focus on flooding
  attacks which consume the switch buffer and controller resource resulting in
  SDN framework resource overloaded. To prevent SDN framework from flooding
  attack, we present a defense approach called PBUF (Packet forwarding based on
  BUFfer sharing), which pools the idle switches to mitigate threat issues. This
  approach consists of buffer management and packet forwarding modules. The
  buffer management module gleans the statistics of incoming packets and then
  analyzes these statistics to estimate the buffer size by network calculus.
  Considering that a lot of table-miss packets will be generated and stored in
  buffer when the flooding attack is happening, the packet forwarding module is
  designed to forward these table-miss packets to idle switches to prevent the
  switch or controller to be overloaded. These table-miss packets will be
  buffered in idle switches and then sent to controller in a limited rate by
  generating packet_in messages. The simulation results show that PBUF is
  effective and only introduces a little overhead in SDN framework.
draft: false
featured: false
tags:
  - 期刊
slides: null
url_pdf: https://ieeexplore.ieee.org/document/9222560/author
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
publication: The 23rd IEEE International Conference on Parallel and Distributed
  Systems (ICPADS'17). [CCF C; Core B]
projects: []
date: 2017-10-10T11:55:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

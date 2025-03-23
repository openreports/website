---
title: "API Aggregation Service"
linkTitle: "API Aggregation Service"
weight: 40
description: Offload reports from etcd using API aggregation
---

Due to etcd size and performance limitations, it is recommended that reports are stored in a separate database. The [Kyverno reports service](https://github.com/kyverno/reports-server) implements an API aggregation layer that allows offloading the cluster's etcd. 

The [plan](https://github.com/orgs/openreports/projects/1) is to migrate this service to the OpenReports project.

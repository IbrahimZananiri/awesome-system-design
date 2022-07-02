# Whitepapers

## Bigtable: A Distributed Storage System for Structured Data

Abstract: Bigtable is a distributed storage system for managing structured data that is designed to scale to a very large size: petabytes of data across thousands of commodity servers. Many projects at Google store data in Bigtable, including web indexing, Google Earth, and Google Finance. These applications place very different demands on Bigtable, both in terms of data size (from URLs to web pages to satellite imagery) and latency requirements (from backend bulk processing to real-time data serving). Despite these varied demands, Bigtable has successfully provided a flexible, high-performance solution for all of these Google products.

Go to [**Bigtable** whitepaper](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)

## Google File System

Abstract: We have designed and implemented the Google File System, a scalable distributed file system for large distributed data-intensive applications. It provides fault tolerance while running on inexpensive commodity hardware, and it delivers high aggregate performance to a large number of clients.
While sharing many of the same goals as previous distributed file systems, our design has been driven by observations of our application workloads and technological environment, both current and anticipated, that reflect a marked departure from some earlier file system assumptions. This has led us to reexamine traditional choices and explore radically different design points.
In this paper, we present file system interface extensions designed to support distributed applications, discuss many aspects of our design, and report measurements from both micro-benchmarks and real world use.

Go to [**Google File System** whitepaper](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf)


## Dynamo: Amazon’s Highly Available Key-value Store

Abstract: This paper presents the design and implementation of Dynamo, a highly available key-value storage system that some of Amazon’s core services use to provide an “always-on” experience. To achieve this level of availability, Dynamo sacrifices consistency under certain failure scenarios. It makes extensive use of object versioning and application-assisted conflict resolution in a manner that provides a novel interface for developers to use.

Go to [**Dynamo** whitepaper](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)
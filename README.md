# Designing Data-Intensive Applications Notes

Personal study notes from the book **"Designing Data-Intensive Applications"** by Martin Kleppmann.

## About the Book

"Designing Data-Intensive Applications" is a comprehensive guide to building scalable, reliable, and maintainable systems that handle large amounts of data. The book explores key concepts in distributed systems, database design, and data processing, making it essential reading for backend engineers and system designers.

## Contents

This repository contains detailed notes for the following chapters:

1. **Chapter 3: Storage and Retrieval**
   - Data structures for efficient storage and retrieval
   - B-trees, LSM-trees, and hash indexes
   - Trade-offs in database engine design

2. **Chapter 4: Encoding and Evolution**
   - Data serialization formats (JSON, XML, Protocol Buffers, Avro, Thrift)
   - Schema evolution and backward/forward compatibility
   - Handling data encoding in distributed systems

3. **Chapter 5: Replication**
   - Leader-based and leaderless replication
   - Synchronous vs. asynchronous replication
   - Handling replication lag and eventual consistency

4. **Chapter 6: Partitioning**
   - Data partitioning strategies (range, hash, consistent hashing)
   - Rebalancing partitions
   - Request routing in partitioned systems

5. **Chapter 7: Transactions**
   - ACID properties and their guarantees
   - Isolation levels and race conditions
   - Multi-object transactions and distributed transactions

6. **Chapter 8: The Trouble with Distributed Systems**
   - Unreliable networks and clocks
   - Partial failures and failure detection
   - Challenges in building reliable systems

7. **Chapter 9: Consistency and Consensus**
   - Linearizability and causal consistency
   - Consensus algorithms and leader election
   - Distributed decision making

## How to Use

These notes serve as a study guide and reference material for understanding the core concepts of designing scalable data systems. Each chapter builds on fundamental concepts to provide a complete picture of modern distributed system design.

## Note

These are personal study notes compiled while reading the book. For comprehensive understanding, please refer to the original book and its examples.

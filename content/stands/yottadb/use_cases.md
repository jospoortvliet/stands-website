---
title: "Use Cases"
draft: false
---

# Use Cases

## Transactional Systems
A real-time transaction processing system is one that records in a database the change in state of an entity as it happens (instead of, for example, capturing changes of state on paper or other means, then processing the data in a "batch" process). A change in the state may be registering a patient at the hospital, recording an empty parking space as occupied, transferring money from one account to another, shipping a widget from a warehouse, etc. Maintaining response times within agreed-to service levels is important.

YottaDB excels as a platform for real-time transaction processing as a consequence of its throughput and scalability, security, logical multi-site application deployment configurations and [ACID](https://en.wikipedia.org/wiki/ACID)(Atomic, Consistent, Isolated, Durable) transaction semantics.

## Health Records

[M](https://en.wikipedia.org/wiki/MUMPS) is a de facto standard for implementing electronic health record applications, and the largest electronic health record systems in the world are written in M, dominating the segment as effectively as SQL dominates accounting and business applications.

The YottaDB code base has its roots in healthcare as an implementation of M, with its first deployment at the Elvis Presley Trauma Center in Memphis in 1986. YottaDB includes an M language subsystem that is mostly compliant with, and extends the ISO/IEC 11756:1999 and ISO/IEC 15851:1999 standards. The YottaDB code base is one of the standard platforms for implementing VistA, ranging from small primary care practices and community clinics, to hospitals such as Oroville Hospital, to Hakeem, an electronic health record system for an entire country.

## Internet of Things

YottaDB fits the needs of real-time IoT systems that need to be “always on” because of its proven availability, reliability and security. Because it is highly scalable and multi-model, it can also handle the varying requirements of application data with ease.

Plus, using a single database engine for the edge and the cloud simplifies application design and operational management, as well as allowing data to move seamlessly from one instance to another.


## Machine Learning and AI

As a language-agnostic, multi-level, key-value database, YottaDB fits well with leading open source ML and data science libraries like H2O, TensorFlow, Keras, and Scikit-learn as well as commercial platforms like DataRobot and Dataiku.

With support for SQL, Go, Perl, Python, Rust and other languages, plus JDBC access, YottaDB is ready for business-critical AI applications. 
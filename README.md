# Resources on designing and operating distributed systems.

## General Concepts
- https://blog.pragmaticengineer.com/operating-a-high-scale-distributed-system/
- https://blog.pragmaticengineer.com/distributed-architecture-concepts-i-have-learned-while-building-payments-systems/
- https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/acrobat-17.pdf (Hints for Computer System Design, Butler Lampson)
- https://engineering.salesforce.com/runway-intro-dc0d9578e248 - Runway design tool for distributed systems
  - https://runway.systems/
- https://blog.acolyer.org/2016/10/31/designing-software-for-ease-of-extension-and-contraction/
- https://blog.acolyer.org/2016/09/12/on-designing-and-deploying-internet-scale-services/ (also see https://gist.github.com/acolyer/95ef23802803cb8b4eb5 as a checklist for large-scale services)
- https://blog.acolyer.org/2019/11/20/local-first-software/
- [System Design Primer](https://github.com/donnemartin/system-design-primer)
- [Amazon Builder's Library](https://aws.amazon.com/builders-library/)


## Books
- Designing Data-Intensive Applications: https://dataintensive.net/


## Event Sourcing/CQRS (Command-Query Responsibility Segregation)/Event Logging
- https://www.ahri.net/2019/07/practical-event-driven-and-sourced-programs-in-haskell/
- https://engineering.salesforce.com/mirrormaker-performance-tuning-63afaed12c21 (Kafka replication performance tuning)
- https://github.com/message-db/message-db (Implementation of messaging/events in Postgres)
- https://arkwright.github.io/event-sourcing.html


## Databases
- https://brandur.org/cloud-databases (compares Aurora, Spanner, Citus, others)
- https://engineering.salesforce.com/the-architecture-files-ep-2-the-crystal-shard-a6025bd9f968 (Salesforce scaling by sharding)
- https://developer.salesforce.com/page/Multi_Tenant_Architecture (Details on Salesforce's multitenant architecture)
- https://engineering.salesforce.com/inside-and-out-transactions-b9535faa5924 (transactions in Salesforce)


## Logging/Monitoring/Alerting
- https://stripe.com/blog/canonical-log-lines
- https://www.honeycomb.io/
  - Discussion: https://news.ycombinator.com/item?id=20569813
- https://opensource.googleblog.com/2019/08/opencensus-web-unlocking-full-end-to.html
- https://engineering.salesforce.com/implementation-of-a-monitoring-strategy-for-products-based-on-microservices-24ad24c4c3e5
- https://linuxczar.net/sysadmin/philosophy-on-alerting/
- https://www.transposit.com/blog/2019.11.14-what-makes-a-good-runbook/
- https://github.com/danielfm/prometheus-for-developers


## Microservices
- https://philcalcado.com/2017/06/11/calcados_microservices_prerequisites.html
- Communication between microservices:
  - Using message queues for request/response - https://www.quora.com/Why-use-message-queues-for-a-request-response-pattern-which-is-synchronous-when-queues-are-asynchronous
  - https://servicemesh.io/


## Idempotency
- https://stripe.com/blog/idempotency
- https://brandur.org/idempotency-keys
- https://brandur.org/http-transactions


## Background Job Processing
- https://brandur.org/job-drain


## Serverless/FaaS
- https://www.owasp.org/index.php/OWASP_Serverless_Top_10_Project (security)
- Lambda tuning - https://github.com/alexcasalboni/aws-lambda-power-tuning


## AWS Cost Analysis
- https://segment.com/blog/the-10m-engineering-problem/


## Simultaneous Work (operational transforms, conflict-free replicated data types, etc.)
- http://archagon.net/blog/2018/03/24/data-laced-with-history/
- https://blog.acolyer.org/2019/11/25/mergeable-replicated-data-types-part-i/
- https://blog.acolyer.org/2014/11/27/swiftcloud-fault-tolerant-geo-replication-integrated-all-the-way-to-the-client/
- https://www.tiny.cloud/blog/real-time-collaboration-ot-vs-crdt/
  - Also see discussion: https://news.ycombinator.com/item?id=22039950


## Chaos Engineering
- https://www.gremlin.com/

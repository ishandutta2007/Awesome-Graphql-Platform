# Awesome-Graphql-Platform

## Top GraphQL Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on GraphQL Federation, Schema Registry, Gateways, Instant APIs, Caching & Graph Management*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **GraphQL**. These systems provide schema registries, federation gateways, instant GraphQL APIs over databases, edge caching, observability, and developer tooling for building and operating GraphQL APIs at scale.



**Examples** include Apollo GraphOS, Hasura, StepZen, GraphCDN (Stellate), WunderGraph, Hygraph, GraphQL Hive, Stellate, 8base, and Dgraph Cloud (the category leaders).



**Open-source emphasis**: GraphQL has a very strong open-source ecosystem. **GraphQL Hive**, **Hasura CE**, **GraphQL Yoga**, **Apollo Server**, **Dgraph**, and **WunderGraph Cosmo** enable full self-hosted federation, gateways, and GraphQL servers. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Apollo GraphOS](https://www.apollographql.com/graphos)**  

  Apollo’s managed platform for GraphQL federation—schema registry, Studio collaboration, supergraph management, observability, and enterprise governance.



- **[Hasura Cloud](https://hasura.io/)**  

  Instant GraphQL (and REST) APIs over databases with authorization, event triggers, and federated data delivery—available as managed cloud and open-source CE.



- **[StepZen (IBM)](https://www.ibm.com/products/stepzen)**  

  GraphQL federation and API composition platform for building unified graphs over existing REST, SOAP, and database sources.



- **[Stellate (formerly GraphCDN)](https://stellate.co/)**  

  Edge caching, rate limiting, and analytics platform purpose-built for GraphQL APIs to improve performance and protect backends.



- **[WunderGraph Cloud / Cosmo Cloud](https://wundergraph.com/)**  

  GraphQL federation and API composition platform with open-source Cosmo core and managed cloud options for schema management and gateways.



- **[Hygraph](https://hygraph.com/)**  

  Headless CMS with a native GraphQL content API, used for content-driven applications and federated content graphs.



- **[GraphQL Hive Cloud](https://the-guild.dev/graphql/hive)**  

  Managed offering of the open-source GraphQL Hive platform—schema registry, usage analytics, and federation gateway services.



- **[8base](https://www.8base.com/)**  

  Backend-as-a-service platform with GraphQL APIs, data modeling, and serverless functions for application backends.



- **[Dgraph Cloud](https://dgraph.io/)**  

  Managed graph database with native GraphQL API support for building graph-powered applications.



- **[Other managed GraphQL BaaS / CMS offerings](https://www.example.com/)**  

  Additional hosted platforms providing GraphQL APIs over content or application data models.



## Open-Source GitHub Projects

- **[GraphQL Hive](https://github.com/graphql-hive)**  

  Fully open-source (MIT) schema registry, analytics, and GraphQL federation gateway/router platform—self-host or use managed Hive Cloud.



- **[Hasura GraphQL Engine (CE)](https://github.com/hasura/graphql-engine)**  

  Open-source engine that generates GraphQL (and REST) APIs over Postgres and other databases with authorization and eventing.



- **[GraphQL Yoga](https://github.com/graphql-hive/graphql-yoga)**  

  Fully-featured, easy-to-use open-source GraphQL server focused on performance and developer experience; runs on any JS environment.



- **[Hive Gateway / Router](https://github.com/graphql-hive/gateway)**  

  Open-source GraphQL federation gateway and proxy (JS and Rust router options) compatible with Apollo Federation.



- **[Apollo Server](https://github.com/apollographql/apollo-server)**  

  Popular open-source GraphQL server for Node.js, widely used as a subgraph or standalone GraphQL API runtime.



- **[WunderGraph Cosmo](https://github.com/wundergraph/cosmo)**  

  Open-source GraphQL federation platform (Apache 2.0) with schema registry, router, and compatibility with Apollo Federation.



- **[Dgraph](https://github.com/dgraph-io/dgraph)**  

  Open-source distributed graph database with native GraphQL support for building graph applications.



- **[Mercurius / other Fastify GraphQL servers](https://github.com/mercurius-js/mercurius)**  

  High-performance open-source GraphQL servers for Node.js frameworks.



- **[GraphQL Mesh / composition tools](https://github.com/)**  

  Open tools for composing GraphQL schemas from multiple sources (REST, gRPC, databases, other GraphQL APIs).



- **[Relay, urql, Apollo Client and open GraphQL clients](https://github.com/)**  

  Client-side open-source libraries for consuming GraphQL APIs in applications.



### Additional Strong Open-Source Options

- Running **GraphQL Hive + Hive Gateway** as a full open alternative to commercial federation control planes.

- Using **Hasura CE** for instant GraphQL over databases with self-hosted control.

- Building subgraphs with **GraphQL Yoga** or **Apollo Server** and composing them via open federation routers.

- Choosing **WunderGraph Cosmo** for Apache-licensed federation compatible with existing Apollo Federation subgraphs.

- Accepting that polished enterprise Studio UX, global managed edge, and turnkey SLAs still favor commercial platforms (Apollo GraphOS, Hasura Cloud, Stellate, etc.).

- Focusing open-source efforts on avoiding lock-in, schema ownership, and self-hosted federation at scale.



**Frameworks for building custom systems**: Define subgraphs with Yoga/Apollo Server/Hasura → register schemas in GraphQL Hive or Cosmo → run Hive Gateway or Cosmo Router as the supergraph → cache at the edge with open or commercial layers → observe with open telemetry. Suitable for platform teams that want full control. Many organizations combine open runtimes with commercial schema registries or vice versa.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- GraphQL platforms expose application data and business logic. Secure schema design, authorization, and rate limiting are essential. Self-hosted deployments require proper hardening. This list is not security advice.



---

**Made for API platform engineers, backend developers, and teams building federated GraphQL architectures.**

Let's keep the graph open, composable, and under your control.

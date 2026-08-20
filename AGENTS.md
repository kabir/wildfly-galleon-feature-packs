# WildFly Galleon Feature Packs -- Agent Instructions

This repository is the central registry of Galleon feature packs for WildFly server provisioning. It maintains per-version directories containing provisioning XML files that list compatible feature packs for bare-metal and cloud execution contexts. WildFly Glow reads this registry from the `release` branch to discover which feature packs are available for a given WildFly version.

## Ecosystem Context & Cross-Repo Routing

- **Local Tasks:** For provisioning file updates, adding new WildFly versions, registering extra feature packs, or modifying the release process, consult the local [WildFly Galleon Feature Packs Documentation Index](https://raw.githubusercontent.com/kabir/wildfly-galleon-feature-packs/ai-index/llms.txt).
- **Cross-Repository Tasks:** For changes involving upstream or downstream components, consult the [WildFly Central AI Hub](https://raw.githubusercontent.com/kabir/wildfly-ai-context/main/llms.txt) and look up the target project:
    - *Core server kernel, management model, or CLI changes* --> Navigate to **WildFly Core** (kabir/wildfly-core).
    - *Full application server features, Jakarta EE subsystems, clustering, or Elytron security* --> Navigate to **WildFly Full** (kabir/wildfly).
    - *Maven plugin for building/provisioning WildFly servers* --> Navigate to **WildFly Maven Plugin** (kabir/wildfly-maven-plugin).
    - *Provisioning analysis, layer discovery, or Glow scanning logic* --> Navigate to **WildFly Glow** (kabir/wildfly-glow).
    - *Cloud-specific Galleon feature pack content* --> Navigate to **wildfly-cloud-galleon-pack**.
    - *Datasource Galleon feature pack content* --> Navigate to **wildfly-datasources-galleon-pack**.
    - *gRPC Galleon feature pack content* --> Navigate to **wildfly-grpc-feature-pack**.
    - *MyFaces Galleon feature pack content* --> Navigate to **wildfly-myfaces-feature-pack**.
    - *GraphQL Galleon feature pack content* --> Navigate to **wildfly-graphql-feature-pack**.
    - *Vault Galleon feature pack content* --> Navigate to **wildfly-vault-feature-pack**.

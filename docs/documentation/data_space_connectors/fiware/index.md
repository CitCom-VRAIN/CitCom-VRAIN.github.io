# FIWARE

Fiware is embarking on the development of different services that in combination meet the requirements defined for implementing a data space. For these developments they are following the [DSBA Technical Convergence](https://data-spaces-business-alliance.eu/wp-content/uploads/dlm_uploads/Data-Spaces-Business-Alliance-Technical-Convergence-V2.pdf) recomentations.

This is a technology that Fiware **currently has in development**, so it is open to major modifications. Currently, versions 2.x.x are the most advanced, achieving significant improvements in simplicity and ease of use at the local level compared to versions 1.x.x.

## Legacy version (1.x.x)

### Demo-Setup DSBA-compliant

As a first approximation of a future data space, Fiware developed a fairly complete example ([Demo-Setup DSBA-compliant Dataspace](https://github.com/FIWARE-Ops/fiware-gitops/tree/master/aws/dsba)), which tries to address the main blocks of a data space:

- [Data Space Operator](legacy_1.X.X/index.md#data-space-operator) (Trust Anchor)
- [Marketplace](legacy_1.X.X/#marketplace)
- [Data Space Connector](legacy_1.X.X/#fiware-data-space-connector) (Provider or Consumer)

![dataspace_schema](./img/fiware_dataspace.png)

However, this example is a demo to show the feasibility of the technology, but **it is far from being easily reusable in other real environments or putting it into production systems**. Furthermore, it is designed to be deployed in [Red Hat Openshift AWS](https://aws.amazon.com/es/rosa/), so the cost of maintaining it may be a limiting factor for a simple test of the technology.

### Minimum Data Space

As an alternative to the previous Fiware example, a minimum data space architecture is proposed, which consists of:

- [Trusted Participant/Issuers Registry](https://github.com/FIWARE/trusted-issuers-registry) (fulfilling the functions of Trust Anchor). 
- [FIWARE Data Space Connector](https://github.com/FIWARE-Ops/data-space-connector) (at least two).

This architecture is what we could call the Minimum Data Space.

![minimum_dataspace_schema](./img/minimum_dataspace_arch.png)

### Guidelines for deployments

[Guidelines](./legacy_1.X.X/index.md#deployments)

## Latest version (2.x.x)

- New version

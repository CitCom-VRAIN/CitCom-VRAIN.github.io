---
title: Overview
---

<div class="grid cards" markdown>

-   :material-store-search-outline:{ .lg .middle } __Eclipse__

    ---

    Eclipse data space connector.

    [:octicons-arrow-right-24: Learn more](./eclipse_mvd.md)

-   :material-store-search-outline:{ .lg .middle } __Fiware__

    ---

    Fiware data space connector.

    [:octicons-arrow-right-24: Learn more](./fiware/index.md)

</div>

## Status overview of existing connectors

The following list has been extracted from Section 2.1 of the [IDSA Data Connector Report (January 2024)](https://internationaldataspaces.org/wp-content/uploads/dlm_uploads/IDSA-Data-Connector-Report-89-No-11-January-2024.pdf). **Only open source connectors have been considered:**

| Name of connector                                                                                  | Real-time data   |    MIM 1 ready   |    MIM 2 ready   | Deployment guide - Quality grade |                                                                                                                                                                                Comments                                                                                                                                                                               |
|----------------------------------------------------------------------------------------------------|------------------|:----------------:|:----------------:|----------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| [Eclipse Dataspace Connector (EDC Connector)](https://github.com/eclipse-edc/Connector)                               |         ✓        |         ✕        |         ✓        |                 A                |                                                                                                                                                                                                                                                                                                                                                                       |
| [EdgeDS Connector](https://github.com/jkalogero/EdgeDS)                                            |         -        |         -        |         -        |                 -                | Based on [IDSA DSC](https://github.com/International-Data-Spaces-Association/DataspaceConnector), which is currently no longer maintained but looking for new maintainers.                                                                                                                                                                                            |
| [EGI Datahub Connector](https://docs.egi.eu/users/data/management/datahub)                         | _Pending review_ |         ✕        |         ✓        |         _Pending review_         |                                                                                                                                                                                                                                                                                                                                                                       |
| [FIWARE Data Space Connector](https://github.com/FIWARE/data-space-connector)                      |         ✓        |         ✓        |         ✓        |                 C                | At this moment, deployment guides are only available on AWS with Openshift. Poor documentation. High computational requirements on AWS with Openshift.                                                                                                                                                                                                                |
| [GATE Dataspace Connector](https://github.com/gate-institute/DataspaceConnector/blob/main/LICENSE) |         -        |         -        |         -        |                 -                | Based on [IDSA DSC](https://github.com/International-Data-Spaces-Association/DataspaceConnector), which is currently no longer maintained but looking for new maintainers                                                                                                                                                                                             |
| OneNet Connector                                                                                   | _Pending review_ | _Pending review_ | _Pending review_ |         _Pending review_         | **Source Code will be available in GitHub upon project completion.**.Based on [TRUE connector](https://github.com/International-Data-Spaces-Association/true-connector). Claims to be ready-to-go, ready to be installed in any environment and integrated with existing platforms via APIs. Fully integrated with the FIWARE Context Broker (in the NGSI-LD version) |
| Silicon Economy EDC                                                                                | _Pending review_ | _Pending review_ | _Pending review_ |         _Pending review_         | A reference implementation of the Connector from the Eclipse Dataspace Components (EDC) for Silicon Economy projects. 

!!! Info

    More information about Data Spaces [here](../../getting_started/data_spaces/index.md).
# Azure IoT Projects

Production-style Azure IoT engineering projects by Mohammad Rafay Khan. Each project is a
self-contained repo with Bicep infrastructure, deploy and teardown scripts, tests and CI,
architecture decision records, and a run verified against live Azure.

## Projects

| # | Project | What it shows |
|---|---------|---------------|
| 1 | [**Device ↔ Cloud Control**](https://github.com/mohammadrafaykhan/azure-iot-device-control) | Telemetry, cloud-to-device messages, direct methods, and device twins with Plug and Play acknowledgements; an X.509 device; a service CLI on Microsoft Entra ID |
| 2 | [**Zero-Touch Fleet Provisioning**](https://github.com/mohammadrafaykhan/azure-iot-fleet-provisioning) | Device Provisioning Service with a three-level X.509 PKI, an enrollment group, one-step revocation, certificate rotation, and a managed-identity DPS link; no keys anywhere |
| 3 | [**Telemetry Routing & Alerting**](https://github.com/mohammadrafaykhan/azure-iot-telemetry-routing) | IoT Hub message routing with queries and enrichments into an event-driven Azure Functions pipeline: a raw archive, threshold alerts with debounce and hysteresis, offline and silent device detection, and Azure Monitor alerting; Entra ID end to end |

## Skills demonstrated

Azure IoT Hub · Device Provisioning Service · X.509 PKI · message routing · Event Hubs ·
Azure Functions (Flex Consumption) · Event Grid · Table and Blob storage · Azure Monitor ·
Microsoft Entra ID and RBAC · managed identities · Key Vault · Bicep · Python (asyncio) ·
GitHub Actions

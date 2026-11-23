# Azure IoT Projects

Production-style Azure IoT engineering projects by Mohammad Rafay Khan. Each project is a
self-contained repo with Bicep infrastructure, deploy and teardown scripts, tests and CI,
architecture decision records, and a run verified against live Azure.

## Projects

| # | Project | What it shows | Status |
|---|---------|---------------|--------|
| 1 | [**Device ↔ Cloud Control**](https://github.com/mohammadrafaykhan/azure-iot-device-control) | Telemetry, cloud-to-device messages, direct methods, and device twins with Plug and Play acknowledgements; an X.509 device; a service CLI on Microsoft Entra ID | ✅ Complete |
| 2 | [**Zero-Touch Fleet Provisioning**](https://github.com/mohammadrafaykhan/azure-iot-fleet-provisioning) | Device Provisioning Service with a three-level X.509 PKI, an enrollment group, one-step revocation, certificate rotation, and a managed-identity DPS link; no keys anywhere | ✅ Complete |
| 3 | **Telemetry Routing & Alerting** | IoT Hub message routing, Azure Functions with managed identity, storage, connectivity alerts through Event Grid | 🔜 Next |
| 4 | **Edge ML on IoT Edge** | ONNX inference module on IoT Edge 1.6, over-the-air model updates with integrity checks, CI to Azure Container Registry | Planned |
| 5 | **Digital Twin Advisory Loop** | DTDL models in Azure Digital Twins, event-driven updates, work orders through Logic Apps | Planned |
| 6 | **OPC UA to Cloud** | Industrial data from an OPC UA server to IoT Hub with OPC Publisher | Planned |

## Skills demonstrated

**So far:** Azure IoT Hub · Device Provisioning Service · X.509 PKI · Microsoft Entra ID and RBAC ·
managed identities · Key Vault · Bicep · Python (asyncio) · GitHub Actions

**Coming:** message routing · Azure Functions · Event Grid · IoT Edge · ONNX · Azure Container
Registry · Azure Digital Twins · Logic Apps · OPC UA

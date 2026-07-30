# SAP CX AI Presales Demo — Joule Skill

A single parameterised AI skill for SAP presales demonstrations. Simulates SAP Joule as an AI Commerce or CRM assistant across **25 industry verticals** using illustrative mock data. No live SAP system is connected.

## Install

```bash
npx skills add sourajitaghosh/sap-cx-ai-presales-demo-sg-Aug2026_v1
npx skills add sourajitaghosh/sap-cx-ai-presales-demo-sg-Aug2026_v1 --skill sap-cx-ai-presales-demo
npx skills add sourajitaghosh/sap-cx-ai-presales-demo-sg-Aug2026_v1 --list
```

## How to Start a Demo

Every demo has three trigger forms — use any one, or combine all three:

| Form | Example |
|---|---|
| Portal / brand name | `start the VeriSupply demo` |
| Industry + business process | `start the pharma B2B commerce demo` |
| All three combined | `start the pharma VeriSupply B2B commerce demo` |

CRM mode: `start the ApexDrive B2B sales service CRM demo`

---

## Supported Demos — Full Trigger Table

### B2B Commerce (25 industries)

| # | Industry | Portal / Brand | Trigger 1 — Portal | Trigger 2 — Industry + Process | Trigger 3 — All Three Combined |
|---|---|---|---|---|---|
| 1 | Healthcare | Metropolitan Health Portal | `start the metropolitan health demo` | `start the healthcare B2B commerce demo` | `start the healthcare metropolitan health B2B commerce demo` |
| 2 | Pharma | VeriSupply Connect | `start the VeriSupply demo` | `start the pharma B2B commerce demo` | `start the pharma VeriSupply B2B commerce demo` |
| 3 | Medical Device | MedConnect Portal | `start the PulseTech demo` | `start the medical device B2B commerce demo` | `start the medical device PulseTech B2B commerce demo` |
| 4 | Medical Distribution | NovaMed Supply Portal | `start the NovaMed demo` | `start the medical distribution B2B commerce demo` | `start the medical distribution NovaMed B2B commerce demo` |
| 5 | Specialty Pharmacy | ClearPath Pharmacy Portal | `start the ClearPath demo` | `start the specialty pharmacy patient commerce demo` | `start the specialty pharmacy ClearPath patient commerce demo` |
| 6 | Industrial MRO | SupplyForce Pro | `start the SupplyForce demo` | `start the industrial MRO B2B commerce demo` | `start the industrial MRO SupplyForce B2B commerce demo` |
| 7 | Industrial Machinery | ProForge Portal | `start the ProForge demo` | `start the industrial machinery B2B commerce demo` | `start the industrial machinery ProForge B2B commerce demo` |
| 8 | Heavy Equipment | IronForce Fleet Connect | `start the IronForce demo` | `start the heavy equipment B2B fleet commerce demo` | `start the heavy equipment IronForce B2B fleet commerce demo` |
| 9 | Automotive Aftermarket | AutoVantage Pro Parts Network | `start the AutoVantage demo` | `start the automotive aftermarket B2B commerce demo` | `start the automotive aftermarket AutoVantage B2B commerce demo` |
| 10 | Automotive Tier 1 | VelocityDrive Supplier Portal | `start the VelocityDrive demo` | `start the automotive tier 1 B2B commerce demo` | `start the automotive tier 1 VelocityDrive B2B commerce demo` |
| 11 | Electrical Distribution | VoltEdge B2B Portal | `start the VoltEdge demo` | `start the electrical distribution B2B commerce demo` | `start the electrical VoltEdge B2B commerce demo` |
| 12 | Electronics | Nexlayer Commerce Portal | `start the Nexlayer demo` | `start the electronics B2B commerce demo` | `start the electronics Nexlayer B2B commerce demo` |
| 13 | Energy | GridBridge Energy Portal | `start the GridBridge demo` | `start the energy B2B commerce demo` | `start the energy GridBridge B2B commerce demo` |
| 14 | Enterprise Infrastructure | CoreAxis B2B Portal | `start the CoreAxis demo` | `start the enterprise infrastructure B2B commerce demo` | `start the enterprise infrastructure CoreAxis B2B commerce demo` |
| 15 | Foodservice | FoodLink B2B Portal | `start the PrimeServe demo` | `start the foodservice B2B commerce demo` | `start the foodservice PrimeServe B2B commerce demo` |
| 16 | Hospitality | Hospitality Connect | `start the LuminaStay demo` | `start the hospitality B2B commerce demo` | `start the hospitality LuminaStay B2B commerce demo` |
| 17 | Lab & Life Sciences | LabVantage Science Portal | `start the LabVantage demo` | `start the lab life sciences B2B commerce demo` | `start the lab sciences LabVantage B2B commerce demo` |
| 18 | OEM Vehicle Fleet | VeloCraft Fleet Connect | `start the VeloCraft demo` | `start the OEM vehicle fleet B2B commerce demo` | `start the OEM fleet VeloCraft B2B fleet commerce demo` |
| 19 | Oil & Gas | EnergyLink B2B Portal | `start the TerraStream demo` | `start the oil gas B2B commerce demo` | `start the oil gas TerraStream B2B commerce demo` |
| 20 | Oilfield Services | PetroServ Field Services Portal | `start the PetroServ demo` | `start the oilfield services B2B commerce demo` | `start the oilfield PetroServ B2B commerce demo` |
| 21 | SaaS / Software | Nexus Software Portal | `start the Nexus demo` | `start the SaaS B2B commerce demo` | `start the SaaS Nexus B2B commerce demo` |
| 22 | Semiconductor | NexaChip Design & Commerce Portal | `start the NexaChip demo` | `start the semiconductor B2B commerce demo` | `start the semiconductor NexaChip B2B commerce demo` |
| 23 | Specialty Chemicals | SpectraChem Connect | `start the SpectraChem demo` | `start the specialty chemicals B2B commerce demo` | `start the specialty chemicals SpectraChem B2B commerce demo` |
| 24 | Streaming & Media | MediaConnect Portal | `start the NovaCast demo` | `start the streaming media B2B commerce demo` | `start the streaming media NovaCast B2B commerce demo` |
| 25 | CPG / Pet Nutrition | Consumer + Professional Portal | `start the CPG pet nutrition demo` | `start the CPG B2B consumer commerce demo` | `start the CPG pet nutrition B2B consumer professional commerce demo` |

### CRM / Sales & Service (1 mode)

| Mode | Platform | Trigger 1 | Trigger 2 | Trigger 3 |
|---|---|---|---|---|
| Sales & Service CRM | Joule Work Desktop + MCP Server | `start the ApexDrive demo` | `start the CRM demo` | `start the ApexDrive B2B sales service CRM demo` |

---

## What Each Demo Covers

### B2B Commerce — 7 Capability Flows (all 25 industries)

1. **Shopping Assistant** — need-based product discovery
2. **Compatibility Intelligence** — installed-base validation
3. **Contract Pricing & Quote** — formal quote generation
4. **Order Management** — checkout, tracking, invoice
5. **Smart Reorder & Replenishment** — reorder rules and automation
6. **Email & RFQ Intake** — document-to-quote processing
7. **Account Growth & Intelligence** — predictive analytics and lifecycle

### CRM / Sales & Service — 9 Acts

Lead Intelligence → Deal Preparation → CRM Updates → Risk Assessment → Quote Creation → Supply Chain Validation → Order Conversion → Service Case Management → Knowledge Creation

---

## SAP Products Illustrated

- SAP Commerce Cloud (B2B Commerce demos)
- SAP Sales Cloud (CRM demo)
- SAP Service Cloud (CRM demo)
- SAP Customer Data Platform
- SAP Business AI Platform / SAP Joule

> **Note:** All scenarios are illustrative simulations using mock data. No live SAP system is connected. These demos are intended to show how SAP Joule and CX AI capabilities would work in a real deployment.

---

## Repository Structure

```
skills/
└── sap-cx-ai-presales-demo/
    ├── SKILL.md
    └── references/
        └── industry-profiles.md
```

---

## License

Copyright 2026 Sourajit Ghosh. Licensed under [Apache-2.0](LICENSE).

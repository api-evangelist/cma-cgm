# CMA CGM (cma-cgm)

CMA CGM is a Marseille-headquartered French container shipping, logistics, and port operator and the third-largest ocean carrier in the world. Founded in 1978 by Jacques Saadé and led today by Chairman & CEO Rodolphe Saadé, the CMA CGM Group operates a fleet of 593 vessels with 4.5M TEU capacity calling 420 ports across 160 countries on 257 maritime services. Through `api-portal.cma-cgm.com` the group exposes a DCSA-aligned REST API surface — Track and Trace v1, Schedules, Booking Request, Quotation, and Invoice — alongside a parallel EDIFACT EDI catalog, the CEVA Logistics tracking API, Traxens-based smart container telemetry, the ZEBOX startup accelerator, and a strategic AI partnership with Mistral.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/cma-cgm/refs/heads/main/apis.yml)

## Tags

Shipping, Container Shipping, Maritime, Logistics, Freight, Supply Chain, Ports, Terminals, Track and Trace, DCSA, EDI, Air Cargo, Intermodal, Ocean Freight, Smart Containers

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Group Snapshot

| Metric | Value |
|---|---|
| Founded | 1978 (Marseille, France) |
| Chairman & CEO | Rodolphe Saadé |
| Headquarters | CMA CGM Tower, Marseille |
| Fleet | 593 vessels — 4.5M TEU |
| Services | 257 maritime services calling 420 ports in 160 countries |
| Employees | ~160,000 |
| Revenue (FY2024) | $55.48B |
| Q1 2026 Revenue | $13.23B |
| Ranking | #3 container carrier (after Maersk, MSC) |
| Alliance | Ocean Alliance (with COSCO, Evergreen) |

## APIs

### CMA CGM Track and Trace API
DCSA Track & Trace v2.2.0 REST API at `https://apis.cma-cgm.net/operation/trackandtrace/v1`. Public tier uses an API key for equipment moves, transshipments, and planned vessel dates; Private tier uses OAuth2 client credentials and verified booking-party identity to additionally expose actual rail/ramp moves and inland event detail.

**Human URL:** [https://api-portal.cma-cgm.com/products/api/operation.trackandtrace.v1](https://api-portal.cma-cgm.com/products/api/operation.trackandtrace.v1)

### CMA CGM Schedules API
Point-to-point sailing solutions, port schedules, and vessel itineraries across the CMA CGM, ANL, APL, CNC, and Containerships networks for a 12-week horizon. Parallels the EDIFACT IFTSAI feed.

**Human URL:** [https://api-portal.cma-cgm.com/products/schedules](https://api-portal.cma-cgm.com/products/schedules)

### CMA CGM Quotation API
Spot quotations and US service contracts with ocean freight rates plus the full surcharge breakdown (BAF, currency, security, handling, peak season).

**Human URL:** [https://api-portal.cma-cgm.com/](https://api-portal.cma-cgm.com/)

### CMA CGM Booking Request API
Programmatic booking submission, amendment, and cancellation against CMA CGM Group services. REST surface mirrors the EDIFACT IFTMBF booking message.

**Human URL:** [https://api-portal.cma-cgm.com/products/api/shipping.bookingrequest.v1](https://api-portal.cma-cgm.com/products/api/shipping.bookingrequest.v1)

### CMA CGM Invoice API
Invoice API family including a Copy Invoice PDF operation for retrieving the original PDF artifact for any invoice number. Parallels the EDIFACT INVOIC feed.

**Human URL:** [https://api-portal.cma-cgm.com/](https://api-portal.cma-cgm.com/)

### CEVA Logistics Tracking API
Shipment tracking REST API from CMA CGM's contract logistics and freight forwarding subsidiary, covering road, ocean, air, and contract logistics flows.

**Human URL:** [https://developer.cevalogistics.com/](https://developer.cevalogistics.com/)

## Subsidiaries & Brands

| Brand | Domain |
|---|---|
| CEVA Logistics (contract logistics, forwarding) | [cevalogistics.com](https://www.cevalogistics.com) |
| APL (American President Lines) | [apl.com](https://www.apl.com) |
| ANL (Australian National Line) | [anl.com.au](https://www.anl.com.au) |
| CNC Line (Cheng Lie Navigation) | [cnc-line.com](https://www.cnc-line.com) |
| Containerships | [containershipsgroup.com](https://www.containershipsgroup.com) |
| Comanav (Compagnie Marocaine de Navigation) | — |
| Mercosul Line | — |
| CMA CGM Air Cargo (4 A330-200F, 2 B777F) | [cmacgm-aircargo.com](https://www.cmacgm-aircargo.com) |
| CMA Terminals / Terminal Link | [cma-cgm.com](https://www.cma-cgm.com) |
| La Méridionale (Corsica ferries) | — |
| Brittany Ferries (stake) | — |
| Freightliner (UK intermodal, acquired 2026) | — |
| CMA Média (La Provence, Corse-Matin, La Tribune, BFM-RMC, Brut) | — |

## Common Properties

- [Website](https://www.cma-cgm.com)
- [Group](https://www.cmacgm-group.com/en)
- [API Portal](https://api-portal.cma-cgm.com/)
- [MyCMA CGM Portal](https://www.cma-cgm.com/my-cma-cgm)
- [Usage Guide](https://api-portal.cma-cgm.com/usage-guide)
- [Release Notes](https://api-portal.cma-cgm.com/release-notes)
- [EDI Catalog](https://cloud.customer.cmacgm-group.com/EDI_catalog_EN)
- [EDI & API Solutions](https://www.cma-cgm.com/products-services/ecommerce/edi-api-channels)
- [API Support](https://mycustomerservice.cma-cgm.com/s/selfcare/article/API-Solution)
- [Schedules](https://www.cma-cgm.com/ebusiness/schedules)
- [Documents & BL](https://www.cma-cgm.com/products-services/ecommerce/documents-bl)
- [Finance / Invoices](https://www.cma-cgm.com/products-services/ecommerce/finance)
- [Smart Containers (Traxens)](https://www.cma-cgm.com/services/smart-containers)
- [Sustainability & Innovation](https://www.cmacgm-group.com/en/sustainability-and-innovation)
- [Digital & Startup Support](https://www.cmacgm-group.com/en/innovation/digital-startup%20support)
- [ZEBOX Accelerator](https://www.ze-box.io/)
- [Newsroom](https://www.cmacgm-group.com/en/news-media)
- [GitHub Organization](https://github.com/cma-cgm)
- [DCSA Standard](https://dcsa.org/)

## Strategic Notes

- **DCSA founding member.** CMA CGM's Track & Trace REST API is one of the earliest and most complete carrier implementations of the DCSA v2.2.0 OpenAPI standard, demonstrating governance maturity around shared maritime data semantics.
- **Two-tier auth model.** Public connection (API Key, free trial) vs Private connection (OAuth2 client credentials, scopes like `tandtcommercial:read:be`) is a clean pattern other carriers should imitate — public data is public, contractual data sits behind verified booking-party identity.
- **REST + EDI parity.** Each REST product (Schedules, Booking, Tracking, Invoice) is shipped alongside the equivalent EDIFACT message (IFTSAI, IFTMBF, IFTSTA, INVOIC), which is rare and important — it lets legacy NVOCC and forwarder integrations migrate at their own pace.
- **Multi-brand surface.** The same API surface covers CMA CGM, ANL, APL, CNC Line, and Containerships, so a single integration reaches five carrier brands.
- **Mistral AI partnership (€100M).** Group-level commitment to apply LLMs to customer service and logistics — worth watching for downstream agentic API products built on this foundation.
- **ZEBOX accelerator.** Six global hubs and 15+ corporate partners (BNSF, Vinci, CEVA, Transdev, Port of Virginia) — distribution channel for startups building on the CMA CGM API.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

# Shipday (shipday)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Shipday is a local delivery management platform for restaurants, retailers, and on-demand businesses. Its REST API lets you create and track delivery and pickup orders, manage drivers (carriers), assign orders to your own fleet, and tap a network of on-demand delivery providers (Uber, DoorDash) for last-mile fulfillment, with webhooks for real-time order and driver-location updates.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/shipday/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/shipday/refs/heads/main/apis.yml)

## Tags

- Delivery
- Logistics
- Last Mile
- Local Delivery
- Dispatch

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Shipday Orders API

Create, list, edit, and delete delivery and pickup orders. Insert a delivery order with customer, restaurant/pickup, and cost details; retrieve active orders; edit an existing order by ID; and manage pickup orders.

- **Human URL:** [https://docs.shipday.com/reference/shipday-api](https://docs.shipday.com/reference/shipday-api)
- **Base URL:** `https://api.shipday.com`

#### Tags

- Orders
- Deliveries
- Pickup

#### Properties

- [Documentation](https://docs.shipday.com/reference/insert-delivery-order)
- [API Reference](https://docs.shipday.com/reference/shipday-api)
- [OpenAPI](openapi/shipday-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shipday.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shipday.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Shipday Drivers / Carriers API

Add carriers (drivers) to your account, retrieve your carrier roster, and remove carriers. Adding a carrier returns an auto-generated password for the driver app login.

- **Human URL:** [https://docs.shipday.com/reference/add-a-carrier-1](https://docs.shipday.com/reference/add-a-carrier-1)
- **Base URL:** `https://api.shipday.com`

#### Tags

- Drivers
- Carriers
- Fleet

#### Properties

- [Documentation](https://docs.shipday.com/reference/add-a-carrier-1)
- [API Reference](https://docs.shipday.com/reference/retrieve-carriers)
- [OpenAPI](openapi/shipday-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shipday.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shipday.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Shipday Order Assignment API

Assign an order to a specific carrier in your own fleet by order ID and carrier ID, and unassign an order from a driver when dispatch changes.

- **Human URL:** [https://docs.shipday.com/reference/assign-order](https://docs.shipday.com/reference/assign-order)
- **Base URL:** `https://api.shipday.com`

#### Tags

- Assignment
- Dispatch
- Drivers

#### Properties

- [Documentation](https://docs.shipday.com/reference/assign-order)
- [API Reference](https://docs.shipday.com/reference/unassign-order-from-driver-1)
- [OpenAPI](openapi/shipday-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shipday.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shipday.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Shipday On-Demand Delivery API

Check on-demand delivery availability and pricing across third-party networks (DoorDash, Uber) for a pickup/delivery pair, then assign the order to a chosen provider for last-mile fulfillment.

- **Human URL:** [https://docs.shipday.com/reference/availability-1](https://docs.shipday.com/reference/availability-1)
- **Base URL:** `https://api.shipday.com`

#### Tags

- On-Demand
- Uber
- DoorDash

#### Properties

- [Documentation](https://docs.shipday.com/reference/availability-1)
- [API Reference](https://docs.shipday.com/reference/assign)
- [OpenAPI](openapi/shipday-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shipday.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shipday.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Shipday Webhooks API

Subscribe to real-time order status events (ORDER_INSERTED, ORDER_ASSIGNED, ORDER_ONTHEWAY, ORDER_COMPLETED, ORDER_FAILED, and more) delivered via HTTP POST, plus a beta driver-location webhook streaming live driver coordinates.

- **Human URL:** [https://docs.shipday.com/reference/order-status-update-2](https://docs.shipday.com/reference/order-status-update-2)
- **Base URL:** `https://api.shipday.com`

#### Tags

- Webhooks
- Events
- Tracking

#### Properties

- [Documentation](https://docs.shipday.com/reference/order-status-update-2)
- [API Reference](https://docs.shipday.com/reference/driver-location-update)
- [OpenAPI](openapi/shipday-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/shipday)
- [LinkedIn](https://www.linkedin.com/company/shipday)
- [Website](https://www.shipday.com)
- [Documentation](https://docs.shipday.com)
- [Plans](plans/shipday-plans-pricing.yml)
- [Rate Limits](rate-limits/shipday-rate-limits.yml)
- [Fin Ops](finops/shipday-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

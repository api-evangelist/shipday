# Shipday (shipday)

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

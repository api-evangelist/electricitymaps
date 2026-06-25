# Electricity Maps (electricitymaps)

Electricity Maps provides electricity grid data - carbon intensity and power production/consumption breakdown - for 200+ zones worldwide, in real time, as historical series, and as 24-72 hour forecasts. The REST API serves the same data behind the live electricity map at app.electricitymap.org, authenticated with an auth-token header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/electricitymaps/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/electricitymaps/refs/heads/main/apis.yml)

## Tags

- Energy
- Carbon Intensity
- Electricity
- Grid
- Sustainability

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Electricity Maps Carbon Intensity API

Last-known, 24-hour history, and 24-72 hour forecast carbon intensity (gCO2eq/kWh) of electricity consumed in a zone, queryable by zone identifier or by latitude/longitude geolocation.

- **Human URL:** [https://portal.electricitymaps.com/docs/api](https://portal.electricitymaps.com/docs/api)
- **Base URL:** `https://api.electricitymap.org/v3`

#### Tags

- Carbon Intensity
- Emissions
- gCO2eq

#### Properties

- [Documentation](https://portal.electricitymaps.com/docs/api)
- [API Reference](https://portal.electricitymaps.com/docs/api#carbon-intensity)
- [OpenAPI](openapi/electricitymaps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/electricitymaps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/electricitymaps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Electricity Maps Power Breakdown API

Combined power consumption and production breakdown for a zone by source (nuclear, solar, wind, hydro, gas, coal, oil, biomass, geothermal, battery), with import/export flows, available as latest, 24-hour history, and forecast.

- **Human URL:** [https://portal.electricitymaps.com/docs/api](https://portal.electricitymaps.com/docs/api)
- **Base URL:** `https://api.electricitymap.org/v3`

#### Tags

- Power Breakdown
- Generation
- Electricity Mix

#### Properties

- [Documentation](https://portal.electricitymaps.com/docs/api)
- [API Reference](https://portal.electricitymaps.com/docs/api#power-breakdown)
- [OpenAPI](openapi/electricitymaps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/electricitymaps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/electricitymaps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Electricity Maps Power Consumption & Production API

Dedicated flow-traced power consumption breakdown and physical power production breakdown endpoints for a zone, reporting megawatts per source and net import/export exchanges with neighbouring zones.

- **Human URL:** [https://portal.electricitymaps.com/docs/api](https://portal.electricitymaps.com/docs/api)
- **Base URL:** `https://api.electricitymap.org/v3`

#### Tags

- Power Consumption
- Power Production
- Flow Tracing

#### Properties

- [Documentation](https://portal.electricitymaps.com/docs/api)
- [API Reference](https://portal.electricitymaps.com/docs/api#power-consumption-breakdown)
- [OpenAPI](openapi/electricitymaps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/electricitymaps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/electricitymaps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Electricity Maps Zones API

Lists all available zones with the endpoints accessible for the caller's token, plus a health endpoint reporting API status. Both can be requested without an API key.

- **Human URL:** [https://portal.electricitymaps.com/docs/api](https://portal.electricitymaps.com/docs/api)
- **Base URL:** `https://api.electricitymap.org/v3`

#### Tags

- Zones
- Coverage
- Metadata

#### Properties

- [Documentation](https://portal.electricitymaps.com/docs/api)
- [API Reference](https://portal.electricitymaps.com/docs/api#zones)
- [OpenAPI](openapi/electricitymaps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/electricitymaps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/electricitymaps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Electricity Maps Forecast API

24-72 hour ahead forecasts of carbon intensity and power production breakdown for a zone, used to schedule compute and other loads toward lower-carbon hours.

- **Human URL:** [https://portal.electricitymaps.com/docs/api](https://portal.electricitymaps.com/docs/api)
- **Base URL:** `https://api.electricitymap.org/v3`

#### Tags

- Forecast
- Predictions
- Day Ahead

#### Properties

- [Documentation](https://portal.electricitymaps.com/docs/api)
- [API Reference](https://portal.electricitymaps.com/docs/api#forecast)
- [OpenAPI](openapi/electricitymaps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/electricitymaps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/electricitymaps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/electricitymaps)
- [LinkedIn](https://www.linkedin.com/company/electricitymaps)
- [Website](https://www.electricitymaps.com)
- [Documentation](https://portal.electricitymaps.com/docs/api)
- [Plans](plans/electricitymaps-plans-pricing.yml)
- [Rate Limits](rate-limits/electricitymaps-rate-limits.yml)
- [Fin Ops](finops/electricitymaps-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

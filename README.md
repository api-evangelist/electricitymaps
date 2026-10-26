# Electricity Maps (electricitymaps)

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

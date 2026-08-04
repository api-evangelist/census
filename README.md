# Census (census)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Census is a reverse ETL and data activation platform that syncs data from cloud data warehouses (Snowflake, BigQuery, Databricks, Redshift) into operational SaaS applications. Census was acquired by Fivetran and is now branded as Fivetran Activations, offering a REST API for managing workspaces, datasets, syncs, destinations, and custom destinations, plus embedded Activations (Connect Links) for Powered by Fivetran use cases.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/census/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/census/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Connectors
- Data Activation
- Data Warehouse
- Destinations
- Fivetran Activations
- Reverse ETL
- Unified API

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-04-23

## APIs

### Census Activations REST API

The Census Activations REST API (formerly Census Management API) lets teams programmatically manage reverse ETL pipelines, sources, models, destinations, syncs, and sync runs. The API is region-scoped and authenticated with personal access tokens, with organization-level resources (workspaces, users, invitations) and workspace-level resources (datasets, destinations, syncs).

- **Human URL:** [https://fivetran.com/docs/activations/rest-api/api-reference/introduction](https://fivetran.com/docs/activations/rest-api/api-reference/introduction)

#### Tags

- Data Activation
- REST
- Reverse ETL

#### Properties

- [Documentation](https://fivetran.com/docs/activations/rest-api/api-reference/introduction)
- [Legacy Documentation](https://docs.getcensus.com/)
- [Getting Started](https://docs.getcensus.com/basics/getting-started)
- [Postman Collection](collections/census.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/census.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Census Custom Destinations API

Custom Destinations API lets partners declare the type of data a destination can process, the operations allowed on that data, and the loading mechanism so that Activations can orchestrate loads into any custom SaaS or application system.

- **Human URL:** [https://fivetran.com/docs/activations/rest-api/custom-destinations/destination-spec](https://fivetran.com/docs/activations/rest-api/custom-destinations/destination-spec)

#### Tags

- Custom Destinations
- Destinations
- Integration

#### Properties

- [Documentation](https://fivetran.com/docs/activations/rest-api/custom-destinations/destination-spec)
- [Postman Collection](collections/census.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/census.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Census Connect Links (Powered by Fivetran)

Connect Links enable embedded Activations flows for Powered by Fivetran partners, letting end users configure destinations and syncs from within a host application via hosted URLs.

- **Human URL:** [https://fivetran.com/docs/activations/rest-api/activations-in-powered-by-fivetran/features/connect-links/connect-links](https://fivetran.com/docs/activations/rest-api/activations-in-powered-by-fivetran/features/connect-links/connect-links)

#### Tags

- Embedded
- Connect Links
- Powered by Fivetran

#### Properties

- [Documentation](https://fivetran.com/docs/activations/rest-api/activations-in-powered-by-fivetran/features/connect-links/connect-links)
- [Overview](https://fivetran.com/docs/activations/rest-api/embedded)
- [Postman Collection](collections/census.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/census.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/getcensus)
- [Website](https://www.getcensus.com/)
- [Documentation](https://fivetran.com/docs/activations/)
- [Reference](https://fivetran.com/docs/activations/rest-api/api-reference/introduction)
- [Getting Started](https://docs.getcensus.com/basics/getting-started)
- [Parent  Company](https://www.fivetran.com/)
- [Git Hub](https://github.com/sutrolabs)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

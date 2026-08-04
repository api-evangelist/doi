# Department of Interior (DOI)

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

The U.S. Department of the Interior manages and conserves federal lands and natural resources across America. This repository catalogs the public APIs and data services provided by DOI bureaus including the National Park Service (NPS), U.S. Geological Survey (USGS), and Bureau of Land Management (BLM).

## APIs

| API | Description | Base URL |
|-----|-------------|----------|
| NPS Data API | National park data — alerts, campgrounds, events, visitor centers | https://developer.nps.gov/api/v1 |
| USGS Water Data APIs | Real-time and historical water resource data | https://api.waterdata.usgs.gov |
| USGS Earthquake Web Services | Real-time seismic event data and feeds | https://earthquake.usgs.gov/fdsnws/event/1 |
| USGS Mineral Resources Data API | Mineral deposit and geochemical databases | https://mrdata.usgs.gov |
| BLM GIS REST Services | Federal land boundaries, cadastral, and land status | https://gis.blm.gov/arcgis/rest/services |
| USGS ScienceBase API | Earth science data management and discovery | https://www.sciencebase.gov/catalog |

## Resources

- [DOI Website](https://www.doi.gov/)
- [NPS Developer Resources](https://www.nps.gov/subjects/developer/index.htm)
- [USGS APIs](https://www.usgs.gov/products/web-tools/apis)
- [BLM GIS Data](https://www.blm.gov/services/geospatial/GISData)
- [DOI Blog](https://www.doi.gov/blog)

## Authentication

Most DOI bureau APIs are free and open. Some require a free API key for higher rate limits:

- NPS API Key: https://www.nps.gov/subjects/developer/get-started.htm
- USGS Water API Key: https://api.waterdata.usgs.gov/signup/

## Notes

- All APIs are free federal government services — no paid tiers
- USGS legacy WaterServices (waterservices.usgs.gov) will be decommissioned Q1 2027; migrate to api.waterdata.usgs.gov
- API availability may be affected by government shutdowns or funding gaps

## Maintainer

Kin Lane — kin@apievangelist.com

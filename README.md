# Blockskye

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

Blockskye is an enterprise travel management and payments platform for large corporate travel
programs, founded in 2017 and headquartered in New York. It combines a consumer-grade online
booking tool sourced through direct supplier and NDC connectivity, BMAX direct settlement that
wires a customer's ERP straight to travel suppliers so booked travel bypasses corporate cards and
expense reports, B360 for capturing personal co-brand card loyalty on business trips while holding
policy compliance, and real-time reporting across every booking channel, with transactions recorded
to a tamper-resistant distributed ledger. Blockskye delivers an end-to-end corporate travel solution
in partnership with KAYAK for Business.

## API surface

Blockskye publishes **no public developer portal, API reference, or machine-readable API contract**.
A live production API host does answer anonymously at `https://api.blockskye.com` (`GET /health`
returns 200; all other probed routes return a structured JSON 404), but no OpenAPI, Swagger,
GraphQL SDL, AsyncAPI, MCP manifest, or A2A agent card is served from any Blockskye host. The
knowledge base at `support.blockskye.com` redirects to a Freshworks OAuth login, so the reference is
reachable only by an existing customer tenant. See `x-coverage` in `apis.yml` for the probed
evidence.

## Links

- Website — https://www.blockskye.com/
- Platform — https://www.blockskye.com/blockskye-platform
- About — https://www.blockskye.com/about
- News — https://www.blockskye.com/latestnews
- Contact — https://www.blockskye.com/contact
- Customer login — https://horizon.blockskye.com/login

# The Clearing House (RTP) (the-clearing-house)

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

The Clearing House (TCH) is a U.S. banking association and payments company owned by many of the largest commercial banks. It operates three core payment systems — CHIPS (large-value wire clearing), the EPN automated clearing house (ACH), and the RTP network, the private-sector real-time payments rail it launched in 2017. RTP is a 24/7/365 instant-payments scheme built on the ISO 20022 messaging standard, supporting immediate credit-push transfers up to $10 million with final settlement, plus Request for Payment (RfP), rich remittance data, and a UID addressing/directory lookup. TCH is the scheme operator for the U.S. market and competes with the Federal Reserve's FedNow service.

TCH's public API posture is documentation- and rulebook-first. It does not publish an open, self-serve public REST API or a downloadable OpenAPI/Swagger specification. Instead it publishes ISO 20022 message specifications (pacs, pain, camt, remt) as PDFs, the RTP network operating rules, playbooks, and a technology-provider program. Real-time HTTP/JSON RTP APIs are surfaced to businesses by participating financial institutions (for example U.S. Bank) and registered technology providers that connect to the RTP network on their behalf.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/the-clearing-house/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/the-clearing-house/refs/heads/main/apis.yml)

## Tags

- Payments
- United States
- Real-Time Payments
- Instant Payments
- ISO 20022
- Account-to-Account
- Payment Rails
- Scheme Operator
- Request for Payment

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

### RTP Network (ISO 20022 Messaging)

The RTP network is The Clearing House's real-time payments scheme for the United States, moving credit-push payments instantly, 24/7/365, with final settlement up to $10 million per transaction. It is defined by published ISO 20022 message specifications rather than an open self-serve REST API: Credit Transfer (pacs.008), Message Status Report (pacs.002), Request for Payment (pain.013/pain.014), Request for Information (camt.026/camt.028), Request for Return of Funds (camt.056/camt.029), Payment Acknowledgement (camt.035), Stand-Alone Remittance Advice (remt.001), and the Business Application Header (BAH). Access is via participating financial institutions and registered technology providers; no downloadable OpenAPI is published by TCH.

- **Human URL:** [https://www.theclearinghouse.org/payment-systems/rtp/technical-documentation](https://www.theclearinghouse.org/payment-systems/rtp/technical-documentation)

#### Tags

- Real-Time Payments
- ISO 20022
- Instant Payments

#### Properties

- [Documentation](https://www.theclearinghouse.org/payment-systems/rtp/technical-documentation)
- [API Reference](https://www.theclearinghouse.org/payment-systems/rtp/document-library)
- [Documentation](https://www.theclearinghouse.org/payment-systems/rtp/rtp-network-operating-rules)

## Common Properties

- [Website](https://www.theclearinghouse.org/)
- [Documentation](https://www.theclearinghouse.org/payment-systems/rtp/technical-documentation)
- [API Reference](https://www.theclearinghouse.org/payment-systems/rtp/document-library)
- [Blog](https://www.theclearinghouse.org/newsroom)
- [Terms of Service](https://www.theclearinghouse.org/terms-of-use)
- [Privacy Policy](https://www.theclearinghouse.org/privacy-policy)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

# The Clearing House (RTP) (the-clearing-house)

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

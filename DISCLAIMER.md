# ⚠️ Disclaimer & Liability Limitation

**Use at your own risk.** The code, workflows, and scripts in this repository (`n8n-hubspot-contact-social-profile-enrichment-bridge`) are provided for educational and architectural demonstration purposes.

## No Liability

The author and dhRobin Systems accept no responsibility or liability for any direct, indirect, incidental, or consequential damages that result from using, misusing, or deploying these scripts. This includes, without limitation, regulatory fines or claims arising from the processing of personal data, profile data attached to the wrong contact, overwritten or incorrect contact properties, provider charges or quota exhaustion, unintended disclosure of contact information, service interruptions, and damage to sender or brand reputation.

## No Warranty

All software, n8n JSON blueprints, JavaScript modules and prompts are provided "AS IS", without warranty of any kind, express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and non-infringement.

No warranty is given that any provider returns accurate, current or lawfully sourced data; that identity checks, confidence thresholds, avatar validation or employment-history normalisation catch every error; that job-change detection is correct; that protected-diff rules preserve every value you consider valid; or that the integrity guard and circuit breaker prevent every unintended write.

## Production Testing Required

Always test thoroughly in an isolated staging environment, such as a HubSpot developer test account or sandbox, with `SANDBOX_MODE=true`, `DRY_RUN=true` and `SYNC_TO_HUBSPOT=false` enabled, before you connect live HubSpot or social graph provider credentials. Enable the live provider, contact writes and webhook processing one step at a time, start with a small `MAX_CONTACTS_PER_RUN`, and review the run statistics and the `mismatch` and `ambiguous` results before you scale up.

Treat every enriched profile, job change and status as automated data that a person must be able to review and correct before it's relied on.

## Third-Party APIs & Compliance

You alone are responsible for complying with the terms of service, rate limits, data privacy regulations (GDPR/CCPA and equivalents), and security policies of HubSpot, your social graph or enrichment provider, and any connected services. That includes:

- establishing and documenting a lawful basis for enriching contact records, and informing data subjects as your privacy obligations require;
- using only providers whose data sourcing, licences and terms of service permit this use, and never connecting tools that scrape professional networks or other sites in breach of their terms;
- executing a data processing agreement with the provider and reviewing its sub-processors, international transfers and retention;
- honouring objections, opt-outs and erasure requests, including suppression with the provider;
- keeping personal emails, phone numbers and other non-professional data out of provider requests and CRM records;
- securing, rotating and restricting access to the HubSpot private app token, the HubSpot app client secret and the enrichment API key;
- reviewing every automatically created or updated record.

## No Affiliation

HubSpot and n8n are trademarks of their respective owners. References to "social graph" or "professional profile" providers are generic and do not refer to, endorse or imply affiliation with any specific network or vendor. All people, companies, profiles, identifiers and URLs in the fixtures and pinned data are fictitious.

## Not Professional Advice

Nothing in this repository constitutes legal, privacy, security, or financial advice. Consult qualified professionals, including your data protection officer, for your specific circumstances.

---

Released under the MIT License. Copyright (c) 2026 DH Robin (dhRobin Systems). See [LICENSE](LICENSE).

Full text: DISCLAIMER.md · Licensed under the MIT License. License: MIT © 2026 dhRobin Systems · Provided as-is, see the disclaimer.

# Magic (magic-dev)

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

Magic (magic.dev) is a San Francisco frontier AI research lab building frontier-scale code models - an "AI coworker" for software engineering, and ultimately a path to safe AGI - rather than a shipping developer product. It has raised roughly $515M from Nat Friedman, Daniel Gross, CapitalG, Elad Gil, Sequoia, Jane Street, and Eric Schmidt, and has published research on ultra-long-context models (LTM-1 at a 5M token context window, and the unreleased LTM-2-mini research prototype claimed to handle up to 100M tokens). As of this review Magic does not publish a public, self-serve developer API, API reference, SDK, or waitlist; its website and careers pages describe mission, research, and open roles only, with no product access model, pricing, or documented endpoints. Its GitHub organization (magicproduct) hosts research tooling (e.g. hash-hop, a long-context evaluation harness) and infrastructure forks, not an API client or SDK.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/magic-dev/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/magic-dev/refs/heads/main/apis.yml)

## Access Model

Magic has no public product surface today:

- No self-serve signup, waitlist, pricing page, or customer dashboard is published on magic.dev.
- No developer portal, API reference, base URL, authentication scheme, or SDK is documented.
- The company's public output is limited to a marketing/mission homepage, a research blog (e.g. the LTM-1 announcement), a safety page describing alignment research priorities, and a careers page hiring research and infrastructure engineers.
- Its GitHub organization, [magicproduct](https://github.com/magicproduct) (verified domain magic.dev, contact office@magic.dev), publishes research tooling - most notably `hash-hop`, a long-context evaluation harness for LLMs - and a handful of forked infrastructure repos (Terraform providers, Kubernetes tooling, CUDA libraries). None of this is an API client, SDK, or developer-facing artifact.
- Co-founder and CEO is Eric Steinberger; co-founder and CTO is Sebastian De Ro.

Because there is no documented public API surface of any kind, this catalog entry intentionally omits the `apis` list along with `openapi/`, `plans/`, `rate-limits/`, `finops/`, and `collections/` artifacts that would otherwise describe endpoints, pricing, limits, and cost - there is nothing sourced to put in them.

## Tags

- AI
- AGI Research
- Coding Agent
- Long Context
- LLM
- Frontier Lab
- No Public API

## Timestamps

- **Created:** 2026-07-02
- **Modified:** 2026-07-02

## Common Properties

- [GitHub Organization](https://github.com/magicproduct)
- [LinkedIn](https://www.linkedin.com/company/magicailabs)
- [Website](https://magic.dev)
- [Blog](https://magic.dev/blog)
- [Careers](https://magic.dev/careers)
- [Safety](https://magic.dev/safety)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

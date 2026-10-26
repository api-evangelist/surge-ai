# Surge AI (surge-ai)

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

Surge AI is a human-data company that provides large-scale, expert-quality labeled data for training and evaluating frontier AI models. The product surface spans RL environments and agents (rich, complex environments that challenge agentic models), rubrics and verifiers (scoring systems for AI outputs), RLHF (preference and reward data), SFT (foundational skill demonstrations), human evaluation, expert professional domains, internationalization across 70+ languages, multimodal (image, audio, video) data, and off-the-shelf datasets. Surge ships an official Python SDK (surge-python) wrapping the Surge API, with API-key authentication, and exposes the dashboard and API reference at app.surgehq.ai. Public datasets published by Surge include the toxicity dataset (the world's largest social-media toxicity dataset).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/surge-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/surge-ai/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Human Data
- RLHF
- SFT
- Rubrics
- Verifiers
- RL Environments
- Multimodal
- Internationalization
- Labeling

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Surge API

Surge's REST API for managing labeling projects, tasks, and results. Endpoints cover projects (list, retrieve, create, download results, save reports in multiple formats), tasks (create, list, retrieve individual tasks), and blueprints (list and use as templates for new projects). Authentication uses an API key sourced from the user's Surge profile, passed via the SURGE_API_KEY environment variable or set explicitly on the client. The reference is published in the Surge dashboard at app.surgehq.ai/docs/api.

- **Human URL:** [https://app.surgehq.ai/docs/api](https://app.surgehq.ai/docs/api)

#### Tags

- REST API
- Projects
- Tasks
- Blueprints

#### Properties

- [Documentation](https://app.surgehq.ai/docs/api)
- [API Reference](https://app.surgehq.ai/docs/api)
- [Authentication](https://app.surgehq.ai/docs/api)
- [SDK](https://github.com/surge-ai/surge-python)
- [Postman Collection](collections/surge-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surge-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Surge Python SDK

Official Python SDK (surge-api on PyPI) wrapping the Surge API. Requires Python 3.10+, MIT-licensed, and last updated May 2026. Configured via surge.api_key or the SURGE_API_KEY environment variable.

- **Human URL:** [https://github.com/surge-ai/surge-python](https://github.com/surge-ai/surge-python)

#### Tags

- SDK
- Python
- Open Source

#### Properties

- [GitHub Repository](https://github.com/surge-ai/surge-python)
- [SDK](https://pypi.org/project/surge-api/)
- [Postman Collection](collections/surge-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surge-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Surge RL Environments and Agents

Surge's product surface for delivering complex reinforcement-learning environments and agents that challenge and evaluate agentic models.

- **Human URL:** [https://www.surgehq.ai/products](https://www.surgehq.ai/products)

#### Tags

- RL Environments
- Agents
- Evals

#### Properties

- [Documentation](https://www.surgehq.ai/products)
- [Postman Collection](collections/surge-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surge-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Surge Rubrics and Verifiers

Scoring rubrics and automated verifiers for grading AI outputs across domains.

- **Human URL:** [https://www.surgehq.ai/products](https://www.surgehq.ai/products)

#### Tags

- Rubrics
- Verifiers
- Evals

#### Properties

- [Documentation](https://www.surgehq.ai/products)
- [Postman Collection](collections/surge-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surge-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Surge RLHF

Preference and reward data for reinforcement learning from human feedback.

- **Human URL:** [https://www.surgehq.ai/products](https://www.surgehq.ai/products)

#### Tags

- RLHF
- Preference Data

#### Properties

- [Documentation](https://www.surgehq.ai/products)
- [Postman Collection](collections/surge-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surge-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Surge SFT

Foundational-skill demonstration data for supervised fine-tuning.

- **Human URL:** [https://www.surgehq.ai/products](https://www.surgehq.ai/products)

#### Tags

- SFT
- Fine-Tuning

#### Properties

- [Documentation](https://www.surgehq.ai/products)
- [Postman Collection](collections/surge-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surge-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Surge Human Evaluation

Quality assessment of AI outputs by Surge's expert workforce.

- **Human URL:** [https://www.surgehq.ai/products](https://www.surgehq.ai/products)

#### Tags

- Human Evaluation
- Quality

#### Properties

- [Documentation](https://www.surgehq.ai/products)
- [Postman Collection](collections/surge-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surge-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Surge Multimodal Data

Image, audio, and video data collection and labeling.

- **Human URL:** [https://www.surgehq.ai/products](https://www.surgehq.ai/products)

#### Tags

- Multimodal
- Image
- Audio
- Video

#### Properties

- [Documentation](https://www.surgehq.ai/products)
- [Postman Collection](collections/surge-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surge-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Surge Internationalization

Multilingual data across 70+ languages for localization, translation, and multilingual model evaluation.

- **Human URL:** [https://www.surgehq.ai/products](https://www.surgehq.ai/products)

#### Tags

- Internationalization
- Multilingual
- Translation

#### Properties

- [Documentation](https://www.surgehq.ai/products)
- [Postman Collection](collections/surge-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surge-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Surge Off-The-Shelf Data

Pre-built datasets ready for licensing and download.

- **Human URL:** [https://www.surgehq.ai/products](https://www.surgehq.ai/products)

#### Tags

- Datasets
- Pre-Built Data

#### Properties

- [Documentation](https://www.surgehq.ai/products)
- [Postman Collection](collections/surge-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surge-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Surge Toxicity Dataset

The world's largest open social-media toxicity dataset, published under MIT license.

- **Human URL:** [https://github.com/surge-ai/toxicity](https://github.com/surge-ai/toxicity)

#### Tags

- Dataset
- Open Data
- Toxicity
- Trust and Safety

#### Properties

- [GitHub Repository](https://github.com/surge-ai/toxicity)
- [Postman Collection](collections/surge-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surge-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.surgehq.ai)
- [Documentation](https://app.surgehq.ai/docs/api)
- [API Reference](https://app.surgehq.ai/docs/api)
- [Authentication](https://app.surgehq.ai/docs/api)
- [Sign Up](https://app.surgehq.ai/customers/sign_in)
- [Console](https://app.surgehq.ai)
- [SDK](https://github.com/surge-ai/surge-python)
- [SDK](https://pypi.org/project/surge-api/)
- [GitHub Organization](https://github.com/surge-ai)
- [GitHub Repository](https://github.com/surge-ai/toxicity)
- [Blog](https://www.surgehq.ai/blog)
- [Support](https://www.surgehq.ai)
- [X (Twitter)](https://x.com/HelloSurgeAI)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** http://apievangelist.com

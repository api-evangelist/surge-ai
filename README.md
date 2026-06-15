# Surge AI (surge-ai)

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

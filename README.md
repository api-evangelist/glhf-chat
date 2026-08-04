# glhf (glhf-chat)

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

glhf (glhf.chat) runs almost any open-source large language model on demand through an auto-scaling GPU scheduler built on vLLM. Any Hugging Face repository can be served by passing its identifier as hf:org/model to an OpenAI-compatible REST API, giving access to models like Llama, Qwen, and Mixtral without self-hosting.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/glhf-chat/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/glhf-chat/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Inference
- Open Source Models
- Hugging Face

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### glhf Chat Completions API

OpenAI-compatible chat completions endpoint that serves almost any open-source model from Hugging Face by passing the repository as hf:org/model. Supports streaming responses via Server-Sent Events when stream is set to true.

- **Human URL:** [https://glhf.chat/users/settings/api](https://glhf.chat/users/settings/api)
- **Base URL:** `https://glhf.chat/api/openai/v1`

#### Tags

- Chat
- Completions
- LLM

#### Properties

- [Documentation](https://glhf.chat/users/settings/api)
- [API Reference](https://glhf.chat/users/settings/api)
- [OpenAPI](openapi/glhf-chat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/glhf-chat-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/glhf-chat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/glhf-chat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### glhf Models API

OpenAI-compatible models endpoint that lists the models available to the account, using the same response shape as the OpenAI models API.

- **Human URL:** [https://glhf.chat/users/settings/api](https://glhf.chat/users/settings/api)
- **Base URL:** `https://glhf.chat/api/openai/v1`

#### Tags

- Models
- Catalog

#### Properties

- [Documentation](https://glhf.chat/users/settings/api)
- [API Reference](https://glhf.chat/users/settings/api)
- [OpenAPI](openapi/glhf-chat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/glhf-chat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/glhf-chat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/glhf-chat)
- [Website](https://glhf.chat)
- [Documentation](https://glhf.chat/users/settings/api)
- [Plans](plans/glhf-chat-plans-pricing.yml)
- [Rate Limits](rate-limits/glhf-chat-rate-limits.yml)
- [Fin Ops](finops/glhf-chat-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

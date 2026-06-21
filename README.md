# glhf (glhf-chat)

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

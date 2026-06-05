# Convai (convai-com)

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/convai-com/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/convai-com/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- AI
- Conversational AI
- Characters
- NPCs
- Virtual Worlds
- Games
- Avatars
- Speech
- TTS
- WebRTC

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Convai Character API

Create, list, update, clone, and delete Convai conversational AI characters. Each character is a reusable conversational agent with backstory, voice, language, personality, knowledge bank, and narrative design configuration that can be embodied in games and virtual worlds via the Unity, Unreal, Web, and other Convai SDKs.

- **Human URL:** [https://docs.convai.com/api-docs/api-reference/core-api-reference](https://docs.convai.com/api-docs/api-reference/core-api-reference)

#### Tags

- AI
- Conversational AI
- Characters
- NPCs

#### Properties

- [Documentation](https://docs.convai.com/api-docs/api-reference/core-api-reference)
- [OpenAPI](openapi/convai-character-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/convai-character-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convai-character-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/convai-character-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/convai-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Convai Interaction API

Runtime conversational endpoint that powers in-game NPC dialogue. Send user text or audio plus a session and character ID and receive the character's text reply, base64 audio, action triggers, emotion state, and narrative section data. The single most-called endpoint in the Convai stack.

- **Human URL:** [https://docs.convai.com/api-docs/api-reference/core-api-reference](https://docs.convai.com/api-docs/api-reference/core-api-reference)

#### Tags

- AI
- Conversational AI
- Characters
- Interaction
- NPCs

#### Properties

- [Documentation](https://docs.convai.com/api-docs/api-reference/core-api-reference)
- [OpenAPI](openapi/convai-interaction-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/convai-interaction-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convai-interaction-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/convai-interaction-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Convai Knowledge Bank API

Upload, update, list, and delete RAG documents attached to characters so they can reference custom knowledge during conversations. Enterprise tier.

- **Human URL:** [https://docs.convai.com/api-docs/api-reference/core-api-reference](https://docs.convai.com/api-docs/api-reference/core-api-reference)

#### Tags

- AI
- Conversational AI
- Knowledge Bank
- RAG

#### Properties

- [Documentation](https://docs.convai.com/api-docs/api-reference/core-api-reference)
- [OpenAPI](openapi/convai-knowledge-bank-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/convai-knowledge-bank-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convai-knowledge-bank-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Convai Text-to-Speech API

Synthesize speech from text using Convai's catalog of 500+ voices across 65+ languages. Returns audio bytes for use in games, virtual worlds, and accessibility flows. Enterprise tier.

- **Human URL:** [https://docs.convai.com/api-docs/api-reference/core-api-reference](https://docs.convai.com/api-docs/api-reference/core-api-reference)

#### Tags

- AI
- Speech
- TTS
- Voice

#### Properties

- [Documentation](https://docs.convai.com/api-docs/api-reference/core-api-reference)
- [OpenAPI](openapi/convai-tts-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/convai-tts-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convai-tts-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Convai Narrative Design API

Configure narrative-driven characters with sections (discrete story beats with objectives) and triggers (conditions that move the character between sections). Backs branching, scripted game experiences on top of Convai's conversational AI.

- **Human URL:** [https://docs.convai.com/api-docs/api-reference/core-api-reference](https://docs.convai.com/api-docs/api-reference/core-api-reference)

#### Tags

- AI
- Conversational AI
- Narrative
- Game Design

#### Properties

- [Documentation](https://docs.convai.com/api-docs/api-reference/core-api-reference)
- [OpenAPI](openapi/convai-narrative-design-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/convai-narrative-design-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convai-narrative-design-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Convai Chat History API

List a character's sessions and fetch full session transcripts for analytics, debugging, evaluation, and auditing of NPC conversations. Scale tier and above.

- **Human URL:** [https://docs.convai.com/api-docs/api-reference/core-api-reference](https://docs.convai.com/api-docs/api-reference/core-api-reference)

#### Tags

- AI
- Conversational AI
- Chat History
- Analytics

#### Properties

- [Documentation](https://docs.convai.com/api-docs/api-reference/core-api-reference)
- [OpenAPI](openapi/convai-chat-history-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/convai-chat-history-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convai-chat-history-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Convai Custom LLM API

Register, update, deregister, and list OpenAI-compatible custom LLM endpoints to use as the reasoning backbone for Convai characters. Lets Enterprise customers route character responses through their own model deployments. Enterprise tier.

- **Human URL:** [https://docs.convai.com/api-docs/api-reference/core-api-reference](https://docs.convai.com/api-docs/api-reference/core-api-reference)

#### Tags

- AI
- Conversational AI
- LLM
- BYO Model

#### Properties

- [Documentation](https://docs.convai.com/api-docs/api-reference/core-api-reference)
- [OpenAPI](openapi/convai-custom-llm-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/convai-custom-llm-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convai-custom-llm-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Convai Evaluation API

Score and evaluate Convai character sessions against a custom prompt and rubric variables. Used to measure NPC quality, role fidelity, safety, and objective completion. Professional tier and above.

- **Human URL:** [https://docs.convai.com/api-docs/api-reference/core-api-reference](https://docs.convai.com/api-docs/api-reference/core-api-reference)

#### Tags

- AI
- Conversational AI
- Evaluation
- Quality

#### Properties

- [Documentation](https://docs.convai.com/api-docs/api-reference/core-api-reference)
- [OpenAPI](openapi/convai-evaluation-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/convai-evaluation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convai-evaluation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Convai Streaming Transcription API

Real-time speech-to-text over WebSocket (wss://transcribe.convai.com/stream). Stream 16-bit PCM, mono, 16 kHz audio and receive incremental transcripts. Used by the Convai plugins to drive low-latency voice input from players.

- **Human URL:** [https://docs.convai.com/api-docs/api-reference/core-api-reference](https://docs.convai.com/api-docs/api-reference/core-api-reference)

#### Tags

- AI
- Speech
- Transcription
- Streaming
- WebSocket

#### Properties

- [Documentation](https://docs.convai.com/api-docs/api-reference/core-api-reference)
- [OpenAPI](openapi/convai-streaming-transcription-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/convai-streaming-transcription-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convai-streaming-transcription-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Convai Live API

Beta Live API for ultra-low-latency, fully duplex character sessions over WebRTC. POST /connect at live.convai.com to establish a session; subsequent audio and event messages flow over WebRTC data channels (RTVI message format) and media tracks. Authenticated via X-API-Key.

- **Human URL:** [https://docs.convai.com/api-docs/api-reference/live-api-reference](https://docs.convai.com/api-docs/api-reference/live-api-reference)

#### Tags

- AI
- Conversational AI
- Live
- WebRTC
- Beta

#### Properties

- [Documentation](https://docs.convai.com/api-docs/api-reference/live-api-reference)
- [OpenAPI](openapi/convai-live-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/convai-live-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/convai-live-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://convai.com)
- [Sandbox](https://convai.com/playground)
- [Documentation](https://docs.convai.com)
- [Documentation](https://docs.convai.com/api-docs/welcome)
- [Documentation](https://docs.convai.com/api-docs/api-reference/core-api-reference)
- [Pricing](https://convai.com/pricing)
- [GitHub Organization](https://github.com/Conv-AI)
- [Forum](https://forum.convai.com)
- [Blog](https://convai.com/blog)
- [About](https://convai.com/about)
- [Contact Sales](https://convai.com/contact-sales)
- [Terms of Service](https://convai.com/terms-of-service)
- [Privacy Policy](https://convai.com/privacy-policy)
- [SDK](https://github.com/Conv-AI/Convai-UnrealEngine-SDK-V4)
- [SDK](https://github.com/Conv-AI/Convai-UnrealEngine-SDK)
- [SDK](https://github.com/Conv-AI/Convai-Web-SDK-Old)
- [SDK](https://github.com/Conv-AI/Convai-JS-SDK-Alpha)
- [Integration](https://docs.convai.com/api-docs/plugins-and-integrations/unity-plugin)
- [Integration](https://docs.convai.com/api-docs/plugins-and-integrations/unreal-engine-plugin)
- [Integration](https://docs.convai.com/api-docs/plugins-and-integrations/web-plugin)
- [Integration](https://docs.convai.com/api-docs/plugins-and-integrations/playcanvas-plugin)
- [Integration](https://docs.convai.com/api-docs/plugins-and-integrations/roblox)
- [Integration](https://docs.convai.com/api-docs/plugins-and-integrations/discord)
- [Integration](https://docs.convai.com/api-docs/plugins-and-integrations/omniverse)
- [Integration](https://docs.convai.com/api-docs/plugins-and-integrations/pixel-streaming)
- [Tools](https://github.com/Conv-AI/convai-analytics)
- [Tools](https://github.com/Conv-AI/convai-evals)
- [Tools](https://github.com/Conv-AI/Convai-UnrealEngine-ModdingTool)
- [Tools](https://github.com/Conv-AI/Convai-UnrealEngine-PakManager)
- [Pricing](plans/convai-plans-pricing.yml)
- [Rate Limits](rate-limits/convai-rate-limits.yml)
- [Fin Ops](finops/convai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com

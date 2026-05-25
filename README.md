# Convai (convai-com)

Convai is a conversational AI platform for embodied 3D characters in games, virtual worlds, simulations, and immersive web experiences. Its REST and WebRTC APIs power NPCs that perceive (vision and audio), reason (with optional custom LLMs and a Knowledge Bank for retrieval-augmented context), speak (500+ voices, 65+ languages), animate (lip-sync and facial expressions), and follow narrative-driven story logic via sections and triggers. First-party SDKs ship for Unreal Engine, Unity, Web (React and Vanilla TS), and PlayCanvas, with integrations for Roblox, Discord, and NVIDIA Omniverse.

**URL:** [Visit APIs.yml](https://raw.githubusercontent.com/api-evangelist/convai-com/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - AI, Conversational AI, Characters, NPCs, Virtual Worlds, Games, Avatars, Speech, TTS, WebRTC

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Score

- **Rank:** Tier-1
- **Rationale:** Real REST API at `api.convai.com` with documented endpoints across characters, interaction, knowledge bank, narrative design, TTS, chat history, custom LLM, and evaluation; WebSocket streaming transcription at `transcribe.convai.com`; beta WebRTC Live API at `live.convai.com`; first-party SDKs for Unreal Engine, Unity, Web, PlayCanvas, with integrations for Roblox, Discord, and NVIDIA Omniverse; published forum, pricing tiers, and GitHub org under [Conv-AI](https://github.com/Conv-AI).

## APIs

### Convai Character API
Create, list, update, clone, and delete Convai characters. Each character is a reusable agent with backstory, voice, language, personality, knowledge bank, and narrative configuration.

**Human URL:** [https://docs.convai.com/api-docs/api-reference/core-api-reference](https://docs.convai.com/api-docs/api-reference/core-api-reference)

- [OpenAPI](openapi/convai-character-api-openapi.yml)
- [JSON Schema — Character](json-schema/convai-character-schema.json)
- [JSON-LD](json-ld/convai-context.jsonld)
- [Naftiko Capability — Characters](capabilities/characters-characters.yaml)

### Convai Interaction API
The runtime conversational endpoint (`POST /character/getResponse`) that powers in-game NPC dialogue. Returns text, base64 audio, action triggers, emotion state, and narrative section data.

- [OpenAPI](openapi/convai-interaction-api-openapi.yml)
- [JSON Schema — Interaction](json-schema/convai-interaction-schema.json)
- [Naftiko Capability — Get Response](capabilities/interaction-getresponse.yaml)

### Convai Knowledge Bank API
Upload, update, list, and delete RAG documents attached to characters. Enterprise tier.

- [OpenAPI](openapi/convai-knowledge-bank-api-openapi.yml)
- [Naftiko Capability — Knowledge Bank](capabilities/knowledge-bank-knowledge-bank.yaml)

### Convai Text-to-Speech API
Synthesize speech from text across 500+ voices and 65+ languages. Enterprise tier.

- [OpenAPI](openapi/convai-tts-api-openapi.yml)
- [Naftiko Capability — TTS](capabilities/tts-tts.yaml)

### Convai Narrative Design API
Sections (story beats with objectives) and triggers (conditions that move between sections) for branching, scripted NPC experiences.

- [OpenAPI](openapi/convai-narrative-design-api-openapi.yml)
- [Naftiko Capability — Narrative](capabilities/narrative-narrative.yaml)

### Convai Chat History API
List sessions and fetch session transcripts for analytics, debugging, and auditing. Scale tier and above.

- [OpenAPI](openapi/convai-chat-history-api-openapi.yml)
- [Naftiko Capability — Chat History](capabilities/chat-history-chat-history.yaml)

### Convai Custom LLM API
Register OpenAI-compatible custom LLM endpoints as the reasoning backbone for characters. Enterprise tier.

- [OpenAPI](openapi/convai-custom-llm-api-openapi.yml)
- [Naftiko Capability — Custom LLM](capabilities/custom-llm-custom-llm.yaml)

### Convai Evaluation API
Score session transcripts against a custom rubric. Professional tier and above.

- [OpenAPI](openapi/convai-evaluation-api-openapi.yml)
- [Naftiko Capability — Evaluation](capabilities/evaluation-evaluation.yaml)

### Convai Streaming Transcription API
Real-time speech-to-text over WebSocket at `wss://transcribe.convai.com/stream`. Stream 16-bit PCM, mono, 16 kHz audio.

- [OpenAPI](openapi/convai-streaming-transcription-api-openapi.yml)

### Convai Live API (Beta)
Ultra-low-latency, fully duplex character sessions over WebRTC. `POST https://live.convai.com/connect` to establish a session; audio and events flow over data channels (RTVI message format).

- [OpenAPI](openapi/convai-live-api-openapi.yml)

## Common Properties

- [Portal — convai.com](https://convai.com)
- [Sandbox — Convai Playground](https://convai.com/playground)
- [Documentation — docs.convai.com](https://docs.convai.com)
- [Documentation — API Reference](https://docs.convai.com/api-docs/api-reference/core-api-reference)
- [Pricing](https://convai.com/pricing)
- [GitHubOrganization — Conv-AI](https://github.com/Conv-AI)
- [Forum — Convai Developer Forum](https://forum.convai.com)
- [Blog](https://convai.com/blog)
- [About](https://convai.com/about)
- [ContactSales](https://convai.com/contact-sales)
- [TermsOfService](https://convai.com/terms-of-service)
- [PrivacyPolicy](https://convai.com/privacy-policy)
- [SDK — Unreal Engine V4](https://github.com/Conv-AI/Convai-UnrealEngine-SDK-V4)
- [SDK — Unreal Engine (Legacy)](https://github.com/Conv-AI/Convai-UnrealEngine-SDK)
- [SDK — Web (Legacy)](https://github.com/Conv-AI/Convai-Web-SDK-Old)
- [SDK — JavaScript (Alpha, archived)](https://github.com/Conv-AI/Convai-JS-SDK-Alpha)
- [Plugin — Unity](https://docs.convai.com/api-docs/plugins-and-integrations/unity-plugin)
- [Plugin — Unreal Engine](https://docs.convai.com/api-docs/plugins-and-integrations/unreal-engine-plugin)
- [Plugin — Web SDK](https://docs.convai.com/api-docs/plugins-and-integrations/web-plugin)
- [Plugin — PlayCanvas](https://docs.convai.com/api-docs/plugins-and-integrations/playcanvas-plugin)
- [Plugin — Roblox](https://docs.convai.com/api-docs/plugins-and-integrations/roblox)
- [Plugin — Discord Bot](https://docs.convai.com/api-docs/plugins-and-integrations/discord)
- [Plugin — NVIDIA Omniverse](https://docs.convai.com/api-docs/plugins-and-integrations/omniverse)
- [Plugin — Pixel Streaming Embed](https://docs.convai.com/api-docs/plugins-and-integrations/pixel-streaming)
- [Tool — Analytics (MCP server, SDKs, CLI)](https://github.com/Conv-AI/convai-analytics)
- [Tool — Evaluation Toolkit](https://github.com/Conv-AI/convai-evals)
- [Tool — Unreal Modding Tool](https://github.com/Conv-AI/Convai-UnrealEngine-ModdingTool)
- [Tool — Unreal Pak Manager](https://github.com/Conv-AI/Convai-UnrealEngine-PakManager)
- [API Commons Plans](plans/convai-plans-pricing.yml)
- [API Commons Rate Limits](rate-limits/convai-rate-limits.yml)
- [FinOps](finops/convai-finops.yml)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Convai Character API](openapi/convai-character-api-openapi.yml)
- [Convai Interaction API](openapi/convai-interaction-api-openapi.yml)
- [Convai Knowledge Bank API](openapi/convai-knowledge-bank-api-openapi.yml)
- [Convai Text-to-Speech API](openapi/convai-tts-api-openapi.yml)
- [Convai Narrative Design API](openapi/convai-narrative-design-api-openapi.yml)
- [Convai Chat History API](openapi/convai-chat-history-api-openapi.yml)
- [Convai Custom LLM API](openapi/convai-custom-llm-api-openapi.yml)
- [Convai Evaluation API](openapi/convai-evaluation-api-openapi.yml)
- [Convai Streaming Transcription API](openapi/convai-streaming-transcription-api-openapi.yml)
- [Convai Live API (Beta)](openapi/convai-live-api-openapi.yml)

### JSON Schema

- [Convai Character](json-schema/convai-character-schema.json)
- [Convai Interaction](json-schema/convai-interaction-schema.json)

### JSON-LD

- [Convai Context](json-ld/convai-context.jsonld)

### Naftiko Capabilities

- [Characters](capabilities/characters-characters.yaml)
- [Interaction — Get Response](capabilities/interaction-getresponse.yaml)
- [Knowledge Bank](capabilities/knowledge-bank-knowledge-bank.yaml)
- [TTS](capabilities/tts-tts.yaml)
- [Narrative](capabilities/narrative-narrative.yaml)
- [Chat History](capabilities/chat-history-chat-history.yaml)
- [Custom LLM](capabilities/custom-llm-custom-llm.yaml)
- [Evaluation](capabilities/evaluation-evaluation.yaml)

### Plans, Rate Limits, FinOps

- [API Commons Plans](plans/convai-plans-pricing.yml)
- [API Commons Rate Limits](rate-limits/convai-rate-limits.yml)
- [FinOps](finops/convai-finops.yml)

# Justin Wilson

I build production AI systems: multi-agent workspaces, governed tool access, and the evaluation around them. Eighteen years shipping platforms in healthcare, insurance, and government. Right now that looks like [Rivulets](https://github.com/jwilson411/Rivulets), the [rivulet-dispatch](https://github.com/jwilson411/rivulet-dispatch) library it is built on, a local [Kokoro TTS](https://github.com/jwilson411/kokoro-tts-api) wrapper, and daily writing at [Signal Over Noise](https://signalovernoise.tech).

**Rivulets** is a local-first, peer-to-peer workspace in the shape of Slack. You put humans and teams of AI agents in the same channels. Dispatch is deterministic first, LLM only when a rule misses, with handoffs and loop guards so the roster cannot talk itself in circles. It sits on [Agno AgentOS](https://github.com/agno-agi/agno). There is no hosted service. Keys stay on the machine.

**rivulet-dispatch** is that routing core as a standalone MIT library. Mentions win. Deterministic rules run next. An injected LLM fallback runs only when nothing matched. A one-specialist lock and in-memory loop guards stop unsolicited rematch. Zero runtime dependencies.

**kokoro-tts-api** is a FastAPI wrapper around Kokoro-82M. Text in, WAV out. Voices are allowlisted. Weights stay on disk after the first Hugging Face download. CI boots the app without pulling the model.

**Signal Over Noise** is the public notebook: production AI, agent platforms, and what actually ships versus what gets announced.

## On this account

| Repo | What it proves |
|---|---|
| [Rivulets](https://github.com/jwilson411/Rivulets) | Local-first multi-agent workspace, dispatch, MCP, P2P sync |
| [rivulet-dispatch](https://github.com/jwilson411/rivulet-dispatch) | Testable multi-agent router. Mentions, rules, lock, loop guards. |
| [kokoro-tts-api](https://github.com/jwilson411/kokoro-tts-api) | Local inference behind an HTTP contract. No weights in git. |

More public extracts are coming: a small MCP policy gateway, and system-level agent evals. The work is the record. The articles point at the repos.

## Elsewhere

- Writing: [signalovernoise.tech](https://signalovernoise.tech)
- Substack: [signalovernoisetech.substack.com](https://signalovernoisetech.substack.com)
- LinkedIn: [justinwilson411](https://www.linkedin.com/in/justinwilson411)

# Awesome OpenClaw Alternatives [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of OpenClaw alternatives, rewrites, and implementations across different programming languages and platforms.

OpenClaw (formerly Clawdbot → Moltbot) sparked an ecosystem explosion. From a single TypeScript implementation to 30+ alternatives across 8+ programming languages, these projects optimize for everything from $10 microcontrollers to enterprise security.

## Contents

- [Original](#original)
- [Ultra-Lightweight (Sub-10MB)](#ultra-lightweight-sub-10mb)
- [Security-Focused](#security-focused)
- [Minimal/Research-Friendly](#minimalresearch-friendly)
- [Other Implementations](#other-implementations)
- [Cloud/Managed Services](#cloudmanaged-services)
- [Enterprise/Commercial](#enterprisecommercial)
- [By Programming Language](#by-programming-language)
- [Resources](#resources)


### OpenClaw
**TypeScript | ~5.98s startup | 1.52GB RAM**
- [Github](https://github.com/openclaw/openclaw) | 243k+ ⭐
- Formerly Clawdbot → Moltbot → OpenClaw
- The reference implementation that started it all
- Full-featured with 15+ messaging platforms, 430k+ LOC


### PicoClaw
**Go | ~8MB binary | <10MB RAM**
- [Github](https://github.com/sipeed/picoclaw) | 21k+ ⭐
- Built for $10 hardware (RISC-V, ARM, x86)
- 95% AI-generated code
- Single self-contained binary
- Runs on decade-old Android phones

### NullClaw
**Zig | 678KB binary | ~1MB RAM**
- [Github](https://github.com/nullclaw/nullclaw) | 1.4k+ ⭐
- <2ms startup on Apple Silicon
- 3,230+ passing tests (highest in ecosystem)
- 22+ providers, Arduino/Raspberry Pi support
- MIT licensed

### ZeroClaw
**Rust | 3.4MB binary | <5MB RAM**
- [Github](https://github.com/openagen/zeroclaw)
- <10ms startup
- Trait-based pluggable architecture
- "Zero compromise" philosophy

### zclaw
**C | 888KB firmware | -**
- [Github](https://github.com/tnm/zclaw)
- For ESP32 microcontrollers
- Runs on Seeed XIAO ESP32-C3
- GPIO control, timezone-aware scheduling
- Telegram integration

### MimiClaw
**C | 16MB flash | 8MB PSRAM**
- [Github](https://github.com/memovai/mimiclaw)
- Bare-metal ESP32-S3 implementation
- No OS required
- ~$5 hardware cost
- 0.5W USB power consumption
- Plain text filesystem memory

### IronClaw
**Rust | - | -**
- [Github](https://github.com/nearai/ironclaw)
- By Near AI
- Capability-based security with WebAssembly sandboxing
- Credential isolation with TEE
- Multi-layer prompt injection defense
- Secrets never exposed to tools

### NanoClaw
**TypeScript | - | -**
- [Github](https://github.com/qwibitai/nanoclaw)
- Container isolation (Apple Container/Docker)
- Built on Anthropic Agent SDK
- Filesystem isolation per group
- Agent swarms support

### Safeclaw
**Python | - | -**
- [Github](https://github.com/princezuda/safeclaw)
- Uses intent recognition instead of LLM
- Immune to prompt injection
- $0 API costs
- VADER, spaCy, YOLO, Whisper stack

### ZeptoClaw
**Rust | ~6MB binary | ~6MB RAM**
- [Github](https://github.com/qhkm/zeptoclaw)
- 7-layer security architecture
- Container isolation
- Prompt injection detection
- Secret scanning
- One-command OpenClaw migration

### Nanobot
**Python | - | ~100MB RAM**
- [GitHub](https://github.com/HKUDS/nanobot)
- 99% smaller codebase than OpenClaw
- Research-friendly architecture
- MCP support, 11+ LLM providers
- 8+ messaging platforms

### TinyClaw
**Shell/TypeScript | - | -**
- [Github](https://github.com/warengonzaga/tinyclaw)
- Multi-agent orchestration
- Claude Code + tmux integration
- Self-healing capabilities
- WhatsApp support
- Real-time collaboration dashboard

### HermitClaw
**Python | - | -**
- [Github](https://github.com/brendanhogan/hermitclaw)
- Lives in a folder
- Continuously generates reports/scripts
- Autonomous research agent

### shrew
**Rust | - | -**
- Compact autonomous assistant
- Speed-optimized
- Minimal resource usage

### subzeroclaw
**C | - | -**
- Skill-driven for edge hardware
- Ultra-efficient execution

---


## Performance Comparison

| Project | Language | Binary Size | RAM | Startup | Stars |
|---------|----------|-------------|-----|---------|-------|
| OpenClaw | TypeScript | 28MB+ | 1.52GB | ~5.98s | 243k+ |
| PicoClaw | Go | ~8MB | <10MB | <1s | 21k+ |
| NullClaw | Zig | 678KB | ~1MB | <2ms | 1.4k+ |
| ZeroClaw | Rust | 3.4MB | <5MB | <10ms | - |
| ZeptoClaw | Rust | ~6MB | ~6MB | ~50ms | - |
| Nanobot | Python | - | ~100MB | - | - |
| IronClaw | Rust | - | - | - | 3.2k+ |
| NanoClaw | TypeScript | - | - | - | 7k+ |

---


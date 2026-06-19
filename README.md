# c3

**c3 (Code Creative Center)** is a coding platform that fuses harness and loop
engineering with AI software-engineering practice. Instead of throwing a raw prompt at a
model and hoping for the best, c3 turns vague, half-formed requirements into structured
intents — each with a clear scope, explicit dependencies, and a verifiable definition of done.

## Features

- **Structured intents** — vague requirements become scoped, dependency-aware tasks with a verifiable definition of done.
- **Automated loops** — planning, implementation, and validation run as repeatable, auditable flows.
- **Multi-agent discussions** — perspectives converge before code is written.
- **Scheduled tasks** — long-running and recurring work keeps moving on its own.
- **Spec-first & locally owned** — the spec is the source of truth, and everything runs as a single local process you control.

## Prerequisites

c3 drives Claude Code and Codex, so you need both installed:

- **Claude Code** — `curl -fsSL https://claude.ai/install.sh | bash`, or see the [quickstart](https://code.claude.com/docs/en/quickstart).
- **Codex** — `curl -fsSL https://chatgpt.com/codex/install.sh | sh`, or see the [CLI docs](https://developers.openai.com/codex/cli).

## Download

Grab the latest build from the [releases page](https://github.com/sequencestream/c3/releases/).

## Usage

```bash
# Extract the release for your platform, e.g. c3-v0.2.0-macos-arm64.tar.gz
tar -xzvf c3-v0.2.0-macos-arm64.tar.gz

# Start c3 on port 9000
./c3 --port 9000
```

> **macOS note:** the first launch may trigger a security warning. Allow c3 to run in
> *System Settings → Privacy & Security*.

Then open http://localhost:9000 in your browser.

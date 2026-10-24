# AI Development Environments

**Status:** Planned

## Goal

Compare two approaches to an AI-assisted development workflow:

- **Setup A:** Warp + TTT + Codex CLI
- **Setup B:** Zed + Codex

The goal is not to replace a primary IDE at any cost. It is to find a comfortable,
low-friction workflow for editing code, collaborating with an agent, reviewing
changes, and running tests in one environment.

## Methodology

Use the same Java/Gradle repository at the same starting commit for both setups.
Record tool versions, configuration, elapsed time, friction points, and any
unexpected behavior. Use separate working trees or reset between trials.

## Evaluation criteria

| Criterion | Weight |
| --- | ---: |
| Editing and navigation | 25% |
| Codex integration | 25% |
| Git and diff review | 15% |
| Java, LSP, and tests | 15% |
| Day-to-day comfort | 15% |
| Setup simplicity | 5% |

Rate each criterion from 1 (poor) to 5 (excellent). Calculate a weighted score
out of 100, but include qualitative observations and limitations.

## Planned scenarios

1. Navigate to a class, definition, and references.
2. Edit a method and assess completion, formatting, and diagnostics.
3. Ask Codex for a small refactor and request a follow-up change.
4. Review and selectively revert changes.
5. Run tests, inspect failures, and make a fix.
6. Switch between agent, editor, and terminal during normal work.

## Results

_Not tested yet. Add setup notes, screenshots, measurements, and conclusions as the experiment progresses._

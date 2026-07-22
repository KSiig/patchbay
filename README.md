# Patchbay

A tmux-overlay TUI for context-switching across AI sessions, worktrees, and tickets.

Opinionated but configurable. Pluggable AI harnesses (Claude Code, OpenCode at launch). Pluggable ticketing (Linear at launch). Designed to offload mental decisions like "what should I switch into", "where is the PR for this", "what's the status" — so you just switch into the context and continue working.

## Status

Early bootstrap. Tracking happens in the [Patchbay Linear project](https://linear.app/velatir/project/patchbay-0477c69f482e) — see there for the current milestone and in-flight issues.

## Goal

Patchbay is a tmux-overlay TUI for context-switching across AI sessions and tickets. It surfaces the live tmux sessions, worktrees, and tickets you're juggling, and lets you jump between them without losing state — pick up where another session left off, switch into the right worktree for a ticket, and resume.

## Building

```sh
cargo build
```

## Running

Not yet usable. Bootstrap only — see the M0 milestone for the first usable feature (tmux session list).

## License

[MIT](LICENSE) — see the [LICENSE](LICENSE) file for the full text.

<img src="notholy.png" width="72" alt="NotHoly">

# NotHoly

Uncensored and abliterated models for offensive security, for teams and solo researchers: reverse engineering of apps and binaries, pentest, bug bounty, red team, malware analysis, vulnerability research and OSINT. Abliterated means the refusal behavior was removed from the weights.

The models are served through an API compatible with OpenAI and Anthropic clients at `api.notholy.com/v1`, and through the tools below.

| Repository | What it is |
|---|---|
| [notholy-cli](https://github.com/notholylabs/notholy-cli) | Agent in your terminal on NotHoly models, built on the open-source Codex CLI. |
| [notholy-vscode](https://github.com/notholylabs/notholy-vscode) | VS Code extension: security review, CVE lookups, regression tests and detection rules. |

Install the CLI:

```bash
curl -fsSL https://notholy.com/install.sh | sh        # macOS, Linux
irm https://notholy.com/install.ps1 | iex             # Windows PowerShell
```

[Website](https://notholy.com) · [Docs](https://docs.notholy.com) · [Models and prices](https://notholy.com/en/models) · [Status](https://status.notholy.com) · [Security reports](https://notholy.com/.well-known/security.txt)

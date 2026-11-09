# FreeFlow Dictation plugins for Claude Code

This repository is a Claude Code plugin marketplace: a catalog that tells Claude Code where to fetch each plugin from. It is published by [FreeFlow Dictation](https://freeflow.audio), the on-device dictation app for macOS.

Add it once:

```bash
claude plugin marketplace add FreemanGT/freeflow-dictation-plugins
```

## Plugins

| Plugin | What it does | Install |
| :- | :- | :- |
| [`freeflow-dictation`](https://github.com/FreemanGT/freeflow-dictation-claude-plugin) | Answer Claude Code's plan, question and permission prompts by voice, on-device. Requires FreeFlow Dictation for macOS. | `claude plugin install freeflow-dictation@freeflow-dictation` |

Or, on Claude Code 2.1.292 or later, add the marketplace and install in one line:

```bash
claude plugin install freeflow-dictation --marketplace FreemanGT/freeflow-dictation-plugins
```

The catalog itself is `.claude-plugin/marketplace.json`. Each plugin's own repository holds its manifest, hooks and documentation.

## Licence

The catalog is released under the MIT licence; see [LICENSE](LICENSE). FreeFlow Dictation itself is a separate commercial product and is not covered by it.

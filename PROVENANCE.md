# Provenance

This repository was split from VIVIAN-LCTL-Agent-Team-1.0.0 on 2026-10-04.
The display name is **Critique**; its original policy identifier is `player_critic`.
The policy triple and Python execution adapter were copied without modification.
The standalone runner, tests, examples and these repository documents are new.

The source package used the native compiler supplied by
`BOTTLE_ROCKET_5.0.1_VM_110K_RC`. Its source authority is frozen at 4.7.0 within
the 5.0.1 maintenance RC. `brim_ref.py` is preserved unchanged from that scaffold.

| Artifact | SHA-256 |
| --- | --- |
| `player_critic.lctlc` | `8cd15080fd2a717b509891975cb16b791ca98cc8fe1263ac69188a4575e15ffc` |
| `player_critic.brir` | `dd3db47b025691d7eed7a0d55c6bafe44eb79a49658b75a274f9823e0e75c450` |
| `player_critic.brimg` | `3c233d8f4b5786f99c9f3377df90bdf03519477d811633bec8720b9fa8827a8d` |
| `brim_ref.py` | `333b8bcf2c876efb6aec1373f24aa21da83e26036fecedd5bdcb99f10cae3056` |
| `runtime.py` | `04ba038237bf1416869483dfd0f37d3ae51deb486ff8305e6d32e406235343a3` |

Conceptual references used in the original team implementation:

- Giacomo Bonanno, *Game Theory* (2015), supplied PDF `1512.06808v1.pdf`:
  explicit players/actions/preferences, declared utility assumptions, and
  distinctions among strategic concepts.
- *Understanding Harness Engineering*, supplied PDF: bounded execution,
  provenance, explicit handoffs, and independent acceptance checks.
- `awesome-ai-agents-main.zip`: a catalogue of agent project descriptions,
  used as design context. AutoGen/crewAI and LangGraph informed coordination;
  Agent Argue and Quorum informed evidence/critique separation. Their code was
  not imported and these policies are not copies of those projects.

The six strategies, the coordination reward model, and the staged BRIM handoff
are implementation choices, not guarantees attributed to those references.
The original PDFs, catalogue archive, full scaffold archive, private logs,
backups, machine paths and model-training files are not redistributed here.

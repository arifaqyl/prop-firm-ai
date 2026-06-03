# Changelog

## v4 - Current public snapshot

Current state of the repository:

- research analyzer + hybrid gate architecture
- paper trading simulation
- risk / sizing / audit scaffolding
- subagent-inspired decision pipeline
- macro context, options GEX, news veto, microstructure monitor
- local-first Ollama support
- public-safe sanitized repo layout

## v3 - Validation-first analyzer plan

Main ideas that shaped the current implementation:

- analyzer must be allowed to say `no_edge`
- confidence and calibration gates come before trade permission
- predictions need evidence next to them
- paper journaling belongs early, not late
- regime-aware reasoning matters

## v2 - Research quality improvements

Main upgrades from the original concept:

- structured LLM contract
- data freshness discipline
- gold-specific macro logic
- Brier skill thinking instead of raw confidence-only evaluation

## v1 - Original concept

Starting point:

- AI trading analyzer
- reads charts and supporting context
- estimates likely direction
- intended to move away from blind guessing toward evidence-backed calls

## Notes

- Public git history begins at the sanitized `v4` snapshot.
- Earlier versions were developed through local iteration, planning, and direct implementation rather than preserved as public git milestones.

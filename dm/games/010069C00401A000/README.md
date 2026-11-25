# RIVE: Ultimate Edition (`010069C00401A000`)

Base game with Update 1.22. No game-specific configuration, patches or pipeline modifications are required; the game works with the default pipeline.

**Mac playtest:** Apple M1 MacBook Air, 16 GB RAM, macOS 27. Approximately four hours of sustained gameplay at a consistent 60 fps, with occasional dips to 59 fps and no noticeable stuttering. The MacBook Air remained barely warm throughout the session, even while resting on a lap.

### Testing

- macOS app build: successful.
- Python 3.14.
- Runs at 60 fps on an M1 MacBook Air with 16 GB RAM, over four hours of continuous gameplay, with occasional dips to 59 fps and no noticeable stuttering.
- Related upstream reference: [RIVE profile review on PR #3326](https://github.com/seedds/nxnative/pull/3326#pullrequestreview-6058738570).

## Validation status

This is a provisional Mac profile: the working build has passed the playtest above, but a formal upstream regression record (`validated.tsv`) has not yet been produced. Game-derived shader keys and shader-pair records are intentionally omitted; the profile therefore does not include a precomputed per-game shader table.

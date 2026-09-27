# Fork handoff

Updated 2026-09-27.

## Finished

The archived integration at `6d83037c2922ed954823a9ecc71296ebf26f30d1`
is merged with `ai-re-agent` at `bc8a9c5ac93ff047e7f902c549505d26a2765679`.
All emulator source and regression tests are unchanged from the integration pin.
The only reconciliation is to target both Windows and Linux PR gates, and their
documentation, at `ai-re-agent`.

## Next

Run both PR gates on this final head before merging into `ai-re-agent`, then
update the parent repository pin. Do not use the retired integration branch.
Existing snapshot limitations remain recorded in `PERSISTENT_STATE_DEBT.md`;
consolidating history does not close those limitations.

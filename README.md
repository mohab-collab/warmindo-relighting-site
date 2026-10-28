# Warmindo — Relighting Consistency Review

A review site for the Pratidina virtual-production relighting tests on shot HD-COMP-B001: 6 camera angles of the same warung set.

## Open it

Clone the repo, then serve the folder (browsers block local video playback from `file://`):

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Tabs

- **Shot by shot**: one card per camera, with an original vs. relight compare slider, every version as a thumbnail, the exact prompt and settings for the selected version, and the original, V6 night and V4 studio videos with their prompts.
- **All angles · consistency**: all 6 cameras in one lighting version, plus a synced video wall.
- **Notes & issues**: what each step tried, what worked, what went wrong, and what to do next.

## Tools

- Stills: Higgsfield **Nano Banana 2.1**, 2K, thinking level medium, 16:9.
- Videos: Higgsfield **Kling 4.0** video-edit, 15s, 16:9, 720p, using the relit still as the reference.

All the prompts are also in [`Lighting_Plan_and_Prompts.md`](Lighting_Plan_and_Prompts.md).

# Cascade Ascendant Editorial Workspace

A human-led, AI-assisted editorial repository for refining *Cascade Ascendant* scene by scene.

This repo is designed to protect the manuscript while making revision organized, recoverable, and targeted. AI agents may analyze, map, compare, detect, compress, and propose; they do **not** decide canon.

## Core Rule

The original manuscript text must never be overwritten. Every scene file preserves:

- `Original Text`
- `Scene Map`
- `Editorial Overlay`
- `Revision History`
- `Current Approved Text`

Only the Human Editor approves canonical changes.

## Repository Map

```text
manuscript/master/        Full manuscript source
manuscript/scenes/        Modular scene files
manuscript/approved/      Human-approved scene versions
overlays/                 Editorial overlays and analysis maps
agents/                   Agent instructions/prompts
proposed_revisions/       Proposed changes by revision pass
lore/                     Canon, symbols, characters, worldbuilding
exports/                  EPUB, DOCX, beta packets
templates/                Reusable scene and overlay templates
docs/workflows/           Operating procedures
```

## Recommended Workflow

1. Add the full manuscript to `manuscript/master/Cascade_Ascendant_Master.md`.
2. Run the SceneMapper instructions in `agents/01_scene_mapper.md`.
3. Create scene files using `templates/scene_file_template.md`.
4. Generate scene overlays using `agents/02_overlay_agent.md`.
5. Apply targeted revision passes in branches.
6. Review proposed revisions manually.
7. Copy approved text into `manuscript/approved/`.
8. Merge only approved work into `main`.

## Suggested Branches

```bash
git checkout -b compression-pass-v1
git checkout -b voice-differentiation
git checkout -b mcclane-pass
git checkout -b emotional-density-pass
git checkout -b final-line-pass
```

## AI Usage Boundaries

Good tasks:

- scene mapping
- editorial diagnostics
- continuity tracking
- emotional density analysis
- voice comparison
- compression suggestions

Avoid:

- autonomous rewrites
- generic “improve this” prompts
- recursive AI self-editing
- replacing authorial judgment

## Start Here

Read `docs/workflows/START_HERE.md` first.

## License

All Rights Reserved.

No permission is granted to copy, modify, distribute, train AI systems on, or create derivative works from this repository or its contents without explicit written permission from the copyright holder.
```markdown
## License

This project is licensed under the Cascade Editorial System License (CESL) v1.0.

Personal and educational use permitted.
Commercial use prohibited without permission.

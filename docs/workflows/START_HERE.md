# Start Here

## First Setup

1. Create a new GitHub repository named `cascade-ascendant-editorial`.
2. Upload this folder structure.
3. Place the full manuscript in:

```text
manuscript/master/Cascade_Ascendant_Master.md
```

4. Do not edit that master file directly once scene extraction begins.

## First Editorial Task

Use `agents/01_scene_mapper.md` to split the manuscript into scene files.

Each scene should use:

```text
templates/scene_file_template.md
```

## Human Checkpoint

Before any revision pass begins, review scene boundaries manually.

Do not let an AI agent decide final boundaries without author approval.

## First Safe Branch

```bash
git checkout -b scene-mapping-v1
```

After scene files are approved:

```bash
git checkout main
git merge scene-mapping-v1
```

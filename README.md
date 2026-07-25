# assets

Central home for reusable brand assets, templates, and prompts across all Brad Weimert projects.

Purpose: one canonical location to reference logos, headshots, brand colors, doc templates, and reusable prompts. Anything referenced by more than one project belongs here.

## Structure

```
assets/
  brand/
    brad-weimert/       BW / BWT personal brand
    easy-pay-direct/    EPD company brand
    beyond-a-million/   BAM podcast brand
  templates/            reusable doc/README/skill templates
  prompts/              reusable LLM prompt scaffolds
```

Each subfolder has its own `README.md` listing canonical files, their intended use, and a `last verified` date.

## How to reference an asset

**In code / HTML / markdown** — use the GitHub raw URL:

```
https://raw.githubusercontent.com/MrWeimert/assets/main/assets/brand/brad-weimert/favicon.ico
```

**Never** hardcode `/home/user/workspace/...` paths in project docs. Those paths are ephemeral and disappear between sessions.

## Adding a new asset

1. Drop the file in the correct subfolder
2. Update that folder's `README.md` with the file, intended use, and today's date
3. Commit with a short message describing what was added
4. Reference the raw GitHub URL from wherever you use it

## Escape hatch

Some projects have their own brand systems and store assets in their own repos. That's fine — declare the location in that project's `docs/OVERVIEW.md` and this repo is not the source of truth for that project.

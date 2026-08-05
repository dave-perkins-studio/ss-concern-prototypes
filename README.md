# Concern Worldwide — SystemSeed design prototypes

Published prototypes for Concern Worldwide, gathered in one place so a single
link reaches all of them.

**Live:** https://dave-perkins-studio.github.io/ss-concern-prototypes/

| Path | Prototype | Source of truth (private) |
|---|---|---|
| `company-checkbox/` | The company checkbox on step 2 of the donation form — the live control measured and reproduced, the two fixes suggested so far built out in full, and three more | `dave-perkins-studio/ss-concern-company-checkbox` |

## Not official Concern builds

These are SystemSeed design prototypes. The Concern branding is a
reconstruction, made so each design question can be judged in its real
surroundings; photography and illustration are placeholders, and each page
carries that notice in its own footer. Every page is marked
`noindex, nofollow` so none will be indexed as Concern's own.

Nothing here submits, takes payment, or collects data.

## This repo is public only to serve the pages

It holds nothing but the built prototypes and this index. The projects they
belong to — the briefs, research, QA reports and decision journals — stay in
private repos, listed in the table above.

## Do not edit the prototypes here

They are **copies**. Edit the source in the private project repo, then
republish from there:

```bash
./tools/publish-prototype.sh
```

`--check` exits non-zero if a published copy has drifted from its source.
Editing a copy here means the next publish silently overwrites your work.

## Adding another prototype

1. New folder, lowercase-hyphenated, named for the prototype.
2. The prototype itself as `index.html` inside it, so the URL stays tidy.
3. A row in the table above, and a card in the root `index.html`.
4. A publish script in the private project repo that copies into this one.

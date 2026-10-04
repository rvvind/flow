# Flow implementation plan

Recover the intent and runnable boundary of the Flow for WSI interface prototype.

Status: proposed next work, prepared from local source inspection on 2026-10-04. Existing behavior below has not been rerun or release-verified in this planning pass. Update this file as work lands; check an item only after recording its acceptance evidence.

## Current evidence

The repository contains static HTML, CSS, JavaScript, and fonts. html/start.html identifies Flow for WSI and contains repeated sample cards and a login form. The README has only the project name.

## Pending implementation

- [ ] Document the intended WSI workflow and whether this remains a reference prototype or should be resumed.
- [ ] Create a local preview procedure and inventory which controls navigate, which use sample data, and which imply an absent backend.
- [ ] For a resumed prototype, replace repeated sample records with a small named fixture and implement one end-to-end navigation path without implying real authentication.

## Acceptance

The README identifies the user and one supported task. The preview opens without missing assets, and sample data and nonfunctional controls are clear.

## Scope and decisions

No backend or new product direction is established by the repository. Archive/reference is a valid outcome of the first decision.

## Sources

- [README.md](<README.md>)
- [html/start.html](<html/start.html>)
- [js](<js>)
- [css](<css>)

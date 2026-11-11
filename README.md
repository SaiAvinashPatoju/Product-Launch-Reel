# Exvisit Studio - product launch reel

A production repository for a **human-crafted, 60-second, fullscreen 9:16 Meta ad**.

**Message:** Understand your project. Direct your agents.

**CTA:** Download Exvisit Studio.

## Start here

1. Read [DESIGNER_BRIEF.md](DESIGNER_BRIEF.md), the current production direction and human-craft requirement.
2. Read [STORYBOARD.md](STORYBOARD.md) and [SCRIPT.md](SCRIPT.md) for the proposed twelve-shot sequence and narration.
3. Open [Designer-Handoff.html](Designer-Handoff.html) for the visual study and shot layouts, or use the [PDF handoff](Exvisit-Studio-Designer-Storyboard.pdf).
4. Track work in [PRODUCTION.md](PRODUCTION.md) and record founder decisions in [reviews/DECISIONS.md](reviews/DECISIONS.md).

## Production requirement

The founder is commissioning a human designer for visual taste, frame composition, animation, pacing, music and sound design. **Do not generate the final film or its creative assets with AI.** Use original human design, real Exvisit footage, human voice, and original or commercially licensed music and sound effects. See the brief for precise scope.

The supplied storyboard and sketches were prepared with AI assistance as planning references. They are not the final visual standard. The human designer should develop and present original style frames and motion direction.

## Repository map

| Location | Purpose |
| --- | --- |
| `DESIGNER_BRIEF.md` | Current assignment, constraints, review process and deliverables |
| `STORYBOARD.md` | Proposed timing, screen actions and scene direction |
| `SCRIPT.md`, `VOICEOVER.txt` | Proposed 130-word narration |
| `Designer-Handoff.html` | Self-contained visual handoff; no installation required |
| `Exvisit-Studio-Designer-Storyboard.pdf` | Printable handoff with current human-production direction |
| `reference-frames/`, `reference-*.jpg` | 48 reference frames and four timestamped contact sheets |
| `reference-index.json` | Original video links and frame timestamps |
| `product-captures/` | Existing Exvisit screenshots used for framing |
| `layout-sketches/`, `storyboard-overview.jpg` | Rough planning sketches, not final creative |
| `designer-project/` | Editable-project delivery instructions and future source location |
| `footage/`, `audio/`, `exports/` | Recording, audio and delivery manifests |
| `ASSET_REGISTER.md` | Asset origins and paid-ad rights tracking |
| `PRODUCTION.md`, `reviews/` | Progress and explicit review decisions |
| `storyboard-data.json` | Structured planning data, not an automatic film generator |

## Current state

The storyboard is a proposal: twelve contiguous shots across exactly 60 seconds, with a 130-word draft voiceover. No style frames, animatic, music, narration or final edit have been approved.

New matching sign-in footage is required. The available Space screenshot shows checkout logic and must not be passed off as a sign-in graph. Existing captures may contain demo data or older labels.

Reference imagery is for internal study, not footage for the ad. Check the final app build, pricing qualifier and download journey before release.

## Working with this repository

Commit coherent changes to the brief, script, visual references and review notes. Keep raw recordings, large project files, audio and film exports in agreed shared storage; their folders explain what locations and versions to record. These large files are currently ignored by Git. Revisit storage deliberately if the team chooses Git LFS later.

`DESIGNER_BRIEF.md` is the authority for production constraints. Update the Markdown proposal first when the story changes, and keep visual exports and structured data consistent with it. Record the founder's approval against the reviewed version rather than inferring it from a file name or commit.

This repository is local. No remote has been configured and no campaign has been published.

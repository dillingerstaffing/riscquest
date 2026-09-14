# RISCQUEST: Throne of the Tag — DM's game log

Private campaign board for Chris's Stack Overflow RISC-V quest.
- Source of truth: `~/workspace/riscquest/index.html` (single self-contained file)
- Private repo: `dillingerstaffing/riscquest` (main branch)
- Playable artifact slug: `riscquest` (web_static, unshared = private to Chris)
- Rule: edit `index.html`, commit + push to the repo, then apply the same change to the artifact via `artifact.edit`. Never let the three drift.

## State (2026-09-14, launch)

- Rank: I (LANDED). Next: II (BLOODED), objective "Post your first answer", 0/1.
- Glory: 70 (7 battle plans x 10).
- Stats: answers 0, accepts 0, upvotes 0, best --, bounties 0, wounds 0.
- Season 1 (Sep 2026): goal "score first points, finish top 3". Board: rivals 2 and 1, Chris 0. 16 days remain.
- Rivals (all-time): Erik Eidt 398, the other Chris 215, Chris 1.
- Achievements: 0/9 unlocked.
- Quests pinned (7): The Preserved Register (79747810, greenhorn), The Missing Barrier (79564665, greenhorn), The False Syscall (78562503, dungeon), The Reservation (70242113, necromancer), The Stale Register (79237441, dungeon), The False Interrupt (64863737, lorekeeper), The Hidden Hart (77925031, dungeon).

## Glory awards

| Date | Event | Glory |
|------|-------|-------|
| 2026-09-12 | Battle plan: The False Syscall | +10 |
| 2026-09-13 | Battle plan: The Reservation | +10 |
| 2026-09-13 | Battle plan: The Stale Register | +10 |
| 2026-09-13 | Battle plan: The Hidden Hart | +10 |
| 2026-09-13 | Battle plan: The False Interrupt | +10 |
| 2026-09-14 | Battle plan: The Preserved Register | +10 |
| 2026-09-14 | Battle plan: The Missing Barrier | +10 |

## Award table (DM use)

- Battle plan drafted: +10 (DM)
- Answer posted: +50
- Upvote received: +25 each
- Answer accepted: +100
- Outscore a top-10 answerer on their question: +75
- Comment thread resolved: +15
- Downvote: -20, plus battle-scar note

## Rank-up checklist (when Chris reports an outcome)

1. Verify on Stack Overflow (question page: his answer exists, score, accepted?).
2. Append a dated entry to GAME.chronicle (Glory auto-sums from it; never edit a total by hand). Update GAME.stats. If a quest resolved, set its status ("answered"/"accepted") and date.
3. If a rank objective completes, bump GAME.rank and stamp that rank's date (the board plays the fanfare on his next open).
4. If an achievement unlocks, set unlocked:true and stamp its date. If an SO milestone completes, stamp its date. If a road projection is achieved, stamp its date.
5. Commit + push repo, artifact.edit the same changes.
6. Announce in this side chat with ceremony. Never a dry diff.

## History law (2026-09-14)

Nothing is ever erased. Completed ranks, milestones, seals, quests, road projections, and seasons keep their dates forever and stay visible on the board. The Chronicle is append-only: every state change adds a dated entry, never rewrites one. Past (dated completions), present (current state), future (objectives and projections) must all read clearly at a glance.

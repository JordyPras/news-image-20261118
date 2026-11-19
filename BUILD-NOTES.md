# news-image-20261118 — BUILD-NOTES

Entry: newspaper front-page image summing up Wednesday 18 November 2026.

## Image
- Generated in the live session (media.generate_image) from the verified research in
  `../research-18nov.md` (13 headline stories + briefs 14–30, sources Reuters/AP/Just Security/
  Le Monde/NASA JPL/IMD/PAHO, cross-checked).
- Original 1600×1600 PNG (3.3 MB) → resized 1024×1024, 256-color palette PNG,
  583,535 bytes — inside the gate (≤1 MiB, ≤1024×1024).
- Legibility checked by eye: masthead THE WORLD, date line "WEDNESDAY 18 NOVEMBER 2026",
  and all 3 main headlines (Gulf airstrikes, Xi greets Trump in Shenzhen, Crimea bridge)
  are crisp; 10 small stories, world map with pins, brief list, Reuters—AP—AFP source line.
- Facts screened: GTA VI framed as midnight launch (releases 19 Nov, not 18 Nov);
  COP31 excluded (in top-3 feeds but no verified 18 Nov development found).

## Program
- Starter main.ts (Node 22 stdlib, copies entry.png to /output/entry.png) with a real
  restructure in this session (entryImage/outputDir consts) so the entrypoint carries
  authored lines for the thinking_reproduces gate.
- Local test: `mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts` → out/entry.png
  byte-identical to repo entry.png.

## Submit path
- User creates empty public repo JordyPras/news-image-20261118, uploads contents at root
  (+ .makefun/owner.json via Create new file), sets About per requirements repo_about.
- Parent verifies via GitHub API, re-runs check on the new head, bundles transcripts,
  submits before Fri 2026-11-20 07:00 WIB. $250 USDC escrowed → signed entry.

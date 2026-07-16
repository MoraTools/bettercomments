# bettercomments — Agent Context

Custom Automation Anywhere A360 package (`BetterComments.jar`) — adds multi-line comments and
embedded images to bot logic. Imported via Control Room > Packages. Build/patch notes in `README.md`.

## Central Knowledge Base

Shared AA knowledge: `<AA_KB_ROOT>`. Resolve environment variable; fallback: sibling `..\aa-kb`.

- Start: `<AA_KB_ROOT>\README.md` → `<AA_KB_ROOT>\projects\bettercomments.md`.
- Never bulk-load `<AA_KB_ROOT>\artifacts\` (~50 GB).
- Updates: `<AA_KB_ROOT>\UPDATE.md`.
- Diffs: compare by default. Ingest requires explicit approval.

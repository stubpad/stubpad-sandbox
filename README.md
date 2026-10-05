# stubpad-sandbox

Test repository for [Stubpad](https://stubpad.com)'s GitHub sync. Its source
is `crates/server/tests/fixtures/sandbox-repo` in the Stubpad repository.

| Path | What it tests |
|---|---|
| `skills/pdf-review/` | a skill with a manifest |
| `skills/commit-helper/` | a `SKILL.md` without a manifest (0.0.N versions) |
| `CLAUDE.md` | recognized as the `claude-md` rules |
| `rules/crlf-rules/` | a file kept with CRLF line endings |
| `code/snippet/` | a `code` artifact, never published |
| `broken/` | an invalid manifest |

# Contributing to Awesome Meta Platform

Thanks for helping keep this list useful and trustworthy.

## What belongs here

**Open-source code only** — libraries, SDKs, API clients, MCP servers, scrapers, and integration tools for Meta's developer platforms:

- Marketing API / Ads
- Graph API
- Conversions API (CAPI) & Pixel
- WhatsApp Cloud API
- Instagram Graph API
- Messenger Platform
- Ad Library / research tools

## What does NOT belong

- Marketing blogs, courses, or "growth hack" articles
- Closed-source SaaS products (no public source repo)
- Dead / inaccessible repositories
- Repos unrelated to the Meta ecosystem (name collisions)

## How to add an entry

1. Fork this repo and edit `README.md`.
2. Add your entry to the correct category table, alphabetically or by relevance.
3. Use this row format:
   ```
   | [repo-name](https://github.com/owner/repo) | One-line factual description. |
   ```
4. If the upstream repo is **archived**, append `` `Archived` `` to the description.
5. Do **not** add the star badge manually — it is injected automatically by a maintenance script.
6. Open a Pull Request describing what the tool does and why it fits.

## Quality bar

- The repo must be **reachable and real** — every entry is verified against the GitHub API before merge.
- Descriptions must be factual and one line — describe the tool's function, not marketing claims.
- No fabricated or unverified entries. If it can't be verified live, it won't be merged.

## Verifying links

Maintainers periodically audit every link:

```bash
grep -oE "https://github.com/[^/)]+/[^/)?]+" README.md | sed 's#https://github.com/##' \
  | grep -v "^ridloabelian/awesome-meta-platform" | sort -u > /tmp/repos.txt
TOKEN=$(gh auth token)
while read r; do
  fn=$(curl -s -H "Authorization: token $TOKEN" "https://api.github.com/repos/$r" | jq -r '.full_name // "DEAD"')
  [ "$fn" = "DEAD" ] && echo "DEAD: $r"
  [ "$fn" != "$r" ] && [ "$fn" != "DEAD" ] && echo "RENAMED: $r -> $fn"
done < /tmp/repos.txt
```

By contributing, you agree that your contributions are released under CC0 1.0.

# RF Studios Miami — Proposals

Client proposal system. HTML files are self-contained and served via GitHub Pages.

## Structure

```
templates/proposals/    ← MASTER TEMPLATES — never edit directly
clients/[client-slug]/  ← client deliverables, one folder per client
assets/                 ← shared images (if hosting externally)
```

## Workflow — New Proposal

1. Copy the right master from `templates/proposals/`
2. Rename: `[client-slug]-[preliminary|proposal]-[YYYY-MM].html`
3. Save to `clients/[client-slug]/`
4. Edit ONLY the `CONFIG` block at the top
5. Push → GitHub Pages serves the live URL

## Naming Convention

```
[client-slug]-[doc-type]-[YYYY-MM].html

continuum-preliminary-2026-06.html
continuum-proposal-2026-07.html
brickell-house-preliminary-2026-08.html
```

- `client-slug` = venue name, lowercase hyphenated (not contact name)
- `doc-type` = preliminary | proposal
- `YYYY-MM` = month sent

## Live URLs (GitHub Pages)

```
https://rfstudiosmiami.github.io/Proposals/clients/continuum/continuum-preliminary-2026-06.html
```

## Templates

| File | Use When |
|---|---|
| `rfstudios-preliminary.html` | Budget not confirmed. No pricing. Ends with Next Steps. |
| `rfstudios-proposal.html` | Budget confirmed. Pricing + signature/sign flow. |

## EmailJS (already wired in proposal template)

- Public Key: `Zsh7DzszsSoxTD4BN`
- Service ID: `service_a2z47rl`
- Template ID: `template_rlsqa1e`
- RF Email: `gina@RFStudiosMiami.com`

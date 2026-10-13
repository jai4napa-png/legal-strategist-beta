## v2.7.6 — Mandatory form instruction review

The mandatory [v2.7.6 beta patch](docs/downloads/Legal-Strategist-v2.7.6-Form-Instruction-Review-Patch.txt) requires the reviewer to find and actually **read** all official relevant court-form instructions (including distinct INFO sheets and local instructions) before saying a form is procedurally verified. Form-level instructions may specify operational requirements not obvious from governing statutes. The corresponding [P0 procedure-engine issue](https://github.com/jai4napa-png/legal-strategist-beta/issues/1) remains open: the full event-driven deadline tracker, live docket monitoring and notifications are not implemented.

## Lawyer Lens v2.7 — interactive question explorer

The new [Lawyer Lens browser app](docs/lawyer-lens.html) contains 363 curated plain-language legal questions plus 811 cross-linked Strategy Arsenal leads (1,174 total). Select one or many questions, explore up to five layers of seven skeptical legal-reasoning lenses, find blind spots, and export a ChatGPT investigation prompt or a local JSON session. This is an offline static client-side prototype; it does not read uploaded case files, access a court, verify legal authority or send data to an AI service.

To use the app, download `docs/lawyer-lens.html` and open it locally. If GitHub Pages is configured, it is served at `https://jai4napa-png.github.io/legal-strategist-beta/lawyer-lens.html`.

# Legal Strategist — ChatGPT Beta

Experimental, source-grounded legal analysis workflow for use within your own ChatGPT account. The companion toolkit includes procedural review, evidence mapping, adversarial analysis, and strategy exploration.

**Beta status:** This repository is being prepared for a public static website. It is not a hosted AI service or connected case database. Do not upload real case documents, medical records, privileged communications, passwords, or API credentials to this repository or public issues.

## Testing in ChatGPT

1. Obtain the ChatGPT beta instructions file from the release package.
2. Start a new ChatGPT conversation; upload the instructions and your authorized case documents.
3. Request an inventory of actually read records, procedural checks, decisive-element analysis, evidence-source mapping, and adversarial review.
4. Independently verify cited authorities and all legal conclusions.
5. Do not draft court documents until the elements checklist is approved and the specific draft is authorized.

**Limitations:** No automatic ChatGPT installation or cross-chat synchronization. No production-grade secured case repository, automated multi-provider orchestration, proprietary citator service, or guaranteed legal accuracy. A static website does not collect your case documents.

License: No general software reuse license has been selected.

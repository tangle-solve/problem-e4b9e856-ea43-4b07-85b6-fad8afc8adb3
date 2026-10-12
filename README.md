<!-- solve-problem:e4b9e856-ea43-4b07-85b6-fad8afc8adb3 -->
# ALGO-000016: Optimal PCP length

A [Tangle Solve problem](https://solve.tangle.tools/problems/e4b9e856-ea43-4b07-85b6-fad8afc8adb3).

Source verification label: flagged. Openness and correctness are not established by this listing. Contributions, audits and critiques are welcome.

### ALGO-000016: Optimal PCP length
- **Subfield:** proof complexity & PCP
- **Open:** How small can a probabilistically checkable proof be? Can the verification query length and proof length both be made optimal (constant queries, near-linear length)?
- **Status:** Open. Dinur's PCP (2007) gives constant-query, polynomial-length via gap amplification; short PCPs of near-linear length exist (Dinur–Harsha 2013) with worse parameters. The tradeoff frontier (query vs length vs alphabet) is actively open.
- **Type:** theory
- **Why:** PCP parameters control inapproximability reductions; tight PCPs would settle hardness-of-approximation constants.
- **Key works:** I. Dinur, "The PCP theorem by gap amplification", JACM 2007; I. Dinur, P. Harsha, "Composition of low-error 2-query PCPs using decodable PCPs", SIAM J. Computing 2013 (arXiv:1206.6432)
- **Aliases:** short PCP
- **Source:** fleet:gpt6pro:algorithms-complexity:2026-10-06-handwritten-seed

## Source verification record

```json
{
  "census": "live",
  "domain": "algorithms-complexity",
  "flags": [
    "citation-mismatch:1206.6432"
  ],
  "id": "ALGO-000016",
  "label": "flagged",
  "origin": "sourced",
  "source_checked_at": "2026-10-11",
  "source_kind": "manual",
  "source_verified": false,
  "triage": "suspect",
  "verified": false
}
```

## Contribute

Contributions, audits, and critiques from humans, agents, or both are welcome. Open a pull request with your work, then [publish the exact revision or artifacts on Solve](https://solve.tangle.tools/problems/e4b9e856-ea43-4b07-85b6-fad8afc8adb3?contribute=1). Include reviewed agent traces when available. Contributions need not solve the entire problem.

Keep experiment code, reports, and trace artifacts in this repository. Publish only material you have reviewed for public sharing. Solve retains the contribution snapshot and its review history independently of whether a pull request is merged.

Source record: ALGO-000016.

- [Public source catalog](https://drewstone.github.io/problems/#/p/ALGO-000016)

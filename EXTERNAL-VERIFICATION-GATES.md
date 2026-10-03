# External Verification Gates

Updated: 2026-10-03

The 150-stage portfolio is intentionally blocked from a false 100% claim until GitHub supplies external evidence for the remaining gates.

| Stage | Repository | Required evidence | Current connector observation |
|---|---|---|---|
| 24 | CyberIQ-DFIR-Lab | successful GitHub Actions run/check | no commit statuses or associated PR workflow runs returned |
| 48 | CyberAI-Lab | successful GitHub Actions run/check | no commit statuses or associated PR workflow runs returned |
| 73 | CyberIQ-Security-Tools-CYBERiQ | successful GitHub Actions run/check | no commit statuses or associated PR workflow runs returned |
| 97 | -CTF-Writeups-cyberiq | successful Pages deployment + reachable public endpoint | deployment workflow exists; successful deployment not yet evidenced |
| 150 | Portfolio | stages 24, 48, 73, and 97 verified | blocked by preceding external gates |

## Prepared remediation

- All three Python CI workflows support push, pull request, and manual workflow dispatch.
- Each Python repository contains `CI-VERIFICATION.md` with the evidence policy.
- The CTF repository contains an official Pages deployment workflow and `PAGES.md`.
- The portfolio contains `PORTFOLIO-RELEASE-READINESS.md`.

## Integrity rule

Do not convert any row above to complete merely because configuration exists. Close it only from observed successful GitHub evidence.

## Linked Bounty
Fixes #<bounty-issue-id>

## What Changed
Brief description of the changes made to address the bounty requirements.

## How to Test
Step-by-step instructions for testing the changes:
1. 
2. 
3. 

## Screenshots / Logs
Include screenshots for UI changes or logs for debugging information.

## Proof JSON Block
```json
{
  "schema": "passport-pr-proof@1.0",
  "github": {
    "repo": "<target-repo>",
    "pr": "<pr-number>",
    "issue": "<bounty-issue-id>",
    "commit": "<commit-hash>"
  },
  "bounty_id": "<bounty-id>",
  "account": {
    "stellar": "<stellar-address>",
    "smart_account": "<contract-id>"
  },
  "webauthn": {
    "alg": "ES256",
    "pubkey_cose": "<public-key>",
    "challenge": "<challenge>",
    "clientDataJSON": "<client-data>",
    "authenticatorData": "<auth-data>",
    "signature": "<signature>"
  },
  "timestamp": "<iso-timestamp>"
}
```

## Checklist
- [ ] CI passes (build, lint, tests)
- [ ] Meets all Acceptance Criteria from bounty
- [ ] Documentation updated where applicable
- [ ] Tests added for new functionality
- [ ] No regressions introduced
- [ ] Code follows target repository standards

## Additional Notes
Any additional context, considerations, or notes for reviewers.

---

_By submitting this PR, you acknowledge that your Passport account is linked to this GitHub handle for verification and payout eligibility._

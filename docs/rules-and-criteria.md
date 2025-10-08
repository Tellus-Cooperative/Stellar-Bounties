# Rules & Acceptance Criteria

## Scope & Governance

- Bounties are published as MDX files in the [`bounties/`](../bounties/) directory with validated front-matter
- Each bounty references tasks in target repositories within the Stellar ecosystem
- Maintainers for each target repository are the final approvers of submissions
- All bounty metadata must conform to the JSON Schema defined in [`config/schema.json`](../config/schema.json)

## Eligibility

- **Passport Account**: Must have a verified Passport account with GitHub OAuth linked
- **GitHub Account**: Active GitHub account with demonstrated contribution history
- **Compliance**: Must comply with payout requirements (KYC verification if requested)
- **Repository Access**: Must have access to fork and submit PRs to target repositories

## Submission Rules

1. **Fork and Branch**: Fork the target repository and create a feature branch
2. **Reference Bounty**: PR must reference the bounty issue: `Fixes #<bounty-issue-id>`
3. **Proof Block**: Include the required proof JSON block in PR body (generated via Passport app)
4. **One Bounty Per PR**: Limit to one bounty per PR unless explicitly bundled by maintainer
5. **Testing Steps**: Include clear reproduction and testing instructions
6. **Code Quality**: Follow target repository's coding standards and patterns

## Definition of Done (DoD)

### Technical Requirements
- [ ] Build passes CI/CD pipeline without errors
- [ ] Lint and style checks pass
- [ ] All existing tests continue to pass
- [ ] New functionality includes appropriate tests
- [ ] No regressions introduced

### Documentation Requirements
- [ ] Acceptance Criteria checklist in bounty is fully satisfied
- [ ] Documentation updated where applicable (README, changelog, comments)
- [ ] Code includes clear comments for complex logic
- [ ] Screenshots or logs provided for UI/SDK changes

### Review Requirements
- [ ] PR has been reviewed by at least one designated reviewer
- [ ] All review feedback has been addressed
- [ ] Maintainer approval obtained
- [ ] PR merged into target repository

## Review Process & Disputes

### Review Timeline
- **First Response**: Target 48-hour response time for initial review
- **Review Outcomes**: Approved (merge), Needs Changes, or Out of Scope
- **Final Arbiter**: Repository maintainers have final decision authority

### Dispute Resolution
- Disputes resolved by repository maintainers
- Decisions are final and binding
- Contributors may appeal through official channels if policy violations occur

## Payouts

### Process
1. **Merge Trigger**: After PR is merged, maintainers apply `payout-approved` label on bounty issue
2. **Payout Method**: Manual XLM payout to contributor's Passport wallet
3. **Timeline**: Q4 2025 manual processing, typically 3–7 days after merge
4. **Verification**: Payout requires verified Passport account and completed KYC if requested

### Partial Awards
- Partial awards may be made at maintainer discretion
- Label: `partial-award` applied to bounty issue
- Amount determined based on completed work and value delivered

## Code of Conduct & Licensing

### Licensing
- All contributions licensed under MIT (unless target repository dictates otherwise)
- Contributors retain copyright to their work
- Target repository licenses must be respected

### Code of Conduct
- Follow the Contributor Covenant
- Security reports via responsible disclosure channels
- Respectful and collaborative communication required
- Violations may result in disqualification from future bounties

## Bounty Models

### First-Come Model
- Single claim allowed
- First valid submission meeting criteria wins
- Auto-assignment on `/claim` comment

### Judged Model
- Multiple submissions allowed
- Best implementation selected by reviewers
- Judging period specified in bounty metadata

### Multi-Capped Model
- Multiple claims allowed up to specified limit
- Each valid submission receives full payout
- Useful for documentation or example improvements

### Custom Model
- Special rules defined in bounty description
- Maintainer discretion on acceptance criteria
- Used for complex or experimental bounties

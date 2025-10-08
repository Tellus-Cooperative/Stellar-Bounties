# Stellar Passport Bounties

![Stellar Ecosystem Passport Bounties Banner](assets/banner.png)

A GitHub-native bounties board for the Stellar ecosystem, operated by the **Tellus Cooperative Foundation**. Bounties are defined as MDX files with validated front-matter and ingested by the Passport app via GitHub API. **Passport** provides identity verification, anti-bot protections, and payout eligibility.

## Quick Start (Contributors)

1. Create a Passport account and connect GitHub OAuth
2. Browse open bounties in the [`bounties/`](bounties/) directory
3. Fork the target repository, create a branch, and implement the change
4. Open a PR against the target repository with `Fixes #<bounty-issue-id>` in the description
5. Include the required proof JSON block in your PR body (generated via Passport app)
6. Respond to review feedback. When merged, maintainers will label the bounty **payout-approved** and schedule XLM payout to your Passport wallet

## Maintainers (Summary)

- Create bounties by adding MDX files to the [`bounties/`](bounties/) directory
- Review incoming PRs in target repositories
- Approve by merging PRs and applying `payout-approved` label on bounty issues
- Use comment templates in [`docs/comment-templates.md`](docs/comment-templates.md) for consistency
- Manage allowlists in [`config/index.mdx`](config/index.mdx)

## Rules & Criteria

See [`docs/rules-and-criteria.md`](docs/rules-and-criteria.md) for complete governance framework.

## Code of Conduct

We follow the Contributor Covenant. Be respectful and collaborative.

## About Tellus Cooperative Foundation

The Tellus Cooperative Foundation operates this bounties program to support public goods development in the Stellar ecosystem. Our mission is to foster community-driven development while ensuring fair compensation for contributors.

Learn more about our mission, values, and impact in [`docs/about-tellus.md`](docs/about-tellus.md).

## License

MIT

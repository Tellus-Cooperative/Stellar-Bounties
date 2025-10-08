# Repository Allowlist Guidelines

## Overview

The repository allowlist ensures bounties are focused on public goods that benefit the Stellar ecosystem. Only repositories meeting specific criteria are eligible for bounty programs.

## Allowlist Criteria

### Primary Requirements

1. **Public Goods Focus**
   - Not primarily for-profit companies' core products
   - Repositories that serve the broader community
   - Open source with permissive licensing

2. **Stellar Ecosystem Relevance**
   - Directly related to Stellar/Soroban development
   - Used by Stellar applications and services
   - Contributes to Stellar protocol adoption

3. **Community Support**
   - Maintained by community or non-profit organizations
   - Used by companies but maintained as public goods
   - Active community contribution and maintenance

4. **Dependency Weight**
   - High usage across the Stellar ecosystem
   - Critical infrastructure for other projects
   - Significant developer adoption

5. **Maintenance Burden**
   - Historical issue volume indicates ongoing needs
   - Active maintenance and community support
   - Regular updates and security patches

### Examples of Eligible Repositories

**Core Infrastructure**
- `stellar/js-stellar-sdk` - JavaScript SDK
- `stellar/wallet-kit` - React components
- `stellar/soroban-examples` - Smart contract examples

**Developer Tools**
- `stellar/stellar-cli` - Command-line tools
- `stellar/soroban-tools` - Development utilities
- `stellar/horizon` - API server

**Documentation & Education**
- `stellar/docs` - Official documentation
- `stellar/developers` - Developer resources
- `stellar/tutorials` - Learning materials

### Examples of Ineligible Repositories

**For-Profit Core Products**
- Company-specific applications
- Proprietary business logic
- Commercial service implementations

**Personal Projects**
- Individual developer experiments
- Non-Stellar related projects
- Inactive or abandoned repositories

## Allowlist Management Process

### Adding Repositories

1. **Proposal**: Open an issue in this repository with:
   - Repository name and description
   - Justification for inclusion
   - Evidence of community usage
   - Maintainer contact information

2. **Review**: Maintainers evaluate against criteria:
   - Public goods alignment
   - Ecosystem relevance
   - Community support level
   - Maintenance sustainability

3. **Approval**: Approved repositories added to [`config/index.mdx`](../config/index.mdx)
4. **Notification**: Repository maintainers notified of eligibility

### Removing Repositories

Repositories may be removed from the allowlist if they:
- Become primarily for-profit
- Cease active maintenance
- Violate community guidelines
- No longer serve Stellar ecosystem needs

### Regular Review

The allowlist is reviewed quarterly to:
- Assess continued eligibility
- Add new qualifying repositories
- Remove inactive or ineligible projects
- Update maintainer information

## Weight Distribution

Bounty prize distribution considers:

1. **Ecosystem Impact** (40%)
   - How critical the repository is to Stellar
   - Number of dependent projects
   - Developer adoption metrics

2. **Maintenance Burden** (30%)
   - Historical issue volume
   - Maintenance complexity
   - Community support needs

3. **Community Support** (20%)
   - Existing funding (GitHub Sponsors, donations)
   - Community contribution levels
   - Maintainer availability

4. **Technical Complexity** (10%)
   - Codebase size and complexity
   - Required expertise level
   - Development time estimates

## Special Considerations

### Bridge Projects
Repositories that bridge Stellar with other ecosystems may receive higher weight if they:
- Enable significant cross-chain functionality
- Serve multiple blockchain communities
- Maintain Stellar compatibility

### Documentation Projects
Documentation repositories receive special consideration for:
- Educational value to new developers
- Ecosystem onboarding improvements
- Knowledge preservation and sharing

### Security-Critical Projects
Repositories handling security-sensitive functionality receive:
- Higher priority for security-related bounties
- Additional review requirements
- Enhanced testing requirements

## Contact & Appeals

- **Questions**: Open an issue in this repository
- **Appeals**: Contact Tellus Cooperative Foundation
- **Suggestions**: Use the repository's discussion forum
- **Program Inquiries**: bounties@telluscoop.org

The allowlist is maintained transparently to ensure fair access while focusing resources on the most impactful public goods for the Stellar ecosystem.

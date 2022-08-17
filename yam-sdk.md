# **Yam SDK**

**Description:** The Yam SDK will be one of the tools used by multiple parties and dapps, its purpose is to make developers interact with yam easier. Main use will be on the yam website for features and interactions with smart contracts, and generally for any party interested in yam read/write data.

**Plan:** SDK to include everything you need related to yam and yam smart contracts interactions as in read/write functions existent on the yam developped contracts, with further helper functions as well to wrappers related to yam projects. It will interact programmatically with off-chain and on-chain data, with different public and private APIs (data and price fetching), smart contracts and other tools we are building such as the Yam API and Subgraph.

1. **Development:** Development will include everything mentioned in the plan above, with documentation that will describe what functions relates to, with examples of use.
2. **Development Testing**: Developer testing will start, through manual and unit tests.
3. **Deployment:** SDK will be deployed and tested, with plans and preparations for automation.
4. **Automation:** Automation will include full automated testing as well to special auto release deployments checkpoints.
5. **Maintenance:** Development will go through updates and bug fixes with additional features support and changes that we see fit to make products better.

**Timeline:**
  - **Development**
  - **Development Testing**
  - **Deployment**
  - **Automation**
  - **Maintenance**

**Specifications:**
- Development
  - [ ] Base preparation
  - [ ] Structure preparation, includes: Contracts and ABIs implementation (for Token, Reserves, Governor, Timelock, Migrator, etc.)
  - [ ] Tokens implementation, includes: WETH WBTC USDT USDC yUSDC DAI
  - [ ] API integration endpoints includes: General, Treasury, Token value/avg, Yam apr
  - [ ] Package deployment and release
  - [ ] Yam Projects Wrappers preparation
  - [ ] Integration assist for website
- Post release
  - [ ] Development snippets examples
  - [ ] Development testing
  - [ ] Tests coverage
  - [ ] Documentation
- Future plans
  - [ ] Automated testing
  - [ ] Automated releases
  - [ ] Subgraph integration

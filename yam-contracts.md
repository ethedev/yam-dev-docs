# **Protocol Restructure: Contracts**
    
**Description:** The protocol had two migrations in the past as well for how its mechanism work, with then turning off the rebase, which plays a big part in the conversion of the numbers in the protocol, even though the core and governance has been maintained and secure to date, it was not very simple if you are a developer or an enthusiast to get yourself familiar with how everything work in accordance to each other, specially on a smart contract level and its little available documentation. That aside, everyone sees how many changes happened on defi in terms of scalability, in specific speaking about general layer 2 focuses and high gas prices on the ethereum mainnet, thats one of the things that can be dealt with. (**Read more on Yam Multichain [here](https://docs.google.com/document/d/1umm0Mf3FufHO7DDNBzCA5ELPl2FnCxsaHcFTnRaXLAI)**)

**Plan:** Reconstruct all existent, relevant and focus on creating new contracts, with what i have started working with **[here](https://github.com/ethedev/protocol)**. Contracts are undergoing major changes, while it will still essentially work to what we have currently related to governance. Major changes will include Governance upgrade, Token upgrade with delegation, Multichain implementation (to Optimism, Arbitrum and other chains), Protocol bridges (network specific), Treasury upgrade, Proxy modular functionality controlled by governance and a migrator. Audited and open source contracts libraries will be used, for example to Compound and OpenZeppelin, with more to be considered moving forward.

1. **Development:** Starting development, including everything mentioned in the plan above. Feedback will be asked from the community at some point to collect further ideas of interactions for potential adjustments.
2. **Development Testing:** Extensive developer testing will start, working on covering as much test cases as possible, everything related will be written in code for automated calls with documentation.
3. **Public Testing:** Deployment will be hosted on public networks with an accessible and documented flow for any yam token holder to test and give their feedback.
4. **Pre Implementation:** Audit and final adjustments with further testing, with snapshot proposals for specific selections (Multichain network selection, Network multisigs).
5. **Implementation:** Once everything looks great with the audit and public testing, deployment on mainnet will take place with further testing prior initiating migration.
6. **Pre Migration:** Actions vote before user migration. Granting new governance access.
7. **Migration:** Migrator will be unlocked. Migration announcement, and migration begins.
8. **Announcement:** Post detailed announcement.
9. **Maintenance:** Contracts are there to stay, we will maintain existent changes and focus on potential upgrades through proxy contracts as well to work on recurring governance proposals contracts.

**Timeline:**

1. **Development**
2. **Development Testing**
3. **Public Testing**
4. **Audit and Selections**
5. **Deployment**
6. **Previous to New gov access**
7. **Unlock Migrator, Migration Announcement, Migrate!**
8. **Announcement**
9. **Maintenance**

**Notes:**

- *Features remaining on the new deployment:*
  - Governance and voting token.
  - Token holders controlled treasury.

**Specifications:**
- [ ] Devtooling
- [ ] Token upgrade
- [ ] Governor upgrade
- [ ] Treasury upgrade (Gov safe controlled)
- [ ] Proxy implementation
- [ ] Multichain implementation
- [ ] Bridge implementation (Mainnet to specific chain)
- [ ] Security testing
- [ ] Security and bugs post
- [ ] Migrator implementation
- [ ] Migrating Users
- [ ] Migrating Treasury, Timelock
- [ ] Migration content for announcement
- [ ] Snapshot signals for selections (Network, Multisigs, Guardian choices)
- [ ] Tests coverage
- [ ] Documentation

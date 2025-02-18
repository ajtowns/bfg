---
title: Finalization
layout: default
nav_order: 6
---

# Finalization Phase

| Work : **Protocol Developers**, **Maintainers** |

Once everybody's on board with the proposal, then it is time for the
final steps:

 * Make sure the BIPs exist, are thorough and are clear
 * Make sure there are comprehensive public test vectors available
 * Open a PR for the changes to core, along with thorough tests
 * Make the code active on regtest and signet (via regular core, not just inquisition)
 * Have some test transactions (in signet or a regtest dump) using the
   new features that people can easily test non-core code against (other
   node implementations, libraries, wallets, etc)

![](img/finalize.jpg)

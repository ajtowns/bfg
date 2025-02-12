---
title: Roles
layout: default
parent: Introduction
nav_order: 1
---

# Roles

This guide categorises participants into the following roles:

 * Independent technical experts
   * **Researchers** -- Academic interest in Bitcoin related areas, and detailed
     high-level research, worst case analysis, etc.
   * **Protocol Developers** -- People who implement/review consensus logic.
   * **Power Users** -- People who have a practical interest in Bitcoin,
     and a high-level of willingness to experiment with new things in the Bitcoin
     space.
   * **Maintainers** -- People who maintain and release node software
     such as Bitcoin Core.
 * Bitcoin businesses
   * **Industry** -- People who build software and services that take advantage
     of and rely on Bitcoin. The technical/programmer side of Bitcoin businesses.
   * **Entrepreneurs** -- The risk-seeking side of Bitcoin businesses.
   * **Miners** -- People who participate in block-building and transaction
     ordering (particularly pool maintainers, hashrate controllers).
 * Oversight
   * **Investors** -- People who hold Bitcoin as a store of value, invest in Bitcoin
     businesses, etc.
   * **Auditors** -- People who audit Bitcoin's supply and ownership (the
     accounting/financial side; see "Protocol Developers" for the coding
     side).

These roles are not in any way exclusive; for example many Protocol
Developers will also be Researchers or part of Industry, many Miners
will also be Entrepreneurs to some degree, and many people who have
another role will also be Investors.

## Focus Summary

This guide expects each role will be focussed on particular phases, rather
than participating in a fork's development equally at every phase.

### Independent Technical Experts

For the independent technical expert roles, this is expected to look like:

 * Researchers: Primarily the [R&D](research) phase, but also monitoring
   the [Power User](power) and [Industry](industry) phases, and supporting
   [Investors](investor) in their evaluation.

 * Protocol Developers: Significant work in both developing a usable
   prototype in the [Power User](power) phase, and producing a high
   quality final implementation in the [Finalization](finalization)
   phase. Also watching of the [R&D](research) phase to see what's worth
   spending time on, as well as monitoring the [Industry](industry)
   phase in case updates to the prototype implementation are needed,
   and supporting [Investors](investor) in their evaluation.

 * Power Users: Mostly focussed on the [Power User](power) phase, but
   also monitoring any interesting advances during the
   [Industry](industry) phase, and supporting [Investors](investor)
   in their evaluation.

 * Maintainers: Mostly focussed on reviewing the high quality final
   implementation produced in the [Finalization](finalization) phase,
   and to a lesser extent ensuring [Activation](activation) also runs
   smoothly. May also check over the prototype developed for [Power Users](power),
   particularly as that may find and fix problems early.

### Bitcoin Businesses

For the Bitcoin business roles, it is expected to look like:

 * Industry: Unsurprisingly, focussed on the [Industry](industry) phase,
   and on reporting the findings from that phase during the
   [Investor](investor) phase.

 * Entrepreneurs: This guide focusses on minimising the risks of
   consensus changes, so has few suggestions on how to benefit from
   embracing risk. One approach that may make sense is in providing
   funding for independent technical researchers in the [R&D](research),
   [Power User](power) and [Industry](industry) phases to fully explore
   the potential of proposed changes. Historically, many Bitcoin
   businesses have been slow to adopt new consensus features, so early
   access to expertise in this manner in regards to new features may be
   able to be leveraged into a time to market advantage as well.

 * Miners: This guide only recommends miners focus on proposals at two stages,
   during the [Investor](investor) review phase, to ensure that any changes that
   may be problematic to their business are caught before being finalised, and
   then during the [Activation](activation) phase, in order to expedite deployment
   of a change.

### Oversight

Finally, for the oversight roles, this is expected to look like:

 * Investors: This guide assumes that the soft fork process should be optimised
   for investors, minimising the work they have to do, but maximising the influence
   they can exert. Hence, they are focussed on the single [Investor](investor) phase
   that acts as the key gateway for establishing social consensus.

 * Auditors: The accountants among us are expected to be involved in the
   [Investor](investor) phase, to ensure that proposed changes don't
   break their ability to do their job, and to quickly upgrade to new
   features during the [Activation](activation) phase to ensure that
   their audit results are still accurate when the new feature is deployed.

![](img/roles.jpg) |

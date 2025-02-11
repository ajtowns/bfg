---
title: Activation
layout: default
nav_order: 7
---

# Activation Phase

| Work : **Maintainers**, **Auditors**, **Miners** |

Once broad consensus has been established, the BIPs are written, the tests
are complete, and the code has been merged, it's time for activation. Provided
all the previous steps were taken, this can be the easiest part of the process.

There are two approaches that can be taken here:

 * Expedited activation
   * An expedited activation becomes active in a short timeframe, despite the
     risk of significant proportion of validating nodes not updating to support the
     new rules.
   * This is made safer by requiring near unanimous enforcement of the new rules by
     miners.
   * As such, expedited activations are triggered after 90% of hashpower
     signals activation readiness, and then occurs automatically after
     some pre-determined delay.
   * If there was not a true consensus for adoption of the change,
     this approach has a chance to detect that when miner signalling
     fails to achieve the 90% threshold.

 * Flag day activation
   * A flag day activation by contrast is simply scheduled to occur automatically
     at a time well in the future.
   * This time must be chosen to be sure that almost all node operators
     will have upgraded to new versions of their node software that
     enforce the new rules.
   * This does not rely on miner support or signalling.
   * If there was not a true consensus for adoption of the change, this approach
     does not provide a way to detect that failure until a chainsplit 

Provided the previous phases were all followed in good faith, both approaches are
likely to work without any problems. The approach recommended here is as follows:

 * Talk to miners, make sure they're not opposed
 * If they are opposed, evaluate their reasons:
   * If there is widespread opposition, determine why you mistakenly
     thought there was consensus for the proposed change, and return to
     earlier phases.
   * If the proposal is known to be distinctly bad for miners, but there
     is widespread consensus for it to be activated anyway, continue
     anyway, on the basis that a long-term benefit for Bitcoin is also
     a long-term benefit for miners.
 * Attempt an expedited activation with a high threshold (90% or 95%) and a short
   window (two or three months).
 * If expedited activation fails, and there is still widespread consensus that
   the change is desirable, do a flag day activation.

![](img/activate.jpg)

Election Process
----------------
As OpenSwitch matures, we envision the project eventually having elections for
various positions. In the early stages, as we grow the community from scratch,
these will be assigned. But we want a healthy community which is self
governing once it's established, so elections will be a part of this process.
The first priority is establishing the community itself. But a part of that
will be community involvement and input into the governance process itself,
including the elections.

The following positions are viewed as future elected positions in the OpenSwitch
governance model:

* OpenSwitch Project Leader
* Release Manager

When we move forward with elections, these positions will be decided by a
yearly election. Elections will be held using CIVS and a Condorcet algorithm
(Schulze/Beatpath/CSSD variant). Any tie will be broken using the tie breaking
described below.

To be eligible to vote in the election, you must have a patch which has merged
into an official OpenSwitch gerrit repository during the prior release period.
Email ballots will be sent out to those who fulfill this requirement.

Election Tie Breaking
---------------------
We use Condorcet voting system for all elected positions.

Condorcet may result in ties, which should be broken fairly and in a
reproducible manner. We will use the hash of a string describing the tie
results as a seed in a random generator to determine the tie winners, this way
anyone may verify the fairness of the tie break.

For more information, please see the OpenStack Election (TieBreaking_) wiki
page.

.. _TieBreaking: https://wiki.openstack.org/wiki/Governance/TieBreaking

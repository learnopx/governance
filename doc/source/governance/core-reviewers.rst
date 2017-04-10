OpenSwitch Core Reviewers
=========================

Projects in OpenSwitch are made up of many different forms of contributors.
One specific example is a core reviewer. A core reviewer has the ability to
merge code into the OpenSwitch project for which they are a member. Core
reviewers responsibilities are outlined below. In general, projects should
strive to have a healthy number of core reviewers to ensure code is merged
in a timely manner and the project is moving forward with decent feature
velocity. There are no hard numbers of how many core reviewers are required,
but as the core reviewers work closely together, experience in other projects
has led us to believe they usually top out at 12-15 or so per project before
requiring another layer in between the maintainer and core reviewers.

Code Merge Responsibilities
===========================

While everyone is encouraged to review changes for OpenSwitch repositories,
OpenSwitch core reviewers have the ability to +2/-2 and +A changes to these
repositories. This is an extra level of responsibility not to be taken
lightly. Correctly merging code requires not only understanding the code
itself, but also how the code affects things like documentation, testing,
and interactions with other projects. It also means you pay attention to
release milestones and understand if a patch you're merging is marked for
the release, especially critical during the feature freeze near a release.

The bottom line here is merging code is a responsibility for all OpenSwitch
core reviewers.

Adding or Removing Core Reviewers
---------------------------------

A new OpenSwitch core reviewer may be proposed at anytime on the openswitch-dev
mailing list. Typically, the existing core reviewer team for a project will
propose a new member after discussions with the existing core reviewers. Once
a proposal has been made, three existing OpenSwitch core reviewers must respond
to the email with a +1.  If the member is being added to a core reviewer team
with less than three members, a simple majority will be used to determine if
the vote is successful. Another OpenSwitch core reviewer can vote -1 to veto
the proposed new OpenSwitch core reviewer.

Removal of an OpenSwitch core reviewer can happen after consultation with the
existing core reviewers. Typically, if someone is no longer involved in working
on code in a specific repository, it is natural for that person to ask for
themselves to be removed. However, if the person has either lost contact
with the existing core reviewers, or the existing core reviewers determine the
person should no longer have core reviewer rights, either the OpenSwitch project
leader or the maintainer covering the repository in question can remove the
core reviewer by sending an email to the openswitch-dev mailing list indicating
the person's core reviewer rights are removed.

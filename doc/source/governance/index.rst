..
      Copyright (C) 2015 Hewlett-Packard Development Company, L.P.

      Licensed under the Apache License, Version 2.0 (the "License"); you may
      not use this file except in compliance with the License. You may obtain
      a copy of the License at

          http://www.apache.org/licenses/LICENSE-2.0

      Unless required by applicable law or agreed to in writing, software
      distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
      WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
      License for the specific language governing permissions and limitations
      under the License.

OpenSwitch Governance
=====================

OpenSwitch governance is structured as follows:

* Contributors are people participating in the project by doing any of the
  following tasks. Note this is not an exhaustive list of tasks, but is meant
  to show a broad example of the valuable contributions contributors take part
  in.

  * Submitting patches into the OpenSwitch repositories. This includes not only
    source code but also tests, documentation, and infrastructure.
  * Reviewing patches in the OpenSwitch repositories.
  * Participating in discussions on OpenSwitch mailing lists.
  * Updating and helping to maintain the OpenSwitch devref documentation.
  * Joining discussions on the OpenSwitch IRC channels on Freenode.
* Committers are responsible for reviewing and merging code into the OpenSwitch
  repositories. They review code from all contributors, including other
  core reviewers. Code can include source code, tests, documents, and
  infrastructure items.
* Maintainers are sub-team leaders for specific areas of OpenSwitch development.
  As an example, there is an infrastructure maintainer, a testing maintainer,
  a protocol maintainer, etc.
* The bug czar is responsible for triaging incoming bugs.
* The release manager is responsible for ensuring each OpenSwitch release is
  executed in a timely and efficient manner, with a low bug count and very high
  stability.
* The OpenSwitch Project Leader is the effective CEO of OpenSwitch and leads the
  overall project.

The following documents cover each of the above governance aspects of OpenSwitch
in detail.

Governance
----------
.. toctree::
   :maxdepth: 3

   contributor-onboarding
   contributor-licensing-agreements
   core-reviewers
   maintainers
   bug-czar
   release-management
   project-leader
   election-process

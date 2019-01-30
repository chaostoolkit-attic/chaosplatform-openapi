# Chaos Platform OpenAPI

This repository contains the [OpenAPI 3 specification][openapi] of the
[Chaos Platform][chaostoolkit].

[openapi]: https://www.openapis.org/
[chaostoolkit]: https://chaostoolkit.org/
[openchaos]: https://openchaos.io/

## Overview

This OpenAPI specification describes resources using a REST-style design
approach. The following resources are currently covered:

* experiment: Chaos Engineering Experiments as per the
  [Open Chaos Initiative][openchaos]
* execution: Chaos Engineering Experiment executions to support the Findings of
  Chaos Engineering workflow as per the [Open Chaos Initiative][openchaos]
* organization/workspace: A two-level hierarchy to organize and manage the
  visibility of your Chaos Engineering effort. The semantic behind organization
  and workspaces is non-prescriptive (e.g., they can mean team and projects for
  instance)
* user: An registered member of a Chaos Platform instance with capacity to
  perform operations
* scheduling: A Chaos Engineering Experiment schedule

In addition, the following definition is being elaborated:

* policy: to control the experiment execution context when scheduled (can
  represent a sign-off or a dynamic set of constraints of the system)

## Contribute

The Chaos Toolkit projects require all contributors must sign a
[Developer Certificate of Origin][dco] on each commit they would like to merge
into the master branch of the repository. Please, make sure you can abide by
the rules of the DCO before submitting a PR.

[dco]: https://github.com/probot/dco#how-it-works

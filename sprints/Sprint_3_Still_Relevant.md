---
title: Sprint 3 - Still Relevant
parent: Progress and Results
---
# Sprint 3 - Still Relevant
For this sprint, we spent some time to review our backlog and determine what tasks are still relevant given the community feedback and user research learnings we have gathered so far. From the engagement with our [public PR](https://github.com/bcgov/openshift-launchpad/pull/30) for [OpenShift Launchpad](https://github.com/bcgov/openshift-launchpad) we learned that:
- Many people are excited to see us working in the open and excited about the Launchpad idea
- A small number of people took the extra step of sharing their feedback on the PR
- Those participating in the PR were deeply engaged with our work and how it could benefit the community

Through collaboration with the [Common Services Showcase Team](https://bcgov.github.io/common-service-showcase/), we developed expanded [contribution guidelines](https://github.com/bcgov/openshift-launchpad/blob/master/CONTRIBUTING.md) for OpenShift Launchpad so that anyone is able to contribute.

At this point we have mapped the teams we've interviewed to date and which stage of the user journey they are at:

![Lab Team User Journey Current Stages](https://bcgov.github.io/common-components-wiki/media/user_research/User_Journey_Stages_2020_03_11.png)

We completed another user research interview, this time with the Wildfire Predictive Services (WPS) Team. From this, we identified that:
- Launchpad in its current state is something exciting, but most useful to teams at the very beginning of their user journey
- Deployment to OpenShift and creation of a CI/CD pipeline is an ongoing pain point during inception
- The WPS team are our potential first users of the deployment tools bundled with Launchpad

After identifying the WPS team as our first users, we took the opportunity to live up to the agile value of **responding to change over following a plan** and pivoted our sprint to spend some dedicated time collaborating on a solution that would work for both teams. The first step: split the [deployment tools of Launchpad into their own repository](https://github.com/bcgov/openshift-launchpad-deployment) so that the WPS team can consume them independently of other Launchpad features.

In this sprint we also headed back to the [betting table](https://bcgov.github.io/common-components-wiki/#how-we-work) with some newly shaped ideas. After sharing our research (and some fun designs we came up with during a 90 minute team competition), we came away with the following priorities:
1. Common Components Library - catalogue and community
1. Notify - assess the features and usability of the federal notify service
1. Launchpad - maintenance and enabling additional usage

## Sprint Goals
- Uptake: Get a team to start using [OpenShift Launchpad](https://github.com/bcgov/openshift-launchpad)
- Prototype what a library of common components might look like

## Sprint Review
Our sprint review slides are [shared here as a PDF](https://bcgov.github.io/common-components-wiki/media/sprint_slides/CoCo_Sprint_3-Still_Relevant.pdf). We host an open sprint review every two weeks that is available in the BC Exchange Lab events calendar. Please contact us if you would like an invitation!

## Next Sprint
In our next sprint we are continuing to support the WPS team with ongoing Launchpad work while shifting our main focus onto the following:

- Getting an initial version of the Common Components Catalogue deployed
- Choosing an appropriate style guide to follow for the catalogue
- Collecting our Launchpad learnings into actionable tickets & documentation
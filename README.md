# TiDev RFCs

This is the official home of RFCs related to the TiDev foundation and related projects.

An RFC is a technical specification that describes a problem and how it should be solved. A
committee will review the RFC and approve it. Once the RFC has been finalized, work may be
committed into the main project.

Any feature, architecture, or breaking change that is of substantial size or complexity must undergo
a technical review via an RFC.

The goal of creating an RFC is to solicit feedback and discussion. We all want to ensure that TiDev
projects are of the upmost quality.

## Contributor License Agreement (CLA)

All contributors must sign the TiDev CLA.

You do not need to sign a CLA to contribute to a RFC discussion.

## Submission Process

1. Fork the RFC repo: https://github.com/tidev/RFC
2. Create a branch for the new RFC
3. Copy the file `0000-template.md` to `doc/0000-<name>.md`
4. Fill out the RFC
5. Submit a pull request
6. Wait for the TiDev contributors to review the RFC

## Review Process

Each RFC must be reviewed by at least one active TiDev maintainer. Only a TiDev maintainer is
permitted to accpet or reject an RFC pull request.

Once a RFC has been submitted, the RFC will be eventually be reviewed. The reviewers may ask for
clarification or a proof of concept.

An RFC may be eventually rejected if the RFC lacks information or justification. Please understand
that it is the duty of the TiDev foundation to ensure the feature or change is warranted and
thoroughly designed.

Please note that TiDev contributors are voluteers, we cannot guarantee the RFC will be reviewed in
a timely manner.

## RFC Lifecycle

Each RFC begins as a "draft" while the pull request is open. During this time, the RFC is discussed
and refined.

After review, the RFC becomes "accpeted" or "rejected".

When "accepted", the PR is merged and a ticket is the related project is created with a link to the
RFC. The RFC gets updated with the corresponding project ticket link. The project issue can then be
assigned to someone for implemetation.

When "rejected", the PR is closed. It is possible for a rejected RFC to be reopened if there is
new activity.

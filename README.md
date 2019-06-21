> A journey of a thousand miles begins with a single step

# Umbraco RFCs

A request for contribution (RFC) is a detailed proposal for a significant change or new feature that will be reviewed and discussed by Umbraco HQ and community. 

Using an RFC process will:
* enable individual contributors to help make decisions.
* allow domain experts to have input in decisions.
* manage the risk of decisions made.
* have a snapshot of context for the future.
* facilitate the transparency of decision making by Umbraco HQ teams.

Most changes, including small features, bug fixes and documentation improvements can be implemented and reviewed via the normal GitHub pull request workflow. __Questions or discussions on more substantial changes should first be done on https://our.umbraco.com until further defined to the RFC format if one is deemed necessary.__

The "RFC" (request for contributions) process is intended to provide a consistent and controlled way for Umbraco HQ and community to collaborate on important decisions on the codebase.

As the name suggests, this is an invitation to contribute to the conversation with suggestions and ideas. Please read and respect the [RFC Code of Conduct](https://github.com/umbraco/rfcs/blob/master/CODE_OF_CONDUCT.md)

### [See Active RFCs](https://github.com/umbraco/rfcs/pulls)

## The Umbraco RFC process

This repository is intended to be used for reviewing submitted RFCs. 

### Reviewing

An RFC will be submitted in the form of a [Pull Request](https://github.com/umbraco/rfcs/pulls). Contribution to the conversation will be done via comments on the Pull Request itself while the PR is open.

### The RFC life-cycle

When an RFC is posted as a PR it is then open for contribution. At some point, a member of HQ will tag the RFC as having a final comment period which will generally be one or two weeks. An RFC may be accepted at the end of its final comment period and a team member will merge the RFCs associated pull request which will mean the RFC is 'active'. 

An RFC may be closed (not accepted) after public discussion has settled and comments have been made summarizing the rationale for being rejected. An RFCs associated PR is closed if this occurs. Other reasons an RFC may not be accepted is if it doesn't contain the appropriate information or if the RFC was submitted without previous discussion or HQ knowledge about it's intentions. In some cases once an RFC is closed, comments may be locked and if a follow up RFC is proposed, another PR will be submitted. 

When an RFC is accepted, then the process of implementing it may begin in the code repository. Being accepted does not imply anything about the priority of having it implemented and doesn't necessarily indicate that it's in active development.

Modifications to 'active' RFCs can be done in followup Pull Requests.

#### Instructions

* Fork this repository
* Copy {tempate-name} to /{product}/0000-my-feature.md (where 'my-feature' is descriptive) Don't assign an RFC number yet as this must match the number of the pull request that you will later submit. For example: /CMS/0000-dotnetCore.md
* Fill in the RFC. Put care into the details ensuring to provide information. RFCs that do not present convincing motivation, demonstrate understanding of the impact of the design, or are disingenuous about the drawbacks or alternatives tend to be poorly-received.
* Submit a pull request. As a pull request the RFC will receive design feedback from the larger community, and the author should be prepared to revise it in response.
* (optional) Now that you have submitted a pull request, you can now assign the RFC number in the filename and title. This must always match the PR number to make the PR easy to find after the RFC has been merged. It's OK to skip this as it can be done while the RFC is being merged.

## Credits

Umbraco's RFC process is inspired by the [React RFC process](https://github.com/reactjs/rfcs), [Rust RFC process](https://github.com/rust-lang/rfcs), [Wagtail RFC process](https://github.com/wagtail/rfcs) and [IETF RFC](https://www.ietf.org/standards/rfcs/) documents

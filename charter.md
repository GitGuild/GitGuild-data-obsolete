# Git Guild Charter

__0.0.4__

This charter is a private contract to cooperate on development of the project(s), which is hosted in the following git repository(ies).

 + https://github.com/gitguild/gitguild_whitepaper
 + https://github.com/gitguild/gitguild_website
 + https://github.com/gitguild/gitguild

By linking this charter from within the above project repositories, the contributors agree to abide by this charter. Each member must keep their respective branch up to date with the consensus master branch to participate in the project(s).

### Membership

Anyone can apply to collaborate on the project by creating a branch of this data repository, adding their gpg key to the members.csv file, and submitting the result as a PR.

The existing members then vote, and, if the approval threshold (66%) is reached, the PR is merged, accepting you as a member into the guild. Until your key is approved and merged into the keyring, you have no standing or rights to earn XP for contributions.

##### Experience Points (XP)

Experience Points (XP) are earned when a PR contribution is merged into the project. The amount and allocation of XP for each PR must receive the minimum approval threshold before merging.

### Voting

Voting "Yes" is done by merging and gpg signing a vote proposal. Voting "No" is done by merging and gpg signing a corresponding dissent branch. Votes are weighted by XP earned by the signer up to that point in the chain.

##### Vote Table

| Vote Type | Approval Threshold | Min. Vote Time | Max. Vote Time |
|-----------|--------------------|----------------|----------------|
| Amend Charter | 90%        | 1 day          | 6 months       |
| Change Treasury Sign Policy | 90%        | 1 day          | 6 months       |
| Accept member | 66%        | 1 minute          | 1 month       |
| Accept Contract | 66%        | 1 minute          | 3 months       |
| Accept PR | 51%        | 1 minute          | 3 months       |
| XGG Redemption | 51%        | 1 day          | 101 days       |

### Economics

XP are for reputation and voting. They cannot be transferred, and have no monetary value. Any other assets tracked in the ledger must be defined in a contract.

##### Sidechains

New assets can be imported by linking another Git Guild as a submodule. This must be defined in a contract, and no specific terms are required as of yet.

### Contracts and Signatures

By signing a commit with their GPG key, a member agrees to the charter, contracts, ledger, and member list contained. This is considered a binding vote. Any commits that violate the terms of this agreement are considered invalid, and not a permanent part of the master branch.

### Intellectual Property and Licenses

All intellectual property (IP) generated under the terms of this agreement will be the property of the Git Guild foundation, unless stated otherwise in a valid, member-voted contract. For all documents, like this one, a [CC by 4.0](https://creativecommons.org/licenses/by/4.0) license must be used. For all software, the [MIT license](http://opensource.org/licenses/MIT) should be used.

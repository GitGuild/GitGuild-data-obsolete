# GitGuild Charter

__0.0.2__

This charter is a private contract to cooperate on development of the project, which is hosted in the following git repository(ies).

 + https://github.com/gitguild/gitguild_whitepaper
 + https://github.com/gitguild/gitguild_website
 + https://github.com/gitguild/gitguild

By linking this charter from within the above project repositories, the contributors agree to abide by this charter. Each member must keep their respective branch up to date with the consensus master branch to participate in the projects.

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
| Accept PR | 51%        | 1 minute          | 3 months       |
| Accept Contract | 51%        | 1 minute          | 3 months       |
| XGG Redemption | 51%        | 3 months          | 12 months       |

### Economics

XP are for reputation and voting. They cannot be transferred. Though they have no monetary value, XP are earned 1:1 with XGG. The exception is 1 XP which is issued to the founding member(s).

XGG Guild Coins are claims against the Treasury. Any member may unilaterally transfer their XGG to another by submitting a signed entry to this ledger. XGG may only be redeemed with fees and vote approval, as specified by the charter. No promise of value or redemption is implied by XGG notations, only the right to propose redemption for other members to vote on.

##### Treasury

The Treasury for this guild will be controlled by a legal Git Guild Foundation that will follow the instructions and votes that are processed by this Proof of Labor chain. The guild has contracted a lawyer who has already registered the foundation and is writing the bylaws to match or upgrade this charter.

Until the Git Guild Foundation is ready to take control of the Treasury funds, members from the community should be voted in to perform key signing duties, with 90% approval required.

##### Revenue

At founding, this guild received only $1 from the legacy TGG Infrastructure fund. More may be distributed out of this Infrastructure fund, depending on charter update vote passing.

The legacy TGG Infrastructure fund transferred the Dash masternode at [Xh4GuTaGPZ9Rtjqm2ME1dY2g8toGhvWJdH](https://explorer.dash.org/address/Xh4GuTaGPZ9Rtjqm2ME1dY2g8toGhvWJdH) along with 1003.92 DASH. This sets a new XGG price of $1.14445 as of Sept. 8 2016.

This guild has no direct revenue streams. We suggest that any git guild support this, the intellectual parent guild with a portion of their revenue. Nothing big. One percent (1%) converted to [Dash](https://dash.org) and sent to the address above would be generous.

##### Contracts and Signatures

By signing a commit with their GPG key, a member agrees to the charter, contracts, ledger, and member list contained. This is considered a binding vote. Any commits that violate the terms of this agreement are considered invalid, and not a permanent part of the master branch.

##### Intellectual Property and Licenses

All intellectual property (IP) generated under the terms of this agreement will be the property of the Git Guild foundation, unless stated otherwise in a valid, member-voted contract. For all documents, like this one, a [CC by 4.0](https://creativecommons.org/licenses/by/4.0) license must be used. For all software, the [MIT license](http://opensource.org/licenses/MIT) should be used.

# Git Guild Charter

__0.1.0__

This charter is a private contract to cooperate on development of the project(s), which is hosted in the following git repository(ies).

 + https://github.com/gitguild/gitguild_whitepaper
 + https://github.com/gitguild/gitguild_website
 + https://github.com/gitguild/gitguild

By linking this charter from within the above project repositories, the contributors agree to abide by this charter. Each member must keep their respective branch up to date with the consensus master branch to participate in the project(s).

### Trusted Parties

Until the Git Guild software is more advanced, a few points of centralization are required for a Guild to operate effectively. These are: git server(s), pgp keyserver(s), and optionally some legal contract or jurisdiction.

| Trust Type | Name | Address |
|------------|------|---------|
| Git server | github | https://github.com |
| PGP server | MIT | https://pgp.mit.edu |

##### Vote Table

The following are minimum XP that each type of vote must receive to be considered valid by this guild.

| Vote Type     | Approval Threshold | Description |
| Fork          | 90%               | Any break of the git chain, i.e. a rebase     |
| Charter       | 90%               | Any change to the charter.md file.            |
| Sidechain     | 75%               | Add, remove or approve a charter ammendment for a sidechain. |
| Agreement     | 66%               | Accept or amend a guild-wide agreement.                |
| Ambassador    | 66%                | Accept a member as Ambassador of the guild.   |
| Member        | 51%               | Accept or reject a member. Also change a member's XP. |

##### Sidechains

This guild maintains a number of sidechains, and imports assets from those chains. Members of this guild do not need to join the sidechain guilds, but do agree to respect their ledgers and transactions through the Guild Exchange system.

### Contracts and Signatures

By signing a commit with their GPG key, a member agrees to the charter, contracts, ledger, and member list contained. This is considered a binding vote. Any commits that violate the terms of this agreement are considered invalid, and not a permanent part of the master branch.

### Intellectual Property and Licenses

All intellectual property (IP) generated under the terms of this agreement will be the property of the Git Guild foundation, unless stated otherwise in a valid, member-voted contract. For all documents, like this one, a [CC by 4.0](https://creativecommons.org/licenses/by/4.0) license must be used. For all software, the [MIT license](http://opensource.org/licenses/MIT) should be used.

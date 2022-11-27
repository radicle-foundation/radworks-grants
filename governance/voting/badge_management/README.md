# Badge Management 

If you are the member of a DAO's multi-sig and help manage governance and interested in badge management, this is the page for you.

> Note: for more context on badge-based governance, see the [OtterSpace Temperature Check here](https://radicle.community/t/temperature-check-use-otterspace-non-transferable-tokens-for-distribution-of-influence-mechanism/3055).

> Note: all the details below assume we are on the Optimism Network, which OtterSpace is using prior to moving to Ethereum Mainnet. 

## Overview 

![img.png](img.png)

Our high-level plan is to confer badges to each Org's contributors (however they are defined).

Some aims with this are:
* Push smaller decisions (e.g. Org level) from the Council down to the Orgs themselves 
* Distribute voting power amongst Org contributors
* Allow for one-person-one-vote governance participation
* Allow for intra-Org voting strategies to evolve without the limitations of a multi-sig

The important thing to keep in mind is: the process that one of our sub-DAOs creates can be largely replicated across others. It is very "copy/paste-able."

## Technical Notes 

### Initial Setup
* Make sure you have a wallet address on Optimism network (personal or Gnosis Safe).
* Get [Raft Token](https://docs.otterspace.xyz/your-guide-to-otterspace/how-communities-are-represented-within-otterspace) from OtterSpace team sent to that wallet address.
* When signing-in using Metamask, make sure it is set to the Optimism network.
* When signing-in using Gnosis Safe, make sure it is set to the Optimism network ([more docs](https://docs.otterspace.xyz/your-guide-to-otterspace/using-a-gnosis-safe-with-otterspace)).
* Make sure your sub-DAO has a community page. Ask the OtterSpace team for help with this.

### Minting / Conferring Badges
* Create N-number of badges for each of the contributor groups you'd like to define ([more docs](https://docs.otterspace.xyz/your-guide-to-otterspace/creating-a-new-badge-for-your-community)).
  * See [OtterSpace's Figma doc here](https://www.figma.com/community/file/1165222532286501657) for design templates.
* Add contributors' ENS or wallet address to the mint list so that they can claim their badge ([more docs](https://docs.otterspace.xyz/your-guide-to-otterspace/adding-members-to-the-mint-list-for-a-badge)).
* Share claim link to your contributors ([more docs](https://docs.otterspace.xyz/your-guide-to-otterspace/sharing-the-badge-claim-link-with-members)).

### OtterSpace x Radicle Grants x Snapshot Votes
* Create a Snapshot page for your sub-DAO on Optimism network ([Snapshot Docs](https://docs.snapshot.org/spaces/create)).
  * Radicle Grants: https://snapshot.org/#/radiclegrants.eth
* Go to _Settings_ -> _Strategie(s)_, and add a policy for OtterSpace badges ([OtterSpace docs](https://docs.otterspace.xyz/your-guide-to-otterspace/using-otterspace-badges-with-snapshot) / [Snapshot Docs](https://docs.snapshot.org/strategies/what-is-a-strategy)).

> Note: multiple strategies can be added to each Org, meaning not just Org badge holders can participate, but members of other Orgs can also be allowed to participate in another Org's votes. We can call this "intra-Org" voting.
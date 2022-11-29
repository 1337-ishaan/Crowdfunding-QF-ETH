# Problem statement

Create a dApp that implements the project matching and public funds distribution protocol.

## Why Quadratic Funding (QF)?

Existing systems for funding public goods through matching programs match individual contributions 1:1 or in some other ratio. To amplify small contributions, incentivise more contributions and greater diversity in potential donors. They aim to capture similar benefits in an unsystematic way.

QF mechanism provides a coherent structure that captures the central motivation of matching funds in a mechanism that is(approximately) optimal from the perspective of economic theory.

## Why a dApp?

Creating a dApp allows us to expand the qualities of QF to publicly funded projects over Web 3.

DAOs, especially those also functioning as business entities, often fail to implement and practice these checks and balances among the members with a larger token share. Consequently, many retain centralised or minority control, limit the breadth of decisions in which community members have a say, or suffer from uninformed and disorganised voting practices. Creating a QF dApp allows us to bring in mechanisms to amplify smaller contributions and increase the diversity of potential stakeholders making DAOs into more democratic structures.

# Features

- Project Owners can list their projects on the website from their GitHub. GitHub OAuth has been implemented in our application via which owners can list their projects and give information about their project to prevent scams.
- When listing the projects and contributing to a project, users need to go through a reCaptcha V2, to ensure bot-free listing.
- Compatible & Customizable across various chains.
- Contributors can filter projects from the list through filters like Project title and Project category.
- Each project is allocated its own description page from where contributors can learn about the project and the owner before contributing.
- Before contributing to a specific project, contributors need to go through an OTP based authentication to validate their contribution and reduce the risk of bot contributions.
- To prevent sybil attack contributors can at max contribute 5 times before their phone number gets dismissed.

> If this project goes in production, instead of OTP based authentication system, we are planning to introduce Aadhar API for user validation, as Aadhar API is not availabe for free we resorted to OTP based authentication system.

> The Sybil Attack is a type of attack seen in peer-to-peer networks in which a node in the network actively operates multiple identities at the same time, undermining authority/power in reputation systems. The main goal of this attack is to gain the majority of network influence in order to carry out illegal (in terms of network rules and laws) actions in the system.

- If a user wants to be a sponsor and donate funds to matching pool for public goods, they can contribute ethers in the sponsor page. We have set an lower limit of 5 ethers, for a user to be a sponsor.
- All the sponsor addresses are displayed on the sponsor page.
- Matching rounds states are displayed on each page, to notify the users whether a matching round is going on or not.
- Only the manager can initiate and distribute funds collected in the matching round, when a certain limit of amount is connected in the pool.
- Each project owner can withdraw the amount collected whenever they want to, through the withdraw button.

# Technologies, Libraries and Packages Used

1. ReactJS + Hooks
2. Ethereum
3. Solidity
4. Truffle
5. MetaMask
6. Ganache
7. Web3
8. jQuery
9. Firebase

# Team

1. Ishaan Parmar: Ishaan is a curious enough web3 developer who has contributed to Ethereum code.
2. Saloni Girhepuje: Saloni is a wizard designer, with a passion for improving web3 user experiences.

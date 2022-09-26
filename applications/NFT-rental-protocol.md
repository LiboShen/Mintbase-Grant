# Mintbase Grant Proposal

- **Project Name:** RentVerse
- **Team Name:** RentVerse Team
- **Payment Address:** libos.near
- **[Level](../README.md#level_slider-levels):** 2

## Project Overview :page_facing_up:

<!-- If this application is in response to an RFP, please indicate this on the first line of this section.

If this is an application for a follow-up grant (the continuation of an earlier, successful Mintbase grant), please provide name and/or pull request of said grant on the first line of this section. -->

This is a follow up project to improve and productionise our winning hackathon: https://devpost.com/software/nft-renting-platform

### Overview

Please provide the following:

- If the name of your project is not descriptive, a tag line (one sentence summary).
  - A Near NFT Rental service.
- A brief description of your project.
  - Our project is to continue building an easy-to-use tool for users to rent/hire utility NFTs (e.g. in-game assets, virtual passes). We would like to use this grant to support important features like creator's royalty, optimise the contract, improve the UX, and potentially integrate with real applications.
- An indication of how your project relates to / integrates into the Mintbase / NEAR ecosystem.
  - Existing projects can integrate rental functions using our service with only a few lines of code, and no change are needed in the NFT contracts (as long as they conforms the [NFT standard](https://nomicon.io/Standards/Tokens/NonFungibleToken/))
- An indication of why your team is interested in creating this project.
  - We believe that renting is an essential feature for a sustainable NFT market. It enables NFT owners to make more efficient use of their digital belongings and allows borrowers to experience the NFT in an inexpensive way. Rental service will also help develop more utilities for NFT and help to adopt more users to NFT and Metaverse.


### Project Details

We expect the teams to already have a solid idea about your project's expected final state. Therefore, we ask the teams to submit (where relevant):

- Mockups/designs of any UI components
<!-- TODO -->

- Data models / API specifications of the core functionality
<!-- TODO -->

- An overview of the technology stack to be used
  - Our smart contract will be developed in Rust, and our Web app will be built with React.
- Documentation of core components, protocols, architecture, etc. to be deployed
<!-- TODO -->
- PoC/MVP or other relevant prior work or research on the topic
  - Hackathon submission: https://devpost.com/software/nft-renting-platform
  - Demo vedio: https://vimeo.com/749514302
  - Testnet MVP app: https://rentverse.netlify.app/
- What your project is _not_ or will _not_ provide or implement
  - This is a place for you to manage expectations and to clarify any limitations that might not be obvious

Our rental service will use the NEP-199 standard to split the rental revenue among the lender and the creators. Therefor the creators in NEAR and Mintbase ecosystem can get extra revenues from the rental market.

### Ecosystem Fit

Help us locate your project in the Mintbase landscape and what problems it tries to solve by answering each of these questions:

- Where and how does your project fit into the ecosystem?
  - On one hand, our project allows users to experience NFT-enabled web3 experiences in an affordable way by remove the upfront capital barrier.
  - On the other hand, it allows the NFT owners and the developers/creators to extra revenue from their assets or work.
  - In genearl, our NFT rental solution can help boosting the NFT economy on Near.
- Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?
  - The developers and users of any dapps and games which utilise NFTs.
- What need(s) does your project meet?
  - For the utility NFT owners, we meet their needs for a safe and convenient way to earn revenue from their NFT assets.
  - For poeple who are interested in certain utility NFTs, we meet their needs for an affordable way to rent the NFT to experience.
  - For developers and creators, we meet their needs for exploring the renting revenue and business model.
- Are there any other projects similar to yours in the Mintbase / NEAR ecosystem?
  - If so, how is your project different?
    - PawnNFT: As the name suggested, it works like a pawn shop rather than, for example, a car rental service. It is a finance service where the NFTs are used as colleteral. 
  - If not, are there similar projects in related ecosystems?
    - https://double.one/: They requires the NFT contracts conform a special NFT standard they issued, i.e. don't support the standard ERC-721 NFTs.
    - ReNFT on Ethereum and Avalanche: Lenders in their platform have no way to trade their leasing assets until the lease expires.

## Team :busts_in_silhouette:

### Team members

- Name of team leader
  Libo Shen
- Names of team members
  Steven Yu

### Contact

- **Contact Name:** Libo Shen
- **Contact Email:** liboooshen@gmail.com
- **Website:**

### Legal Structure

- **Registered Address:** N/a
- **Registered Legal Entity:** N/a

### Team's experience

<!-- Please describe the team's relevant experience. If your project involves development work, we would appreciate it if you singled out a few interesting projects or contributions made by team members in the past. For research-related grants, references to past publications and projects in a related domain are helpful. -->

<!-- If anyone on your team has applied for a grant at the Mintbase previously, please list the name of the project and legal entity here. -->

- Libo Shen - Full-stack engineer, worked at Google London for 6 years, Head of Engineering of a startup.
- Steven Yu - Experienced Machine Learning Engineer with strong analytical and technical skills. Strong software engineering professional with a MSc Computer Science from University of Oxford.

We have participated and won the IRL hackathon in Nearcon 2022: https://devpost.com/software/nft-renting-platform.

In the past, we also worked on Solana build our NFT store: 
<!-- TODO: github link -->

### Team Code Repos

- https://github.com/LiboShen/nft-rental (To be moved to a org account)
- https://github.com/LiboShen/mooncake-nft

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- https://github.com/LiboShen
- https://github.com/stevenyu530

### Team LinkedIn Profiles (if available)

- https://www.linkedin.com/in/libo-shen/
- https://www.linkedin.com/in/tianlin-steven-yu/

## Development Status :open_book:

As mentioned above, we started this project during the 2022 NEARCON IRL Hackathon. The code currently locates at https://github.com/LiboShen/nft-rental. 


## Development Roadmap :nut_and_bolt:

**Note**: All of our milestones do not deliver any server side programs. We will continousely deploy our smart contracts to testnet and our frontend to hosting platforms (like Netlify). As such there is no need for Dockerfiles to test our deliverables.


### Overview

- **Total Estimated Duration:** 3 months
- **Full-Time Equivalent (FTE):**  2 FTE
- **Total Costs:** 45,000 USD

### Milestone 1 - Royalty

- **Estimated duration:** 1 month
- **FTE:**  2 (plus UX, editing and potential extra dev contractors)
- **Costs:** 15,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can lend and borrow NFTs and how the NFT creators will get their royalty split. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0e. | Article | We will publish an **article/document** that explains why NEAR dapp and games should integrate with our service to enable NFT rental (hint: royalty). |
| 1. | Gas Optimisation | Improves data structure and algorithms in the existing code to make all functions gas-efficient when there are significant number of renting items. |  
| 2. | Royalty | Develop the royalty payout mechanism respectin NEP-199 standard. With it, **the NFT creators can get a split of the rent revenue.** |  
| 3. | Integration tests | Develop integration tests to ensure the contract software quality and facilitate fast iteration |
| 4. | UX Improvements | Re-design the UX to match the expectation of the potential userbase. Various polishments of the UX. |


### Milestone 2 - FT Payment & SDK

- **Estimated duration:** 1 month
- **FTE:**  2 (plus UX, editing and potential extra dev contractors)
- **Costs:** 15,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** about how to use the SDK to integrate with our project. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0e. | Article | We will publish an **article/document** that explains why users should use our service to lend and borrow NFTs (hint: easy-to-use, affordable, and safe). |
| 1. | Support NEP-141 FT Payment | **The rental contract supports NEP-141 FTs as rent payment.** The web app allows users to choose popular FT as the rent currency. |  
| 2. | Owner's IOU NFT | An NFT will be issued to the lender when the lease starts. The NFT represents that ownership of the rented NFT and rent revenue. **It enables the owner to trade their assets while being rented.** |  
| 3. | JavaScript Integration SDK | A package to make dapp and web game developers easily integrate with our service. |
<!-- | 4. | Allow Early Lease Termination | If both the lender and the borrow agree, the NFT can be returned before the expire date with an agree percentage of rent refunded to the borrower. |   -->

### Milestone 3 - Marketplace

- **Estimated duration:** 1 month
- **FTE:**  2 (plus UX, editing and potential dev contractors)
- **Costs:** 15,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a lender can use the marketplace to list their NFTs and a borrower can take the offer. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0e. | Article | We will publish an **article** to introduce the our marketplace and shopfront for renting NFTs. |
| 1. | Marketplace contract | Develop a marketplace contract where NFT owners can list their assets as rental offers, and other users can choose to accept the offers to start renting.  |  
| 2. | Marketplace frontend | Build a web app to allow users to use the marketplace. |
| 3. | Marketplace Shopfront | Provide a solution to allow users setup customised market shopfront for certain NFTs to be listed. |
| 4. | Example game integration | Provide a simple open sourced web game to demostrate both how users can lend and borrow NFTs adn how developers can integrate with our service |


## Future Plans

Please include here

- how you intend to use, enhance, promote and support your project in the short term, and
  - If given the 
- the team's long-term plans and intentions in relation to it.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Mintbase Website / Medium / Twitter / Element / Announcement by another team / personal recommendation / etc.

Personal recommendation via Maria Magdalena

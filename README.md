Hi there 👋
I'm Parth. I am looking for full time roles in smart contract development/security. I am currently working as Junior Security Researcher(part time) at SpearbitDAO. Apart from this, I also do bug hunting on code4rena and immunefi.

# Achievements

* Got offer as an apprentice auditor from [SpearbitDAO](https://spearbit.com/). Spearbit connects independent security experts to the Web3 projects that need them.
* Got awarded 10000$ for securing AAVE contracts under [Certora formal verification program](https://discord.com/channels/814328279468474419/927065287172427798/1019940597353697281).
* Got 2nd rank out of 77 participants in Secureum [RACE-7](https://discord.com/channels/814328279468474419/927065287172427798/995142134082580601). Secureum is a community focused on improving the security of Ethereum. RACE — Readiness Assessment(quizzes) for CARE Endeavor. CARE — Comprehensive Audit Readiness Evaluation: Smart contract security reviews of real-world, security-minded protocols is held whenever protocols collaborate with Secureum. 16 participants are invited to participate in a CARE. More info [here](https://discord.com/channels/814328279468474419/928441092116975696/928520290047242292).
* Got 4th rank out of 60 participants in Secureum [RACE-8](https://discord.com/channels/814328279468474419/927065287172427798/1004355015646916709).
* Got 21st rank out of 93 participants in Secureum [RACE-10](https://discord.com/channels/814328279468474419/927065287172427798/1026417347965231114).
* Got 18th rank out of 106 participants in Secureum [RACE-11](https://discord.com/channels/814328279468474419/927065287172427798/1036822349510623334). This good score gave me chance to attend Scribble workshop by Consensys Diligence. See [Announcement here](https://twitter.com/0xRajeev/status/1583348269542801409).

# Work experience: 

#### Nethermind - Smart Contract Intern (June 2022 - Present)

* Working with Synnax/Gauss team which aims to improve the security of smart contracts.
* Responsible for doing the audits of various Solidity smart contracts along with team of other interns and auditors. Finding low severity bugs and also helping in gas optimization
and share my findings there
* Skills: Solidity, Smart Contracts, Auditing

#### TrakInvest - Full Stack Blockchain Developer (Jan 2022 - June 2022)

* Writing smart contracts on Ethereum blockchain using solidity and understanding ERC20 standards
* Hands-on experience using hardhat, metamask, remix, web3.js / ether.js
* Understanding of flash loans, Stablecoins and decentralized exchanges.
* Audited smart contracts to find vulnerabilities and gas optimizations.
* Tools and Languages: Solidity, Smart Contracts, Auditing, Truffle, web3.js, Metamask

#### Amazon - Software Development Engineer (Jan 2020 - Dec 2021)
* Built the Automated Defect Identifier services on top of mapping, pricing and crawling data for the Competitive Monitoring Team (CMT). This helped in increasing the percentage of root cause analysis(RCA) of products from 26% to 95% for the North American region.
* Enabled Defect Identifier services for all the marketplaces of Europe and the Far-east region. This involved the process of ingesting 12 TB of one-time data and automating daily ingestion of 3 TB of data to respective pipelines. This helped in increasing the percentage of RCA from 23% to 87% in those regions compared to what was done manually.
* Built SQL Query API which can work for different AWS databases which support SQL as a querying language.
* Tools and Languages: Java, Scala,  AWS(Athena, S3, SNS, SQS, Firehose, Data Pipelines, EMR)

# 📫 How to reach me

* Twitter - [Parth Patel](https://twitter.com/__parthpatel__) Follow me on twitter to know about what I am learning
* Gmail - [Parth Patel](mailto: parth4321patel@gmail.com)
* Discord - Parth#7949
* Linkedin - [Parth](https://www.linkedin.com/in/parth-patel11/)


# Projects I have built:

## Securing Aave protocol
* Written rules for this [file](https://github.com/MichaelMorami/aave-protocol-v2-AStETH/tree/feature/steth-on-prev-version) using certora verification language(CVL). These rules were part of [Formal verification of AAVE](https://governance.aave.com/t/continuous-formal-verification). 
* I have mainly worked on `feature/steth-on-prev-version` branch and written some rules. 
* My pull requests can be viewed [here](https://github.com/MichaelMorami/aave-protocol-v2-AStETH/pull/4) and [here](https://github.com/Certora/aave-token-v3/pull/2).
* Got awarded 10000$ for securing AAVE contracts under [Certora formal verification program](https://discord.com/channels/814328279468474419/927065287172427798/1019940597353697281). Also got listed as contributor in formal verification report published by [Certora](https://www.certora.com/wp-content/uploads/2022/09/Formal-Verification-Report-of-AAVE-Token-V3.pdf).
* Language: Solidity, Certora Verification language

## Crowdfund 
* A fundraising contract which provides ERC721 contributor badge NFTs to contributors that invest past a certain threshold. 
* A project owner can deploy a fundraising contract through the factory contract with set fundraising goals and timelines. 
* Investors are refunded their contributions if the fundraiser is unsuccessful or cancelled.
* Contracts: https://github.com/parth-15/solidity-portfolio/tree/main/crowdfund
* Audit report: https://github.com/parth-15/solidity-portfolio/blob/main/crowdfund/staff-audit-crowdfund.md

## ICO
* A multi-phase ERC20 token fundraiser which includes a whitelist-only private phase, a public general phase, and an open phase where tokens become claimable. 
* The token is designed with an optional transfer tax. 
* This project has been deployed to Rinkeby testnet, and also includes a custom barebones JS front-end.
* Contracts: https://github.com/parth-15/solidity-portfolio/tree/main/ico
* Audit report: https://github.com/parth-15/solidity-portfolio/blob/main/ico/staff-audit-ico.md

## DAO
* An ownerless DAO contract with the purpose of acquiring NFTs with treasury funds. 
* Members can submit proposals to purchase NFTs or execute arbitrary code. 
* Votes can be made either on-chain or off-chain through gasless signature. 
* No imports were used for this project. The spec was custom designed to incentivize behavior benefitting long-term success of the DAO.
* Contracts: https://github.com/parth-15/solidity-portfolio/tree/main/dao
* Audit report: https://github.com/parth-15/solidity-portfolio/blob/main/dao/staff-audit-dao.md

## Liquidity-pool(LP)
* A uniswap V2-style AMM core and router that allows liquidity provisioning and swaps through a constant curve formula. 
* The contracts take special care to handle a token with internal transfer tax without unexpected slippage. 
* The code is more readable than Uniswap's, and the core contract design prevents liquidity providers from unexpectedly donating additional funds to the pool if their provided liquidity ratio differs from the pool. 
* This project has been deployed to Rinkeby testnet, and also includes a custom barebones JS front-end.
* Contracts: https://github.com/parth-15/solidity-portfolio/tree/main/lp
* Audit report: https://github.com/parth-15/solidity-portfolio/blob/main/lp/staff-audit-lp.md

## Uniswap v1 clone
* Created clone of Uniswap v1 in Solidity.
* The code of the original protocol was written in Vyper.
* Contracts: https://github.com/parth-15/uniswap-v1-clone
* Language: Solidity

## Calorie Tracking App

* Created a role-based app with the role of User and Admin.
* Users can add the breakfast, lunch and dinner items they took along with calories.
* They can also view average calories per week and month.
* Admin gets data of all users and can perform CRUD  operation on users.
* https://github.com/parth-15/CalorieTrackingApp
* Technologies: React, NodeJS, HTML, CSS



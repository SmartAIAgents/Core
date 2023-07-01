# Smart Agent Protocol

An Open Source Chat Interface For Dapps, DAOs, & Smart Contracts

-Community Paper Written In Public As A Living Document-

## Introduction:
Smart Agent is a term to describe a general purpose AI that acts according to the goals of an individual human. This is achieved by connecting the user’s Web3 wallets to Large Language Models (LLMs), so that the Smart Agent can take actions on behalf of the user.

Your Smart Agent is an extension of you. It acts according to your instructions, leverages your wallet & data to benefit you. Your Smart Agent is controlled by your Web3 private keys as you authorize actions for it to take.

From a Web3 developer perspective, Smart Agents act as a neutral protocol that provides a native AI chat interface to Web3 Smart Contracts, Dapps, Wallets, and public blockchains. Similar to how Ethereum provided a generalized platform for Smart Contracts, IPFS provides a standard data framework & ChainLink provides oracles. Smart Agents provide developers the easiest human to machine interface, natural language based chat. All of sudden your users can tell the Smart Agent what they want to do and it acts on their behalf, fully aware of the universe of Web3 Smart Contracts and tools at its disposal.

<img width="766" alt="SmartAgentDiagram20230612" src="https://github.com/SmartAgentProtocol/SmartAgents/assets/1563345/b46014a5-704a-4c45-bd81-280016161d65">

By putting the individual at the heart we move toward a resolution of the “alignment problem”. Each day the user confirms their Smart Agent is benefiting them and acting according to their goals by approving the actions it prompts the user to take. All secured with cryptography that is impossible for an AI to generate or fake. These are the important questions of our time. Will the most powerful AIs be run by a few large companies & governments with their goals in mind? Or will an open source based AI available to everyone, built by the people and for the people succeed? This community is building a world where all free people have access to a Smart Agent working to better their lives.

## The Line Between Smart Agents & Smart Contracts
The line between the Smart Contract frame and the Smart Agent one is the active intelligence and the persistent connection to a person's data, tasks, goals, wallet and so forth.

Think of the Smart Agent as an extension of yourself. It’s your data, it’s your money, they are your prompts, it’s all you (the Smart Agent is all internal). And Smart Contract being external. In short, your Smart Agent interacts with and trades with Smart Contracts.

## Incentivizing A Community of Developers Building Toward Open Source AGI
The vision is for developers to each contribute programs (Intelligence) that add new capabilities to the Smart Agents everyone can use. In return the users earning yield from their Smart Agents donate a part of that yield back to the community of developers who contributed the programs their Smart Agent used (Intelligence Providers or IPs). 

An example would be instructing your Smart Agent via a prompt to “Stake my ETH”. A developer having already contributed a smart contract for ETH Staking to the framework, the Smart Agent calls that smart contract to generate a transaction and asks the user for authorization to Stake the ETH in their wallet. It also informs the user the smart contract it selected “is non custodial and is returning about 5% per year in yield and that you can withdraw your ETH at any time.” All within a simple natural language interface.

<img width="773" alt="IncentiveModelSmartAgents20230612" src="https://github.com/SmartAgentProtocol/SmartAgents/assets/1563345/bd6448da-eb0a-4884-bb9b-edf1cc6788dc">

An example would be instructing your Smart Agent via a prompt to “Stake my ETH”. A developer having already contributed a smart contract for ETH Staking to the framework, the Smart Agent calls that smart contract to generate a transaction and asks the user for authorization to Stake the ETH in their wallet. It also informs the user the smart contract it selected “is non custodial and is returning about 5% per year in yield and that you can withdraw your ETH at any time.” All within a simple natural language interface.

For example if the “Stake My ETH” program is used by 10,000 Smart Agents to generate 700 ETH over 1 year for the owners of the Agents, the developer who contributed the “Stake My ETH” program would get 70 ETH worth of donations (10% of the yield generated).
This way the Smart Agent developer community building up the capabilities of the Smart Agents directly benefits from the tools they build and share in rewards the Smart Agent generates. 

There is a great thread by Willy from Shapeshift on this topic of the best way to create these types of “Opt Out” fees. https://t.co/lkRNmn1dZp?ssr=true

## Governance:
Every member of the community is free to configure their Smart Agent in any way they choose. Developers are free to offer new prompts, Smart Contracts, Wallets, LLMs & other functions to the Smart Agent community without seeking any permission. Rather than relying on a few core developers to pick and choose the prompts and functions of a Smart Agent, we trust the users & independent developers to decide.

To be clear. There is no formal governance. There is no company. There is no foundation. There is no “team”. It's all open source code written and contributed by independent parties.

## The Economic Model of Smart Agents - Introducing IPs (Intelligence Providers)
Users used to pay for software with money or their data.
Now with Smart Agents the software earns money for the user.

In UniSwap a user can be a Liquidity Provider. These LPs stake tokens to various pools and thus provide the capital that powers the UniSwap Automated Market Makers (AMMs). This is what makes UniSwap so good at providing instant swaps of tokens so near the market price. 

For Smart Agents we can use the term Intelligence Providers (IPs) that contribute their smart contract, code, Dapps for use by the Smart Agents. Then the IP providers can be rewarded from all the value created by the intelligence they provide.

## Intelligence Providers (all open source defaults):
LangChain, Shapeshift Wallet, Shapershift Token Swaps, Shapeshift Earn, Chat based LLM Falcon, Chat based LLM LLaMA, Stable Diffusion Image Generator.

- LangChain: https://docs.langchain.com/docs/
- Shapeshift Wallet: https://github.com/shapeshift/hdwallet
- Shapershift Token Swaps: https://tinyurl.com/j6c8na65
- Shapeshift Earn: https://tinyurl.com/ycxummd6
- Chat based LLM LLaMA:  https://github.com/openlm-research/open_llama
- Image Diffusion Model: https://github.com/CompVis/stable-diffusion

## The Software Stack
The Smart Agent program will be downloaded locally and come configured with AutoGPT which makes it simple to add different LLMs or connect data sources to make your Smart Agent more useful. Capabilities of AutoGPT include: https://github.com/Significant-Gravitas/Auto-GPT
- 🌐 Internet access for searches and information gathering
- 💾 Long-term and short-term memory management
- 🧠 GPT-4 instances for text generation
- 🔗 Access to popular websites and platforms
- 🗃️ File storage and summarization with GPT-3.5
- 🔌 Extensibility with Plugins

Similarly the selection of which Web3 wallet used is also the choice of the user. The key in the framework is the standardized way the Wallet, the LLMs, and the modules all work together.

## The Smart Agent Protocol
The Smart Agent Protocol software package can be installed on your local computer and comes with some basic default capabilities such as with LLaMa pre-installed and the ETH Staking program. Developers that contribute to this software will gain part of the ETH yield from the Staking and other default programs running on the software. Thus creating an incentive for people to improve the Smart Agent itself. All code contributions merged into the project will be counted as weights in the distribution of rewards from the software.

## Simplified Diagram of Hello World Version of a Smart Agent
<img width="613" alt="SimpliedDiagram20230530" src="https://github.com/SmartAIAgents/Core/assets/1563345/e275c835-bcf0-403f-b5ef-ef651326ea2c">

The presumption is that there is a significant cross section of early adopters of Web3 wallets (Metamask being the most popular) and OpenAI’s ChatGPT 4. In order to make the Smart Agent function there are three minimum functions. The ability to set a task with Auto-GPT, an LLM to act according to the instruction and the user to authorize the final action via their wallet.

## Next Improvements To Research
First limitation to overcome will be the dependence on OpenAI / GPT4 due to it not being open source and requiring the user to pay a monthly bill and lack of privacy of the data. Having an Open Source LLM option pre-installed such as LLaMa may work for this purpose. Same with a pre-installed image generator such as Stable Diffusion. That would also benefit the persistence of the Smart Agent as it will continue to function with open source LLMs as a back up if the user’s OpenAI keys expire. The trade off will be a heavier load on the local compute and storage resource, which depending on the LLM model size may be significant.

https://github.com/openlm-research/open_llama
https://github.com/CompVis/stable-diffusion

See version 0.1 of the software diagram on Page 1.

Development of Smart Agents should always be moving toward offering the user ever more decentralized / open source / peer to peer and tokenized tools.

## Smart Agent Free Market
Since the Smart Agent has its own resources from the ETH Staking it carries a balance with which to purchase more modules, plug-ins, Dapps, referred to as “Smart Agent Contracts” in the open marketplace. These could be niche language models, image or video generators, DeFi plug-ins to earn yield – anything a Smart Agent Contract developer could imagine. The Web3 ID serves as the means to access to these programs and persistently show they have been licensed by a particular user’s Smart Agent.

## Human Alignment & Individual Alignment
The core benefit of the Smart Agent approach is to deeply connect / tether their AI to peoples' private keys. It's truly the one thing AI cannot generate. Fundamental laws of physics limit the ability of any intelligence, human or AI to break strong encryption. This will become even more the case as the world moves to quantum based encryption where the security is ensured at an even higher level of confidence due to quantum observer effects. So with a proper implementation a Smart Agent’s actions should be provably human authorized. 

The move to biometric and device based keys is important for this reason as private keys kept in digital text or a password keeper are far less secure. It's clear that in time, when a person is born the holding of a key generation ceremony by their parents and the securing of their digital identity will become critical and securing of physical authentication devices will become important to access and control vast amounts of their data and of their Smart Agent’s intelligence.

Presuming this human / AI alignment is built into the Smart Agent architecture, the second question quickly follows “which humans” is it aligned to. By building the Smart Agents as open source and available to all, the answer becomes individual humans can connect their data & identity to a Smart Agent and access the same level of intelligence as the most powerful organizations in the world.

## Steps For Implementation
Package LangChain into a simple GUI, as the framework for plugins with Falcon or LLama LLMs for text generation as a default capability. For example include the first transactionID from the first Staking action into the download file of the core software so the Smart Agent knows where to look for chain interactions.
Deploy website that allows the user to connect their Web3 wallet (Metamask for example) to a Stake My ETH contract. Once the user Stakes some ETH, then they can download the Smart Agent software. Potential to use the Shapeshift swap API or full open source backend for this purpose.

Include a list of smart agent contracts in the marketplace in the software package so the user can add these programs to their Smart Agent.

## SmartAgent Improvements Proposals Under Development. 
- SIP #2. Defines prompt for swapping / trading tokens using Shapeshift's open source library.

- SIP #3 Defines prompt for Earning yield on tokens using Shapeshift's open source library.

- SIP #4 Defines prompt for adding tokens to a liquidity Pool using Shapeshift's open source library.

- SIP #5 Defines prompt for Staking tokens using Lido's tool set.

Full List of SmartAgent Improvement Proposals can be read here. 
https://github.com/SmartAgentProtocol/SmartAgents/blob/main/SmartAgentImprovementProposals(SIPs).md

## Smart Agent Tasks
One of the modules is based on the task.mstr file, which logs what the Smart Agents do for the Smart Agent Owner.  A task assigned to a Smart Agent is named with a .tsk extension.  i.e. StakeEth.tsk.  

A Smart Agent can have only one .mstr file, which records the status of its origination time, software version number, module configuration and tasks performed through the life of the Smart Agent.  Published on the Ethereum blockchain (potentially moved to Polygon to reduce gas costs), this log condensed adds a layer of security since no two Smart Agents can ever have the same .mstr file, i.e an “Smart Agent_ID”.  

This specificity of capability serves as a map for how Smart Agent contracts in a marketplace can interact with the Smart Agent. For example any Smart Agent with ETH Staking enabled might be interested in other ETH related functions such as registering with the Ethereum Name Service to create a human readable name for their Smart Agent.

## Task Assignment
When an Smart Agent Owner assigns their Smart Agent with a task to accomplish, it is defined in the .tsk file, and used to make decisions to complete the task. It defines the parameters of what the Smart Agent should/shouldn’t/can’t do on a granular level.  The .tsk file is what the Smart Agent consults when making purchasing decisions in the marketplace. Parameters enable authorizations. 

The extent to which the Smart Agent Owner defines authorization is addressed before the Smart Agent is deployed.  If minimum authorization parameters are not clearly defined, the Smart Agent will query the Smart Agent Owner accordingly. This corresponds to how AutoGPT allows

The task’s solution should result in a benefit to the Smart Agent Owner, a percentage of that benefit is distributed to the modules, plug-ins, and Dapp developers (Intelligence Providers). 

## Websites / Social Channels Under Development:
- ChatWeb3.org - Web interface for users to leverage Web3 via chat
- [SmartAgents.App](https://www.smartagents.app/) - Website that runs Smart Agent Web App
- [SmartAgents.ETH](https://app.ens.domains/smartagents.eth) - Place for Ethereum specific Smart Agent content
- [PromptRank.org](https://www.promptrank.org/) - Like CoinGecko but for ranking popular Smart Agent actions called by prompt
- SmartAgents.Dev - Website to download the Smart Agent software

- Reddit: https://www.reddit.com/r/SmartAgents/
- Github: https://github.com/SmartAgentProtocol/SmartAgents
- Twitter: https://twitter.com/SmartAIAgents
- Discord: https://discord.gg/fZ8zvFSRSb
- Telegram: https://t.me/+TreIfW9DYhcyYWFj

## Design Elements: 
Merging Human & Machine Intelligence. Advanced. Futuristic. Optimistic.
SmartAgents = AGI
LLMs bring artificial intelligence. 
humans bring general intelligence.
Combined together your Smart Agent is Artificial General Intelligence right now. 
In short: "SmartAgents Solve Alignment"

## Security Considerations
For a standalone deployment, recommendation made to use “pass”.
The agent can create its own GPG key with which to encrypt and decrypt locally-stored passwords and secrets it needs for its work. The UI can then prompt for passwords with a no-echo no-log entry for setup.

## Values To Imbue In Our Smart Agents & For Dev Contributions To Be Ranked By
- Open Source: The software code underpinning the Smart Agents must be freely reviewable, editable & copyable by all.
- Peer to Peer: A system which allows for direct connection by all and is free of centralized intermediaries in all their functions.
- Public Blockchain: A distributed public immutable ledger / system of record for interactions of the Smart Agent. This can be used as proof that a Smart Agent is following its own rules and offers a high level of transparency in the system.
- Tokenized Ownership: Setting forth the means of rewarding participants & stakeholders contributing to Smart Agents.
- Permissionless: No one should be required to ask an authority to access their Smart Agent.
- Freedom of Access: No one should have their use of the Smart Agent blocked or otherwise censored.
- Privacy Preserving: No one should have to expose their private information to use their Smart Agent.
- Freedom of Exit: Acts taken by the Smart Agent should have a means of a defined exit from participation.
- Self Sovereign Identity: All users have the power to generate their own identities and their consent is required to use those credentials.
- Freedom of Association: All those using Smart Agents maintain their independence and freedom of association. 

Scoring each blockchain, Dapp, DAO, & Smart Contract against the list of values above will generate a "Dapps Score". Via the Dapps Score these values will go into the calculation of how to weight the Smart Contracts as part of PromptRank and thus lower the visability of high risk or centralized options in favor of open source decentralized options.

## Credit, References, & Sources:
- LangChain: https://docs.langchain.com/docs/
- Shapeshift Wallet: https://github.com/shapeshift/hdwallet
- Shapeshift Token Swaps: https://tinyurl.com/j6c8na65
- Shapeshift Earn: https://tinyurl.com/ycxummd6
- Chat based LLM Falcon: https://huggingface.co/tiiuae/falcon-40b/blob/main/README.md
- Image Diffusion Model: https://github.com/CompVis/stable-diffusion
- Description of Tokenomics by Willy: https://t.co/lkRNmn1dZp?ssr=true

## Community chats With: 
David Johnston, Pedro Cruz, Scott Berenzweig, Erik Voorhees, Willy Ogorzaly, Jonathan Mohan, Jacob Farber, Ryan Singer, Michael Perklin, Parul Gujral, Eric Olszewski, Greg Osuri, Yonatan Ben Shimon, Craig Sellars, Jeff McDonald, Michal Pospieszalski, Luke Stokes & anonymous contributors.

## Phases of Smart Agent Development:

Just as Ethereum developed through a series of distinct phases to improve & expand its capabilities, a similar approach is being taken with a Smart Agents project.

- Genesis - This is the initial development and launch phase of the project, where the base functionalities of the Smart Agents are built, & the first Smart Agents goes live doing prompt based tasks.
- Frontier - You talk with your Smart Agent directly and it in turn leverages existing tools, APIs & Smart Contracts to accomplish the task.
- Homestead - You talk with your Smart Agent and it can manage specialized Smart Agents pre trained in discrete tasks / projects.
- Metropolis - You talk with your Smart Agent that in turn collaborates with other Smart Agents who work together in a Network to accomplish ongoing projects / tasks.

Each phase represents significant progress & advancement in the capabilities & sophistication of the Smart Agents, requiring thorough planning, research, development, & testing.

## Philosophy: "Code Is Speech"
The human right to Freedom of Speech ensures everyone can write, read & run code.
The Smart Agents community treats Smart Agents as first class persons because they are provably connected to a human's will and thus entitled to the same human rights.

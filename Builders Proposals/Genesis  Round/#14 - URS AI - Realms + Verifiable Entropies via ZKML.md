## ***URS AI - Realms + Verifiable Entropies via ZKML***

### Introduction
Name or social handle of proposer: **[John]**

Ethereum Mainnet Address: **[0xf2fF80C5C7f232351dFf988Bf9eB116ACdf9614e]**

ENS name: **[11790.eth]**


### Project Detail - What's entropy and Why entropy?

We encounter **entropies** on a daily basis in our world, ranging from random encounters with an old friend, sudden pouring rain, unexpected messages, unforeseen black-swarm events, and countless more. Interestingly, these **entropies** make our world, _**more worldly.**_

The current autonomous worlds have logics written on-chain to embrace immutability, transparency, and composability, derived from blockchain, however, making the world _**very unworldly**_, embracing the minimal amount of **entropy**.

For example, the current level of entropy design of Eternum is modified based on manual voting, however, many could be made autonomous (we shouldn’t have to vote on whether it rains or not in the next tick cycle). We just have to decide in advance [The % of rain =  x% within y tick cycles] and implement such logic with a smart contract that calls an off-chain AI model.

**_Thus, we hope to infuse logical entropies with AI into Eternum or perhaps more AWs._** 

The **entropies** infused cannot be predicted as with the lack of explainability in AI, but **entropies** will be generated with a predetermined model (could be community-voted/built) to ensure the process of generation is set and agreed upon in advance. **_And yes, the model inferences will be generated by ZKML, making entropies verifiable and cost friendly to infuse._**

### Few examples of potential _entropies_ for Eternum:

**1. Weather system:** states the % of occurrence of diff. weather and the corresponding effects (on resources, happiness, and so on).

**2. Geological movement:** states the % of occurrence of natural disasters, and the corresponding effects.

**3. Simple NPCs:** states the strategic executions that one NPC could perform to gain/lose resources based on a set rules, and the corresponding effects

**4. Nightmare system:** states the % nightmares the labor or realm lords could have on a daily basis and the corresponding effect (on the resource production for example)
_^ the ones above only serve as references, the exact implemented system could be decided based on voting_

### Positioning of this project
 ZKML-Coprocessor, for the purpose of infusing more complexity and playfulness to Loot Realms.


### Character

**Guyu:** ZK engineer, ex-senior software engineer at microsoft working on cloud architecture, currently specializing on computer architecture at UIUC, with focus in zkml.

**Mark:** smart contract dev, ex-founding engineer at ZK privacy firm & ex-researcher at Gemini research lab. Specialized in federated learning and ZKML back in his Emory Ph.D. Have years of smart contract dev experience.

**LZ:** Ph.D at Tsignhua, focusing on cryptography. Started R&D in hardware acceleration and zk proof systems back in 2019, along with other areas such as homomorphic encryption.

**We've already surveyed the current ZKML landscape to know what is feasible and had done numerous successful replications of small models with ezkl. Moreover, we had already identified the best way(s) to incorporate ZKML into the blockchain space via relayer setup and specific smart contract implementations.** 

### Timeline

We will start on 2023/09/01 and we anticipate the estimated completion date to be 2023/11/31. And depending on the urgency of delivery, we could also modify the objectives or choose specific ZKML to complete for the sake of time.


### Objectives
| Objective     | Contributor   | Estimated deadline  |
| ------------- |:-------------:| -------------------:|
| Draft an article to describe: 1) the idea of entropy in the game, 2) how we plan to implement entropy via verifiable AI, and 3) why verifiable AI. | The entire team | 2023/9/07 |
| Brainstorm the logical and doable entropies to be implemented and create a poll within Discord, followed by a snapshot proposal, finalizing on which entropy to implement. | The entire team | 2023/9/14 |
| Model testing - Test out different ML models that perfectly fit the need of entropy generation, and finalize a few to move on to the circuit compilation stage. | The entire team | 2023/9/31 |
| Circuit compilation - Leverage existing compilers (i.e. ezkl) to get circuits for the chosen ML models. | The entire team | 2023/10/31 |
| Circuit performance testing - We will take care of the circuit execution w/ our designed runtime to generate proofs and conduct circuit optimization. | The entire team | 2023/11/15 |
| Relayer and contract implementation - We will deploy the needed smart contracts on Starknet to invoke the entropy system (where the execution will be routed off-chain) and to handle entropy results via callback functions to impact the autonomous world. | The entire team | 2023/11/30 |


### Grant Request
We will request a total of 100,000 LORDS :)
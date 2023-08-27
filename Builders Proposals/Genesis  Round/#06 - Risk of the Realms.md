# Frontinus House Builder Proposal

## Cheelax - Risk of the Realms

![Risk of the Realms](https://github.com/BibliothecaDAO/Frontinus-House-Docs/assets/18716884/9bc63334-76a3-4564-b6f7-66f52bca0178)

**Introduction**

Name or social handle of proposer: Cheelax

Ethereum Mainnet Address: 0xc57B65B26CBA8169F10295D8152deF3e0Bc8864e

Twitter handle : [https://twitter.com/Cheelax_](<https://twitter.com/Cheelax_>) feel free to dm !

## Project detail

### Abstract
This paper explores an open source project to bring a multiplayer turn-based adaptation of Risk to Starknet's blockchain ecosystem. Titled "Risk of the Realms", the game will be set in the fantasy world of Realms. By utilizing Starknet and Dojo game engine, the project aims to establish open source gaming standards and best practices for the Starknet community. The goal is to provide an engaging gaming experience with transparent rules, while positioning the team as specialists able to assist future Realms and StarkNet gaming projects.

### Introduction
Blockchain technology presents new opportunities in gaming. Starknet's Layer 2 architecture offers ideal speed and affordability for multiplayer games. This paper outlines an open source project to develop one of the first turn-based blockchain titles on Starknet and Dojo - a Risk adaptation called "Risk of the Realms" set in the fantasy Realms universe.

By innovatively adapting an iconic game in this manner, we hope to highlight blockchain gaming benefits, energize a community of players, and define open source development standards. Our solution guarantees fair rules and randomness via blockchain properties. We aim to showcase our expertise in Starknet gaming as an ongoing resource for the ecosystem.

### Core Gameplay
Risk is a turn-based strategy game where 2-6 players aim to conquer all territories on a map.  Each player will have a defined time to play his turn. This parameter will be set at the beginning of the game. On each turn, players can:

- Draft new armies based on controlled territories
- Attack adjacent enemy territories to attempt capture
- Move armies between owned territories

Combat outcomes are decided by dice rolls. The goal is to eliminate all opponents by occupying every territory. Key gameplay elements involve strategic reinforcements, effective dice roll battles, and diplomatic negotiations.

For diplomatic negociations, we will implement a bot in Realm or the project’s discord. Users will bind their wallet to their discord user. On game start, a new channel will be created with read/write access for players of the game only.

The first version will implement the classic Risk experience but we may implement some variants or a Realm specific set of rules.

### Technical architecture 
To implement Risk on Starknet, we plan to utilize the following key components:

- **Smart Contracts** - The core game logic and rules will be coded as Cairo contracts running on Starknet and integrated with the Dojo game engine framework. Dojo is a community driven open-source Provable Game Engine, providing a comprehensive toolkit for building verifiable games and autonomous worlds. Dojo's ECS model will help quickly build the game logic and gameplay elements.
- **User Interface** - We will build a frontend UI using React and Phaser.js to provide an intuitive user experience. Players can interact with the contracts through the UI.

Our aim is to create a reliable and scalable architecture that delivers seamless blockchain gameplay, similar to what is build with Eternum. With experience building other projects on Starknet and Dojo, the team is well-equipped to execute on this ambitious vision.
![image](https://github.com/Calcutatator/Frontinus-House-Docs/assets/18716884/08a59bfb-2c48-4b53-8130-e16488a289d8)

### **Integrating with Realms**
The team entered the Realms ecosystem a few months ago by investing in Realm NFTs. We properly introduced ourselves by winning the play2Die bounty from Realm during the Pragma hackathon. In this period, we had the pleasure of meeting very talented and inspired people and working with individuals like Loaf on examples. Meeting inspiring people like Secretive, Calc, and Amaro in person at events like StarkNetCC Paris reinforced our commitment to supporting Realms and decided us to be even more dedicated to the Realms ecosystem and build around it.


As part of the vibrant Realms ecosystem, Risk of the Realms aims to:

- **Map** - Generate a playable map based on Realm Atlas
here is a first draft of a map we can play with: 
![carte](https://github.com/BibliothecaDAO/Frontinus-House-Docs/assets/18716884/4b8727cf-dd5e-4dd4-a8e7-f8c6cdfb6fe5)

- **Theme** - Collaborate with Realms creators to integrate narrative elements like factions, heroes, events. Bring the fantasy setting to life.
- **Economics** - Players can wager $LORDS tokens and winners earn a share. NFT holders earn revenue share when their assets are used in gameplay.
    - The game's revenue will be distributed as follows:
        - The top three players receive the largest portions of the $LORDS.
        - A small portion goes to the project's team.
        - Holders of the map NFTs also receive a small share depending on the number of troops on the territory during the game
        
        The repartition of the income is not yet determined, we will engage with the community to ensure everyone is satisfied with the model.

![image](https://github.com/Calcutatator/Frontinus-House-Docs/assets/18716884/9b77c53b-19c8-46c5-bec0-3b30c2f74476)

By seamlessly integrating with the Realms universe in terms of narrative, aesthetics, and tokenomics, we believe Risk of the Realms can become an exciting new experience for the community while upholding the spirit of the original game.

### **Development Roadmap**

We plan to develop Risk of the Realms in stages:

#### **Alpha**

- Game lobby for creating/joining matches
- Core game logic implemented
- Bidding system for wagers
- Design of the board (Realm altas based)

#### **V1**

- ELO ranking system
- Player leaderboards

#### **Future Goals**

- Realm narrative events/quests
- League tournaments and prizes
- 3D generated map

This staged approach allows us to focus on robust core gameplay first, then expand with more advanced features. We'll incorporate community feedback regularly to drive development priorities.

### **Conclusion**

In summary, this project aims to bring Risk gameplay to Starknet in an innovative form with ties to the Realms ecosystem. It has the potential to provide transparent, engaging multiplayer experiences through blockchain integration.

By pioneering best practices and collaborating with Realms, Risk of the Realms can help advance the adoption of blockchain in gaming. It demonstrates how traditional titles can be updated through emerging technology while empowering players and creators.

This initiative presents promising opportunities to leverage Starknet's strengths for competitive matches and pursue creative integrations with Realms. However, as early blockchain adopters we recognize there will be challenges and obstacles to overcome. We are committed to tackling these issues in order to fully realize the potential of this project.

Overall, we see strong potential in adapting an iconic board game to showcase the possibilities of blockchain technology and Starknet’s advantages. We welcome you to follow our journey as we bridge the classic world of Risk with the next era of gaming.

## Character

The initial team is:

**Bal7hazar:** 

https://twitter.com/bal7hazar

Balthazar is a smart contract developer at Carbonable and has been with the company for over a year after leaving a very famous french brand he worked for 7 years. He was on the wining team of the Dojo bounty implementing a MineSweaper using Dojo framework.

**Matthias:**

https://twitter.com/ProvableMat

Having spent over five years as a software architect at a robotics startup, Matthias played a key role in building retail robots for top brands in Europe and Asia. Now, after transitioning into the web3 space for the past 2 years, he serves as the CTO of Monopole, a cross-chain startup studio for impactful projects. He's at the forefront of building the studio's tech infrastructure and guiding mentored projects through their development journey.

**Cheelax:**

https://twitter.com/Cheelax_

With over 7 years of experience as a software developer, Cheelax has had the privilege of working with renowned French companies such as Paris Airports, SNCF (the national French railway company), and Total. He is leaving the web 2 world to enter the web 3 full time after having contribute to big Starknet projects such as the cairo book or the Dojo framework. He was in the team with Bal7hazar for the Minesweaper.

<h3>Timeline</h3>
<p>As it is a long term project, we provided in the objectives some milestones that seem relevant to us.</p>
<h3>Objectives</h3>


Objective | Contributor | Estimated deadline
-- | -- | --
Game design documentation (Published) | Team | 09/15/23
Basic game mechanics  (POC) | Team | 11/15/23
MVP version | Team | 01/01/24
Lobby system (POC) |   |  
Game economics implementation (POC) | Team | 02/01/24
Alpha version | Team | 03/01/24


<p>Each part represent a smart contract and its related frontend, we will organise a live demo for each milestone (when relevant).</p>
<h3>Grant Request</h3>
<p>100000 $LORDS</p>


## Art tests
![image](https://github.com/Calcutatator/Frontinus-House-Docs/assets/18716884/4166dd10-8414-47ef-b8ee-6635e48cfebb)
![image](https://github.com/BibliothecaDAO/Frontinus-House-Docs/assets/18716884/227dd54b-9dd8-4629-aff0-d411bb1986b0)

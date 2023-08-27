# Frontinus House Builder Proposal
A standard of how a Frontinus House Builder Proposal should be submitted. Please follow each Proposal to Frontinus house in a similar fashion. Amendments are required in sections highlighted boldly. Please submit your proposal as an issue within this [repository](https://github.com/Calcutatator/Frontinus-House-Docs/issues).

## ***BLADEDAO GAMES - Loot Royale***

### Introduction
Name of proposer: **[BladeDAO]**

Ethereum Mainnet Address: **[0x43fC86aAaaD9984708348031108b6722F87AC244]**

Twitter handle (optional): **[@Blade_DAO]**

Any relevant links/Websites (optional): **[BladeDAO GitHub](https://github.com/BladeDaoGames/loop-royale)**

### Project Detail
**Please give a detail of what you wish to build. Please give an overview of the project and its nuances. This is where you wish to give detail about why this project should be chosen for a grant. A few possible points to use**

-  **What is the name of the project**: Loot Royale
-  **What is it based upon (If the are any examples of similar projects):** Loot royale is a fast-paced battle royale game with heavy loot NFT references. Users can summon game characters using their loot NFTs through on-chain ML and decentralized storage. We will abstract realm NFT’s map into a pixelated board (think Catan Island with a battle royale twist) and use a random algorithm to determine the shrinking zone in each round of battle royale. The zone shrinking is then further Players will explore the realm's map while participating in the “winners-take-all” battle, earning $LORDS reward from other players.

Sources: [Fantasy map generator](https://github.com/mewo2/terrain) Realm’s text to image also sourced this part of the code)
https://github.com/mewo2/terrain

![Loot Royale](https://github.com/Calcutatator/Frontinus-House-Docs/assets/133518284/1362cfc1-19d0-4799-92e5-64f61506b98c)
![Loot Royale 2](https://github.com/Calcutatator/Frontinus-House-Docs/assets/133518284/8be26331-8627-4a6a-8ba6-d3886c9e19aa)
![Loot Royale 3](https://github.com/Calcutatator/Frontinus-House-Docs/assets/133518284/65ccc45f-14f2-4988-953f-4e6b596c4148)


**Role of $LORDS in the game:**
- $LORDS can be staked as prize pot of the game, winner takes all 
- $LORDS can be used to craft various in-game items with a restriction on the carry amount
- Potentially, $LORDS can also be used for future transactions sequencing in a bidding format

**Game Mechanics Breakdown:**

- **Number of Players and Duration:** A round consists of 3-6 players with a maximum duration of [x] minutes and [x] seconds ([x] seconds).

- **Circle Closing:** Players take action [x] times or after [x] blocks, the circle shrinks. This happens every [x] blocks.

- **Victory Conditions** (in descending order to determine winner):

  - **Last Person Standing:** The game is automatically won by the last remaining player (others are ranked in descending order).

  - **Fighting Power (FP):** If more than or equal to 2 players survive after 400 seconds, players on the field are ranked from highest to lowest FP. The player with the highest FP receives the reward.

  - **Kill Count:** If the FP is the same, the number of kills is calculated. Players with a higher kill count rank higher.

  - **Items:** If the kill count is also the same, it's checked whether any player has consumed more than or equal to 1 item (buff).

  - **Tie Situations:** If none of the 4 conditions are met, the players share the rewards equally.

- **Participation and Rewards:**

  - **Entry Requirement:** Players participate using tokens they obtained from the faucet. At the start of each round, they stake an equivalent number of tokens.

  - **Room Creation:** The creator of the room can set the stake amount rule (no upper limit).

  - **Victory Reward:** The winning player(s) take all the staked tokens.

- **Items:**

  - **Spawn Logic:**

    - **At the Beginning:** The number of items spawned equals the count of players who entered the room. The type of item spawned has an equal random percentage. The location of the spawn is random.

    - **Per Closing Circle:** New items spawned equals the current count of players that are still alive.

  - **Buff:** Increases or decreases attack power by a range of (-50, 50). Consuming it will either increase or decrease the Fighting Power. The value is random and is based on block hashes. Later, it will be based on automata or ARPA.

  - **Poison Pill / Resurrection Pill (50% chance for each):**

    - **Condition:** Only when picked up, it is determined whether it's a poison pill or a resurrection pill.

    - **Poison Pill:** Upon picking up, the player dies instantly.

    - **Resurrection Pill:** Upon picking up, the player gains a second life. If they die, they will resurrect in their original grid with an initial FP (Fighting Power) of 100.

  - **Bomb:** Upon consuming, it immediately deals 100 damage to an area around the player. Within the 4x4 range, it creates an attack of 100/(X+100). It won't cause damage to the player themselves.

**Player Instruction:**

- **Movement:** Players move one grid per block. When two players converge on the same grid, a battle occurs.

- **Battle Outcome:** The result of each battle is determined by a probability function dependent on the players' respective fighting powers. 
  - *Example:* If player A has a fighting power of 200 and player B has 250, the chances of winning are calculated as 200/(200+250) for player A, and 250/(200+250) for player B.

- **Game Board Buffs:** The game board contains various buffs that players can utilize to potentially impact their battle outcomes.

- **Participation:** To participate, players are required to stake [x] amount of $LORDS. 

- **Endgame:** The game continues until only one player remains on the board, who then claims all the stakes.

**Generating your loot character:**

We use Bacalhaus’s compute + Lilypad’s on-chain scripts to bring on-chain ML and AI art to instant NFT deployment.

**Example:**

- (masterpiece, top quality, best quality), pixel, pixel art, pixlelated RPG character, full body, full human face, standing position, 1 male, mace, demon husk, necklace of titans, platinum ring of the twins
  ![447671692956692_ pic](https://github.com/Calcutatator/Frontinus-House-Docs/assets/133518284/be0fd5eb-7c85-41e1-b052-fa2b2d7e6f13)
- pixel, pixel art, pixlelated RPG character with mace, demon husk, "demon bite" sash of power, heavy boots of brilliance, wool gloves, necklace of titans, platinum ring of the twins

![447681692956762_ pic](https://github.com/Calcutatator/Frontinus-House-Docs/assets/133518284/e87feb8d-6181-4752-bcd2-ccc9e610efbb)


**Design Details:**

- Run smart contracts and render maps using cairoVM’s off chain smart contract compute (inspired by shoshin)
- Using cairo-wasm to run web client with verifiable transactions
- Katana local node to test the game and map generation
- Veedo library for random number generation
- Dojo’s framework provides efficient data storage and event-callbacks for optimised transaction representations of game play. Nature of hero-idle-brawler most suited for Dojo’s ECS data frameworks.


**What does this do that is unique or different to other projects:** 
- On-chain generated maps based on realms NFT
- Bringing utlity to loot NFTs such as Genesis Adventurers and Loot Bags
- Community driven design of in-game items that changes the style of the game drastically
- Meta game in the form of betting that gets defi users speculate on game results


**Who is the target audience of this project:** Loot NFT holders, Realms NFT, Lords token holders & the starknet on-chain game players

**What about this project excites you to build:** A fully on-chain, verifiable and transparent integration game that allows players to battle with game theory

**Any further details you might want to elaborate on:** Only those with the realm NFT can initiate a game. The game map is generated from the player's NFT and abstracted into a pixelated board.

### Character
BladeDAO is a fully on-chain game studio with a diverse team from backgrounds like game economist, defi degen, smart contract dev, crypto media and zkp research. The team has a strong belief in crafting digital realities and autonomous worlds. The co-founders are Brawler and Zee, with 0xhatsume as the CTO.
Brawler: Co-founder of BladeDAO, indie game addict, repeat founder, advisor to crypto game studios. Previously built a crypto media company in 2019-2021 that had 180,000 subscribers with a heavy focus on DeFi, L1/L2s, crypto games and metaverses.
Zee: Co-founder of BladeDAO, game economics connoisseur, sometimes dev 
0xHastume: Anon dev, ex-data scientist. Loves strategy games, board games

### Timeline
**Please give an approximate start and end date of your project. If it's a rolling term just detail as such.**

| Objective | Estimated Deadline |
|-----------|--------------------|
| Turn the black & white SVG loot realm map into pixelated yet colorful boards for it to fit into the framework of Dojo using [fantasy map generator](https://github.com/mewo2/terrain), then test integration locally with Katana local client and Torii indexer. | 10 September 2023 |
| Design an interactive user interface and functions for automatic characters generation for Genesis Adventurer, using bacalhau-deployed stable diffusion art. | 10 September 2023 |
| Rewrite existing game logic typescript / solidity code in the [rollup-royale github repo](https://github.com/BladeDaoGames/rollup-royale) in cairo with potential typescript SDK, version managed by Sozo. | 30 September 2023 |
| Setup data structures and Torii indexer under the dojo on-chain game engine, setup randomized value generation function using VeeDo. [Reference](https://medium.com/starkware/tagged/random-number-generator) | 30 September 2023 |
| Allow users to stake $LORDS and distribute the stakings to winners | 7 October 2023 |
| Deploy smart contracts on starknet goerli and test the game, receive feedback from community | 15 October 2023 |
| Open sourcing the game repo for users to build customized in-game items, game rules and player hosted games | 30 October 2023 |
        
### Grant Request
The team is requesting a grant of 100,000 LORDS at an estimation of 720 hours of work taken (10 working hours / day, 60-75 days)

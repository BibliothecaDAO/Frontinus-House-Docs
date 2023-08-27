[![image](https://user-images.githubusercontent.com/102239225/262834081-9d41c43c-cefc-4622-8fa9-e1aaedde3463.png)](https://user-images.githubusercontent.com/102239225/262834081-9d41c43c-cefc-4622-8fa9-e1aaedde3463.png)

# Frontinus House Builder Proposal

## On-Chain Call the Banners: Game

### Introduction  
Proposed by the Knights of Ser Anthony (KoSA) the stewards of the Banners Project and creators of Call the Banners.

eth:0x775DC4AB56Fec6Da6c79bb21EDf78CfE38d17c17  
[@bannersNFT](https://github.com/bannersNFT)  
Bannersnft.com

### TL;DR:

Banners, the social layer of the Lootverse, introduced a social engagement game called Call the Banners (CtB). The game, which has successfully run for four seasons, is now evolving from a Discord-based game to an on-chain version, CtBOC, within the Realms Autonomous World ecosystem. This transition aims to attract a global audience and foster innovation by providing an open-source, modular design that allows community developers to refine features and create new game modes.

The game will be hosted on StarkNet and will consist of three phases: Staging, Battle, and End. The Staging Phase involves strategic team formation, the Battle Phase includes attack and defence strategies along with treasure hunting, and the End Phase rewards players and allows for the introduction of new narratives.

The technical architecture will be similar to Loot Survivor, with game logic housed in contracts built using Dojo and Cairo and deployed on StarkNet. A web interface for UI/UX will be created using Next.JS and deployed on Vercel, with wallet-based player authentication and login. The development will focus on creating a v1 first, then building on top of it for a v2, incorporating features from the off-chain version of the game. The next season, CtB5, is planned for the end of September, and work is underway to transition the game to CtBOC.

[![image](https://user-images.githubusercontent.com/102239225/262834152-216a0ea5-ac8a-4470-86b2-55fe8f8b1eba.png)](https://user-images.githubusercontent.com/102239225/262834152-216a0ea5-ac8a-4470-86b2-55fe8f8b1eba.png)

### A Brief History of Call the Banners

Banners is a society, politics and identity layer for the Lootverse founded in October of 2021, intended to define everyone in the Lootverse who was not an Adventurer. Shortly thereafter, we began working on narrative projects including our social engagement game, Call the Banners.

The game thrives on its simplicity. There are two castles, two generals and a host of soldiers employing attack and defence commands. When the battle commences, intrigue ensues for along with each general’s pledged armies, many of players start the battle as sellswords. Generals command their armies and vie to sway those sellswords, or free-lancers, to their side with promises of glory, impassioned speeches, memes, vibes and should those not work, the promise of coin.

The “coin” in the game is a valueless currency used to buy attack buffs, sway soldiers to your cause, bet within duels and ultimately, purchase raffle tickets for the prize draw at the end of the game. To date we have run 4 seasons and given away: our titular Banner NFTs, a Realms NFT, and a Genesis Adventurer, as well as a sub100k Ordinal.

The game has seen resounding success. Many who participate in the Call the Banners event come back to play the next season. Some notable communities who have participated with select members representing as Generals are, 1337 Skulls, Loot Explorers, as well as nearly 10k lifetime participants. 1337Skulls even built a tongue-in-cheek Attack North (only) command in their discord to pay homage to their win in Season 4 as the Souther Castle.

[![image](https://user-images.githubusercontent.com/102239225/262834196-c3499ec3-d7b2-40ae-adff-66874c6403ae.png)](https://user-images.githubusercontent.com/102239225/262834196-c3499ec3-d7b2-40ae-adff-66874c6403ae.png)

The game has a few core beliefs and north stars:

1.  It is low-to-no stakes. Call the Banners is currently free and should remain inexpensive to participate in. The prizes are gated behind a randomly drawn raffle meaning there is little incentive to play to earn.*
    
2.  The game is meant to be conversational and engaging. With only two common targets the players eventually find their way to either side and form relationships, leading to players following each other on social media and recruiting others to join the “Larpy” fun game.
    
3.  The game aims to inspire stories. Everything that happens in the game is a narrative hook for a greater story. , There has been a wealth of tales that have come out of Call the Banners so far. Even our namesake, the Knights of Ser Anthony came from the game. It’s improv comedy for fantasy storytelling.
    
4.  The game is episodic. Like the majors in golf or tennis, Call the Banners happens several times a year. It is not meant to be perpetually in play. We’ve found that we get the most engagement when there are several months between seasons.
    

Since the early development stages on CtB4, we’ve had the idea of building CtB Onchain (CtBOC) and have been adjusting our code so that the inevitable switch would be much easier. We’re nearly ready with the code for CtB5 and plan to run that game in our discord, while work begins on CtBOC. The target date for CtB5 is the end of September.

*Early in CtB3 we anticipated the usage of bots to sway the odds of winning the raffle in one's favour and have implemented server restrictions to counteract their efforts.

### Project Detail: Technical

The "Call the Banners" journey has always been one of evolution. From its humble beginnings as a narrative-rich Discord-based game to its impending on-chain metamorphosis, CtBOC promises a blend of recognizable features and cherished traditions along with ground-breaking enhancements. Here's a deep dive into what this transformation holds:

Migrating from Discord to StarkNet within the Realms Autonomous World ecosystem marks a seismic shift. However, the essence remains the same: cultivating CtB into an enthralling, enduring social ritual. Beyond the confines of the Loot community, the allure will now beckon a global audience. The blueprint for this was laid with the Community vs. Community model in CtB4, establishing the framework for monumental showdowns like Realms vs. Influence in the envisioned CtB7.
  
CtBOC will be designed with a modular, open-source spirit. The intent is clear: empower community developers to innovate. Whether it's refining features, crafting stellar UI/UX experiences, or devising fresh game modes, the architecture is permissionless, fostering a hotbed of innovation and collaboration.  

This also means that a key aspect of how CtBOC is different is that once we lay down the groundwork in terms of the contracts + a web UI to interact with them in an accessible manner, the number of times it happens depends entirely on community interest and it can happen as often as folks sign up for it and get it started.  

The CtBOC game loop consists of three key phases:

[![image](https://user-images.githubusercontent.com/102239225/262834238-dc0b5b87-9d56-46a5-978d-8c13395974bc.png)](https://user-images.githubusercontent.com/102239225/262834238-dc0b5b87-9d56-46a5-978d-8c13395974bc.png)

### Staging Phase:  

Choices rule this phase. Players can either rally their allies to form formidable factions or plunge into the unknown, getting randomized placements in either Attacking or Defending Armies. Strategy reigns supreme here. The entry fee, denominated in $LORDS tokens, not only deepens immersion but also bolsters the CtB and Realms ecosystems. With a keen eye on game design, there's a conscious effort to strike a balance, ensuring the avoidance of the "pay-to-win" quagmire.  

### Battle Phase:  

As soon as the ranks swell on both sides, battle cries fill the air. The battle mechanics mirror those of the original – bring your opponent’s HP down to nil. But there's more to it now. Players juggle between accumulating points and devising attack and defence strategies. Taking a leaf from CtB4, players can now fend off attacks, synchronise assaults, and even delve into the art of battlefield looting, uncovering coin, attack buffs/debuffs, or even stumble across hidden enemies. This isn’t solely about warfare; it's a treasure hunt reminiscent of classic video games. Amid the clashing swords, the quest for valuable artefacts or a stash of $LORDS tokens adds another layer of intrigue, benefiting both CtB and the overarching Realms ecosystem.

[![image](https://user-images.githubusercontent.com/102239225/262834307-1f575f25-189a-4c15-bd9a-a978edbc2243.png)](https://user-images.githubusercontent.com/102239225/262834307-1f575f25-189a-4c15-bd9a-a978edbc2243.png)

### Existing CtB Commands:  

#### Battle Commands  

!attack: strike a castle dealing between x → y damage  
!sharpen: buff your next attack boosting your attack to x+n → y+n  
!parry: attempt to offset a recent attack made by an enemy  
!arrowslits: take up a defensive position within your castle and fend off attackers  
!aim: load ⅕ ballista  
!fire: after five (5) “!aim” commands, launch a unified attack on enemy castle, can only be performed by a General  
!trebuchet: attack castle by manning this heavy damage attack with a 24 hour cooldown

#### Banner Commands  

!callbanner: equip a banner you own to use its bonuses in battle  
!showbannerinfo: reveal the stats for a given banner  
!flybanner: select a banner from your holdings to represent you on the leaderboards

#### Side Quest Commands  

!duel: wager coins and battle any contender who will match your ante, winner takes all  
!loot: input a time duration to leave the fighting to others and go scour the battlefield for treasure  
!pay: give coins to other players

#### User Commands  

!stats: full list of players ranked based on the total strikes dealt  
!bal: show player's balance  
!rank: show player’s role  
!merit: display the money list leaderboard  
!honor: display the damage leaderboard  
!glory: display the dueling leaderboard

#### Raffle Commands  

!shop: buy items with your coins  
!ticket: show all your available entries into the raffle

#### General Only Commands  

!rally: automatically sharpen the swords targeting the enemy castle for a set amount of timeby spending 75 coins per attacker  
!bounty: automatically pays out attackers targeting a specified castle  
!fortify: spend coin to buff your castle’s health before the battle begins

**Implementation Plan**: We will de-risk by implementing features of the battle phase as instalments with v1 focusing on the core feature set needed to provide a complete experience, creating a version that captures Season 1 of the CtB discord game and then build on top going forward once v1 is fully playable with the on-chain aspects and an interface functional and ready to use.  

### V1:  

#### Sellsword Commands  

- I can !attack a castle of my choice subject to cooldowns  
- I can !sharpen my blade before attacking by spending coin prior to the attack  
- I can send/receive payments of coin to/from other players  

#### General Commands  

- As a general, I can !fortify my castle by spending my coin during the staging phase  
- I can do anything that a sellsword can except attack my own castle, subject to potentially lower cooldowns  

#### V2:  

A whole world of possibilities, including:  

#### Sellsword Commands  

- I can !aim the ballista and charge ⅕ the amount of power needed to fire  
- I can attempttry to !parry incoming attacks to reduce their damage against the castle they are targeting  
- I can choose to !duel other players for a wagerbet of coin if they accept or accept other duel requests that are made to me  
- I can !loot the battlefield to find positive and negative effects including gain/loss of coins, temporary buffs/debuffs, and other items  

#### General Commands  

- Continued ability to perform Sellsword actions not targeting one’s own castle  
- I can !aim the ballista at the enemy castle and !fire it once it is fully loaded if my castle has lower HP than the enemy castle to try and even the odds  
- I can offer automatic payouts of coin (of my choosing) to sellswords that attack my enemy castle within a designated time period of my choosing  

[[Click here to read the gamepaper](https://drive.google.com/file/d/1PFsGQGv9ShSCt_DBT_eszxSPJiVUQZ0I/view)]

[![image](https://user-images.githubusercontent.com/102239225/262834365-07bc05cd-cf62-49c6-98d2-92574c360c2d.png)](https://drive.google.com/file/d/1PFsGQGv9ShSCt_DBT_eszxSPJiVUQZ0I/view)

### End Phase:

Post-battle, accolades are distributed. Players bask in the glory of their achievements, with the cream of the crop immortalized on a public leaderboard, and the elite few making their mark in an on-chain Hall of Fame. The game doesn't stagnate here. Game administrators, initially helmed by the Banners team, can infuse fresh narratives through special events. These episodic injections, reminiscent of the original game, provide players with richer rewards and diverse challenges. The decentralized spirit of on-chain gaming also paves the way for player-curated events, adding layers to the already-rich CtB lore.  

Marrying blockchain mechanics with CtB doesn't just provide a technical uplift; it rejuvenates the soul of the game. By fortifying cross-community bonds, amplifying the CtB gaming experience, and heralding a golden era of immersive social gaming, CtBOC is poised to be a beacon in the vast landscape of the Realms Autonomous World.  

### Technical Architecture:  

In a nutshell, it will work really similar to Loot Survivor in terms of the architecture.  

Contracts will house the game logic and control and will be built using Dojo and Cairo and deployed on Starknet  
For UI/UX, a web interface will be written using Next.JS and deployed on Vercel with wallet-based player authentication and login.  

We will focus on creating a v1 first: complete with the on-chain contracts + an interface for accessibility that will complete a playable gameplay loop and then utilize the remaining time to continue building on top for a v2: working on incorporating the features we have introduced to the current off-chain version of the game through its various seasons.  

### Core Contributors:  

**TheSkyvalkeR**: PhD in computer science, builder of CtB, lead developer of Banners, former Starknet Hackathon participant, past contributor to  [https://realms.world/](https://realms.world/)

**Andre_**: Learning Cairo, Banners community member since Day 1, worked on a number of technical aspects of Insignia, the Banners Ordinal project.

**Raulonastool**: Co-creator of CtB, onchain enthusiast, philosopher, writer, engineer

**Caygeon**: Co-creator of CtB, storyteller, graphic designer,

**ThomasRadio, TylerHarries, Pepe, Wellzy, Calculator, FoolishSwami, Nicabar, Pinky, D4rkSh33p, Misfit**: Have all had immeasurable input into the game over the past 4 seasons and into season 5.

### Timeline

| Item                   | Duration    | Date Started | Lead |
|------------------------|-------------|--------------|------|
| Finalize on-chain code | 1.5 months  | 9/23/23      | Sky  |
| Deploy to TestNet + QA | 2 weeks     | Q4           | Sky  |
| Web Interface          | 2 - 4 weeks | Q4           | Sky  |

[![image](https://user-images.githubusercontent.com/102239225/262834411-57b1b0d5-6f0b-4dfc-9fe3-c71602faa9e6.png)](https://user-images.githubusercontent.com/102239225/262834411-57b1b0d5-6f0b-4dfc-9fe3-c71602faa9e6.png)

### Grant Request 
 
We’re seeking a grant of 100,000 $Lords with the vast majority of that going to paying SkyValker and Andre for their time spent as developers of the game. A small portion may be used for supplemental costs such as domain names, hosting services, etc.

100,000 Lords = $9100 (as of writing, August 20th)

$400 for domain names, hosting, etc

$8600 / $40/hr = ~215 hours of development work.

[![image](https://user-images.githubusercontent.com/102239225/262834450-a8650cff-b006-419d-b64e-352e07b00a34.png)](https://user-images.githubusercontent.com/102239225/262834450-a8650cff-b006-419d-b64e-352e07b00a34.png)

# Frontinus House Builder Proposal

## Kist: a lock-picking hack

```
- nicabar
- 0x7896062Cbee5B512ea2b5A6182d1c89438aaeE5f
- @nicabar
- kist.dev
```



## TLDR /.

**Kist** *N. Scottish and Northern England dialect*
- a large chest or coffer

Build the framework for a competition designed to onboard the hackers of the Realms Autonomous Worlds (RAW).  Create 1 example dojo arcade game with an easy-to-follow tutorial and reusable components. Launch the annual "Kist" game jam hack.

---

## History /.

Over the past few years, I have fallen through the most fantastic rabbit hole toward a wonderland full of world builders and creative storytellers, where a hungry community is always ready for the next adventure. This is the world of tabletop roleplaying, and it will blow your mind. It is slated to be a nearly [$50 billion market by 2028](https://www.arizton.com/market-reports/tabletop-games-market), with a $1+ million [Kickstarter](https://www.kickstarter.com/projects/exaltedfuneral/dolmenwood-tabletop-rpg) actively running, and countless other small creative projects are flourishing with PDF sales and Patreon support.

While I traveled further and learned more, devouring all the oddities from [Troika](https://youtu.be/FNDNBlBP3Mw) and [The Ultraviolet Grasslands](https://twitter.com/stratometaship) to [Dungeon Crawl Classics](https://youtu.be/mHd3YYdV9Lw) and [Old School Essentials](https://necroticgnome.com/products/old-school-essentials-basic-rules), I stumbled upon an alternate wonderland called [LOOT](https://loot.foundation/). In the words of the great Timshel, I was instantly nerd-sniped.

![Image | 300](https://media.discordapp.net/attachments/994289105376645251/1144268357240115260/nicabar_fantasy_illustration_of_a_man_with_a_beard_dressed_as_a_785c9283-f73c-4319-8f13-ab54dcae3417.png?width=1274&height=1274)

With LOOT as my north star, I imagine a future where centralized platforms like Kickstarter and Patreon give way to the decentralized solutions of [Lens](https://mirror.xyz/lensprotocol.eth/-hJH-2IYSe56rK7IEdwSI17hUWt-paTyAs1r4Zes0uQ) and [Farcaster](https://www.farcaster.xyz/), allowing creators and their communities to intertwine more profoundly and sustainably. With their unique and provable characters, Solo players can one day roam freely between Autonomous Worlds (AWs), thanks to groundbreaking innovations developed by platforms like [Dojo](https://book.dojoengine.org/) and [MUD](https://mud.dev/). As Large Language Models advance, AI will blur the lines between computer-run RPGs (CRPGs) and tabletop RPGs (TTRPGs), paving the way for autonomous worlds run by AI dungeon masters.

Wide-eyed and optimistic, I set out to build this decentralized onchain TTRPG deeply integrated with AI. However, I quickly discovered the scope of such a project was well beyond my resources, coupled with the glaring fact that many foundational components are dependent on extraordinarily nascent and changing code.

So here I am, distilling my dream to its essence: a locked box, or in this context, a kist—a symbolic representation of untapped potential and undiscovered treasure. Or, maybe it's just a fun, fast, and easy way to get hacking and to get others hacking on some much-needed primitives.

## Project Detail /.

---
## **Objectives: Foster a new community of LOOT development in the RAW**

1) Build (1) example of a lock-picking mini-game
2) Write a tutorial to help guide new developers
3) Design and launch an annual lock-picking game jam 
---

### Part (1) Lock-picking a mini-game

Computer roleplaying games have implemented countless solutions to handling a locked door or chest. Games like [Elder Scrolls and Skyrim](https://thenerdstash.com/10-best-lockpicking-minigames-in-gaming-ranked/) have embraced a more realistic style with their explanation of working an actual lock. In contrast, other games like [The Room](https://youtu.be/SpGmYXXcElU) and [The Witness](https://youtu.be/KZokQov_aH0) have profoundly more complex and intricate puzzle mechanics that become increasingly difficult with deterministic blockchains.

Full Stop: It's time to set realistic expectations on where we are with RAW and why starting these game jam hacks is essential. On August 27, 2021, @dhof tweeted LOOT and gave birth to an idea that will outlive us all with any luck. We are extremely early, even if it doesn't always feel true. 

Dom's tweet came ten days after [Bevy](https://bevyengine.org/) celebrated its first birthday. This is the game engine that is a frontline contender to be integrated into Dojo, a game engine one year older than LOOT, and that a very competent Rust developer, Chris Biscardi, recently [failed to recreate Pong](https://youtu.be/wpx9qhKEuP8), a game from 1972.

As much as I would love an onchain version of Skyrim's lock-picking mini-game or a fully onchain clone of The Room, we are building primitives and creating foundations for others to integrate and iterate. These first examples will be simple, fun to play, and educational, to teach hackers about the Entity Component System of DoJo and demonstrate the similarities between Cairo and Rust.

After too much internal deliberation, I have decided to build a Cairo [Hillsfar lock-picking mini-game](https://youtu.be/aE5ue0YU2J8?si=OopMnD-cK-_lJiMQ&t=308) clone with the Dojo engine that I'm calling **Pick**.

CRPG Addict writes the following from their [2013 review](https://crpgaddict.blogspot.com/2013/03/hillsfar-final-rating.html) of this 1989 game.

>The game feels very much like an "experiment." What's all the more striking is that I don't think any of the innovations in Hillsfar lived beyond the game, which is too bad. It would have been fun to see the lockpicking mini-game, for instance, employed in the context of a true RPG. In the Gold Box games, when you want to pick a door or chest lock with a thief, you just choose "Pick Lock" from a menu, and a random roll determines success or failure; adding the mini-game as an option would have been a lot of fun; alas, we had to over a decade before we saw a lockpicking mini-game again (unless someone did it before Oblivion), and it wasn't as good.
>
> ![main_051.png](https://4.bp.blogspot.com/-4k4Srm9VxSQ/UTAepUR7K_I/AAAAAAAAPOg/Gx1aWfqtqHY/s400/main_051.png)

The art and user interface (UI) used in **Pick** is planned to mirror that of Loot Survivor, building cohesiveness within the current arcade-style ecosystem. **Pick** will also be a modular system encouraging integration with other games.


### Part (2) ~~Turtles~~ Tutorials all the way down

The underlying challenge with creating tutorials in Cairo and Dojo is that both change almost daily. 🥺
However, MY underlying challenge is that I'm still learning both. 🤣

So, the tutorial approach I will be taking is that of a dev blog with write-ups and videos documenting the journey. Coding in the open-style approach to learning Cairo and the Dojo Engine, a typical zero-to-hero blog. Exploring my journey building Pick.


### Part (3) Kist - Annual Realms Hack (a game jam) 

The mini-game Pick, alongside its tutorial, is envisioned primarily as a proof-of-concept, setting the stage for an annual game jam hack. The plan is to launch the first **Kist** in February 2024. While Kist is a working title, it's growing on me. It's short and has a nice meaning (a chest), and I've been tossing around the idea of - Keep It Simple Thief.

Future Opportunity Ideas: 
- Sponsorship Prizes
- Quarterly mini-jams
- Bounties

There is still much to flush out on all the jam details, but the basic premise is after the first year, Kist 2024, the DAO will decide on a new theme, change any necessary goals and rules for that year's participants, and then vote on the winner(s).

Examples: 

Year | Title | Goal | Rules
--- | --- | --- | ---
Kist 2025 | Magic Runes | Multiplayer weight balancing PVP lock | Utilize WebRTC 
Kist 2029 | Ghost Key | Time-sensitive lock using a disappearing key | ERC 6551 Only
Kist 2069 | Neural Transfer | Co-op consciousness defender lock | No Implants

Let's create our very own [JS13KGAMES](https://js13kgames.com/) for Dojo and Realms Autonomous Worlds. An annual competition that changes/advances with our ever-evolving technology and pushes the limits of what's possible while opening the door to new participants.

---

## Character /.

In this current version of my life, I've been LARPing as nicabar, the LOOT connoisseur and scholar. A nimble squire of [KoSA, the Knights of Sir Anthony](https://twitter.com/BannersNft/status/1603547350718640128?s=20), a proud acolyte of the [manny.game](https://www.mannys.game/leaderboard) cult and [FWB member](https://www.fwb.help/) at large.

Once upon a time, I ran several technology companies that mostly managed infrastructure in the pre-docker era. (Xen, Vmware, and Cisco days) I hand-crafted artisanal websites during the dawn of LAMP. My first computer games were pre-graphics, but that's just because I'm an early adopter and not because I'm old. (maybe a little old)

Somewhere along the timeline, I built a [Makerspace](https://makezine.com/article/education/the-difference-between-hackerspaces-makerspaces-techshops-and-fablabs/). Created curriculum for [Arduino](https://www.arduino.cc/) to [Shopbot](https://www.shopbottools.com/) training and housed/cat-herded 100+ members and volunteers. Our family of misfits built the world's largest video game cabinet (debatable). Created CNC houses and accidentally launched several companies that incubated their way out of our doors and onto bigger and brighter things.

Designed, Hosted, and Managed countless hackathons—from little community fixit weekenders to large NASA and Cisco sponsored events. 

## Timeline /.

The working timeline is to have a functional version of Pick, the lock-picking Hillsfar mini-game clone, by the first of December 2023. The dev blog will start on day 1 of proposal acceptance, run regular updates until game completion, and then be adapted to a tutorial 30 days before the Kist 2024 Hack on February 2024.

## Objectives /.

Objective | Contributor | Estimated deadline 
--- | --- | --- 
Pick Game Completion | nicabar | 23/12/01 
Dev Blog and Tutorial | nicabar | 24/01/01 
Kist 2024 Hack | nicabar | 24/02/01 


## Grant Request /.

I am requesting 100,000 LORDS (50,000 LORDS for the creation of Pick, Dev Blog, Tutorial, and Design of Kist 2024 Hack. The remaining 50,000 LORDS will be used as prize money for the participants of Kist 2024)


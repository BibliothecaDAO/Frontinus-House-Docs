# Abstract
Glyphs and Grammars aims to fill a crucial niche in the fantasy-themed Realms Autonomous World: magic spells. 

Realms provide a world setting, and the Crypts and Caverns project is poised to provide individual loci of adventuring. Within those  dungeons dank and deep there is treasure to be found. Besides troves of coin, the archetypal dungeon haul can be broken down into (at the very least) three broad categories:
- Magic items (represented by Loot)
- Potions and consumables (a project for another day)
- Spell books and spell scrolls

It is this third category that Glyphs and Grammars will address. This project will supply a primitive token that follows in the original spirit of Loot project, which contains secrets to be discovered, and which facilities the thrill of arcane research in the search for the perfect spell. 

It will also lay fertile ground for a future $LORDS token sink. 

# ***Glyphs and Grammars by Revenant Scholar***

## Introduction
Name or social handle of proposer: **Revenant Scholar**

Ethereum Mainnet Address: **0x0dD6fD47bb4d2F940541341f42827400F48EBf86**

Twitter handle: **@ScholarRevenant**, **@SpellsForLoot**

## Project Detail
### Overview
The proposed project will produce text-based NFTs on StarkNet, each containing 8 spells. Diegetically, these can be regarded as spell books, long forgotten, brimming with power, and recently unearthed.  They will stylistically match the original Loot project. 

Each Realms holder will receive one such spell book (TBD by minting or by airdrop, but using Herodotus to verify ownership).  Thereafter a VRGDA will be used to auction off additional spell books at a rate adjustable by the contract owner. Profits froth auction will be split between the RealmsDAO and the contract owner. As the creator, I will also receive some amount of spell books as well--either in bulk when the contract is deployed or periodically based on the timing of the VRDGA (like the creators of Nouns).

Under the hood, each spell will be deterministically generated using the token ID, and will be composed of 2 to 4 **glyphs** that are combined via **grammars** to form the spell's text. Accordingly, each spell book will be a collection of at least 16 distinct glyphs, and some number of grammatical patterns. 

Additionally, the contract will serve as a queryable on-chain database of glyphs and grammars, so its hundreds of thousands of spell combinations can serve as the foundation for magic in the Lootverse, Realms AW, and beyond. 

### Glyphs
A glyph is an ancient word of power encapsulating a single idea. It can be morphologically altered by a grammar, and in English it can be expressed as a noun, verb, adjective, or gerund. (Some glyphs with narrower meanings might only have 2 or 3 of those listed forms.) The name _glyph_ is at the moment purely diegetic, and this project will not contain visual representations beyond the text. Example glyphs include:

| Glyph     | Nominal   | Verbal  | Adjectival | Gerund |
| ------------- |:-------------:| ----------:|---------:|--------:|
| Example 1 | Frost | Freeze | Frozen | Freezing |
| Example 2 | Blast | Blast | Blasted | Blasting |
| Example 3 | Star | Shine | Astral | Shining | 

Note that the majority of glyph forms will be derived from a common English root, but where English doesn't do a concept justice, the English translations of the forms may not share a (recent) root, as in example 3. 


### Grammars
A grammar is a method of combining glyphs by selecting appropriate forms to create a noun or verb phrase in the style of a traditional fantasy spell. These will be binomial and recursive, so spells with more than two glyphs will necessary be arranged using nested grammars. Below are five core grammars (though the examples are illustrative of the structure, and not guaranteed to be on the final spell list). 

| Name | Structure | Example 1 | Example 2 |
|-------|:---------:|-----------:|----------:|
| Adjectival Noun | Adj. + N. | Chromatic Orb | Eldritch Blast |
| Gerundic Noun | Gerund + N. | Burning Hands | Booming Blade |
| Compound Noun | N. + N. | Chaos Bolt | Fire Storm |
| Genitive Noun | N. of N. | Cone of Cold | Wall of Force |
| Transitive Verb | V. + N. | Detect Thoughts | See Invisibility |

### Example Spell School
These is a tentative arrangement of glyph to populate the base spell of the Divination school. Note how the 20 columns and 15 rows align to produce exactly 60 unique spells for the school. If the spells are sufficiently deciphered, they will be modified by additional glyphs. For example _Apocalyptic Portent of Evil_ or _Authoritative Astral Augury_.

Curating a list and arranging the glyph and grammars into favorable combinations like this can take hours of work. I try to prioritize spells that make sense, iconic spells from other media, and alliteration. 
<img width="1682" alt="image" src="https://github.com/BibliothecaDAO/Frontinus-House-Docs/assets/143145157/085b31e2-c24a-419a-b260-e4c47b07b979">

### Scope
- 8000 spell books granted to Realms holders
- TBD spell books granted to contract creator (either bulk or vesting)
- 8 schools of magic
- (tentatively) 20 glyphs per school set aside as spell "shapes"* (e.g. cone, bolt, ball, etc.)
- (tentatively) 15 glyphs per school set aside as spell "elements"* (e.g. fire, freezing, shadow, etc.)
- with the above numbers, 60 unique curated base spells for each school of magic
- additional glyphs for each school set aside as additional modifiers for highly deciphered spells
- 4 forms per glyph
- between 5 and 8 total grammar patterns

By the numbers, the project will contain north of 300 glyphs, which can be combined in billions of combinations and reused in other projects.

## Vision

### Guiding Principles

#### Principles from Loot
- **Decomposable.** Just as Loot was a collection of items that in turn were a collection of attributes, each spell book will contain multiple spells, and each spell itself will be comprised of glyphs and grammars. In this way, it supplies primitives, but also offers more than just bare primitives. 
- **Composable.** This project will not try to do too much. The spells, glyphs, and grammars will be easily useable in derivative projects, and while possible future direction is presented, this is intentionally only the firsts step. 
- **Lore in the contract.** There will be secrets in the data for those with a discerning eye to discover.
- **Greatness.** In this case, a score called _deciphered_, representing how much the spell is understood.
- **Eight slots.** Every spell book will contain one spell from each of the eight schools of magic. These schools will overlap with but not entirely match those in Dungeons and Dragons. 
- **Twelve Orders.** The orders will be represented by glyphs, and some spells will have resonance with a specific order. A tentative example: _Acid Blast of Vitriol_. 
- **Elegance and simplicity.** A necessary constraint of the medium, but, like Loot, this project will favor straightforward solutions.

#### Additional Principles
- **Arcane.** While the logic of the contract should be simple, the vocabulary surrounding the project will make use of linguistic jargon to enhance the flavor of arcane research and study. It's supposed to feel like a wizard wrote it. 
- **Aesthetic.** Given the algorithmic recombination of glyphs and grammars, there may be some duds. But 90% of the spells generated for the spells books should sound like something someone would want to use in a game of _Dungeons and Dragons_. Indeed, the spell lists from the various editions of that game are a jumping off point for compiling and curating the list of glyphs.
- **Curated.** The math and method of selecting glyphs will make it that only certain combination of glyphs can appear in the spell books. It will not be a giant pile of purely random word combinations.
- **Useful.** In addition to the metadata for each spell book token and its composite spells, the contract will expose the master list of glyphs in a public view function, queryable by glyph id or by string. The same goes for the algorithm used to combine glyphs using a given grammar.

### Influences and Uniqueness
#### Similar Projects
Over the last several years there have been a number of spells-based projects in the Loot space. Some are better than others, but none of them satisfy my vision of the core fantasy archetype of spell casting and spell crafting, which I believe the Lootverse is craving.  
- Spellbook (for Adventurers) https://opensea.io/collection/spellbookadventurers
- Spells (for Adventurers) https://opensea.io/collection/spells-for-loot-adventurers
- Spells for Looters https://opensea.io/collection/spells-for-looters
- Spellbooks for Looters https://opensea.io/collection/spellbooks-for-looters
- Spell & Talent (for Loot, N, Adventurers and others) https://opensea.io/collection/spellandtalent
- Spells* https://opensea.io/collection/spellsdao
  - I give props to the experimental work that Spells* has done in using the ERC-5050 standard. This will not be used in this project, as each token corresponds to a bundle of spells, but when the spells are eventually distilled onto L2, this level of interactivity will be applied to the individual spell NFTs. 
  - I will be stealing the idea of using a VRGDA from this project
#### Influences
- Loot
- The field of linguistics
- Dungeons and Dragons/Pathfinder spells
- Magic the Gathering card names
- Pokemon moves
- Eragon--notably, when he attempts to bless a child to "be protected" but fumbles the grammar of the ancient language, thereby enchanting her to "be a protection"
#### Uniqueness
Much of what makes this project unique has already been described above--chiefly:
1. the unyielding commitment to compliment the ethos, lore and style of Loot
2. the composable nature of the spells
3. rooting spells in linguistic principles
4. building directly on StarkNet L2
5. a compelling plan for what comes next

### What Comes Next
This section describes future projects that are **out of the scope of this grant**, but are noted here to help illustrate the long-term vision that this project is kicking off.
#### ~~L2 Distillation~~ [Removed because this project will now be build directly on L2]
~~The current plan for Loot L2 distillation is to allow Loot holders 1 instance of their items, and for future distillations to give them $LORDS in exchange for putting their items in the DAO treasury. This has not yet been implemented because we are waiting for the Herodotus storage proof solution to mature. Per @loothero:~~

>  ~~I don't expect the distillation infrastructure to be particularly difficult though, the more challenging part will be coming up with viable utility and durable tokenomics for the items once they arrive.~~

~~Whenever the Loot distillation infrastructure is built, the spells from Glyphs and Grammars will be ready and waiting to be distilled in the same manner. One of the potential utilities of distilled Loot that is mentioned in the Realms white paper is for dungeon treasure and monster drops. That is a role these spells can likewise fill.~~

#### Spell Research
Spells can be granted a measure of utility via a spell research and collection game. Such contract would create derivative spell scroll NFTS each containing a single spell. If players can buy, sell, and recombine spells, the spells will have intrinsic aesthetic and collectible value. Players may well want to research a _Meteoric Fire Ball of Burning Rage_ because they can, and to show it off in their collection. 

Along these lines, I am enamored by the concept of a spell, and the idea of spell breeding from Coins and Scroll's [OSR: GLOG-based Homebrew v.01: Rat on a Stick Edition](https://coinsandscrolls.blogspot.com/2018/01/osr-glog-based-homebrew-v01-rat-on.html)
<details> 
<summary>What is a Spell?</summary>

> Spells are extra-dimensional entities. Wizards use them like items, or ammunition. Spells are semi-sentient. Most are about
as smart as a toad. Spellcasting is throwing spells at your enemies using your brain.
Wizard brains are like coral reefs, with spells living in the gaps.

</details>
<details> 
<summary>Spell Breeding</summary>

> You can attempt to crossbreed and combine two spells into one new spell. Both spells need to be stored on separate scrolls initially. This process takes 1 week of uninterrupted work. You can combine the spells to produce one of the following:
a) a random spell from your spell list (roll 1d10)
b) a random spell from a random spell list
c) a mutant version of one of the two spells
</details>

This could be considered a Realms AW fantasy analogue to CryptoKitties, except players breed spells instead of cats. 

Additionally, the L2 contract could contain additional hybrid glyphs that can only be accessed by combining specific glyphs. For example, a Lava glyph from combing Earth and Fire. This would add a flavor of alchemy and discovery to the game.

##### Integrations with Realms
It would be advantageous to the Realms AW to have such a spell breeding game integrated into its game environment. For example:
- It would be a token sink: $LORDS or resource cost to research/breed spells.
- Players could receive benefits to spell breeding from having a wizard tower or a wizard unit in their realm.
- When implementing ERC-5050-esque interactivity, each spell could have a cast() function and a castWithComponent() function, the latter of which could burn a resource. Other contracts could give spells greater effects if spells are cast with certain components. 

#### Spells as Dungeon Keys

Using Crypts and Caverns to generate random dungeons, spells (hardcoded, selected from a curated list, or fully randomized) could be used as keys to advance to the next room. With sufficient prizes at the end, this would incentive players to breed the spells necessary for the dungeons. To the extent that spell breeding is a token sink, utility beyond mere collectibility would only strengthen the sink, benefiting the $LORDS tokenomics. 

## Target Audience
Loot NFT holders, Realms NFT holders, people who want to secure a role in the Realms AW even if they don't currently hold an NFT, people who want to live out the fantasy of being a wizard and discovering new spells. 

The project that this grant enables in the future, however, is of wide appeal, as spell research can be abstracted entirely away from crypto with account abstraction and a user friendly UI. 

#### Spells DAO
I would be willing to transfer ownership of the contract to a DAO where spell books are the voting tokens. In this case, I'd code the VRGDA profits to be split three ways between the creator, the owner, and the Realms DAO.

A spells DAO with a treasury would be nice because it could, in turn, fund projects that make use of the spell book (or spell scrolls) tokens. 

# Character

## What about this project excites you?
I don't know if it's clear from the rest of the application, but I am brimming with excitement to build the whole thing; it's a bit of a passion project of mine. I have seen too many spell projects that don't do the genre justice or that don't achieve the full potential of fantasy magic, and I have a compulsive urge to see it done in a way that satisfies my soul. I'm a fantasy nerd, a linguistics nerd, and a computer nerd, so this really gets at the intersection of all of my favorite things. And I am excited to build something that is foundational to a whole new genre of gaming, fantasy, and collaborative storytelling for decades to come. 

## Who are you?
I've been lurking on the edge of the Lootverse since 2021, and I've been thinking about how to build spells the whole time--and I'm ready to make my entrance with a splash. This project is a natural extension of me: I grew up on Dungeons and Dragons, Pokemon, Neopets, and Legos; I have a degree in linguistics and a minor in computer science; and I have over half a decade of BE development experience (mostly in Java). I've played around in Solidity, but this will be my first project I publish to the blockchain. I am obsessive about unit testing. And I find the task of curating a list of glyphs in a way that balances the short term spell lists with the long term combinatorial potential to be a very satisfying mental puzzle. 

# Timeline
I'm not ready to quit my day job, and I'd rather overestimate than underestimate the time cost. I may well go faster than this, but I shouldn't go any slower.

Start date: September 1, 2023
End date: Feb 1, 2024

### Objectives
| Objective     | Contributor   | Estimated deadline  |
| ------------- |:-------------:| -------------------:|
| Write contract with dummy data glyphs, including tests  | Revenant Scholar | 2023/10/01            |
| Curate glyphs for schools 1 and 2 | Revenant Scholar | 2023/10/15 |
| Curate glyphs for schools 3 and 4 | Revenant Scholar | 2023/11/01 |
| Curate glyphs for schools 5 and 6 | Revenant Scholar | 2023/11/15 |
| Curate glyphs for schools 7 and 8 | Revenant Scholar | 2023/12/01 |
| Secret features necessary for lore | Revenant Scholar | 2024/01/01 |
| Deploy to testnet for alpha testing*  | Revenant Scholar | 2024/01/15 |
| Deploy to mainnet, private mint begins  | Revenant Scholar | 2024/02/01 |
| Public mint begins  | Revenant Scholar | 2024/02/14 |

*Note: a nonce phrase based on the block ID and the block difficulty of the contract deployment will be added to the randomization algorithm so that developers and testers will not have advanced knowledge of which spellbooks will contain which spells. 
# Grant Request
100,000 $LORDS

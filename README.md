`Date last modified: 2023 05 31`

# 🐂 BullRun Documentation

[BullRun](http://w3bbie.xyz/bullrun), courtesy of [W3BBIE](https://twitter.com/w3bbie_xyz). Built for [Theta Network 2023 Hackathon](https://theta2023.devpost.com/).

#### Development & Design Repositories 
* [ Unity Source ](https://github.com/W3bbieLabs/bullrununity)
* [ Marketplace ](https://github.com/W3bbieLabs/bullrun-marketplace)
* [ UI ](https://github.com/W3bbieLabs/BullRunFrontEnd)
* [ SoundPack ](https://github.com/W3bbieLabs/BullRunSoundPack)
* [ Character ]()

---

## Context
BullRun is a massively multiplayer arcade-style runner game for mobile and desktop. Players race as bulls against the bears ( and other obstacles ). Winning the race earns BullTokens, which can be used to purchase character emotes. 

---

## Tracks We Are Submitting To

| Track Name         | Description                                                         | How we approached                                                                 |  
| ------------------ | ------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Video API          | Build decentralized video into application using Theta's Video API. | Used API in our marketplace for easter egg content.                               |
| NFTs/ThetaPass     | Integrate ThetaPass in application.                                 | Create Emote NFTs applicable to character attributes, singnature finishing moves. |
| Metaverse & Gaming | N / A                                                               | Build and deploy a multiplayer game.                                              |

---

## Features and Functionality

### ⚙️ Mechanics

#### Gameplay Physics

* Movement
  - Left, Right
      + WASD or arrow keys
      + UI Joystick
  - Jump
      + Spacear
      + UI "A" touchpad
* Powerups
  - Caffeine boost
      + Triggers hyper-jump or speed boost ( if player is not jumping ).

---

### Aesthetics

* Environment
    - Low-poly 3d farm with:
        + Barns
        + Lighhouse
        + Tractors
        + Crop patches
        + Log Stacks
        + Trees
        + Scarecrows
        + Empty bottles

* Characters
    - "The Bull" 
        + Chibi inspired
        + styled in Theta's branding for tie-in.
    - Bears ( non-playable character )
        + Animated to roam, high five, sleep, or fight.

* Visual Styling
    - Additional polish was achieved via:
        + Bloom effects
        + Color grading
        + Grain
        + Gradient treatments

* Sound Design
    - Level Start
        + Inspired by Larry Heard
        + Engaging yet chill.
    - Collision & Powerups
        + Drum-and-bass inspired.
        + High energy, connotes impact.
    - Level Complete ( winner )
        + Linked to Level Start sounds
        + Carries a sense of energy and accomplishment.
    - Walking
        + SFX
    - Bears growling
        + SFX

* Interface Design
    
---

## Tech Stack
* Unity
* NextJS
* Solidity
* AWS EC2
* Vercel
* TailwindCSS
* Figma
* Paint 3D
* Midjourney
* MPC Live
* Natural Reader Text to Speech

## Components and Ecosystem
* Mirror Site
* Marketplace
* Leaderboard
* Wallet Connect
* Emotes ( ERC 1150 )
* BullToken ( TNT 20 )

---

## Milestones

| Milestone Name                                                 | Date of Milestone   |
| -------------------------------------------------------------- | ------------------- |
| Decide on prototype build.                                     | 2023 04 16          |
| Set up GitHub repo.                                            | 2023 04 16          |
| Begin character concepting.                                    | 2023 04 16          |
| Setup base ERC 1155 & TNT 20                                   | 2023 04 23          |
| Present design system exploration                              | 2023 04 23          |
| Wireframe UI for Marketplace                                   | 2023 04 30          |
| Wireframe UI for Leaderboard                                   | 2023 04 30          |
| Wireframe UI for Gameplay                                      | 2023 04 30          |
| Server test                                                    | 2023 04 30          |
| Primary character designed                                     | 2023 04 30          |
| Make UI Kit available to dev team                              | 2023 05 07          |
| Wallet Connect test                                            | 2023 05 07          |
| Game Loop Test                                                 | 2023 05 07          |
| Sound Pack and SFX to environment                              | 2023 05 14          |
| HTTP, beta test #1                                             | 2023 05 14          |
| HTTPS beta test #2                                             | 2023 05 21          |
| Server stress test, 5 players                                  | 2023 05 21          |
| Create Emotes                                                  | 2023 05 21          |
| Marketplace Live                                               | 2023 05 21          |
| Leaderboard live                                               | 2023 05 24          |
| Environment Polishing                                          | 2023 05 24          |
| Transact w/ Emotes                                             | 2023 05 24          |
| Beta Test #3                                                   | 2023 05 24          |
| Complete DevPost submission                                    | 2023 05 31          |
| Complete repo documentation                                    | 2023 05 31          |
| Beta Test #4                                                   | 2023 05 31          |

---
## Known Bugs and Issues

| Bug Name             | Description                                                |  Severity (1-5) | Resolved                |
| -------------------- | ---------------------------------------------------------- | --------------- | ------------------------ |
| WASM                 | Affects gameplay                                           | 5               | Yes.                     |
| IPFS                 | Affects marketplace whne viewing emote videos.             | 2               | In Progress.             |
| Theta Video API      | Theta Video API outage.                                    | 3               | Yes ( Thank you Theta! ) |
| Theta Testnet        | Theta testnet temporary outage                             | 5               | Yes ( Thank you Theta! ) |
| Countdown glitch     | Countdown not starting from expected value.                | 1               | Yes.                     |
| Countdown glitch     | Countdown not starting from expected value.                | 1               | Yes.                     |
| Reject lag           | Gameplay lag if transaction rejected in wallet             | 3               | Yes.

_Note: Submit future bugs via Issues. This is only a temporary bug tracker._

---

## Team W3BBIE

| Name                                                                         | Role(s)                                  |
| ---------------------------------------------------------------------------- | ---------------------------------------- |
| [Kyn Adams](https://twitter.com/Tek_Gawd)                                    | Server, Tester                           |
| [Tabari Humphries](https://www.instagram.com/gyasi.eth/)                     | Environmental Design, Level Design       |
| [Jack Lester](https://www.linkedin.com/in/jacklester/)                       | UI, Technical Documentation, Music & SFX |
| [Travis Rice](https://www.linkedin.com/in/travislrice/)                      | Project Manager, Character Design        |
| [Sailesh Sivakumar](https://www.linkedin.com/in/sailesh-sivakumar-453061141) | Marketplace, Smart Contracts             |
| [Chris Smith](https://twitter.com/last_gigabyte)                             | Gameplay Physics, Level Design           |

---

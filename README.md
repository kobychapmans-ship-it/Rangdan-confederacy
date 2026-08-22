# Rangdan Confederacy — BattleScribe HH v1 repository

This is a standalone catalogue repository built in the same layout as the original Zutan Scribes repository. It does not import the larger `Xenos_of_the_Great_Crusade_HH1.catz` catalogue.

## Repository files

- `Rangdan_Confederacy_HH1.catz` — standalone Rangdan catalogue
- `index.bsi` — BattleScribe Data Index archive (contains `index.xml`)
- `index.xml` — readable copy of the repository index
- `README.md` — these instructions

Upload all four files to the root of the existing `kobychapmans-ship-it/Rangdan-confederacy` repository. The phone Data Index URL is:

`https://raw.githubusercontent.com/kobychapmans-ship-it/Rangdan-confederacy/main/index.bsi`

## Install on a phone

1. In BattleScribe, open **Manage Data** / **Data Repositories**.
2. Add the raw `index.bsi` URL above as a new Data Index URL.
3. Refresh data and download **Rangdan Confederacy**.
4. Create a roster using **The Horus Heresy (HH v1)** and choose the **Sleeper Host Detachment**.

The catalogue targets HH v1 game-system revision 165, matching the standalone Zutan catalogue.

Archived HH1 armoury data source: `https://github.com/BSData/horus-heresy-1st-edition` at commit `0a4c10da15f4ea40eea0932090fadafe3b90b696`.

## Revision 6 — v5 hotfix and Osseivore faction trees

- The Legendary Cerabvore's GMC/Titan Rangdan weapons are now in a separate hidden group. They appear only after selecting **Gargantuan Monstrous Creature** or **Flying Gargantuan Monstrous Creature**. The Warleader continues to have no GMC/Titan weapon allowance.
- **Walking Meat** is generated only for datasheets limited to one model. It is absent from every multi-model unit and from the Moderate leader embedded in a Lesser brood.
- **Hidden Mutant** is available only to the two Independent Character entries: the Rangda Warleader and Legendary Cerabvore Host.
- The separate Moderate Cerabvore profile inside a Lesser brood now receives its own live host-body baseline, racial modifiers, Host Strengthening increments, mount type/bonuses, armour changes and manual display adjustments. The audit example resolves to WS 6, BS 4, S 7, T 9, W 3, I 4, A 3, LD 8 and Save 3+/5++.
- Every Osseivore now has one max-1 host-faction selector covering 34 host factions. Weapons and equipment are nested beneath the chosen faction. The Astartes branch contains all 18 Legion affiliations and 75 profiled HH1 armoury components; the other factions retain faction-gated source-priced and uncosted-component choices.
- The former top-level **External Host-Vehicle Upgrades**, **Modular Chassis — Faction Weapons** and **Modular Chassis — Faction Vehicle Equipment** sections have been removed. Their functionality now lives inside the selected host faction.

Revision 5's Cerabvore mobility/Monstrous mutual exclusion, separate Sergeant-style Moderate leader equipment, Legion host armouries, Osseivore source-cost cleanup, exact chassis profiles and Amalgam display cleanup are retained. The v4 modular chassis work and v3 live-statline fix also remain intact.

## Upgrade-button coverage

The source document was converted into separate, incrementable BattleScribe choices instead of combined text-only upgrades:

- 13 unit entries
- 615 option groups
- 2854 selectable upgrade entries
- 147 host-body selections across eligible profiles
- 18 HH1 Astartes Legion affiliations, 75 distinct Legion armoury items and 300 profile-level Legion weapon buttons
- 34 Osseivore host factions and 300 profiled Legion component buttons across the four Osseivore tiers
- 4 exact modular Osseivore chassis profiles
- 99 explicit twin-linked weapon selections
- 2795 live displayed-profile modifiers (2274 conditional and 521 incrementable)
- 230 zero-cost manual +/- stat buttons and 319 manual Save overrides
- individual buttons for Strength, Toughness, Weapon Skill, Ballistic Skill, Wounds, Initiative, saves and Mastery Levels where eligible
- explicit groups for natural weapons, Rangdan weapons, specialist/heavy allowances, eligible non-Osseivore armour and mounts, unique equipment, mutations, external vehicle hosts, faction-gated modular chassis components, Osseivore modifications and Osseivore upgrades

## Dynamic statline controls

- Choosing an alternate host body replaces the displayed WS, BS, S, T, W, I, A, LD, Save and applicable Unit Type with that tier's host-body values, including every race modifier printed in the source.
- The Moderate leader in a Lesser Cerabvore brood has a separately modified live profile, so its tier-correct values no longer collapse into or mirror the Lesser row.
- Monstrous and Gargantuan mutations change Unit Type and add the printed +2 or +4 to Strength, Toughness and Wounds.
- Numeric Host Strengthening and Osseivore statistic options now increment the displayed profile once per click; the priced Save improvement points to the manual Save override because HH v1 stores combined armour/invulnerable saves as text.
- Mount bonuses and unit types are applied automatically for eligible non-Osseivore entries where the source gives a numeric change.
- Osseivore statistic upgrades apply directly to the selected modular chassis row. The tested Higher Skimmer example resolves to WS 6, BS 5, S 9, AV 14/14/12, I 5, A 4 and 7 HP after its selected increments.
- Unit-wide host bodies, eligible armour/mounts, mutations, chassis forms and statistic upgrades are selected once; their points modifiers charge the listed cost for every model in the unit.
- Where retained, the manual +/- and Save override groups are zero-cost display tools for mixed host forms, scenario effects or unusual combinations. They never grant a rules discount; both Amalgam entries intentionally omit them in revision 5.

Per-unit audit:

- Rangda Warleader: 257 selectable upgrade buttons
- Higher Cerabvore Host: 255 selectable upgrade buttons
- Moderate Cerabvore Hosts: 221 selectable upgrade buttons
- Moderate Osseivore Host: 388 selectable upgrade buttons
- Lesser Cerabvore Hosts: 125 selectable upgrade buttons
- Lesser Osseivore Host: 371 selectable upgrade buttons
- Amalgams, Flesh Abominations: 1 selectable upgrade buttons
- Lesser Amalgams: 0 selectable upgrade buttons
- Higher Osseivore Host: 409 selectable upgrade buttons
- Monstrous Osseicerabvore: 99 selectable upgrade buttons
- Legendary Cerabvore Host: 267 selectable upgrade buttons
- Legendary Osseivore Host: 418 selectable upgrade buttons
- Oblivion Parasite: 43 selectable upgrade buttons

## Source gaps retained honestly

The supplied rules list **Pirates** and **Kroot** as host bodies but provide no rules, wargear, statistic changes or points modifiers. Both remain selectable, with a 0-point race modifier and a note identifying the missing source data. The eighteen Astartes Legions have explicit imported profiles. The chassis document permits components from many other external vehicle datasheets but does not enumerate their individual profiles, so those factions use nested source-priced and uncosted-component choices beneath their selected faction. Tier access and hardpoints remain enforced without reintroducing manual point-increment buttons.

Catalogue ID: `069890da-d908-533f-9a7b-8ba24b3e3773`  
Catalogue revision: `6`  
`Rangdan_Confederacy_HH1.catz` SHA-256: `612c31b6450013b10a2da8084ef91e8b105ab5bbe5f966e2073ccaf716a3d2ac`  
`index.bsi` SHA-256: `9f325bf302eb70a255e36cf7b87265c63778f2ae03efaf5fa4c3474b8ed5cd5d`

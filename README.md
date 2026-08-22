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

## Revision 4 — modular Osseivore vehicle forms

- Lesser, Moderate, Higher and Legendary Osseivore Hosts no longer have the ordinary Rangdan Armour or Mobility / Mount groups. Those groups remain available to eligible non-Osseivore entries.
- Each Osseivore Host now has exactly one matching-tier modular chassis choice. Selecting it displays the source document's final vehicle profile rather than a text-only rules entry.
- Chassis costs and totals are encoded per model: Lesser +10 / 40 total, Moderate +40 / 90 total, Higher +150 / 225 total, and Legendary +300 / 450 total.
- The four profiles encode their printed WS, BS, Strength, Front/Side/Rear Armour, Initiative, Attacks, Hull Points and Vehicle (Tank) type, with 2/4/6/8 hardpoints respectively.
- Separate controls cover the Facsimile Origin, Walker/Skimmer/Flyer movement patterns, hardpoint use, published-cost and uncosted faction weapons/equipment, and manual source-cost point increments.
- Transport Ship is repeatable: the first purchase grants Transport, one rear access point and the tier capacity; further purchases add that capacity again without another access point.
- A complete external host vehicle remains an alternative form. Its melding-values profile appears only when that alternative is chosen.

The revision 3 live-statline fix is retained: modifiers are attached to each roster-context profile link, manual controls do not create redundant Selection Rules entries, and host-body text stays unique to the correct unit/tier.

## Upgrade-button coverage

The source document was converted into separate, incrementable BattleScribe choices instead of combined text-only upgrades:

- 13 unit entries
- 141 option groups
- 1411 selectable upgrade entries
- 147 host-body selections across eligible profiles
- 4 exact modular Osseivore chassis profiles
- 99 explicit twin-linked weapon selections
- 2752 live displayed-profile modifiers (2195 conditional and 557 incrementable)
- 258 zero-cost manual +/- stat buttons and 377 manual Save overrides
- individual buttons for Strength, Toughness, Weapon Skill, Ballistic Skill, Wounds, Initiative, saves and Mastery Levels where eligible
- explicit groups for natural weapons, Rangdan weapons, specialist/heavy allowances, eligible non-Osseivore armour and mounts, unique equipment, mutations, external vehicle hosts, modular chassis components, Osseivore modifications and Osseivore upgrades

## Dynamic statline controls

- Choosing an alternate host body replaces the displayed WS, BS, S, T, W, I, A, LD, Save and applicable Unit Type with that tier's host-body values, including every race modifier printed in the source.
- Monstrous and Gargantuan mutations change Unit Type and add the printed +2 or +4 to Strength, Toughness and Wounds.
- Numeric Host Strengthening and Osseivore statistic options now increment the displayed profile once per click; the priced Save improvement points to the manual Save override because HH v1 stores combined armour/invulnerable saves as text.
- Mount bonuses and unit types are applied automatically for eligible non-Osseivore entries where the source gives a numeric change.
- Osseivore statistic upgrades apply directly to the selected modular chassis row. The tested Higher Skimmer example resolves to WS 6, BS 5, S 9, AV 14/14/12, I 5, A 4 and 7 HP after its selected increments.
- Unit-wide host bodies, eligible armour/mounts, mutations, chassis forms and statistic upgrades are selected once; their points modifiers charge the listed cost for every model in the unit.
- The manual +/- and Save override groups are zero-cost display tools for mixed host forms, scenario effects or unusual combinations. They never grant a rules discount.

Per-unit audit:

- Rangda Warleader: 169 selectable upgrade buttons
- Higher Cerabvore Host: 163 selectable upgrade buttons
- Moderate Cerabvore Hosts: 129 selectable upgrade buttons
- Moderate Osseivore Host: 107 selectable upgrade buttons
- Lesser Cerabvore Hosts: 87 selectable upgrade buttons
- Lesser Osseivore Host: 88 selectable upgrade buttons
- Amalgams, Flesh Abominations: 44 selectable upgrade buttons
- Lesser Amalgams: 43 selectable upgrade buttons
- Higher Osseivore Host: 128 selectable upgrade buttons
- Monstrous Osseicerabvore: 101 selectable upgrade buttons
- Legendary Cerabvore Host: 173 selectable upgrade buttons
- Legendary Osseivore Host: 136 selectable upgrade buttons
- Oblivion Parasite: 43 selectable upgrade buttons

## Source gaps retained honestly

The supplied rules list **Pirates** and **Kroot** as host bodies but provide no rules, wargear, statistic changes or points modifiers. Both remain selectable, with a 0-point race modifier and a note identifying the missing source data. The chassis document permits components from many external faction datasheets but does not enumerate those catalogues. This file therefore preserves each tier's access restrictions and uncosted-component prices, provides hardpoint and manual-cost controls, and does not invent unavailable faction profiles.

Catalogue ID: `069890da-d908-533f-9a7b-8ba24b3e3773`  
Catalogue revision: `4`  
`Rangdan_Confederacy_HH1.catz` SHA-256: `c60e4b362a1558d26f7961bd11fd6b7bba2a84b3bcbce1b9acedacc7d4abe9be`  
`index.bsi` SHA-256: `840035bb45d3da4e1b525afefb368541be3e852e84a4318a29b5f2348b58a963`

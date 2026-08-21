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

## Revision 3 compatibility fix

- Dynamic characteristic modifiers are attached to each model's roster-context profile link, so BattleScribe applies them to the existing Unit row instead of leaving the base values unchanged.
- Manual +/- selections no longer add redundant rules to the printed Selection Rules section.
- Host-body rule text is unique to each unit/tier, preventing a Lesser host from displaying the Legendary host-body cost description.
- Regression case: Greater Orks Lesser Host Body + Manual +1 WS/S + Manual +2 T resolves to WS 5, BS 3, S 6, T 8, W 1, I 3, A 2, LD 7, Save 5+/6++.

## Upgrade-button coverage

The source document was converted into separate, incrementable BattleScribe choices instead of combined text-only upgrades:

- 13 unit entries
- 121 option groups
- 1381 selectable upgrade entries
- 147 host-body selections across eligible profiles
- 99 explicit twin-linked weapon selections
- 2615 live displayed-profile modifiers (2138 conditional and 477 incrementable)
- 258 zero-cost manual +/- stat buttons and 377 manual Save overrides
- individual buttons for Strength, Toughness, Weapon Skill, Ballistic Skill, Wounds, Initiative, saves and Mastery Levels where eligible
- explicit groups for natural weapons, Rangdan weapons, specialist/heavy allowances, armour, unique equipment, mounts, mutations, vehicle hosts, Osseivore modifications and Osseivore upgrades

## Dynamic statline controls

- Choosing an alternate host body replaces the displayed WS, BS, S, T, W, I, A, LD, Save and applicable Unit Type with that tier's host-body values, including every race modifier printed in the source.
- Monstrous and Gargantuan mutations change Unit Type and add the printed +2 or +4 to Strength, Toughness and Wounds.
- Numeric Host Strengthening and Osseivore statistic options now increment the displayed profile once per click; the priced Save improvement points to the manual Save override because HH v1 stores combined armour/invulnerable saves as text.
- Mount bonuses and unit types are applied automatically where the source gives a numeric change.
- Unit-wide host bodies, armour, mounts, mutations and statistic upgrades are selected once; their points modifiers charge the listed cost for every model in the unit.
- The manual +/- and Save override groups are zero-cost display tools for mixed host forms, scenario effects or unusual combinations. They never grant a rules discount.

Per-unit audit:

- Rangda Warleader: 169 selectable upgrade buttons
- Higher Cerabvore Host: 163 selectable upgrade buttons
- Moderate Cerabvore Hosts: 129 selectable upgrade buttons
- Moderate Osseivore Host: 99 selectable upgrade buttons
- Lesser Cerabvore Hosts: 87 selectable upgrade buttons
- Lesser Osseivore Host: 79 selectable upgrade buttons
- Amalgams, Flesh Abominations: 44 selectable upgrade buttons
- Lesser Amalgams: 43 selectable upgrade buttons
- Higher Osseivore Host: 121 selectable upgrade buttons
- Monstrous Osseicerabvore: 101 selectable upgrade buttons
- Legendary Cerabvore Host: 173 selectable upgrade buttons
- Legendary Osseivore Host: 130 selectable upgrade buttons
- Oblivion Parasite: 43 selectable upgrade buttons

## Source gaps retained honestly

The supplied rules list **Pirates** and **Kroot** as host bodies but provide no rules, wargear, statistic changes or points modifiers. Both remain selectable, with a 0-point race modifier and a note identifying the missing source data. The source also says eligible wargear from external host factions will be catalogued later; this file therefore provides an explicit manual-cost button and preserves the eligibility text without inventing unavailable faction options.

Catalogue ID: `069890da-d908-533f-9a7b-8ba24b3e3773`  
Catalogue revision: `3`  
`Rangdan_Confederacy_HH1.catz` SHA-256: `90612788a263669e42a6cd90b3078dbf16dab60228610f63fc2717b1f993b861`  
`index.bsi` SHA-256: `817e0f39ea88831eba888bdb5da19d266f69beab55837d3603181ed5149ea306`

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

## Revision 5 — Cerabvore armouries and option cleanup

- The Rangda Warleader no longer exposes GMC/Titan Rangdan weapons or Lord of War/Super-heavy external-host allowances. Its ordinary HQ weapons, mobility and Monstrous Creature choices remain.
- Every Cerabvore entry that can take both a mobility option and a Monstrous mutation now has one combined max-1 group, so the two can no longer be selected together.
- An Astartes Host Body now reveals a nested HH1 Legion armoury: 18 Legion affiliations and 75 distinct faction-specific host-eligible weapon/equipment entries, with profiles and listed upgrade prices sourced from archived HH1 BSData commit `0a4c10da`. Named-character, Primarch-only, Relic and vehicle-only items are excluded.
- The Lesser unit's single Moderate Cerabvore upgrade is now a separate Sergeant-style selection. Its natural weapon, regular weapon, specialist/heavy weapon, unique equipment, armour and eligible external host-faction choices are nested under that Moderate model rather than mixed into the Lesser unit's main choices.
- All Osseivore entries have had the manual source-cost increment buttons and the Facsimile Origin section removed. Their v4 chassis profiles, movement patterns, hardpoints, component placeholders and live displayed-statline changes remain intact.
- Amalgams, Flesh Abominations and Lesser Amalgams no longer show the manual displayed-statline adjustment or displayed-Save override sections.

The v4 modular chassis work and v3 live-statline fix are retained: matching-tier chassis remain exact selectable vehicle profiles, Transport Ship remains repeatable, and modifiers remain attached to roster-context profile links.

## Upgrade-button coverage

The source document was converted into separate, incrementable BattleScribe choices instead of combined text-only upgrades:

- 13 unit entries
- 210 option groups
- 1707 selectable upgrade entries
- 147 host-body selections across eligible profiles
- 18 HH1 Astartes Legion affiliations, 75 distinct Legion armoury items and 300 profile-level Legion weapon buttons
- 4 exact modular Osseivore chassis profiles
- 99 explicit twin-linked weapon selections
- 2623 live displayed-profile modifiers (2108 conditional and 515 incrementable)
- 230 zero-cost manual +/- stat buttons and 319 manual Save overrides
- individual buttons for Strength, Toughness, Weapon Skill, Ballistic Skill, Wounds, Initiative, saves and Mastery Levels where eligible
- explicit groups for natural weapons, Rangdan weapons, specialist/heavy allowances, eligible non-Osseivore armour and mounts, unique equipment, mutations, external vehicle hosts, modular chassis components, Osseivore modifications and Osseivore upgrades

## Dynamic statline controls

- Choosing an alternate host body replaces the displayed WS, BS, S, T, W, I, A, LD, Save and applicable Unit Type with that tier's host-body values, including every race modifier printed in the source.
- Monstrous and Gargantuan mutations change Unit Type and add the printed +2 or +4 to Strength, Toughness and Wounds.
- Numeric Host Strengthening and Osseivore statistic options now increment the displayed profile once per click; the priced Save improvement points to the manual Save override because HH v1 stores combined armour/invulnerable saves as text.
- Mount bonuses and unit types are applied automatically for eligible non-Osseivore entries where the source gives a numeric change.
- Osseivore statistic upgrades apply directly to the selected modular chassis row. The tested Higher Skimmer example resolves to WS 6, BS 5, S 9, AV 14/14/12, I 5, A 4 and 7 HP after its selected increments.
- Unit-wide host bodies, eligible armour/mounts, mutations, chassis forms and statistic upgrades are selected once; their points modifiers charge the listed cost for every model in the unit.
- Where retained, the manual +/- and Save override groups are zero-cost display tools for mixed host forms, scenario effects or unusual combinations. They never grant a rules discount; both Amalgam entries intentionally omit them in revision 5.

Per-unit audit:

- Rangda Warleader: 257 selectable upgrade buttons
- Higher Cerabvore Host: 257 selectable upgrade buttons
- Moderate Cerabvore Hosts: 223 selectable upgrade buttons
- Moderate Osseivore Host: 100 selectable upgrade buttons
- Lesser Cerabvore Hosts: 127 selectable upgrade buttons
- Lesser Osseivore Host: 81 selectable upgrade buttons
- Amalgams, Flesh Abominations: 1 selectable upgrade buttons
- Lesser Amalgams: 0 selectable upgrade buttons
- Higher Osseivore Host: 121 selectable upgrade buttons
- Monstrous Osseicerabvore: 101 selectable upgrade buttons
- Legendary Cerabvore Host: 267 selectable upgrade buttons
- Legendary Osseivore Host: 129 selectable upgrade buttons
- Oblivion Parasite: 43 selectable upgrade buttons

## Source gaps retained honestly

The supplied rules list **Pirates** and **Kroot** as host bodies but provide no rules, wargear, statistic changes or points modifiers. Both remain selectable, with a 0-point race modifier and a note identifying the missing source data. Revision 5 begins the external-host armoury expansion with the eighteen Astartes Legions. Other host factions remain represented by the source-priced external choice until their armouries are added. The chassis document permits components from many external vehicle datasheets but does not enumerate their individual profiles; the catalogue preserves tier access, hardpoints and uncosted-component prices without reintroducing manual point-increment buttons.

Catalogue ID: `069890da-d908-533f-9a7b-8ba24b3e3773`  
Catalogue revision: `5`  
`Rangdan_Confederacy_HH1.catz` SHA-256: `54dcceaaa22e2007370b5071f71805628c4df4ac178374cd5428f2574b3b70c1`  
`index.bsi` SHA-256: `0dbf52fe6ee3b0fb403c626dc10151697563f41fa66da0a269ab35eaf4e2930b`

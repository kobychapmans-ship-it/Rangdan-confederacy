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

## Revision 8 — requested next-version update

- **Walking Meat** is present on all eight eligible Rangdan entries. On units that can add models, BattleScribe now hides the option and sets its maximum to zero whenever the unit contains two or more models; reducing the unit to exactly one model makes it available again.
- All 193 formerly source-dependent Astartes, Militia, Solar Auxilia, Mechanicum, Sisters of Silence and Custodes entries now have fixed BattleScribe prices. The generator uses the most common positive archived HH1 upgrade cost, choosing the lower value on a tied mode. Items only included as base wargear remain 0 points for Cerabvores and use the chassis fallback price for Osseivores.
- Unlisted external-faction Cerabvore wargear and Osseivore vehicle components now use visible fixed tier/chassis fallback prices instead of a zero-point manual source-price placeholder.
- The **Higher Osseivore Host** no longer has a Monstrous Mutation group or any Monstrous/Flying Monstrous Creature choices.
- Every Skimmer and Flyer modular chassis movement pattern now subtracts 1 Hull Point from the displayed profile. Walker and Tank forms retain their full Hull Points; all 8 tier/movement bindings are validated.

### Revision 7 faction-armoury foundation retained

- The Astartes armoury now includes 49 base Legion weapons and equipment alongside the 75 Legion-specialised entries. Base items sit above the eighteen-Legion affiliation selector, so they do not need to be duplicated inside every Legion.
- Militia and Cults (46 named items) and Solar Auxilia (43 named items) now have profiled weapon and equipment trees for every tier that can select their host form, including Lesser Cerabvores.
- Mechanicum (44 named items) and Sisters of Silence (15 named items) forms and armouries are tier-gated to Moderate, Higher and Legendary Cerabvores and Osseivores.
- Custodes forms and their 23 named items are tier-gated to Higher and Legendary Cerabvores and Osseivores.
- Osseivore host-faction selectors now enforce the host grade: Lesser cannot select Astartes, Mechanicum, Sisters or Custodes; Moderate adds Astartes, Mechanicum and Sisters; Higher adds Custodes. Their Militia, Solar Auxilia, Mechanicum, Sisters, Custodes and Astartes branches use the same imported profiles as the Cerabvore armouries.
- Included/base vehicle components pay the matching chassis uncosted-component value. Every other named imported component now uses its fixed revision 8 price.

Revision 6's gated GMC/Titan weapons, Hidden Mutant eligibility, live Moderate-leader profile, consolidated Osseivore faction selector and removed legacy vehicle-upgrade sections are retained. All earlier exact chassis, live-statline and Cerabvore mutual-exclusion work also remains intact.

## Upgrade-button coverage

The source document was converted into separate, incrementable BattleScribe choices instead of combined text-only upgrades:

- 13 unit entries
- 610 option groups
- 4278 selectable upgrade entries
- 147 host-body selections across eligible profiles
- 18 HH1 Astartes Legion affiliations, 49 base Legion items, 75 specialised Legion items and 300 specialised Legion buttons across Cerabvore entries
- named Militia (46), Solar Auxilia (43), Mechanicum (44), Sisters of Silence (15) and Custodes (23) inventories
- 34 Osseivore host factions and 225 profiled Legion component buttons across the four Osseivore tiers
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
- Osseivore statistic upgrades apply directly to the selected modular chassis row. The tested Higher Skimmer example resolves to WS 6, BS 5, S 9, AV 14/14/12, I 5, A 4 and 6 HP after its selected increments and the Skimmer's -1 HP adjustment.
- Unit-wide host bodies, eligible armour/mounts, mutations, chassis forms and statistic upgrades are selected once; their points modifiers charge the listed cost for every model in the unit.
- Where retained, the manual +/- and Save override groups are zero-cost display tools for mixed host forms, scenario effects or unusual combinations. They never grant a rules discount; both Amalgam entries intentionally omit them in revision 5.

Per-unit audit:

- Rangda Warleader: 482 selectable upgrade buttons
- Higher Cerabvore Host: 481 selectable upgrade buttons
- Moderate Cerabvore Hosts: 423 selectable upgrade buttons
- Moderate Osseivore Host: 558 selectable upgrade buttons
- Lesser Cerabvore Hosts: 216 selectable upgrade buttons
- Lesser Osseivore Host: 236 selectable upgrade buttons
- Amalgams, Flesh Abominations: 1 selectable upgrade buttons
- Lesser Amalgams: 0 selectable upgrade buttons
- Higher Osseivore Host: 618 selectable upgrade buttons
- Monstrous Osseicerabvore: 100 selectable upgrade buttons
- Legendary Cerabvore Host: 492 selectable upgrade buttons
- Legendary Osseivore Host: 628 selectable upgrade buttons
- Oblivion Parasite: 43 selectable upgrade buttons

## Source gaps retained honestly

The supplied rules list **Pirates** and **Kroot** as host bodies but provide no rules, wargear, statistic changes or points modifiers. Both remain selectable, with a 0-point race modifier and a note identifying the missing source data. Astartes, Militia, Solar Auxilia, Mechanicum, Sisters of Silence and Custodes have explicit imported profiles and fixed prices. Because the chassis document does not enumerate individual profiles for the other external factions, those branches use fixed tier-appropriate component fallback prices. Tier access and hardpoints remain enforced without manual point-increment buttons.

Catalogue ID: `069890da-d908-533f-9a7b-8ba24b3e3773`  
Catalogue revision: `8`  
`Rangdan_Confederacy_HH1.catz` SHA-256: `d2641c2c952298dfe21d73469a738381c694a676f4025a651f17933c8fe89664`  
`index.bsi` SHA-256: `8e78a2a2a11a5e2fba1e716ebbafbe65ebe217e33ae5c95f2be5db581e4eda31`

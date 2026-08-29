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

Archived 7th-edition Harlequin data source: `https://github.com/BSData/wh40k-7th-edition` at commit `6fd52df8ad613b98b34c635cc6d8011bc312f2e7`.

## Revision 13 — Book Two factions and vehicle-only Osseivore armouries

- Added complete host armouries for **Exodites** (57 items), **Demiurg** (27), **Interex** (29), **Keylekid** (26), **Hrud** (25) and **Jorgall** (28) from the supplied Great Crusade Book Two reference.
- Every printed weapon profile, available equipment rule and distinct option price is represented. Source omissions such as Pulsar, Sonic Lance, Exodite Missile Launcher ammunition, Flechette Launcher, Survey Glass and Hexagrammatic Wards are labelled as omissions instead of receiving invented rules.
- 184 armoury entries across all factions are now explicitly tagged **[Vehicle Weapon]** or **[Vehicle Equipment]** in both their option labels and linked profile names.
- Every Osseivore faction branch now contains only those tagged vehicle components. Infantry weapons, character relics, personal armour, mounts and other non-vehicle wargear remain available to eligible Cerabvores but cannot be selected on an Osseivore chassis.
- Generic fallback buttons remain vehicle-only and are used solely for eligible components that are present on a source vehicle datasheet but not explicitly profiled in this catalogue.

## Revision 12 — six Great Crusade xenos armouries

- Removed all eight Harlequin role/sub-form selectors. **Harlequins Host Body** is again the single standard Harlequin body choice, exactly as in the original Rangdan host list.
- Added explicit **Laer** (22 items), **Storm Scions** (12), **Nephilim** (41), **Megarachnids** (16), **Nurthene** (23) and **Olamic Quietude** (23) armouries.
- Every available racial weapon has a BattleScribe weapon profile. Armour, artefacts, biological adaptations, command equipment and other non-weapon upgrades have fixed prices and rules descriptions.
- Where the same item has different printed prices for different source units, separate labelled buttons preserve those costs instead of collapsing them into one estimate.
- Their matching Osseivore Host Faction branches retain only items identified as vehicle weapons or vehicle equipment; included components use the chassis fallback price and purchased upgrades retain their printed cost.
- Generic Imperial equipment mentioned by the Nephilim list is included only where a profile or cost was supplied; externally referenced Crusade Imperialis datasheets remain cross-references and were not invented.

## Revision 11 — Harlequin armoury retained

- Added 45 Harlequin weapons and equipment choices across the 7th-edition base armoury and the supplied additions, including 17 custom revision 11 items.
- The single standard Harlequin Host Body displays its Holo-suit 5++ save alongside the Cerabvore host's armour save.
- The matching Harlequin Host Faction branch is available to Moderate, Higher and Legendary Osseivore vehicle forms and is restricted to explicitly vehicle-mounted Harlequin weapons and equipment.
- Incomplete supplied entries are preserved honestly: Riveblades and the Blind-Barrage Launcher are selectable markers with their supplied costs where present, but no invented profile was added.

## Revision 10 — Rangdan xenos host-faction armouries

- **Slaugth** host bodies and vehicle facsimiles now expose 37 named weapons and equipment choices from the supplied Slaugth Intendant faction insert, including Necrotic and Parepleth sceptres, Husk weapons, Slaugth relics, Voidling weapons, Rad weapons, drone components, Shoggoth weapons and fixed-cost upgrades.
- **Barasonilash** now expose their 2 supplied items: the Flechette Burster Pistol Bandolier and Crown of Mental Dispersion.
- **Baalite / Fire Scorpion** now expose their 2 supplied natural weapons: Igneous Claws and the Flameblood Stinger.
- **Cythor Fiends** now expose all 4 supplied choices: Stare of Stone, Scything Talons, Crystalline Scythe Matrix and Toiphoid Assistance Nanobots.
- These four armouries use the same structure as the existing Imperial factions: selecting the matching Cerabvore Host Body reveals its weapon/equipment branch. Their Osseivore branches now expose only explicitly vehicle-classified components; factions with no printed vehicle component use the vehicle-only fallback controls.

### Revision 9 Monstrous Osseicerabvore update retained

- Added 38 selectable forms derived from all 37 printed non-Unique host entries supplied in the Monstrous Osseicerabvore catalogue. The separate upgraded Arch-Daemon button accounts for the extra selection. Coverage includes Mechanicum, Legiones Astartes, Solar Auxilia, Questoris support, Daemons of the Ruinstorm, legacy 7th-edition Chaos Daemons, Craftworld and Necron compatibility sources.
- Each selection adds the printed host cost per model and replaces the live Unit Type, WS, BS, S, T, W, I, A, Ld and Save fields instead of appending a second statblock.
- The 4 Gargantuan choices are hidden until **Gargantuan Monstrous Host** is selected. The upgraded Arch-Daemon is represented at its full 700-point source cost, with the separate Rangdan +75-point Gargantuan surcharge retained.
- Named characters, Unique models, Walkers, Vehicles, Infantry, Beasts, Cavalry and Primarchs remain excluded. Source-faction, allegiance, Rite of War and campaign-tier restrictions remain visible on their applicable choices.

### Revision 8 update retained

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
- Osseivore host-faction selectors enforce the host grade and filter every imported armoury to vehicle weapons and vehicle equipment only. Lesser cannot select Astartes, Mechanicum, Sisters or Custodes; Moderate adds Astartes, Mechanicum and Sisters; Higher adds Custodes.
- Included/base vehicle components pay the matching chassis uncosted-component value. Every other named imported component now uses its fixed revision 8 price.

Revision 6's gated GMC/Titan weapons, Hidden Mutant eligibility, live Moderate-leader profile, consolidated Osseivore faction selector and removed legacy vehicle-upgrade sections are retained. All earlier exact chassis, live-statline and Cerabvore mutual-exclusion work also remains intact.

## Upgrade-button coverage

The source document was converted into separate, incrementable BattleScribe choices instead of combined text-only upgrades:

- 13 unit entries
- 759 option groups
- 5764 selectable upgrade entries
- 147 host-body selections across eligible profiles
- 18 HH1 Astartes Legion affiliations, 49 base Legion items, 75 specialised Legion items and 300 specialised Legion buttons across Cerabvore entries
- named Militia (46), Solar Auxilia (43), Mechanicum (44), Sisters of Silence (15), Custodes (23), Harlequins (45), Laer (22), Storm Scions (12), Nephilim (41), Megarachnids (16), Nurthene (23), Olamic Quietude (23), Exodites (57), Demiurg (27), Interex (29), Keylekid (26), Hrud (25), Jorgall (28), Slaugth (37), Barasonilash (2), Baalite / Fire Scorpion (2) and Cythor Fiends (4) inventories
- 34 Osseivore host factions and 51 profiled Legion component buttons across the four Osseivore tiers
- 4 exact modular Osseivore chassis profiles
- 99 explicit twin-linked weapon selections
- 3175 live displayed-profile modifiers (2654 conditional and 521 incrementable)
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

- Rangda Warleader: 918 selectable upgrade buttons
- Higher Cerabvore Host: 917 selectable upgrade buttons
- Moderate Cerabvore Hosts: 816 selectable upgrade buttons
- Moderate Osseivore Host: 433 selectable upgrade buttons
- Lesser Cerabvore Hosts: 407 selectable upgrade buttons
- Lesser Osseivore Host: 207 selectable upgrade buttons
- Amalgams, Flesh Abominations: 1 selectable upgrade buttons
- Lesser Amalgams: 0 selectable upgrade buttons
- Higher Osseivore Host: 473 selectable upgrade buttons
- Monstrous Osseicerabvore: 138 selectable upgrade buttons
- Legendary Cerabvore Host: 928 selectable upgrade buttons
- Legendary Osseivore Host: 483 selectable upgrade buttons
- Oblivion Parasite: 43 selectable upgrade buttons

## Source gaps retained honestly

The supplied rules list **Pirates** and **Kroot** as host bodies but provide no rules, wargear, statistic changes or points modifiers. Both remain selectable, with a 0-point race modifier and a note identifying the missing source data. Astartes, Militia, Solar Auxilia, Mechanicum, Sisters of Silence, Custodes, Harlequins, Laer, Storm Scions, Nephilim, Megarachnids, Nurthene, Olamic Quietude, Exodites, Demiurg, Interex, Keylekid, Hrud, Jorgall, Slaugth, Barasonilash, Baalite / Fire Scorpion and Cythor Fiends now have explicit profiled inventories and fixed prices. Remaining unexpanded external factions use fixed tier-appropriate vehicle-component fallback prices. Tier access and hardpoints remain enforced without manual point-increment buttons.

Catalogue ID: `069890da-d908-533f-9a7b-8ba24b3e3773`  
Catalogue revision: `13`  
`Rangdan_Confederacy_HH1.catz` SHA-256: `f423d472638c078cbff5a2661b1e263e30e4ba6e9bf008cbb8349436d8927a92`  
`index.bsi` SHA-256: `161d7804503a3ab3723d1b6beb651e43b78c247ad44c7014a1b3221f770c237b`

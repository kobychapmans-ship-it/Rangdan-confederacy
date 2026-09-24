# Rangdan Confederacy — Revision 40

Selected complete HH1 Vehicle/Walker profiles now include the Host Level's meld minimums, plus +1 HP and +1 Attack (+2 Attacks for Legendary). Superior source characteristics remain unchanged. Missing/non-numeric WS, Strength, Initiative and Attacks are not invented. These meld values are already included in the displayed profile: do not add them again. The existing modular chassis profiles already include their meld baseline and are not charged or boosted twice.

Live source vehicle profiles are linked to the Osseivore organism, so the chosen shell receives unit-wide Statistic Modifications and that individual's Carrion Adaptation. Core Escape/Non-Melded hides that model's shell row; a specific HH1 shell suppresses the generic chassis row. The generic row appears only when the modular chassis itself is selected. The Lesser Dracosan baseline is BS3, Front13, Side12, Rear11, HP6 before purchased upgrades. Source weapon, transport and equipment options and prices are retained.

Collective Form is now a selectable Free Vehicle Upgrade submenu. Only the selected host faction's refund pool is available, and a refund still requires the matching paid non-weapon vehicle upgrade. The Legendary provider, shared-faction and one-upgrade limits remain. This is an editing submenu; roster output lists only selected entries, not every refund option.

External host vehicle/manual source-cost buttons have been removed. Existing Monstrous Mutation choices are under the organism's Non-Melded control, not among vehicle upgrades. No new mutation eligibility is granted to Lesser, Higher or Synarch. Native mutation effects remain on the organism and cannot modify a vehicle shell.

Existing costs, Enhanced Host Weapons and vehicle eligibility are retained. XML, reference, selection-condition and arithmetic regression checks are included in the project. These are local tests, not a mobile BattleScribe execution. After replacing all four repository files, update the catalogue; reselect affected forms/upgrade controls in an existing roster if cached selections persist.

# Rangdan Confederacy — Revision 39

Enhanced Host Weapons now changes Legendary Cerabvore weapon profiles, including pre-battle Maturation entries: Acidic Bite is Strength +1, AP4. Shared weapons on other units remain unchanged.

Complete HH1 vehicle options appear under Vehicle Form and require their matching Host Faction. Lesser: Troops/Dedicated Transport, not Heavy or Super-heavy; Moderate: Elites/Fast Attack/Heavy Support, not Heavy or Super-heavy; Higher: any non-Super-heavy; Legendary: any vehicle. Existing faction tiers remain. Complete vehicles replace the modular chassis and use their listed vehicle/upgrade costs without armoury surcharges. Configuration is unit-wide and prices scale with Osseivore count. Synarch uses Higher access. Source vehicle squadron options are restricted to one shell per organism. Dedicated transports remain part of the parent Osseivore unit for scoring/FOC.

Collective Form provides one non-weapon vehicle upgrade refund per Osseivore, requires a Legendary provider and a single Osseivore vehicle faction, and does not stack with additional providers. Buy the upgrade then select its matching refund. Unit-wide configuration refunds the same upgrade for each organism. Weapons and chassis are excluded.

Source: BSData/horus-heresy-1st-edition, archived commit 0a4c10da. Native army FOC restrictions are replaced with Rangdan eligibility; source mount/replacement and faction restrictions remain applicable. Mobile application rendering requires testing.

Replace all four GitHub repository files, then update BattleScribe data.

# Revision 38 — HH1 vehicle armoury inventory audit

Source: BSData/horus-heresy-1st-edition, commit 0a4c10da15f4ea40eea0932090fadafe3b90b696.

182 new tier-specific selectable entries; 160 existing item/tier matches retained with their existing costs and restrictions. Vehicle melee requires a Walker. New choices require an active chassis and are unavailable while Non-Melded. Shared Higher options also serve the Synarch.

## Added options

| Tier | Faction | Option | Points | Source vehicle |
|---|---|---|---:|---|
| Lesser | Solar Auxilia | Auxiliary Drive | 15 | Dracosan Armoured Transport |
| Lesser | Solar Auxilia | Dozer Blade | 10 | Dracosan Armoured Transport |
| Lesser | Solar Auxilia | Extra Armour | 10 | Saturnyne Pattern Aurox Armoured Transport |
| Lesser | Solar Auxilia | Flare Shield | 30 | Dracosan Armoured Transport |
| Lesser | Militia and Cults | Multi-laser | 15 | Arvus Lighter, Auxilia |
| Lesser | Militia and Cults | Autocannon | 15 | Arvus Lighter, Auxilia |
| Lesser | Militia and Cults | Lascannon | 25 | Arvus Lighter, Auxilia |
| Lesser | Militia and Cults | Twin-linked Heavy Bolter | 25 | Land Raider Proteus |
| Lesser | Militia and Cults | Twin-linked Lascannon | 25 | Land Raider Proteus |
| Moderate | Astartes | Auxiliary Drive | 15 | Land Raider Phobos (DT) |
| Moderate | Astartes | Dozer Blade | 10 | Land Raider Phobos (DT) |
| Moderate | Astartes | Extra Armour | 10 | Terrax Pattern Termite Assault Drill |
| Moderate | Astartes | Frag Assault Launchers | 15 | Anvillus Pattern Dreadclaw Drop Pod |
| Moderate | Astartes | Hunter-killer Missile | 10 | Dreadnought Talon, Legion |
| Moderate | Astartes | Smoke Launchers | 15 | Triaros Armoured Conveyor |
| Moderate | Astartes | Explorator Augury Web | 55 | Land Raider Proteus (DT) |
| Moderate | Astartes | Armoured Cockpit | 10 | Xiphon Interceptor |
| Moderate | Astartes | Cyclonic Melta Lance | 30 | Leviathan Siege Dreadnought |
| Moderate | Astartes | Leviathan Storm Cannon | 20 | Leviathan Siege Dreadnought |
| Moderate | Astartes | Grav-flux Bombard | 30 | Leviathan Siege Dreadnought |
| Moderate | Astartes | Twin-linked Lascannon | 20 | Mhara Gal Tainted Dreadnought |
| Moderate | Astartes | Laser Destroyer Array | 20 | Vindicator Tank, Legion |
| Moderate | Astartes | Laser Destroyer | 15 | Spartan Assault Tank (DT) |
| Moderate | Astartes | Aiolos Missile Launcher | 45 | Deredeo Pattern Dreadnought |
| Moderate | Astartes | Reaper Autocannon Battery | 20 | Fire Raptor Gunship, Legion |
| Moderate | Astartes | Heavy Conversion Beamer | 40 | Contemptor Dreadnought Talon |
| Moderate | Mechanicum | Anbaric Claw | 25 | Krios |
| Moderate | Mechanicum | Auxiliary Drive | 20 | Macrocarid Explorator |
| Moderate | Mechanicum | Blessed Autosimulacra | 15 | Triaros Armoured Conveyor |
| Moderate | Mechanicum | Explorator Augury Web | 60 | Macrocarid Explorator |
| Moderate | Mechanicum | Smoke Launchers | 10 | Triaros Armoured Conveyor |
| Moderate | Mechanicum | Autocannon | 15 | Crusade Fleet Arvus Lighter Orbital Shuttle |
| Moderate | Solar Auxilia | Armoured Cockpit | 25 | Auxilia Arvus Lighter Orbital Shuttle |
| Moderate | Solar Auxilia | Auxiliary Drive | 15 | Dracosan Armoured Transport |
| Moderate | Solar Auxilia | Dozer Blade | 10 | Dracosan Armoured Transport |
| Moderate | Solar Auxilia | Extra Armour | 10 | Saturnyne Pattern Aurox Armoured Transport |
| Moderate | Solar Auxilia | Flare Shield | 25 | Auxilia Thunderbolt Heavy Fighter |
| Moderate | Solar Auxilia | Hunter-killer missile | 15 | Auxilia Leman Russ Annihilator |
| Moderate | Solar Auxilia | Searchlight | 11 | Auxilia Arvus Lighter Orbital Shuttle |
| Moderate | Solar Auxilia | Multi-Laser | 20 | Saturnyne Pattern Carnodon Strike Squadron |
| Moderate | Solar Auxilia | Pintle-mounted Heavy bolter | 20 | Auxilia Basilisk |
| Moderate | Solar Auxilia | Twin-Linked Lascannon | 30 | Saturnyne Pattern Carnodon Strike Squadron |
| Moderate | Militia and Cults | Dozer blade | 15 | Leman Russ Annihilator |
| Moderate | Militia and Cults | Extra armour | 15 | Leman Russ Annihilator |
| Moderate | Militia and Cults | Armoured Ceramite | 30 | Malcador Heavy Tank, Auxilia |
| Moderate | Militia and Cults | Hunter-killer Missile | 10 | Auxilia Sentinels |
| Moderate | Militia and Cults | Auxiliary Drive | 20 | Malcador Heavy Tank, Auxilia |
| Moderate | Militia and Cults | Heavy Stubber | 12 | Carnodon Strike Squadron |
| Moderate | Militia and Cults | Heavy flamer | 20 | Leman Russ Annihilator |
| Moderate | Militia and Cults | Multi-laser | 15 | Arvus Lighter, Auxilia |
| Moderate | Militia and Cults | Autocannon | 10 | Auxilia Sentinels |
| Moderate | Militia and Cults | Lascannon | 15 | Auxilia Sentinels |
| Moderate | Militia and Cults | Multi-melta | 15 | Auxilia Sentinels |
| Moderate | Militia and Cults | Twin-linked Heavy Bolter | 25 | Land Raider Proteus |
| Moderate | Militia and Cults | Twin-linked Lascannon | 25 | Land Raider Proteus |
| Moderate | Sister of Silence | Armoured Ceramite | 25 | Sisters of Silence Kharon Pattern Acquisitor |
| Moderate | Sister of Silence | Extra Armour | 10 | Sisters of Silence Kharon Pattern Acquisitor |
| Moderate | Craftworld Aeldari | Star Engines | 20 | Vyper Squadron |
| Moderate | Craftworld Aeldari | Spirit Stones | 15 | Vyper Squadron |
| Moderate | Chaos Daemons | Phlegm Bombardment | 40 | Soul Grinder of Chaos |
| Moderate | Chaos Daemons | Warp Gaze | 35 | Soul Grinder of Chaos |
| Moderate | Chaos Daemons | Baleful Torrent | 30 | Soul Grinder of Chaos |
| Higher | Astartes | Auxiliary Drive | 15 | Land Raider Phobos (DT) |
| Higher | Astartes | Dozer Blade | 10 | Land Raider Phobos (DT) |
| Higher | Astartes | Extra Armour | 10 | Terrax Pattern Termite Assault Drill |
| Higher | Astartes | Frag Assault Launchers | 15 | Anvillus Pattern Dreadclaw Drop Pod |
| Higher | Astartes | Hunter-killer Missile | 10 | Dreadnought Talon, Legion |
| Higher | Astartes | Smoke Launchers | 15 | Triaros Armoured Conveyor |
| Higher | Astartes | Explorator Augury Web | 55 | Land Raider Proteus (DT) |
| Higher | Astartes | Armoured Cockpit | 10 | Xiphon Interceptor |
| Higher | Astartes | Cyclonic Melta Lance | 30 | Leviathan Siege Dreadnought |
| Higher | Astartes | Leviathan Storm Cannon | 20 | Leviathan Siege Dreadnought |
| Higher | Astartes | Grav-flux Bombard | 30 | Leviathan Siege Dreadnought |
| Higher | Astartes | Twin-linked Lascannon | 20 | Mhara Gal Tainted Dreadnought |
| Higher | Astartes | Laser Destroyer Array | 20 | Vindicator Tank, Legion |
| Higher | Astartes | Laser Destroyer | 15 | Spartan Assault Tank (DT) |
| Higher | Astartes | Aiolos Missile Launcher | 45 | Deredeo Pattern Dreadnought |
| Higher | Astartes | Reaper Autocannon Battery | 20 | Fire Raptor Gunship, Legion |
| Higher | Astartes | Heavy Conversion Beamer | 40 | Contemptor Dreadnought Talon |
| Higher | Mechanicum | Anbaric Claw | 25 | Krios |
| Higher | Mechanicum | Auxiliary Drive | 20 | Macrocarid Explorator |
| Higher | Mechanicum | Blessed Autosimulacra | 15 | Triaros Armoured Conveyor |
| Higher | Mechanicum | Explorator Augury Web | 60 | Macrocarid Explorator |
| Higher | Mechanicum | Smoke Launchers | 10 | Triaros Armoured Conveyor |
| Higher | Mechanicum | Autocannon | 15 | Crusade Fleet Arvus Lighter Orbital Shuttle |
| Higher | Solar Auxilia | Armoured Cockpit | 25 | Auxilia Arvus Lighter Orbital Shuttle |
| Higher | Solar Auxilia | Auxiliary Drive | 15 | Dracosan Armoured Transport |
| Higher | Solar Auxilia | Dozer Blade | 10 | Dracosan Armoured Transport |
| Higher | Solar Auxilia | Extra Armour | 10 | Saturnyne Pattern Aurox Armoured Transport |
| Higher | Solar Auxilia | Flare Shield | 25 | Auxilia Thunderbolt Heavy Fighter |
| Higher | Solar Auxilia | Hunter-killer missile | 15 | Auxilia Leman Russ Annihilator |
| Higher | Solar Auxilia | Searchlight | 11 | Auxilia Arvus Lighter Orbital Shuttle |
| Higher | Solar Auxilia | Multi-Laser | 20 | Saturnyne Pattern Carnodon Strike Squadron |
| Higher | Solar Auxilia | Pintle-mounted Heavy bolter | 20 | Auxilia Basilisk |
| Higher | Solar Auxilia | Twin-Linked Lascannon | 30 | Saturnyne Pattern Carnodon Strike Squadron |
| Higher | Militia and Cults | Dozer blade | 15 | Leman Russ Annihilator |
| Higher | Militia and Cults | Extra armour | 15 | Leman Russ Annihilator |
| Higher | Militia and Cults | Armoured Ceramite | 30 | Malcador Heavy Tank, Auxilia |
| Higher | Militia and Cults | Hunter-killer Missile | 10 | Auxilia Sentinels |
| Higher | Militia and Cults | Auxiliary Drive | 20 | Malcador Heavy Tank, Auxilia |
| Higher | Militia and Cults | Heavy Stubber | 12 | Carnodon Strike Squadron |
| Higher | Militia and Cults | Heavy flamer | 20 | Leman Russ Annihilator |
| Higher | Militia and Cults | Multi-laser | 15 | Arvus Lighter, Auxilia |
| Higher | Militia and Cults | Autocannon | 10 | Auxilia Sentinels |
| Higher | Militia and Cults | Lascannon | 15 | Auxilia Sentinels |
| Higher | Militia and Cults | Multi-melta | 15 | Auxilia Sentinels |
| Higher | Militia and Cults | Twin-linked Heavy Bolter | 25 | Land Raider Proteus |
| Higher | Militia and Cults | Twin-linked Lascannon | 25 | Land Raider Proteus |
| Higher | Custodes | Armoured Ceramite | 25 | Legio Custodes Coronus Grav-Carrier |
| Higher | Sister of Silence | Armoured Ceramite | 25 | Sisters of Silence Kharon Pattern Acquisitor |
| Higher | Custodes | Extra Armour | 10 | Legio Custodes Coronus Grav-Carrier |
| Higher | Sister of Silence | Extra Armour | 10 | Sisters of Silence Kharon Pattern Acquisitor |
| Higher | Custodes | Arachnus Storm Cannon | 50 | Legio Custodes Telemon Heavy Dreadnought |
| Higher | Craftworld Aeldari | Star Engines | 20 | Vyper Squadron |
| Higher | Craftworld Aeldari | Spirit Stones | 15 | Vyper Squadron |
| Higher | Chaos Daemons | Phlegm Bombardment | 40 | Soul Grinder of Chaos |
| Higher | Chaos Daemons | Warp Gaze | 35 | Soul Grinder of Chaos |
| Higher | Chaos Daemons | Baleful Torrent | 30 | Soul Grinder of Chaos |
| Legendary | Astartes | Armoured Ceramite | 50 | Fellblade, Legion |
| Legendary | Astartes | Auxiliary Drive | 15 | Land Raider Phobos (DT) |
| Legendary | Astartes | Dozer Blade | 10 | Land Raider Phobos (DT) |
| Legendary | Astartes | Extra Armour | 10 | Terrax Pattern Termite Assault Drill |
| Legendary | Astartes | Flare Shield | 45 | Thunderbolt Heavy Fighter |
| Legendary | Astartes | Frag Assault Launchers | 15 | Anvillus Pattern Dreadclaw Drop Pod |
| Legendary | Astartes | Hunter-killer Missile | 10 | Dreadnought Talon, Legion |
| Legendary | Astartes | Smoke Launchers | 15 | Triaros Armoured Conveyor |
| Legendary | Astartes | Explorator Augury Web | 55 | Land Raider Proteus (DT) |
| Legendary | Astartes | Armoured Cockpit | 10 | Xiphon Interceptor |
| Legendary | Astartes | Cyclonic Melta Lance | 30 | Leviathan Siege Dreadnought |
| Legendary | Astartes | Leviathan Storm Cannon | 20 | Leviathan Siege Dreadnought |
| Legendary | Astartes | Grav-flux Bombard | 30 | Leviathan Siege Dreadnought |
| Legendary | Astartes | Twin-linked Lascannon | 20 | Mhara Gal Tainted Dreadnought |
| Legendary | Astartes | Laser Destroyer Array | 20 | Vindicator Tank, Legion |
| Legendary | Astartes | Laser Destroyer | 15 | Spartan Assault Tank (DT) |
| Legendary | Astartes | Aiolos Missile Launcher | 45 | Deredeo Pattern Dreadnought |
| Legendary | Astartes | Reaper Autocannon Battery | 20 | Fire Raptor Gunship, Legion |
| Legendary | Astartes | Heavy Conversion Beamer | 40 | Contemptor Dreadnought Talon |
| Legendary | Mechanicum | Anbaric Claw | 25 | Krios |
| Legendary | Mechanicum | Auxiliary Drive | 20 | Macrocarid Explorator |
| Legendary | Mechanicum | Blessed Autosimulacra | 15 | Triaros Armoured Conveyor |
| Legendary | Mechanicum | Explorator Augury Web | 60 | Macrocarid Explorator |
| Legendary | Mechanicum | Smoke Launchers | 10 | Triaros Armoured Conveyor |
| Legendary | Mechanicum | Autocannon | 15 | Crusade Fleet Arvus Lighter Orbital Shuttle |
| Legendary | Mechanicum | Bio-Corrosive Rounds | 15 | Questoris Knight Armiger Talon |
| Legendary | Mechanicum | Heavy Stubber | 10 | Questoris Knight Armiger Talon |
| Legendary | Mechanicum | Canflagration Cannon | 35 | Questoris Knight Dominus |
| Legendary | Mechanicum | Plasma Decimator | 60 | Questoris Knight Dominus |
| Legendary | Mechanicum | Thundercoil Harpoon | 55 | Questoris Knight Dominus |
| Legendary | Mechanicum | Volcano Lance | 50 | Questoris Knight Dominus |
| Legendary | Solar Auxilia | Armoured Cockpit | 25 | Auxilia Arvus Lighter Orbital Shuttle |
| Legendary | Solar Auxilia | Auxiliary Drive | 15 | Dracosan Armoured Transport |
| Legendary | Solar Auxilia | Dozer Blade | 10 | Dracosan Armoured Transport |
| Legendary | Solar Auxilia | Extra Armour | 10 | Saturnyne Pattern Aurox Armoured Transport |
| Legendary | Solar Auxilia | Flare Shield | 25 | Auxilia Thunderbolt Heavy Fighter |
| Legendary | Solar Auxilia | Hunter-killer missile | 15 | Auxilia Leman Russ Annihilator |
| Legendary | Solar Auxilia | Searchlight | 11 | Auxilia Arvus Lighter Orbital Shuttle |
| Legendary | Solar Auxilia | Multi-Laser | 20 | Saturnyne Pattern Carnodon Strike Squadron |
| Legendary | Solar Auxilia | Pintle-mounted Heavy bolter | 20 | Auxilia Basilisk |
| Legendary | Solar Auxilia | Twin-Linked Lascannon | 30 | Saturnyne Pattern Carnodon Strike Squadron |
| Legendary | Militia and Cults | Dozer blade | 15 | Leman Russ Annihilator |
| Legendary | Militia and Cults | Extra armour | 15 | Leman Russ Annihilator |
| Legendary | Militia and Cults | Armoured Ceramite | 30 | Gorgon Heavy Transporter, Auxilia |
| Legendary | Militia and Cults | Hunter Killer Missile | 10 | Gorgon Heavy Transporter, Auxilia |
| Legendary | Militia and Cults | Auxiliary Drive | 20 | Malcador Heavy Tank, Auxilia |
| Legendary | Militia and Cults | Heavy Stubber | 12 | Carnodon Strike Squadron |
| Legendary | Militia and Cults | Heavy flamer | 20 | Leman Russ Annihilator |
| Legendary | Militia and Cults | Multi-laser | 15 | Arvus Lighter, Auxilia |
| Legendary | Militia and Cults | Autocannon | 10 | Auxilia Sentinels |
| Legendary | Militia and Cults | Lascannon | 15 | Auxilia Sentinels |
| Legendary | Militia and Cults | Multi-melta | 15 | Auxilia Sentinels |
| Legendary | Militia and Cults | Twin-linked Heavy Bolter | 25 | Land Raider Proteus |
| Legendary | Militia and Cults | Twin-linked Lascannon | 25 | Land Raider Proteus |
| Legendary | Custodes | Armoured Ceramite | 25 | Legio Custodes Coronus Grav-Carrier |
| Legendary | Sister of Silence | Armoured Ceramite | 25 | Sisters of Silence Kharon Pattern Acquisitor |
| Legendary | Custodes | Extra Armour | 10 | Legio Custodes Coronus Grav-Carrier |
| Legendary | Sister of Silence | Extra Armour | 10 | Sisters of Silence Kharon Pattern Acquisitor |
| Legendary | Custodes | Arachnus Storm Cannon | 50 | Legio Custodes Telemon Heavy Dreadnought |
| Legendary | Craftworld Aeldari | Star Engines | 20 | Vyper Squadron |
| Legendary | Craftworld Aeldari | Spirit Stones | 15 | Vyper Squadron |
| Legendary | Chaos Daemons | Phlegm Bombardment | 40 | Soul Grinder of Chaos |
| Legendary | Chaos Daemons | Warp Gaze | 35 | Soul Grinder of Chaos |
| Legendary | Chaos Daemons | Baleful Torrent | 30 | Soul Grinder of Chaos |

## Not added — source or price required

These entries have not been assigned invented prices or made free. Bundled gear is not a standalone purchase. Existing matching options are preserved. Some attachment names denote families rather than exact source options.

- **Legiones — Searchlight**: No exact vehicle-option match in HH1 source.
- **Legiones — Machine Spirit / Power of the Machine Spirit**: No exact vehicle-option match in HH1 source.
- **Legiones — Flare/Chaff Launchers (Flyers)**: No exact vehicle-option match in HH1 source.
- **Legiones — Twin-linked heavy bolter**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Legiones — Twin-linked heavy flamer**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Legiones — Siege drill**: No exact vehicle-option match in HH1 source.
- **Legiones — Siege claw**: No exact vehicle-option match in HH1 source.
- **Legiones — Twin-linked multi-melta**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Legiones — Dreadnought close combat weapon**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Legiones — Accelerator autocannon**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Legiones — Neutron beam laser**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Legiones — Quad lascannon**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Legiones — Twin-linked autocannon**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Legiones — Demolisher cannon**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Legiones — Battle cannon**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Legiones — Combi-weapon**: No exact vehicle-option match in HH1 source.
- **Legiones — Earthshaker cannon**: No exact vehicle-option match in HH1 source.
- **Legiones — Havoc launcher**: No exact vehicle-option match in HH1 source.
- **Legiones — Medusa siege gun**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Legiones — Whirlwind missile launcher**: No exact vehicle-option match in HH1 source.
- **Legiones — Quad mortar**: No exact vehicle-option match in HH1 source.
- **Legiones — Twin-linked volkite culverin**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Legiones — Arachnus pattern heavy lascannon battery**: No exact vehicle-option match in HH1 source.
- **Legiones — Volkite falconet**: No exact vehicle-option match in HH1 source.
- **Legiones — Avenger bolt cannon**: No exact vehicle-option match in HH1 source.
- **Legiones — Conversion beamer**: No exact vehicle-option match in HH1 source.
- **Legiones — Hellstrike missile**: No exact vehicle-option match in HH1 source.
- **Legiones — Tempest rockets**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Legiones — Kheres assault cannon**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Legiones — Kraken penetrator missiles**: No exact vehicle-option match in HH1 source.
- **Taghmata — Armoured Ceramite**: No exact vehicle-option match in HH1 source.
- **Taghmata — Flare/Chaff Launchers**: No exact vehicle-option match in HH1 source.
- **Taghmata — Infra-vision**: No exact vehicle-option match in HH1 source.
- **Taghmata — Searchlight**: No exact vehicle-option match in HH1 source.
- **Taghmata — Atomantic Shielding**: No exact vehicle-option match in HH1 source.
- **Taghmata — Mauler bolt cannon**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Taghmata — Sollex heavy las**: No exact vehicle-option match in HH1 source.
- **Taghmata — Mauler bolt cannon (twin-linked)**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Taghmata — Volkite culverin**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Taghmata — Multi-melta**: No exact vehicle-option match in HH1 source.
- **Taghmata — Volkite chieorovile**: No exact vehicle-option match in HH1 source.
- **Taghmata — Darkfire cannon**: No exact vehicle-option match in HH1 source.
- **Taghmata — Photon thruster**: No exact vehicle-option match in HH1 source.
- **Taghmata — Heavy conversion beamer**: No exact vehicle-option match in HH1 source.
- **Taghmata — Irad-cleanser**: No exact vehicle-option match in HH1 source.
- **Taghmata — Siege wrecker**: No exact vehicle-option match in HH1 source.
- **Taghmata — Irad engine**: No exact vehicle-option match in HH1 source.
- **Taghmata — Macrostubber**: No exact vehicle-option match in HH1 source.
- **Taghmata — Maxima bolter**: No exact vehicle-option match in HH1 source.
- **Taghmata — Graviton ram**: No exact vehicle-option match in HH1 source.
- **Taghmata — Rotor cannon**: No exact vehicle-option match in HH1 source.
- **Taghmata — Lightning gun**: No exact vehicle-option match in HH1 source.
- **Taghmata — Lascannon**: No exact vehicle-option match in HH1 source.
- **Taghmata — Plasma fusil**: No exact vehicle-option match in HH1 source.
- **Taghmata — Heavy bolter**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Taghmata — Plasma mortar**: No exact vehicle-option match in HH1 source.
- **Taghmata — Heavy flamer**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Questoris — Ionic Flare Shield**: No exact vehicle-option match in HH1 source.
- **Questoris — Armoured Ceramite (where listed)**: No exact vehicle-option match in HH1 source.
- **Questoris — Flare/Chaff Launchers (where listed)**: No exact vehicle-option match in HH1 source.
- **Questoris — Questoris battle cannon**: No exact vehicle-option match in HH1 source.
- **Questoris — Volkite chieorovile**: No exact vehicle-option match in HH1 source.
- **Questoris — Rapid-fire battle cannon**: No exact vehicle-option match in HH1 source.
- **Questoris — Thermal cannon**: No exact vehicle-option match in HH1 source.
- **Questoris — Shock lance**: No exact vehicle-option match in HH1 source.
- **Questoris — Avenger gatling cannon**: No exact vehicle-option match in HH1 source.
- **Questoris — Acheron flamestorm cannon**: No exact vehicle-option match in HH1 source.
- **Questoris — Reaper chainsword**: No exact vehicle-option match in HH1 source.
- **Questoris — Reaper chainfist**: No exact vehicle-option match in HH1 source.
- **Questoris — Thunderstrike gauntlet**: No exact vehicle-option match in HH1 source.
- **Questoris — Castigator bolt cannon**: No exact vehicle-option match in HH1 source.
- **Questoris — Tempest warblade**: No exact vehicle-option match in HH1 source.
- **Questoris — Atrapos lascutter**: No exact vehicle-option match in HH1 source.
- **Questoris — Icarus autocannon array**: No exact vehicle-option match in HH1 source.
- **Questoris — Graviton singularity cannon**: No exact vehicle-option match in HH1 source.
- **Questoris — Ironstorm missile pod**: No exact vehicle-option match in HH1 source.
- **Questoris — Stormspear rocket pod**: No exact vehicle-option match in HH1 source.
- **Questoris — Phased plasma-fusil**: No exact vehicle-option match in HH1 source.
- **Questoris — Hekaton siege claw**: No exact vehicle-option match in HH1 source.
- **Questoris — Magna lascannon**: No exact vehicle-option match in HH1 source.
- **Questoris — Rad cleanser**: No exact vehicle-option match in HH1 source.
- **Questoris — Helios defence missiles**: No exact vehicle-option match in HH1 source.
- **Solar — Armoured Ceramite**: No exact vehicle-option match in HH1 source.
- **Solar — Explorator Adaption**: No exact vehicle-option match in HH1 source.
- **Solar — Flare/Chaff Launchers**: No exact vehicle-option match in HH1 source.
- **Solar — Smoke Launchers**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Solar — Volkite macro-saker**: No exact vehicle-option match in HH1 source.
- **Solar — Neutron beam laser**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Solar — Heavy conversion beamer**: No exact vehicle-option match in HH1 source.
- **Solar — Mortar battery**: No exact vehicle-option match in HH1 source.
- **Solar — Battle cannon**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Solar — Stormsword siege cannon**: No exact vehicle-option match in HH1 source.
- **Solar — Volcano cannon**: No exact vehicle-option match in HH1 source.
- **Solar — Executioner plasma cannon**: No exact vehicle-option match in HH1 source.
- **Solar — Melta cannon**: No exact vehicle-option match in HH1 source.
- **Solar — Gravis lascannon**: No exact vehicle-option match in HH1 source.
- **Solar — Laser destroyer array**: No exact vehicle-option match in HH1 source.
- **Militia — Searchlight**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Militia — Smoke Launchers**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Militia — Executioner plasma cannon**: No exact vehicle-option match in HH1 source.
- **Militia — Eradicator nova cannon**: No exact vehicle-option match in HH1 source.
- **Militia — Heavy mortar**: No exact vehicle-option match in HH1 source.
- **Militia — Quad launcher**: No exact vehicle-option match in HH1 source.
- **Militia — Battle cannon**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Talons — Armoured Cockpit**: No exact vehicle-option match in HH1 source.
- **Talons — Eclipse Shield**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Talons — Flare Shield**: No exact vehicle-option match in HH1 source.
- **Talons — Macro Arae-shrikes**: No exact vehicle-option match in HH1 source.
- **Talons — Machine Spirit**: No exact vehicle-option match in HH1 source.
- **Talons — Capture-grid / vehicle-specific defensive systems**: No exact vehicle-option match in HH1 source.
- **Talons — Hellion-pattern heavy cannon array**: No exact vehicle-option match in HH1 source.
- **Talons — Iliastus accelerator cannon**: No exact vehicle-option match in HH1 source.
- **Talons — Vratine missile launcher**: No exact vehicle-option match in HH1 source.
- **Talons — Spiculus bolt launcher**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Talons — Spiculus heavy bolt launcher**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Talons — Corve las-pulsar**: No exact vehicle-option match in HH1 source.
- **Talons — Iliastus accelerator culverin**: No exact vehicle-option match in HH1 source.
- **Talons — Magna blaze cannon**: No exact vehicle-option match in HH1 source.
- **Talons — Adrathic destructor**: No exact vehicle-option match in HH1 source.
- **Talons — Twin-linked multi-melta**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Talons — Infernus incinerator**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Talons — Twin-linked heavy bolter**: No exact vehicle-option match in HH1 source.
- **Craftworld — Shuriken cannon**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Craftworld — Distortion cannon**: No exact vehicle-option match in HH1 source.
- **Craftworld — Heavy D-scythe**: No exact vehicle-option match in HH1 source.
- **Craftworld — Scatter laser**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Craftworld — Bright lance**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Craftworld — Vibro cannon**: No exact vehicle-option match in HH1 source.
- **Craftworld — Starcannon**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Craftworld — Shadow weaver**: No exact vehicle-option match in HH1 source.
- **Craftworld — Fusion gun / fusion weapon**: No exact vehicle-option match in HH1 source.
- **Craftworld — Pulse laser**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Craftworld — Laser lance**: No exact vehicle-option match in HH1 source.
- **Craftworld — Shuriken catapult**: No exact vehicle-option match in HH1 source.
- **Craftworld — D-cannon**: No exact vehicle-option match in HH1 source.
- **Necron — Living Metal**: No exact vehicle-option match in HH1 source.
- **Necron — Quantum Shielding (where listed)**: No exact vehicle-option match in HH1 source.
- **Necron — Symbiotic Repair / self-repair rules where listed**: No exact vehicle-option match in HH1 source.
- **Necron — Vehicle-specific teleportation and phase systems**: No exact vehicle-option match in HH1 source.
- **Necron — Gauss cannon**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Necron — Particle whip**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Necron — Heavy gauss cannon**: No exact vehicle-option match in HH1 source.
- **Necron — Heat ray**: No exact vehicle-option match in HH1 source.
- **Necron — Gauss flayer array**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Necron — Heavy death ray**: No exact vehicle-option match in HH1 source.
- **Necron — Gauss flux arc**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Necron — Death ray**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Necron — Tesla cannon**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Necron — Doomsday cannon**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Necron — Twin-linked tesla destructor**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Necron — Transdimensional beamer**: No exact vehicle-option match in HH1 source.
- **Necron — Particle beamer**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Necron — Tachyon arrow**: No exact vehicle-option match in HH1 source.
- **Necron — Particle shredder**: No exact vehicle-option match in HH1 source.
- **Necron — Warscythe / vehicle-mounted melee systems**: No exact vehicle-option match in HH1 source.
- **Chaos Daemons — Daemon / Daemonic vehicle rules where applicable**: No exact vehicle-option match in HH1 source.
- **Chaos Daemons — Daemonic Resilience and vehicle-specific gifts where listed**: No exact vehicle-option match in HH1 source.
- **Chaos Daemons — Harvester cannon**: No exact vehicle-option match in HH1 source.
- **Chaos Daemons — Iron claw / daemon-engine close-combat weapons**: No eligible published standalone/upgrade price; requires explicit Host Facsimile Cost or source clarification.
- **Chaos Daemons — Tongue / maw attacks where represented as weapon profiles**: No exact vehicle-option match in HH1 source.

Agents, Dark Compliance, Mournival, Varangian and Ruinstorm sections supply no discrete item list in the attachment; their parent/entry-specific pools remain unchanged. Questoris additions are under Legendary Mechanicum vehicle armoury. No new Necron pool is created without eligible priced options. No mobile BattleScribe execution was available.


## Installation

Replace all four repository files on GitHub and update BattleScribe data. Existing chassis prices, Walking Meat restrictions and previous revisions are preserved.

# Rangdan Confederacy — revision 37

Walking Meat now requires exactly one Osseivore organism in the unit and a Non-Melded state (explicitly marked, or no chassis selected). Monstrous mutations are not eligible. The attached Levy is a separate unit and does not invalidate the one-Osseivore requirement.

Purchased melee weapons require an active Walker chassis: this includes native replacements, Ablative Morphology, Titan weapons and every Host Faction armoury. Mixed shooting/melee packages are Walker-only. Tanks, Skimmers, Flyers and Non-Melded/Monstrous organism forms cannot buy these melee options. Existing grade, faction and Titan restrictions remain; ranged choices retain their existing access rules. Intrinsic default Liquid Bone Tendrils are not removed by this purchase restriction.

Host-armoury weapon options retain the vehicle-only pools and now consistently display a Vehicle Weapon tag. No Cerabvore or Monstrous Osseicerabvore pools are changed. Shared options carry these restrictions to the Synarch and Carrion Forge Moderate Troops.

Revision 36 chassis costs and all other prices/stat profiles are retained. Replace all four repository files and refresh BattleScribe. Local selection and archive validation is supplied; mobile application testing is still required.

# Rangdan Confederacy — revision 36

Chassis options now carry explicit base prices instead of zero prices calculated entirely through repeats. Unit-wide chassis selection still charges every model, using explicit total prices for two- and three-model units.

Per model: Lesser +10; Moderate +40; Higher +150; Legendary +300 points. Moderate Carrion Forge Troops use the same +40 chassis. The Synarch uses the shared Higher +150 chassis, for 80 + 150 = 230 points before other upgrades. Non-Melded models with no selected chassis pay no chassis charge.

Chassis IDs, profiles, weapons, other upgrades, Carrion Forge rules and Puppet Masters are preserved. Replace the four repository files and refresh BattleScribe. Local cost and structural tests pass; the mobile application is not directly tested.

# Rangdan Confederacy — revision 35

Adds Carrion Forge Detachment and Osseivore Synarch (HQ, 80 points). The new force has 1–3 HQ, 2–8 Troops, 0–3 Elites, 0–3 Fast Attack, 0–4 Heavy Support and 0–1 Lords of War, with additional Osseivore compulsory-choice checks. Moderate Osseivore Hosts — Carrion Forge Troops is a separate Troops selection available only in this detachment. Normal Moderate Elites remain available.

Synarch options link the same Higher Osseivore model/option definitions rather than maintaining another armoury copy. Its command identity changes only its own base cost, unit size and Non-Melded profile. It has no starting Tendrils or other wargear. Select Warlord to display Machine-Sovereign; Master of the Carrion Forge appears only in that force.

Carrion Evolution controls are per model, one state/adaptation maximum. Leave them empty during army creation. After Core Escape mark Available; on subsequent legal Living Forge choose one adaptation. Core and vehicle profiles display appropriate changes. AV/HP are dormant Non-Melded. Adaptations are not in Puppet Masters pools. Split model selections when individual adaptations differ; purchased host/chassis choices remain unit-wide as before.

The No Force Org Slot section contains optional Carrion rules and battlefield records, one active Imperative, and three infection records. Timings, ranges, targets, legal battlefield transfers, casualties and newly spawned organisms are tabletop state, not automatically simulated by BattleScribe. No army-building purchase is added for spawned organisms.

The supplied infection rule requires exactly three enemy vehicles; no alternative is invented for an opponent with fewer than three. Its explicit Explodes exception is retained.

Replace the four files in the GitHub repository root and refresh BattleScribe. Structural and scenario checks accompany this build; the mobile app has not been directly tested.

# Rangdan Confederacy — revision 34

Puppet Masters free upgrades are now costed controls. Select normal Host Strengthening / Osseivore statistic upgrades, then select matching claims under Puppet Masters — Free Upgrade Allocation. Each claim refunds its exact cost, including per-model scaling. The original choice remains responsible for stats and normal caps.

Allowance: one free increment per starting Legendary Cerabvore, including pre-battle Maturation selections. Claims share a total allowance and cannot exceed purchased increments. Mixed host-faction armies and recipients without a host are ineligible.

Army creation only. Maturation, Collective Body, Mass Spawning, Host Breeder and other models created after the battle begins receive no free upgrades and cannot create new grants. A zero-point Created after battle began marker disables the corresponding allocation and removes a newly created Legendary from the provider count. For mixed starting/created models, use separate entries. Keep the original army roster as the starting allocation record: these are army-building controls, not automatic casualty or real-time battle tracking.

Normal unit prices, stat modifiers, caps, host options, Maturation and Titan access are retained. Mobile application testing is still required; XML, price and eligibility scenarios are validated separately.

# Rangdan Confederacy — revision 33

Maturation of the Host is in the common Rangdan rules section. Army-building Maturation entries appear in the original grade’s Force Organisation category. Each resulting model includes all contributing organisms’ base costs plus its own base cost. Destination-grade unit sizes and upgrade options apply; contributors do not also appear as living roster models.

Direct paths per resulting model before options:
- Lesser → Moderate: 60 points (Troops).
- Lesser → Higher: 200 points (Troops).
- Moderate → Higher: 80 points (Elites).
- Higher → Legendary: 350 points (HQ).

Chained paths include the intermediate organisms’ base costs:
- Lesser → Moderate → Higher: 230 points (Troops).
- Lesser → Higher → Legendary: 800 points (Troops).
- Moderate → Higher → Legendary: 440 points (Elites).
- Lesser → Moderate → Higher → Legendary: 890 points (Troops).

Battlefield Maturation costs no additional points. Resolve it after the eligible Assault victory, using Non-Melded contributors. Track the resulting models on the tabletop; BattleScribe does not automatically process casualties or transformations during play. If any contributor has spent Collective Body, set the resulting model’s tracker to Used; otherwise it retains one use appropriate to its new grade.

The revision32 Titan pools and form restrictions are retained. Replace all four repository files and refresh BattleScribe. Structural and scenario validation is provided; the mobile application is not directly tested.

# Rangdan Confederacy — revision 32

- Collective Body: once per model per battle in the Sleeper Host Detachment. Additional Non-Melded Lesser Cerabvores: Lesser 1; Moderate D3; Higher D6+2; Legendary 2D6+3.
- Configuration rules note plus independent numbered Available / Used indicators for each eligible model (including the Moderate leader). Only slots for the selected model count appear. These are manual battle-state indicators; reset before each new battle.
- Legendary Osseivore: complete six-weapon normal Titan pool and matching six-weapon Ablative pool (+10 points per selected Ablative weapon). The normal pool follows the Legendary Cerabvore six-selection limit; Ablative remains one weapon.
- Titan eligibility: actual melded Super-heavy chassis, Gargantuan or Flying Gargantuan organism form. Ordinary Non-Melded Infantry remains ineligible; an intrinsic Gargantuan mutation qualifies without a vehicle shell. Imported faction Titan weapons keep their faction/price restrictions.
- Validated XML, archive metadata, prices, weapon coverage and eligibility scenarios. Mobile BattleScribe application not available for direct testing.

Replace all four repository files and refresh BattleScribe data.

# Rangdan Confederacy — revision 31

- Free stock equipment now lives in the corresponding Host Armoury. Each item defaults to equipped; select Replaced / not equipped to remove its profiles and save effects.
- Indomitus, Cataphractii and Tartaros Terminator armour cost 35 points, using the archived HH1 Centurion/Praetor price as explicitly requested. Replace stock Power Armour before selecting a Terminator pattern.
- Anrathe draft: racial rules, stock equipment, doctrine selections, published-cost personal and vehicle equipment. Existing Rangdan body prices and characteristic baselines are preserved.
- Xenos imports checked against upstream catalogue revision 6. No inferred prices for unpriced powerful weapons, relics or unique gear.
- Armour and invulnerable saves combine across selected equipment, with a 2+/2++ limit. Conditional battlefield saves remain in their equipment rules.
- Validation covers catalogue references, default equipment, selection predicates, statline scenarios and nested archives. Not tested in the BattleScribe mobile application.

Upload all four files to the repository root, then refresh BattleScribe data.

# Rangdan Confederacy — revision 30

- Militia Provenance is one mandatory, free Configuration choice shared by every Militia Host Body.
- Ablative Weapon Morphology now opens one real next-grade Rangdan weapon choice; its +10-point surcharge is included in that weapon.
- Stock Host Body armour and unconditional save-affecting wargear now update the live Save characteristic, including Militia Provenance interactions, capped at 2+/2++.

# Rangdan Confederacy — revision 29

- Corrected selected Host Body stock-wargear visibility for every faction.
- Added one published Militia Provenance of War per Militia Host Body.
- Added the Rangdan psychic-discipline reference to Configuration.
- Removed source Relics/Artefacts/Heirlooms/Treasures from Host Armouries.
- Removed manual statline/save controls and ordinary Cerabvore external fallback wargear.
- Natural Weapons are labelled for Non-Melded use; Osseivore Walking Meat now requires Non-Melded state.
- Clarified that body/provenance/wargear effects may exceed Strengthening tier caps, to universal 10 and 2+/2++ limits.

# Rangdan Confederacy — revision 28

Presentation cleanup: duplicate equivalent Host Body wargear profiles removed;
explicit selected-body/form Unit names; shared Rangdan melding and organism
rules consolidated into a zero-point Configuration (non-Force-Org) entry.
Individual unit, weapon, selected-body and upgrade rules remain on their entries.
All revision 27 prices, characteristic values and statistical modifiers retained.

Replace all four repository files and refresh BattleScribe data. Existing rosters
may need the Rangdan Melding and Organism Rules Configuration entry added once.
Archive/XML validation is automated; rendering in the mobile app needs checking.

## Retained revision 27 documentation and pricing review

# Rangdan Confederacy — Revision 27

Host Armoury Pricing: use a published standalone or upgrade cost plus the lowest applicable source-role surcharge within the correct faction: Troops +5; Fast Attack +5; Elites +10; Heavy Support +10; HQ +15; Lords of War +25 points. Unpriced common personal equipment costs 5 points total, without an additional surcharge. Other unpriced equipment is unavailable until an explicit Host Facsimile Cost is listed. A Host Body's included equipment is free, displayed with that body, and cannot be bought again from its armoury. Vehicle-only equipment is marked; Osseivore host armouries offer only equipment verified for vehicles in that faction. Source availability and existing tier/Titan restrictions still apply.

## Installation

Upload the four files from this ZIP to the existing repository root, then update BattleScribe data. Review older rosters: withdrawn purchases have a maximum of zero and must be removed. The catalogue does not silently legalise them as free equipment.

## Changes and validation

Faction-scoped price evidence replaces the former cross-faction highest-role lookup. Included host-body purchases are withdrawn; body profiles remain free. Revision 26 Non-Melded forms, statlines, unit costs and restrictions are preserved. Automated archive/XML and roster-condition checks are supplied; this has not been tested in the BattleScribe app.

## Withheld items requiring review

No new Host Facsimile Costs have been invented. Entries below are unavailable pending a verified source price/role, vehicle use, or an explicit Host Facsimile Cost. Items already included by a body are not listed here.

| Faction | Item | Reason |
|---|---|---|
| Agents of the Imperium | Alpha Cognis-signum — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Animus Speculum — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Arae-shrikes — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Assured Destruction — Breacher Charge upgrade | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Ballista-miasma — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Blind Grenade Launcher — Corvus mount [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Blind Grenades — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Boltgun — profile reference | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Breacher Charges — four included | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Ceramite Plating — Corvus [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Combi-bolter — Fire Wasp exchange | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Cortex Controller — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Envenomed Blade — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Etherium — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Executioner Missile Launcher — Corvus mount [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Executioner Missile Payload Rules | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Executioner Pistol — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Exitus Ammunition Rules | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Exitus Pistol — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Exitus Rifle — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Flamer — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Four Deathblow Missiles — Corvus mount [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Frenzon — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Grenade Launcher — profile reference | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Haywire Gauntlet — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Heavy Bolters — included pair | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Heavy Flamer — Heavy Servitor exchange | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Hybrid Cortex — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Inferno Pistol — Machinator Array | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Las Rifle | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Machinator Array — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Master-crafted Weapon Upgrade | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Navigator Powers — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Netfly Automata — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Neural Shredder — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Neuro-gauntlet — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Phase Sword — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Poisoned Blades — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Power Claw — profile reference | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Power Glaive — profile reference | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Power Maul — profile reference | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Power Sword — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Psyk-out Grenades — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Remote Teleport Transponder — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Searchlight — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Sentinel Array — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Sheathed Blade / Transport Capacity 6 — Corvus [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Spy Mask — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Twin-linked Lascannons — Corvus exchange [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Twin-linked Maxima Bolter — Corvus mount [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Twin-linked Rotor Cannons — Corvus exchange [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Twin-linked Volkite Culverins — Corvus mount [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Imperium | Void Hardened Armour — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Warrant of Trade — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Imperium | Ætherlabe Staff — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Anbar Armour — named-agent reference | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Armour of the Last Runes — named-agent reference | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Atomic Disassembler — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Cursed Breath — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Demux Interceptor — named-agent reference | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Diresword — named-agent profile reference | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Eradicator Glove — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Exitus Ammunition Rules | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Void | Flip Belt — Consort reference | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Ghosthelm — named-agent reference | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Heavy Void Stalker Armour — named-agent reference | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Void | Holo-suit — Consort reference | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Necrotic Sceptre — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Pair of Shuriken Pistols | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Void | Power Sword — Consort profile reference | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Runes of Warding — named-agent reference | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Runes of Witnessing — named-agent reference | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Shimmer Shield — named-agent reference | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Staff of Ulthamar — named-agent profile reference | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Sub-dermal Armour — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Teeth and Claws — two included | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Void | The Aegis — named-agent reference | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Agents of the Void | Void Stalker Armour — profile reference | Faction/source-role provenance requires confirmation; no inferred price. |
| Agents of the Void | Witchblade — named-agent profile reference | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Alpha Legion — Banestrike Ammunition | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Blood Angels — Angel's Tears Grenade Launcher | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Blood Angels — Fallen-star Pattern Power Spear | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Dark Angels — Plasma Incinerator [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Astartes | Dark Angels — Stasis Shells — grenade launcher [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Astartes | Dark Angels — Stasis Shells — missile [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Astartes | Death Guard — Assault Grenade Launcher | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Death Guard — Chem-Munitions Flamer | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Death Guard — Chem-Munitions Heavy Flamer [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Death Guard — Chem-Munitions Heavy Flamer [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Astartes | Emperor's Children — The Cacophany | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Iron Hands — Graviton Cannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Astartes | Iron Hands — Graviton Imploder [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Iron Hands — Graviton Imploder [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Astartes | Iron Warriors — Graviton Maul | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Iron Warriors — Olympia Pattern Bolt Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Iron Warriors — Olympia Pattern Bolt Cannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Astartes | Iron Warriors — Shrapnel Bolts [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Legiones Astartes — Combi-bolter [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Legiones Astartes — Combi-weapon — Flamer [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Astartes | Legiones Astartes — Combi-weapon — Plasma Gun [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Astartes | Night Lords — Nostraman Chainblade | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Night Lords — Volkite Cavitor [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Night Lords — Volkite Cavitor [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Astartes | Raven Guard — Anti-Materiel Rounds | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Raven Guard — Fulcrum Hand-cannon | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Salamanders — Pyroclast Flame Projector | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Sons of Horus — Combi-Bolter with Banestrike Rounds | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Thousand Sons — Asphyx Light Shells | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Thousand Sons — Bolter with Asphyx Shells | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Thousand Sons — Mauler Pattern Bolt Cannon with Asphyx Shells [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Thousand Sons — Mauler Pattern Bolt Cannon with Asphyx Shells [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Astartes | Ultramarines — Nemesis Ammunition | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | White Scars — Kontos Power Lance | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | White Scars — Scatterbolt Launcher | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Word Bearers — Curs'd Boltspitter [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Word Bearers — Tainted Power Claw | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Astartes | Word Bearers — Warpfire Plasma Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | 2 x Shuriken Cannons [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | 2 x Shuriken Cannons [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | 2x Bright Lances [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | 2x Bright Lances [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | 2x Nightfire Missile Launchers [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | 2x Phoenix Missile Launchers [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | 2x Phoenix Missile Launchers [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | 2x Shuriken Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | 2x Shuriken Cannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | 2x Twin-linked Pulse Lasers [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | 2x Twin-linked Pulse Lasers [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Bright Lance [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Chain Snares [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Corsairs | Corsair Jet Packs | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Corsair Kinetic Shroud — 0 pts / Corsair Vampire Raider [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Corsairs | Corsair Kinetic Shroud — 15 pts / Corsair Balestrike Band [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Corsairs | Corsair Void Burners [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Corsairs | D-Flail [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | D-Flail [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Dark Lance [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Doomweaver [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Doomweaver [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Eldar Missile Launcher (Plasma & Starshot) [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Eldar Missile Launcher [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Fire Storm Laser Array [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Fire Storm Laser Array [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Heavy Mesh Armour | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Lasblaster | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Lynx Pulsar [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Lynx Pulsar [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Prism Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Prism Cannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Pulse Laser — 0 pts / Corsair Balestrike Band [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Pulse Laser — 5 pts / Corsair Hornet Squadron [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Scatter Laser [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Shadowwave Grenades | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Shadowweave Grenades | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Shuriken Cannon — 0 pts / Corsair Balestrike Band [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Shuriken Cannon — 10 pts / Corsair Fire Prism Squadron [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Shuriken Cannon — 20 pts / Corsair Balestrike Band [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Sonic Lance [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Sonic Lance [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Splinter Cannon — 0 pts / Corsair Balestrike Band [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Splinter Cannon — 10 pts / Corsair Balestrike Band [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Star Engines — 0 pts / Corsair Hornet Squadron [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Corsairs | Star Engines — 15 pts / Corsair Balestrike Band [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Corsairs | Starcannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Twin-linked Bright Lance [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Twin-linked Bright Lance [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Twin-linked Lasblaster | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Twin-linked Lasblaster [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Twin-linked Lasblaster [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Twin-linked Lasblasters [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Twin-linked Lasblasters [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Twin-linked Phoenix Missile Launcher [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Twin-linked Phoenix Missile Launcher [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Twin-linked Pulsar [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Twin-linked Pulsar [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Twin-linked Shuriken Catapult | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Twin-linked Shuriken Catapult [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Twin-linked Shuriken Catapult [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Twin-linked Shuriken Catapults [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Twin-linked Shuriken Catapults [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Twin-linked Splinter Rifle | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Twin-linked Splinter Rifle [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Twin-linked Splinter Rifle [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Twin-linked Splinter Rifles [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Twin-linked Splinter Rifles [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Twin-linked Starcannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Twin-linked Starcannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Corsairs | Voidplate Harnesses | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Wasp Jump Pack [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Corsairs | Wasp Jump Pack [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | 2x Bright Lance | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | 2x Bright Lance [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | 2x Bright Lance [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | 2x Ghostswords | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | 2x Heavy D-Scythe [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | 2x Heavy D-Scythe [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | 2x Starcannon | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | 2x Starcannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | 2x Starcannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | 2x Twin-linked Phoenix Missile Launcher [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | 2x Twin-linked Phoenix Missile Launcher [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | 2x Twin-linked Pulse Laser [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | 2x Twin-linked Pulse Laser [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Armour of the Last Runes | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Aspect Armour | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Bright Lance — 10 pts / Black Guardian Vyper Squadron [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Bright Lance — 5 pts / Black Guardian War Walkers [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Cloudburst Missile Launcher [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Cloudburst Missile Launcher [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Crystal Targeting Matrix [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | D-Flail [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | D-Flail [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | D-Impaler [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | D-Impaler [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | D-Scythe | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Death and Destruction | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Deathshroud Cannon | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Doomweaver [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Doomweaver [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Dragon's Breath Flamer | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Eldar Jetbikes | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Eldar Missile Launcher (Plasma & Starshot Missiles) [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Eldar Missile Launcher [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Eldar Titan Holo-Fields [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Eldar Titan Holo-Fields [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Eldar Titan Holo-fields [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Eldar Titan Holo-fields [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Fire Axe | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Forceshield | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Ghost Axe and Forceshield | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Ghosthelm | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Ghostwalk Matrix [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Grenade Pack | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Haywire Grenades | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Heavy Aspect Armour | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Holo-Fields [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Holo-fields [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Improved Holo-fields [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Improved Holo-fields [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Inferno Lance | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Lynx Pulsar [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Lynx Pulsar [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Mask of Jain Zar | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Mindshock Pod [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Mindshock Pod [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Phantom D-Bombard [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Phantom D-Bombard [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Phantom Glaive and Twin-linked Pulse Laser [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Phantom Glaive and Twin-linked Starcannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Phantom Missile Launcher [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Phantom Missile Launcher [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Phantom Pulsar [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Phantom Pulsar [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Phoenix Armour | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Power Field [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Power Field [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Power Sword and Shuriken Pistol | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Power Weapon and Shimmershield | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Power Weapon and Shuriken Pistol | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Prism Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Prism Cannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Pulsar [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Pulsar [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Pulse Laser — 0 pts / Cloudstrike Squadron [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Pulse Laser — 15 pts / Phantom Titan [FW] [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Pulse Laser — 5 pts / Hornet Squadron [FW] [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Ranger Long Rifle | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Reaper Rangefinder | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Revenant Jump Jets [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Revenant Jump Jets [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Rune Armour | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Scatter Laser — 0 pts / Black Guardian War Walkers [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Scatter Laser — 10 pts / Black Guardian Vyper Squadron [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Scattershield | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Serpent Shield [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Serpent Shield [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Shadow Weaver | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Shuriken Cannon — 0 pts / Black Guardian Vyper Squadron [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Shuriken Cannon — 10 pts / Black Guardian Vyper Squadron [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Shuriken Pistol and CCW | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Sonic Lance [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Sonic Lance [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Spirit Stones — 0 pts / Hemlock Wraithfighters [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Spirit Stones — 10 pts / Black Guardian Vyper Squadron [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Staff of Ulthamar | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Star Engines — 0 pts / Hornet Squadron [FW] [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Star Engines — 15 pts / Black Guardian Vyper Squadron [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Starcannon — 0 pts / Phantom Titan [FW] [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Starcannon — 5 pts / Black Guardian Vyper Squadron [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Starshot Missiles | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | The Eye of Wrath | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | The Maugetar | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | The Shining Blade | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | The Spear of Starlight | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | The Spear of Twilight | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | The Sundered Spear | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | The Sword of Asur | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | The Wailing Doom | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Twin-Linked Shuriken Catapult | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Twin-linked Bright Lance — 0 pts / Phoenix Bombers [FW] [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Twin-linked Bright Lance — 5 pts / Dark Reapers [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Twin-linked Eldar Missile Launcher [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Twin-linked Pulsar [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Twin-linked Pulsar [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Twin-linked Scatter Laser [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Twin-linked Shuriken Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Twin-linked Shuriken Cannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Twin-linked Shuriken Catapult | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Twin-linked Shuriken Catapult [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Twin-linked Shuriken Catapult [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Twin-linked Starcannon — 0 pts / Phoenix Bombers [FW] [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Twin-linked Starcannon — 5 pts / Dark Reapers [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Two Bright Lances [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Two Bright Lances [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Two Nightfire Missile Launchers [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Two Phoenix Missile Launchers [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Two Phoenix Missile Launchers [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Two Shuriken Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Two Shuriken Cannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Vectored Engines [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Vibro Cannon | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Voidbringer | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Wasp Jump Pack [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Wasp Jump Pack [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Craftworld Aeldari | Webway Shunt Generator | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Craftworld Aeldari | Witch Staff | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Custodes | Adrastus Bolt Caliver | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Custodes | Adrathic Devastator [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Custodes | Adrathic Exterminator | Faction/source-role provenance requires confirmation; no inferred price. |
| Custodes | Aquillon Terminator Armour | Faction/source-role provenance requires confirmation; no inferred price. |
| Custodes | Custodian Jump Harness | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Custodes | Gyrfalcon Jetbike | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Custodes | Lastrum Bolt Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Custodes | Lastrum Storm Bolter [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Custodes | Magisterium Vexilla | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Custodes | Multi-Layer Refractor Field [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Custodes | Sentinel Warblade | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Cythor Fiends | Stare of Stone | Faction/source-role provenance requires confirmation; no inferred price. |
| Cythor Fiends | Toiphoid Assistance Nanobots | Faction/source-role provenance requires confirmation; no inferred price. |
| Dark Eldar | 2 Dark Lances [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | 2 Disintergrator Cannons [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | 2 Disintergrator Cannons [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | 2 Wrack tools | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Armoured Carapace | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Baleblast | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Beastmaster Skyboard | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Bladevanes | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Casket of Flensing | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Chain-snares [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Dark Lance [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Disintegrator cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Disintegrator cannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Enhanced Aethersails — 0 pts / Court of the Archon [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Enhanced Aethersails — 5 pts / Bloodbrides [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Executioner's Armour | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Eyeburst | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Flickerfield [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Four implosion missiles [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Four shatterfield missiles [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Ghostplate armour | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Gnarlskin | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Grisly Trophies [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Hellion Skyboard | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Incubus Warsuit | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Klaive | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Monoscythe Missile [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Monoscythe Missile [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Necrotoxin Missile [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Necrotoxin Missile [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Night Shields [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Pulse-disintegrator [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Pulse-disintegrator [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Reaver jetbike | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Shaimeshi blade | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Shardcarbine | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Shatterfield Missile [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Shock Prow [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Spirit Syphon | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Splinter Cannon — 0 pts / Archon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Splinter Cannon — 10 pts / Archon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Splinter Pods | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Splinter Racks [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Torment Grenade Launcher [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Twin Linked Splinter Rifles [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Twin Linked Splinter Rifles [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Twin-Linked Splinter Cannon | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Twin-linked Splinter Rifle [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Twin-linked Splinter Rifle [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Two dark scythes [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Two dark scythes [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Two shatterfield missiles and two implosion missiles [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Two void lances [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Two void lances [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Void Mine [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Void Mine [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Dark Eldar | Wrack tool | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Wrack tools | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Dark Eldar | Wychsuit | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Demiurg | Additional Ion Pistol | Faction/source-role provenance requires confirmation; no inferred price. |
| Demiurg | Chainblade — free exchange | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Demiurg | Cortex — construct equipment [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Demiurg | Cortex — construct equipment [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Demiurg | Cutting Lasers — included pair [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Demiurg | Drilling Rig — Miner Droid mount [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Demiurg | Droid Controller — construct equipment [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Demiurg | Droid Controller — construct equipment [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Demiurg | Electro-magnetic Conveyor [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Demiurg | Exo-armour | Faction/source-role provenance requires confirmation; no inferred price. |
| Demiurg | Exo-armour Drilling Rig — paid option | Faction/source-role provenance requires confirmation; no inferred price. |
| Demiurg | Heavy Cutting Laser — profile only [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Demiurg | Ion Accelerator [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Demiurg | Kroot Rifle — plasma rounds | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Demiurg | Kroot Rifle — sniper rounds | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Demiurg | Ore Extruder — profile only | Faction/source-role provenance requires confirmation; no inferred price. |
| Demiurg | Ore Striker — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Demiurg | Pair of Ion Rifles — Miner Droid replacement [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Demiurg | Twin-linked Wrecker Carbines | Faction/source-role provenance requires confirmation; no inferred price. |
| Exodites | Aspect Armour | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Exodites | Banshee Mask | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Exodites | Battle Fortune Battle Skill | Faction/source-role provenance requires confirmation; no inferred price. |
| Exodites | Crushing Blow Battle Skill | Faction/source-role provenance requires confirmation; no inferred price. |
| Exodites | D-cannon — profile only | Faction/source-role provenance requires confirmation; no inferred price. |
| Exodites | Disarming Strike Battle Skill | Faction/source-role provenance requires confirmation; no inferred price. |
| Exodites | Exodite Missile Launcher — profile omitted by source | Faction/source-role provenance requires confirmation; no inferred price. |
| Exodites | Flakk Missile Upgrade | Faction/source-role provenance requires confirmation; no inferred price. |
| Exodites | Fusion Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Exodites | Fusion Cannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Exodites | Ghostaxe — free exchange | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Exodites | Ghostfist — Exodite Knight mount [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Exodites | Ghostglaive — Exodite Knight mount [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Exodites | Ghostglaive — Exodite Knight mount [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Exodites | Ghostsword — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Exodites | Grenade Pack — profile omitted by source | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Exodites | Heavy Void Stalker Armour | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Exodites | Kuron-Kiest | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Exodites | Lasblaster | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Exodites | Mandiblasters | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Exodites | Melta Bombs | Faction/source-role provenance requires confirmation; no inferred price. |
| Exodites | Pulsar — profile omitted by source [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Exodites | Reaper Launcher | Faction/source-role provenance requires confirmation; no inferred price. |
| Exodites | Reaper Rangefinder | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Exodites | Rune Armour | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Exodites | Scatter Laser — Exodite Knight mount [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Exodites | Shield of Grace Battle Skill | Faction/source-role provenance requires confirmation; no inferred price. |
| Exodites | Shuriken Cannon — Clan Citadel mount [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Exodites | Sonic Lance — profile omitted by source [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Exodites | Starcannon — construct mount [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Exodites | Static Holo-field [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Exodites | Suncannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Exodites | Suncannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Exodites | Swooping Hawk Wings | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Exodites | Titan Holo-field — Clan Citadel upgrade [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Exodites | Titan Holo-field — included construct equipment [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Greater Orks | Additional Arm | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Additional Close Combat Weapon | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Additional Hull Point — large Junker [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Additional Hull Point — massive Junker [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Additional Slug Pistol | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Bio-corrosive Rotor Cannon Upgrade | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Bio-corrosive Rotor Cannon Upgrade — Junker [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Canopy — Junker [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Ceremonial Blade — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Greater Orks | Chem-flame Pistol — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Greater Orks | Heavy Cybernetic Armour | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Heavy Ramshackle Armour — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Greater Orks | Legs — Junker movement [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Missile Launcher — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Greater Orks | Motorised Melee Weapon — Primeork | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Greater Orks | Motorised Melee Weapon — War Chief / Ironclad | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Power Maul — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Greater Orks | Primitive Cortex — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Greater Orks | Reinforced Armour — Junker [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Scrap Cannon — Junker option [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Greater Orks | Scrap Cannon — included artillery weapon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Greater Orks | Shamanic Totems — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Greater Orks | Sub-dermal Armour — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Greater Orks | Super-heavy Upgrade — massive Junker [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Target Lockers — unit upgrade | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Tools — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Greater Orks | Tracks — medium/large/massive Junker [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Tracks — small Junker [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Transport Capacity +1 — Junker [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Two twin-linked Photonic Lances — artillery exchange [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Greater Orks | Two twin-linked Rotor Cannons — artillery exchange [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Greater Orks | Void Hardened Armour — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Greater Orks | Wheels — Junker movement [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Greater Orks | Wings — Junker movement [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Harlequins | Bladed Edges [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Harlequins | Blastblind Launcher [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Harlequins | Blind-Barrage Launcher (profile pending source completion) [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Harlequins | Goesh Gyer Mask | Faction/source-role provenance requires confirmation; no inferred price. |
| Harlequins | Hallucinogen Grenade Launcher | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Harlequins | Haywire Cannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Harlequins | Heart Phase Gauntlet | Faction/source-role provenance requires confirmation; no inferred price. |
| Harlequins | Helical Scythe Pinions | Faction/source-role provenance requires confirmation; no inferred price. |
| Harlequins | Helion Skyboard | Faction/source-role provenance requires confirmation; no inferred price. |
| Harlequins | Holo-fields [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Harlequins | Holo-fields [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Harlequins | Linked Prism Pistols | Faction/source-role provenance requires confirmation; no inferred price. |
| Harlequins | Mirage Launchers [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Harlequins | Mirage Launchers [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Harlequins | Miststave | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Harlequins | Phractal Phase Blade | Faction/source-role provenance requires confirmation; no inferred price. |
| Harlequins | Phractal Phase Dagger | Faction/source-role provenance requires confirmation; no inferred price. |
| Harlequins | Phractal Phase Lance (Skyweaver only) | Faction/source-role provenance requires confirmation; no inferred price. |
| Harlequins | Prismatic Cannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Harlequins | Riveblades (profile and price pending source completion) | Faction/source-role provenance requires confirmation; no inferred price. |
| Harlequins | Shrieker Cannon | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Harlequins | Shuriken Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Harlequins | Shuriken Cannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Harlequins | Skyweaver Jetbike | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Harlequins | Spinneret Launcher [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Harlequins | Star Bolas | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Harlequins | Teare Grenades | Faction/source-role provenance requires confirmation; no inferred price. |
| Harlequins | Writ of the Great Jest | Faction/source-role provenance requires confirmation; no inferred price. |
| Harlequins | Writer's Wand | Faction/source-role provenance requires confirmation; no inferred price. |
| Hrud | Additional Phased Plasma Missile Launcher [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Hrud | Armourbane Weapon Upgrade | Faction/source-role provenance requires confirmation; no inferred price. |
| Hrud | Fleshbane Weapon Upgrade | Faction/source-role provenance requires confirmation; no inferred price. |
| Hrud | Haywire Weapon Upgrade | Faction/source-role provenance requires confirmation; no inferred price. |
| Hrud | Heavy Darughachis Claw — Yaugan Moog mount [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Hrud | Heavy Darughachis Claw — Yaugan Moog mount [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Hrud | Heavy Phased Plasma Fusil — Yaugan Moog mount [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Hrud | Hybrid ISD — large | Faction/source-role provenance requires confirmation; no inferred price. |
| Hrud | Hybrid ISD — medium | Faction/source-role provenance requires confirmation; no inferred price. |
| Hrud | Hybrid ISD — small included | Faction/source-role provenance requires confirmation; no inferred price. |
| Hrud | Hybrid ISD — small option | Faction/source-role provenance requires confirmation; no inferred price. |
| Hrud | Interceptor Weapon Upgrade | Faction/source-role provenance requires confirmation; no inferred price. |
| Hrud | Master-crafted Weapon Upgrade | Faction/source-role provenance requires confirmation; no inferred price. |
| Hrud | Pair of Darughachis Claws | Faction/source-role provenance requires confirmation; no inferred price. |
| Hrud | Phased Plasma Missile Launcher — Yaugan Moog mount [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Hrud | Skyfire Weapon Upgrade | Faction/source-role provenance requires confirmation; no inferred price. |
| Hrud | Sub-dermal Armour | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Interex | Demux Interceptor | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Interex | Flechette Launcher — profile omitted by source [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Interex | Interex Body Glove | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Interex | Meturge Discharger — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Interex | Security Grid Interface [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Interex | Twin-linked Lascannon [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Interex | Twin-linked Warcannon [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Interex | Warcannon Infernus [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Jorgall | Additional Arc Pistol | Faction/source-role provenance requires confirmation; no inferred price. |
| Jorgall | Four Chem Missiles [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Jorgall | Heavy Arc Thrower — vehicle profile [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Jorgall | Jorgalli Mech-wings | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Jorgall | Jorgalli Medi-psych Pack | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Jorgall | Macro-gill | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Jorgall | Razor Tentacles — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Jorgall | Twin-linked Arc Throwers — Ninurta mount [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Keylekid | Additional Keylek Shard Pistol | Faction/source-role provenance requires confirmation; no inferred price. |
| Keylekid | Demux Interceptor | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Keylekid | First Master-crafted Trophy Weapon | Faction/source-role provenance requires confirmation; no inferred price. |
| Keylekid | Keylek Shard Blaster — Insurgent exchange | Faction/source-role provenance requires confirmation; no inferred price. |
| Keylekid | Keylek Shard Blaster — included exchange | Faction/source-role provenance requires confirmation; no inferred price. |
| Keylekid | Keylek Shard Blaster — option | Faction/source-role provenance requires confirmation; no inferred price. |
| Keylekid | Numus Engine Interface [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Keylekid | Numus Engine Interface [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Keylekid | Second Master-crafted Trophy Weapon | Faction/source-role provenance requires confirmation; no inferred price. |
| Keylekid | Sunfire Incendiary [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Keylekid | Thermo-scalpel — included | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Laer | Barbed Mandibles | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Laer | Cult of Pleasure | Faction/source-role provenance requires confirmation; no inferred price. |
| Laer | Extra Set of Arms | Faction/source-role provenance requires confirmation; no inferred price. |
| Laer | Heavy Laeran Energy Gauntlet — heavy weapon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Laer | Heavy Sonic Disruptor [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Mechanicum | Demolisher Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Mechanicum | Djinn-skein [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Mechanicum | Earthshaker Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Mechanicum | Enhanced Targeting Array [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Mechanicum | Graviton Cannon [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Mechanicum | Haemonculite Cyber-corpus | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Mechanicum | Heavy Arc Rifle | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Mechanicum | Heavy Grav Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Mechanicum | Heavy Grav Cannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Mechanicum | Ion Shield [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Mechanicum | Laser Destroyer [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Mechanicum | Lightning Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Mechanicum | Lorica Thallax | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Mechanicum | Mechadendrite Combat Array | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Mechanicum | Medusa Siege Gun [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Mechanicum | Mitralock | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Mechanicum | Phospex Medusa Shell [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Mechanicum | Phosphor Blaster | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Mechanicum | Plasma Culverin | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Mechanicum | Rad Furnace [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Mechanicum | Sollex Heavy Lascannon [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Megarachnids | Pair of Spinceps | Faction/source-role provenance requires confirmation; no inferred price. |
| Militia and Cults | Artificer Armour | Faction/source-role provenance requires confirmation; no inferred price. |
| Militia and Cults | Auxilia Pistol | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Militia and Cults | Dual Battlecannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Militia and Cults | Earthshaker Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Militia and Cults | Earthshaker Cannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Militia and Cults | Explorator Augury Web [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Militia and Cults | Exterminator Autocannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Militia and Cults | Gorgon Mortar Battery [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Militia and Cults | Gorgon Mortar Battery [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Militia and Cults | Kinetic Piercer Missile [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Militia and Cults | Lascarbine | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Militia and Cults | Laser Destroyer [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Militia and Cults | Medusa Siege Gun [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Militia and Cults | Medusa Siege Gun [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Militia and Cults | Platoon Standard | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Militia and Cults | Quad Heavy Bolter [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Militia and Cults | Quad Heavy Bolter [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Militia and Cults | Quad Mortar [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Militia and Cults | Quad Multi-laser [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Militia and Cults | Quad Multi-laser [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Militia and Cults | Stormhammer Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Militia and Cults | Sub-flak Armour | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Militia and Cults | Vanquisher Battlecannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Nephilim | Armoured Cockpit [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Nephilim | Breacher Charge | Faction/source-role provenance requires confirmation; no inferred price. |
| Nephilim | Chorum Blade | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Nephilim | Demolition Charge | Faction/source-role provenance requires confirmation; no inferred price. |
| Nephilim | Displacement Cannon | Faction/source-role provenance requires confirmation; no inferred price. |
| Nephilim | Flakk Missile Upgrade | Faction/source-role provenance requires confirmation; no inferred price. |
| Nephilim | Flare/Chaff Launcher [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Nephilim | Fleshmask Interface [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Nephilim | Heavy Flamer [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Nephilim | Hellstrike Missiles — pair [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Nephilim | Illum Flares [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Nephilim | Lascannon [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Nephilim | Missile Launcher | Faction/source-role provenance requires confirmation; no inferred price. |
| Nephilim | Multi-laser [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Nephilim | Pair of Carnodon Sponson Autocannons [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Nephilim | Pair of Carnodon Sponson Heavy Bolters [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Nephilim | Rad Grenades | Faction/source-role provenance requires confirmation; no inferred price. |
| Nephilim | Searchlight [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Nephilim | Shriekpulse — Corpore Caelesti exchange | Faction/source-role provenance requires confirmation; no inferred price. |
| Nephilim | Shriekpulse — Elevatum | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Nephilim | Smoke Launchers [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Nephilim | Twin-linked Autocannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Nephilim | Twin-linked Lascannon [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Nephilim | Twin-linked Multi-laser [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Nurthene | Ballista Rocket Launcher [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Nurthene | Banner Bearer | Faction/source-role provenance requires confirmation; no inferred price. |
| Nurthene | Caiman Howdah — five Combi-bow infantry | Faction/source-role provenance requires confirmation; no inferred price. |
| Nurthene | Caiman Howdah — three Ballista Rocket Launchers | Faction/source-role provenance requires confirmation; no inferred price. |
| Nurthene | Ceremonial Blade | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Nurthene | Iron Scale APC Ablative Armour and Armoured Cockpit [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Nurthene | Iron Scale Turret Autocannon [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Nurthene | Iron Scale Turret Heavy Flamer [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Nurthene | Naphta Rifle — character option | Faction/source-role provenance requires confirmation; no inferred price. |
| Nurthene | Naphta Rifle — unit-wide exchange | Faction/source-role provenance requires confirmation; no inferred price. |
| Nurthene | Reinforced Reed Plate Armour | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Nurthene | Totem Bearer | Faction/source-role provenance requires confirmation; no inferred price. |
| Olamic Quietude | Heavy Heat Beamer — Electro-talon exchange [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Olamic Quietude | Heavy Heat Beamer — Flechette exchange [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Olamic Quietude | Induz Pattern | Faction/source-role provenance requires confirmation; no inferred price. |
| Sisters of Silence | Arae-Shrikes [Vehicle Equipment] | Faction/source-role provenance requires confirmation; no inferred price. |
| Sisters of Silence | Assault Needler | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Sisters of Silence | Boltgun [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Sisters of Silence | Execution Blade | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Sisters of Silence | Needle Pistol | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Sisters of Silence | Proteus Neuro-Lash | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Sisters of Silence | Proteus Plasma Projector [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Sisters of Silence | Psyk-Out Grenades | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Sisters of Silence | Psyk-Out Missile [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Sisters of Silence | Psyk-Out Missile [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Sisters of Silence | Refractor Field [Vehicle Equipment] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Sisters of Silence | Refractor Field [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Sisters of Silence | Snare Gun | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Sisters of Silence | Stake-Crossbow | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Sisters of Silence | Teleportation Transponder | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Additional Light Snuffer | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Animus Speculum | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Corpulence Flamer Mouth | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Cult Ambush, Return to the Shadows and Lone Killer | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Discipline Collars | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Engulfing Maws | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Flazorslip Whip | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Gargoathen Mind Nimbus | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Gravity Suction Whip | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Husk Glaive | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Husk Lance | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Irad Cleanser | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Irradiation Engine | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Light Snuffer (included weapon) | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Missile Launcher with Rad Missiles | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Nanyte Projector Cloud | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Necrotic Sceptre (HQ pistol replacement) | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Nervesalve Crystal | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Pair of Graviton Guns | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Parepleth Symbiotic Sceptre | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Power Claws | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Powered Armour | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Powered Limbs | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Psydrain Blade | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Psyk-out Grenades | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Rad Furnace | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Rad Grenades | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Radium Carbine | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Radium Jezzail | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Random Appendages | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Sludge Spitters | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Stasis Grenades | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Teleport Transponders | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Void Ejection | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Void-hardened Carapace Plate | Faction/source-role provenance requires confirmation; no inferred price. |
| Slaugth | Voidling Teeth and Claws | Faction/source-role provenance requires confirmation; no inferred price. |
| Solar Auxilia | Auxilia Lasrifle with Blast-charger | Faction/source-role provenance requires confirmation; no inferred price. |
| Solar Auxilia | Auxilia Lasrifle with Collimator | Faction/source-role provenance requires confirmation; no inferred price. |
| Solar Auxilia | Charonite Claws | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Solar Auxilia | Cognis-signum | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Solar Auxilia | Cohort Vexilla | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Solar Auxilia | Combat Shield | Faction/source-role provenance requires confirmation; no inferred price. |
| Solar Auxilia | Demolition Charge | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Solar Auxilia | Earthshaker Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Solar Auxilia | Earthshaker Cannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Solar Auxilia | Executioner Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Solar Auxilia | Executioner Cannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Solar Auxilia | Exterminator Autocannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Solar Auxilia | Exterminator Autocannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Solar Auxilia | Grav-wave Generator [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Solar Auxilia | Graviton Cannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Solar Auxilia | Illum Flares [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Solar Auxilia | Kinetic Piercer Missile [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Solar Auxilia | Las-lock | Faction/source-role provenance requires confirmation; no inferred price. |
| Solar Auxilia | Laser Destroyer [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Solar Auxilia | Medi-pack | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Solar Auxilia | Medusa Siege Gun [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Solar Auxilia | Medusa Siege Gun [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Solar Auxilia | Psi-jammer [Vehicle Equipment] | No vehicle use verified for this item in this faction. |
| Solar Auxilia | Quad Mortar [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Solar Auxilia | Quad Multi-laser [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Solar Auxilia | Quad Multi-laser [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Solar Auxilia | Reinforced Void Armour | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Solar Auxilia | Stormhammer Cannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Solar Auxilia | Troop Vexilla | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Solar Auxilia | Vanquisher Battlecannon [Vehicle Weapon] | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Solar Auxilia | Vanquisher Battlecannon [Vehicle Weapon] | No vehicle use verified for this item in this faction. |
| Storm Scions | Bolt Carbine Pistol | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |
| Storm Scions | Electro Relay Arc [Vehicle Weapon] | Faction/source-role provenance requires confirmation; no inferred price. |
| Storm Scions | Electro Shield | Faction/source-role provenance requires confirmation; no inferred price. |
| Storm Scions | Heavy Electro Discharger | No published standalone/upgrade cost: explicit Host Facsimile Cost required. |

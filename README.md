# Rangdan Confederacy — compact revision 53

Extract and replace all four files in your GitHub repository root, then refresh BattleScribe data.

Data index: https://raw.githubusercontent.com/kobychapmans-ship-it/Rangdan-confederacy/main/index.bsi
Requires Horus Heresy 1.0 game system revision 165.

## Memory-focused changes

- Shared 18,855 identical profile/rule definitions using native BattleScribe infoLinks. Complete guarded contents must match before sharing; differently scoped profiles are not merged.
- Replaced 2,643 repeated any-member/none-member guards with 11 shared internal memberships, removing 81,197 repeated predicates. All scopes, thresholds and source selection definitions remain intact. Internal categories and membership links are hidden.
- Expanded catalogue XML reduced from 223,195,828 to 191,450,633 bytes (14.2%).
- Retained the host bodies, faction armouries, costs, weapon slots, hardpoints, rules, stat modifiers and selected-only headings. No selection entries or choice groups were removed. Guarded profile headings remain guarded on the new links as well as the shared definitions.
- Specialised 2,331 native vehicle mount references to their own faction plus Rangdan options. Potential candidate-choice expansion falls from 883,885 to 249,036 (71.8% less). Only branches already unavailable on those native vehicles are excluded. Facsimile menus retain every eligible faction branch.

## Validation and limits

Official BattleScribe 2.03 catalogue XSD, archive integrity, IDs/references/defaults, index metadata and entry-link cycles passed. Existing scoped statline, save, host payload, hardpoint and Collective Form tests passed.

The compressed catalogue and repository ZIP are both below 14,000,000 bytes. BattleScribe expands the catalogue in memory; compressed size alone does not establish runtime safety. The expanded XML remains substantial. Native iOS/Android testing was not available, so this build is not certified crash-free.

After updating, create a fresh small roster first. Preserve existing roster files. If BattleScribe retains an older catalogue, remove and redownload only the Rangdan data. Existing selection identifiers have been retained; shared profile/rule IDs are consolidated through the included source-project alias audit.

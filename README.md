# Rangdan Confederacy — revision 46 loading repair

The published revision 45 catalogue and repository index match the delivered files. The upload was intact.

The full BattleScribe 2.03 XSD check found actual structural failures: Carrion Forge's rules links followed its category links in the wrong order; four Gargantuan host options contained two modifier containers each; and an imported game-system profile retained the game-system namespace. Revision 46 fixes these faults without dropping their rules or option modifiers.

Revision 45 also expanded to 657,890,264 bytes of XML, with condition nesting up to 124 levels. Compact numeric decision tables reduce this to approximately 255 MB, with maximum overall XML depth 41. Numeric replacements still apply on the selected model/form's live profile link. These tables respect mutually exclusive host selections and the universal stat/AV limits.

Validation includes the full catalogue XSD, nested ZIP integrity and matching indexes, unique identifiers and resolved targets, selected-owner profile links, chassis costs, exclusive Primarch access, stock/Terminator saves, vehicle statistic modifications and caps, sampled raw arithmetic comparisons, and unchanged selection/cost/constraint inventories. Detailed counts are in the JSON reports included with the project.

Native BattleScribe on iOS is not available here. The repaired file is schema-valid; on-device loading and performance still require confirmation. The catalogue remains large because it includes the extensive faction and vehicle options.

Upload all four files from the repository ZIP to the repository root, replacing the existing files. Confirm index.xml reports revision 46, then refresh BattleScribe. If BattleScribe retains the failed revision, remove its local Rangdan catalogue and redownload it. Keep existing roster backups; recreate affected selections if their old option paths persist.

Reproduction: run work/revision46.py against the bundled revision45 repository ZIP; then run work/validate_schema46.py, work/validate_revision46.py and work/audit_preservation46.py.

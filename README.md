# Rangdan Confederacy — catalogue revision 51

Extract this ZIP and replace all four files in the root of your GitHub repository:
- index.bsi
- index.xml
- Rangdan_Confederacy_HH1.catz
- README.md

BattleScribe data-index URL:
https://raw.githubusercontent.com/kobychapmans-ship-it/Rangdan-confederacy/main/index.bsi

Requires the Horus Heresy 1.0 game system, ID ca571888-56a9-c58e-ddaf-54f4713538bc, revision 165.

## Revision 51

- Expanded catalogue XML reduced from 370,363,055 to 204,528,626 bytes (44.78%).
- Consolidated repeated guards and identical set effects. Removed editor comments, empty containers and explicitly defaulted XML attributes. No existing public selection IDs, choice definitions, profile contents or listed base costs were removed or renamed.
- Each individual Titan weapon requires one additional choice named "Second slot occupied by Titan weapon" in another weapon slot. That slot has a maximum of one choice, so it cannot also hold an ordinary weapon. The catalogue validates one reserved slot per selected Titan weapon; an incomplete or excessive reservation is an invalid selection. Squad quantity pools and the existing two-hardpoint Titan costs are retained.

## Validation

Official BattleScribe 2.03 catalogue XSD: passed.
Archive CRCs, catalogue/index metadata, IDs, references, defaults, HH1 profile types and selection dependency cycles: passed.
14,653 automated behaviour checks passed, covering selected profile visibility, vehicle stat changes, individual model isolation, Primarch equipment, armour/save effects, Gargantuan eligibility and Titan slot reservations.
All 220,999 existing identifiers and 17,997 profile definitions are retained.

Native Android/iOS BattleScribe runtime was not available for testing. These checks validate the files and tested selection behaviour; they do not establish that every phone will load or run the catalogue without crashing. The expanded XML remains substantial despite the reduction.

After updating the repository, refresh BattleScribe data. If an old roster retains invalid selections, remove and re-add the affected selection. For a Titan weapon, choose the weapon first, then its reserved slot.

# Rangdan Confederacy — Revision 41

Vehicle display repair: catalogue queries now use real ancestor IDs instead of the invalid unit pseudo-scope. Specific vehicle and generic chassis rows are hidden by default and enabled only by their matching purchased form. This also repairs the stat, eligibility, price-scaling and refund queries that used the same unsupported scope. Individual core/adaptation scopes are retained for mixed-state units.

Higher/Synarch and Moderate/Carrion Troops share a real options container. Both now receive their Collective Form refund tab, which had previously been incorrectly placed at catalogue root. Source vehicle and modular chassis choices remain alternatives.

Facsimile Component Rules are supplied only by a Facsimile Vehicle Chassis. Movement-pattern and hardpoint controls are inside that chassis option. Faction selection or a complete source vehicle does not add the Facsimile rules.

Conservative cleanup removes unreachable shared definitions, exact duplicate modifiers/links and obsolete generic uncosted/fallback placeholder choices. Named, explicitly priced armoury items are retained. The project includes a detailed audit and regression results.

Replace all four repository files and refresh BattleScribe. Because the shared Osseivore option hierarchy changed, recreate affected Osseivore selections in old rosters. Tests check actual query scopes and selection paths as well as arithmetic; native iOS BattleScribe rendering still requires user confirmation.

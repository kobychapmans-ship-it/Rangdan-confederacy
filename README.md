# Rangdan Confederacy revision 54

Replace all four repository root files and refresh BattleScribe data.

This build groups stat/rule modifiers only when their complete conditions are identical and each field retains its operation order. Modifier order, selection IDs, choices, costs, host forms, hardpoints and Collective Form are preserved. Higher/Synarch Facsimile chassis remains +150 points; Legendary +300 points.

Validated against BattleScribe catalogue schema and compared all modifiers against the original conditions and operation order for each owner and field. This reduces catalogue memory overhead; native BattleScribe roster creation on iOS has not been tested and crash resolution remains unconfirmed.

Data URL: https://raw.githubusercontent.com/kobychapmans-ship-it/Rangdan-confederacy/main/index.bsi

Build measurements:
{
  "revision": 54,
  "expanded_before": 191596048,
  "expanded_after": 191300020,
  "groups": 100,
  "verified_owners": 86,
  "schema_valid": true,
  "native_tested": false
}

Regression results: 522 host rows; 1,729 visibility cases; 6,480 vehicle cases; 4,296 scope-isolation cases; 35 Primarch cases; 52 host payloads; 1,932 armour cases; 15,086 focused hardpoint/Collective Form checks; 2,331 native mount menus. Entry-link cycle checks passed.

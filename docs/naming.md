# Naming Conventions – Court of Cats

## Prefixes
- Traits: `cat_trait_`
- Modifiers: `cat_mod_`
- Events: `court_of_cats.XXXX`
    - 1000-1999: Traits
    - 2000-2999: Activities
    - 3000-3999: Court positions
    - 4000-4999: Misc/expansion
- Activities: `cat_<name of activity>_activity`
- Scripted Effects: `cat_effect_`
- Scripted Triggers: `cat_trigger_`
- Decisions: `cat_decision_<name>`
- On Action: `cat_on_action_<trigger>`
- Localization Keys: `cat_loc_<context>_id`
- Court Positions: `cat_position_<name>`


## Optional Suffixes
- `_core` → foundational systems (e.g. `cat_trait_enthusiast_core`)
- `_exp` → expansion content (e.g. `cat_effect_feast_exp`)
- `_debug` → testing hooks (e.g. `cat_trigger_debug_start`)

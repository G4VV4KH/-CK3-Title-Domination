# Developing Title Domination

The editable store description is `publishing/description.en.md`. Platform variants and README are generated from it. Keep gameplay scripts, localization and publication materials separate.

The first public package targets CK3 1.20.1.2. Its development history contains scoped engine tests for title creation, response choices, coalition formation, outcomes, costs/cooldown and diplomacy. Test counts from different revisions must not be added together or represented as one current run.

For a gameplay change, test the affected paths in an isolated native CK3 profile and bind the result to the complete source snapshot. In particular, inspect actual truce expiry dates as well as the displayed peace terms. Preserve failed attempts and raw local evidence. Hidden engine testing does not prove visual layout.

For translations, maintain every key and formatting/substitution token across all nine target languages. Publication localization acceptance uses static checks; routine per-language engine launches are not required.

Known coverage limits include long-term AI balance, multiplayer, broad government and total-conversion compatibility, old DEV save migration and exceptional lifecycle recovery with the latest diplomacy records. Do not claim universal compatibility. The full `gui/window_title.gui` replacement requires a merged compatibility patch when another mod overrides the same window.

Cover artwork, scripts, translations and publication copy were developed with AI assistance. User-provided gameplay screenshots are genuine game captures; publication processing changes only file encoding and size, never the depicted game state.

Use the [GitHub issue tracker](https://github.com/G4VV4KH/-CK3-Title-Domination/issues), or email **g4vv4kh@gmail.com**. The README contains the assigned publication links. Keep the shared family catalog and sibling descriptions synchronized through scoped metadata updates without altering sibling gameplay.

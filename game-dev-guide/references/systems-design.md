# Gameplay systems

Choose systems in service of the core experience; games can have no combat, progression or numerical economy. Clarify what the player decides, what information supports it, what action occurs, what feedback follows, and how the game state changes. Define failure, recovery and accessibility where relevant.

For combat, if requested: specify player verbs and controls, timing, hit and hurt areas, enemy cues, damage and defense, interruption, recovery, feedback and encounter goals. Start with one player action and one enemy or obstacle; check readability and fairness before scaling.

For numerical systems, if requested: identify the player-facing purpose, input variables and units, formulas, progression boundaries, failure cases and expected time or cost. Start with a few representative scenarios and transparent tunable values; compare early/mid/late outcomes and edge cases. State assumptions and avoid presenting unmeasured balance as proven.

For economy, progression, saving, multiplayer or AI, define their dependency and persistence contracts only if needed. Review effects on other systems and content workload, describe the tradeoffs, and request decisions at material scope changes. Use bounded experiments before broad implementation when evidence is missing.

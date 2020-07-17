## Lancer Macros

### Game System and Module Agnostic

Users will require the "Use Script Macros" permission for these.

#### Basic Roll:

Default values can be set at the top of the macro script, to allow for customisation (e.g. creating a custom Skill roll).

The form has input for:
- Number of Accuracy dice,
- Number of Difficulty dice,
- A Modifier (e.g. Pilot GRIT).
- Notes to add as Flavor text to the roll in chat (e.g. "Tech Attack").

#### Damage Roll:

Default values can be set at the top of the macro script, to allow for customisation (e.g. creating a custom Damage roll).

The form has input for:
- Number of dice to roll,
- Type of dice (d3/d6),
- Damage Modifier,
- Whether to treat the roll as a Critical hit,
- Notes  to add as Flavor text to the roll in chat (e.g. "Kinetic Damage, AP").

#### Custom Weapon Template:

The form has input for:
- Number of Accuracy dice,
- Number of Difficulty dice.

This macro will roll both an "Basic" roll and a "Damage" roll, if the result of the Attack is 20 or higher it will automatically roll the Damage with Critical hit rules.

Desired values can be set by editing the macro.

Supports the Brutal Tier I Talent (Predator) for max dice-roll damage.

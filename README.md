# STA-1E-2E

Manifest URL:
https://raw.githubusercontent.com/tokeidlom/STA-1E-2E/master/src/system.json

Based on the excellent work in:
https://github.com/mkscho63/sta

This release is in place as a way to continue updating STA module for Foundry until the original is able to pick this back up.

This version adds support for V12 of Foundry, it includes the LCARS UI and maintains compatibilty with Compendia module.

For 1e users, this version maintains the same functionality, it includes updates to allow V12 of Foundry to work. If you had previousy been using LCARS UI module, you can disable this as it is now included.

For 2e users, you can change the default sheets to the 2e versions in the settings, and per character, to the 2e versions. This remove challenge dice button, and takes into account the new rules for stress calculation.

You will need to create any weapons in the 2e weapons sheet as there is now a flat (not rolled) damage and the weapon qualities were changed.

Characters created in 1e will transfer over to 2e and back without any issues in case you want to switch rulesets or just experiment with the 2e rules.

This system is based on the 2e quickstart guide rules at present, and will be updated with the new rules as soon as the books are released.

# v1.2.1
- updated system to work with v12,
- included the LCARS UI module as this module has not been updated for v12,
- added character sheet for 2e, which removes challenge dice button and calculates stress based on the new rules,
- added sharship sheet for 2e, which removes challenge dice button, addition of a "shaken" checkbox and converted power bar into a reserve power checkbox, added a "maximum" box under shields to manually add the correct amount of shields until we know how it is calculated,
- as starship for small craft,
- added new weapon sheet with the 2e qualities and new damage rules,
- added new starship weapons sheet with new damage rules and the qualities included in the quickstart, can use text blob as a placeholder until the weapon qualities are known,
- added option for dedicated focus roll (2x discipline value is critical success) to the task roll window.

# v1.2.2 roadmap
- update the starship sheet to be compatible with the new rules,
- update the starship weapons sheet for compatibility with the new rules,
- any further updates to characher and character weapons sheet in line with the full rulesets,
- new extended task tracker based on the new rules,
- combine the CSS sheets,
- update language translations if possible.
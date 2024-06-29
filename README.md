# STA-1E-2E

Manifest URL:
https://raw.githubusercontent.com/tokeidlom/STA-1E-2E/master/src/system.json

Based on the excellent work in:
https://github.com/mkscho63/sta

This release is in place as a way to experiment with updates before pushing them to the main module.

For 1e users, this version maintains the same functionality, it includes updates to allow V12 of Foundry to work.

For 2e users, you can change the default sheets to the 2e versions in the settings, or per character, to the 2e versions. This remove challenge dice button, and takes into account the new rules for stress calculation.

You will need to create any weapons for 2e actors in the 2e weapons sheet as there is now a flat (not rolled) damage and the weapon qualities were changed.

Characters created in 1e will transfer over to 2e and back without any issues in case you want to switch rulesets or just experiment with the 2e rules.

# v1.2.1
- Updated to replace all V12 deprecated functions and syntax, should now be fully compliant.
- Small craft item drop-down menu improved, name appears as blank in opening sheet (TBD), but drop-down now working and updating.
- Starship weapons "with scale" function now working.
- Added new actor and weapons sheets for 2e based on quick start rules & Modiphius forum posts.
- Maintains 1e functionality, no substantive or stylistic changes to 1e beyond updating for V12.
- New translations were added in the language files at the bottom in English only currently if anyone can assist with translations.
-  Added option for dedicated focus roll (2x discipline value is critical success) to the task roll window.
- If you use the LCARS UI module a couple of the new items won't look right, you can use the updated version at: https://raw.githubusercontent.com/tokeidlom/STA-LCARS-UI/main/src/module.json

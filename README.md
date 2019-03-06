# L4D2 Smart Item Selector
Selectively gives items to survivors when they spawn and inlcudes VIP/admin options.

This is a re-write of <a href="https://forums.alliedmods.net/showthread.php?p=1131184" rel="nofollow">L4D & L4D2 Round Start Items Giver by kwski43</a>

Complete Details and Installation Instructions: <a href="https://forums.alliedmods.net/showthread.php?t=314556" rel="nofollow"> [l4d2] Smart Item Selector</a>

<b>Files:</b>
1. l4d2_smart_item_selector_v1.1.sp - main code
2. l4d2_smart_item.phrases.txt - translation file
3. l4d2_weapon_stocks_sis.inc - inlcude file required for compile
4. l4d2_smart_item_selector_v1.1.smx - compiled binary (compiled on SM 1.8)

<B>Change Log:</B>

v1.2 (5-Mar-2019)
	- Added cvar to choose which weapon is active after items are given.
	- Added code to change game cvar "survivor_respawn_with_guns" value to "0"
	- Added chat message that prints if the knife is selected but knife unlock plugin is not running
	- Removed duplicate chainsaw entries in l4d2_weapon_stocks_sis.inc so sIs will compile on sm 1.10
	- Added a formatted l4d2_smart_item_selector.cfg file with all cvars organized into logical groups

v1.1 (1-Mar-2019)
    - corrected mismatched config and selection values for primary and melee weapons
    - reformatted & wrapped cvar descriptions so all values print in the cfg file

v1.0 (24-Feb-2019)
    - Initial release.

# 1.4 (June 7th, 2019):
* [Change] Update ES-ES localization.
* [Enhancement] Use icon of better resolution in the editor to avoid bluring.
* [Fix #271] KSP 1.7.1 breaks grabbing connectors from winch type parts.

# 1.3 (April 21st, 2019):
* [Change] KSP 1.7 compatibility.
* [Fix #263] Missing files trying to compile locally.
* [Fix #264] It's seems that KAS v1.2 do not support KSP v1.7.

# 1.2 (Apr 8th, 2019):
* [Change] ATTENTION! The lagacy parts are _not_ provided in this verison!!! Read [Wiki](https://github.com/ihsoft/KAS/wiki/Legacy-parts-destiny) for more details.
* [Enhancement] Add French localziation.
* [Enhancement] Add Portuguese localziation.
* [Enhancement #260] Add a setting to control the couple state on link.
* [Change] Major update to the basic renderer module to increase UX experience.
* [Fix #236] Support action groups in winches.
* [Fix #252] NRE when entering the vessel from EVA.
* [Fix #255] KAS link throws when loading save file.
* [Fix #258] Connectors break on entering the physics bubble.
* [Fix #260] Add a setting to control the couple state on link.

# 1.1 (October 29th, 2018):
* [Enhancement] Add ES-ES localization.
* [Fix #249] Pylons are not get equipped when carried.

# 1.0 (October 21st, 2018):
* [Change] KSP 1.5 compatibility.
* [Fix #238] Multiple RTS dialogs conflict with each other.
* [Fix #239] RTS dialog cannot be moved.
* [Fix #240] RTS-1 doesn't see all the resources on the vessel.
* [Fix #241] RTS-1 doesn't allow passing fuel in the docked mode.
* [Fix #242] Use resource definition to check if it can be transferred in RTS.
* [Fix #244] GP-20 & BGP-400 are not in the KAS tab in VAB.
* [Fix #246] Timewarp doesn't affect the RTS-1 transfer speed.

# RC2 (Sep 29th, 2018):
* [Fix] Small fix to RU localization.
* [Fix #230] Cable joints get reinforced by the autostruts.
* [Fix #232] NPE when connected vessels go on rails (range more than 2.5km).
* [Fix #235] Fix attach function of the legacy hooks .
* [Change] Improve parts tech tree and categories.
* [Change] Use the stock game logic to create rigid joints.
* [Change] Use aluminum instead of steel for JS-1 part. This reduced its mass down to 8kg (vs 30kg).
* [Enhancement #231] Add the pylon parts: GP-20 and BGP-400.

# RC1 (July 27th, 2018):
* [Fix #229] Exception when adding another fuel mixture.
* [Change] Show the RTS trafgser dialog even if the vessels are docked. Present a message that explains why the controls are not available.
* [Change] Show the fuel mixture percents with a better precision - up to two digits after the dot.
* [Enhancement] Add Itialian localziation.
* [Enhancement] Release KAS API v1.
* [Enhancement] Integrate support of the legacy KAS.

# Beta 11 (July 9th, 2018):
* [Fix] The parts, preattached to a winch in VAB, don't dock when the vessel goes in flight.
* [Fix] GUI crashes if RTS and winch remote dialogs are opened simultaneously,
* [Fix] TB-60 does lock.
* [Fix] Joint limit angles in TJ-2 and TB-60 are wrong: they remember the attach position instead of the "neutral" one.
* [Fix #220] KAS-1.0b10: Wrong max length on W-1.
* [Change] Rename W-1 winch to W-50.
* [Change] Use the 64-bit profile. The 32-bit game mode is no more supported!
* [Change] Setup breaking force for all the links.
* [Enhancement] Prevent KAS parts detaching from the vessel when the joint between the link source and the link target is broken.
* [Enhancement] Add HW-80 part.
* [Enhancement] All textures changed to make a distinguished look for the KAS 1.0 parts (even though many of them use the same models).
* [Enhancement] Huge texture optimizations for better quality, smaller sizes (when possible) and better loading speed.
* [Enhancement] Fully support localization in all the parts.
* [Enhancement] Make fun part descriptions.
* [Enhancement] Show the energy consumption and motor speed in the winch part info.
* [Enhancement] Load winch remote activation key from settings.
* [Enhancement] Add RU localization.

# Beta 10 (May 28th, 2018):
* [Fix] RTS-1 connector not being picked up by kerbal.
* [Fix] Multiple connectors of the different types are get focused at the same time.
* [Fix] On game load, the RTS-1 keeps a fixed hose length instead of the maximume allowed.
* [Fix] Winch could dock without creating a rigid joint between the port and the winch.
* [Fix] When winch docks with the attached vessel, it could be missaligned if the velocitioes are too different.
* [Change] New textures for RTS-1.
* [Change] Animate RTS-1 to make it more dynamic.
* [Change] Load restricted resources and fuel mixtures from the KAS settings. Can be adjusted by MM.
* [Change] Dramatically improve performance of the resource station GUI.

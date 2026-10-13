# Fjordbound

Gather timber and provisions, recover raid caches and defend a fjord settlement before the longship departs.

**Status: development.** Three authored chapters with distinct objectives, original cast and live gameplay rules. This source is being built and playtested toward a premium Steam release; it is not a certified or finished Steam game.

## Story

### The Broken Longship

Astrid returns to a broken longship and a settlement waiting for winter.

### Stormward Shore

Eirik needs timber and the stores lost on the stormward shore, where raiders now camp.

### Oath of the Fjord

Liv calls the clan to keep its oath: defend the homes before chasing glory across the fjord.

## Play and build

Unity6000.6.0f1; project `Game/`. Native Mac: `python3 tools/playtest/build.py --platform macos --output /absolute/fresh/output`. Windows/Linux profiles require native hosts and their corresponding editor modules. Outputs remain outsideGit.

WASD/leftstick move, mouse/rightstick aim, E/A interact, LMB/RT/X attack, B/LB build, Q/RB craft, Escape/Start pause, J/Select journal. Menus accept keyboard, mouse and gamepad; Actions chooses structures, supplier goods, recipes and crafting. Audio/display/rebinding preferences and earned chapter unlocks save locally pergame.

1-4 player LAN sessions use an authoritative TCP host, optional UDP discovery and a controller-operable IP keypad. Clients cannot grant themselves resources or control host-only campaign actions. LANmenus do notpause the host; solo pause does. No internet relay, Steam SDK, host migration or online matchmaking is claimed.

Selected purchased models/textures remain private, pinned by ContentSource/Art/selection.json. Original game characters, story, simulation and view source are versioned. See Docs/VALIDATION.md for actual evidence and remaining acceptance gates.

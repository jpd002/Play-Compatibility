# Play! - Compatibility Tracker

This is the official Play! compatibility tracker. Based on the same concept for cxbx: https://github.com/Cxbx-Reloaded/game-compatibility.

# Guidelines

The games can be tested on either platform, but you can add the info about the platform it was tested on in the report. The compatibility should be more or less the same for every supported platform. If there's conflicting reports about a game's status on different platforms it probably means there's a platform specific bug that should be addressed differently than a compatibility issue. In that case, please open an issue on the main repository.

The games can be tested on the build you've made yourself. Just specify the commit hash of your build in the report.

# Game statuses

**state-playable** means that the game is fully playable.

**state-ingame** means somewhat playable past title screens (including with graphics bugs, crashes, and other major problems).

**state-intro** means nothing but an intro/opening of the game is shown (such as a video/animation/company name/etc.).

**state-loadable** means that the game is capable of being read but can't actually start/run yet.

**state-nothing** means that the game won't even be read by the emulator and/or crashes the emulator before the game even gets to show much of anything.

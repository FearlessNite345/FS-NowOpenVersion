# Changelog v1.1.1

- Made a small tweak so `postals.json` can tolerate a few stray comments left inside without breaking anything.

# Changelog v1.1.0

- Added support for fully optional database persistence for businesses (disabled by default).
- Added an option in the business directory to **close** a business without deleting it (works without a database).
- Replaced the old `Config.deleteBusinessOnLeave` setting with `Config.onLeaveAction`, allowing you to choose whether a business is closed or deleted when leaving.
- Added a new **EDIT MODE** in the `/openbusiness` UI to edit businesses you already own.
- Introduced a **PRESETS** feature to save businesses as reusable templates for future use (does not require a database).
- Tweaked various UI elements in the `/openbusiness` interface for a cleaner experience.

# Changelog v1.0.2

- Fixed an issue where texting your own number would cause you to get stuck in the NuiFocus.

# Changelog v1.0.1

- Fixed an issue where the version checker incorrectly directed users to GitHub, even when the update should be downloaded from the CFX portal.
- Texting your own number now has no effect to prevent unintended behavior.

# meshtastic-android (v4 fork)

> This is a fork of `meshtastic/Meshtastic-Android` on the `v4` branch.
> When merging upstream releases, consult the V4 Modifications section
> to understand which conflicts are expected vs accidental.

## Upstream Base

- **Tag:** v2.7.13
- **Commit:** 7a68802bc2b8cdb9c76a77f2093aac130fc8ec05
- **Channel:** stable
- **Upstream repo:** meshtastic/Meshtastic-Android
- **Fork repo:** ncwn/meshtastic-android

## Build

- Gradle-based Android project
- Build: `./gradlew assembleDebug`
- Test: `./gradlew test`
- See `build.gradle.kts` for dependencies and SDK versions

## Rules

- Always merge upstream, **never rebase v4**
- Update the V4 Modifications section below when changing files
- Feature work goes on branches off v4, merged back to v4
- After pushing v4, update the wrapper repo submodule SHA

## V4 Modifications

<!-- When you modify a file, add an entry here:

### path/to/File.kt
- **What:** Brief description of the change
- **Why:** Reason this modification is needed for the v4 project
- **Conflict risk:** Low / Medium / High when merging upstream
-->

_No modifications yet — v4 branch starts clean from upstream base._

### New Files

<!-- Files added that don't exist in upstream -->

_None yet._

### Deleted Files

<!-- Upstream files removed intentionally -->

_None yet._

# Third-party material

Psychopomp is MIT-licensed (`LICENSE`). The parts below are derived from other projects and stay
under their licenses as well; the full texts are in `LICENSES/`.

## xmake-io/xmake-skills

- Source: <https://github.com/xmake-io/xmake-skills>, commit `ef67caa`.
- License: Apache License 2.0 (`LICENSES/Apache-2.0.txt`).
- Used in: the `xmake-*` skills under `skills/` (not in the tree yet; the table is the plan they
  follow). Each is rewritten for the Charon toolchain and
  modified: content that does not apply to apps for old iOS was removed, advice that conflicts with
  Charon was replaced, and new material was added. Each file says at its top which upstream skills it
  derives from.

| Skill here | Upstream skills |
| --- | --- |
| `xmake-basics` | `xmake-env-vars`, and material on targets, modes and configuration |
| `xmake-packages` | `xmake-packages`, `xmake-addons` |
| `xmake-objc` | `xmake-objc` |
| `xmake-swift` | `xmake-swift` |
| `xmake-rules` | `xmake-rules` |
| `xmake-toolchains` | `xmake-toolchains`, `xmake-cross-compilation` |
| `xmake-scripting` | `xmake-scripting`, `xmake-script-modules` |
| `xmake-tests` | `xmake-tests` |
| `xmake-troubleshooting` | `xmake-troubleshooting` |

## mattpocock/skills

- Source: <https://github.com/mattpocock/skills>, commit `c55ee46`: the skills `grilling` and
  `grill-me` (and the earlier `grill-me` at `a6bdfd9`).
- License: MIT, Copyright (c) 2026 Matt Pocock (`LICENSES/MIT-mattpocock-skills.txt`).
- Used in: `skills/init`. Its interview follows their approach: a design tree, rounds that ask
  the whole frontier with a recommended answer each, facts looked up rather than asked, and done
  only when every branch is settled and the user confirms. The text was written anew for this plugin.

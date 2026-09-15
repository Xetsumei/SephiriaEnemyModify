# EnemyModify 1.6.1

- README and patch notes are available in the GitHub repository and are not included in release ZIPs.


[한국어](README_ko.md) · [English](README_en.md) · [日本語](README_jp.md) · [中文](README_zh.md)

A Sephiria mod for monster bans, randomizers, and elite enemy modifiers. Open EM Options in the game to configure it. QoL and DungreedEnemies are optional.

## 1.6.1 — 2026-09-15

- Release update history is available in the `patchlog` files.

## Features

- Monster bans: choose normal, miniboss, and boss candidates by floor. The last required candidate is kept.
- Randomizers: replace normal monsters and minibosses, with per-floor settings.
- Modifiers: configure 23 types, their chances, tier weights, and rewards.
- Settings, modifier names and descriptions, and notices follow the game language: Korean, English, Japanese, or Simplified Chinese.
- `/em ban all` applies bans in bulk; `/em ban off` removes them.
- Everyone in a multiplayer modifier lobby needs EM. The host chooses run settings.

## Installation

Extract the ZIP into `Sephiria/AddOns/EnemyModify`. Keep `metadata.json`, the DLL, and `Libs` together.

## Automatic updates

When you enter the game, the mod checks for a new version. In the lobby, choose Update now, Remind me later, or Skip this update. Update now downloads the release and restarts the game. Automatic prompts and restarts are postponed during a run.

Use `/em update` to check manually, `/em update off` to turn off automatic checks, and `/em update on` to turn them back on. A manual check also shows a version you skipped.

Downloads are verified before installation. Your settings carry over. If a release changes Libs, download the ZIP and install it with the game closed.

Older versions without this feature need one manual ZIP installation first.

[Update history](patchlog_en.md)

After entering the game, once your character and chat display are ready, a single `[EnemyModify] Up to date.` notice or a new-update notice appears. Update prompts wait for other mods’ prompts to close. Disabled checks and skipped versions do not show an automatic update prompt.

# EnemyModify 1.6.7

- README and patch notes are available in the GitHub repository and are not included in release ZIPs.

[한국어](README_ko.md) · [English](README_en.md) · [日本語](README_jp.md) · [中文](README_zh.md)

A Sephiria mod for monster bans, randomizers, and elite enemy modifiers. Open EM Options in the game to configure it. QoL and DungreedEnemies are optional.

## Recent changes — 1.6.7 (2026-09-17)

- Updated the README and patch notes to match current features, including the boss/miniboss stun and freeze immunity option, automatic update settings, and manual installation instructions.
- This release does not change gameplay behavior.

## Features

- Monster bans: choose normal, miniboss, and boss candidates by floor. The last required candidate is kept.
- Randomizers: replace normal monsters and minibosses, with per-floor settings.
- Modifiers: configure 23 types, their chances, tier weights, and rewards.
- Settings, modifier names and descriptions, and notices follow the game language: Korean, English, Japanese, or Simplified Chinese.
- `/em ban all` applies bans in bulk; `/em ban off` removes them.
- Everyone in a multiplayer modifier lobby needs EM. The host chooses run settings.
- Boss/miniboss stun and freeze immunity: enable it in the General tab (off by default). Ice damage and frostbite stacks still apply. Multiplayer uses the setting chosen by the host.

## Installation

Close the game, download `EnemyModify.zip` from the latest Release, and extract it into `Sephiria/AddOns/EnemyModify`. The extracted `metadata.json`, `EnemyModify.dll`, and `Libs` must be directly inside that folder. When updating an existing installation, overwrite the files in the same location and keep `EnemyModify.json` and `update-settings.json`.

## Automatic updates

When you enter the game, the mod checks for a new version. In the lobby, choose Update now, Remind me later, or Skip this update. Update now downloads the release and restarts the game. Automatic prompts and restarts are postponed during a run.

Use `/em update` to check manually. Turn off [Automatic updates] in the [General] tab of EM Options to stop the startup check and update prompt; you can then check only with `/em update`. `/em update off` and `/em update on` change the same setting. A manual check also shows a version you skipped.

When you re-enable the Automatic updates checkbox in the General tab, automatic checks resume on the next game launch. Use `/em update` to check immediately.

Downloads are verified before installation. Your settings carry over. If a release changes Libs, download the ZIP and install it with the game closed.

Older versions without this feature need one manual ZIP installation first.

[Update history](patchlog_en.md)

After entering the game, once your character and chat display are ready, a single `[EnemyModify] Up to date.` notice or a new-update notice appears. Update prompts wait for other mods’ prompts to close. Disabled checks and skipped versions do not show an automatic update prompt.

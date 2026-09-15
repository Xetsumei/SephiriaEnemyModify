# EnemyModify 1.6.0

[한국어](README_ko.md) · [English](README_en.md) · [日本語](README_jp.md) · [中文](README_zh.md)

用于设置塞菲莉亚怪物禁用、随机化及精英敌人词缀的模组。在游戏的［EM 设置］中调整。无需安装QoL或DungreedEnemies也可使用。

## 主要功能

- 怪物禁用：按楼层选择普通怪物、中BOSS及BOSS候选，保留推进所需的最后一个候选。
- 随机化：替换普通怪物和中BOSS，支持分层设置。
- 词缀：设置23种词缀的启用、概率、阶级权重及奖励。
- 设置、词缀名称和说明、提示跟随游戏语言，支持韩语、英语、日语、简体中文。
- `/em ban all`批量禁用，`/em ban off`全部解除。
- 联机词缀房间的所有玩家都需安装EM，本局设置由房主决定。

## 安装

将ZIP解压至`Sephiria/AddOns/EnemyModify`，将`metadata.json`、DLL与`Libs`保存在同一文件夹。

## 自动更新

进入游戏后会检查新版本，并在大厅提供［立即更新・稍后提醒・跳过此更新］。点击立即更新后会下载并重启游戏。冒险中不会自动弹窗或关闭游戏。

用`/em update`手动检查，`/em update off`关闭自动检查，`/em update on`重新开启。手动检查也会显示已跳过的版本。

文件通过验证后才会安装，现有设置会保留。若新版本更改了Libs，请下载ZIP并关闭游戏后覆盖安装。

没有此功能的旧版本需要先手动安装一次新ZIP。

[更新记录](patchlog_zh.md)

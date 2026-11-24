# -Astral-Chain-Combat-Rumble
基于[《异界锁链》PC 重编译项目](https://github.com/captainj-sparrow/astral-chain-pc-recomp)的震动扩展模组，为主角武器和雷基恩的攻击添加与出招节奏同步的手柄震动。A rumble mod for the [Astral Chain PC recompilation](https://github.com/captainj-sparrow/astral-chain-pc-recomp) that adds controller feedback timed to weapon and Legion attacks.
# Astral Chain Combat Rumble ·《异界锁链》战斗震动


本模组为[《异界锁链》PC 重编译版](https://github.com/captainj-sparrow/astral-chain-pc-recomp)补充战斗震动，保留游戏原有的震动。反馈对齐武器和雷基恩的出招动作：即使挥空也能感到挥击

### 已在 Steam Deck 实测

- **警棍：** 开局四连击每段各震一下，最后一拍对准向前突刺的瞬间。
- **初始手枪：** 连续三轮点射，每轮三发，每一发都有与枪声同步的短震。
- **剑型雷基恩：** 自主攻击时，普通三连、上挑和下砸都有反馈；回旋斩用四拍震动跟随旋转节奏。

测试环境：游戏 `1.0.1`，PC 重编译版 `1.19.3+fc285fc`。已在 Steam Deck 上使用内置及外接手柄测试；Windows 尚未验证。

**实验性内容：** 已加入后期警棍与手枪连段、大剑，以及斧、弓、腕、兽型雷基恩的部分招式，尚未逐招实测。部分动作由敌我共用，可能在敌方出招时触发。扩展招式按类型区分轻重，最重的砸地设为 100% 模组强度；实际手感取决于手柄和游戏的全局震动设置。

### 安装与卸载

1. 完全退出游戏，把整个 `CombatRumble-Complete` 文件夹放到游戏的 `mods` 目录中。安装后路径应为 `mods/CombatRumble-Complete/romfs/`。
2. 停用其他替换 `pl/pl.pkz` 或 `em/em.pkz` 的模组，再启动游戏。若没有震动，可在日志中查找 `CombatRumble-Complete: on, romfs, ok`，并确认两份资源均已加载且没有被覆盖。

**卸载：** 退出游戏，将 `CombatRumble-Complete` 移出 `mods` 后重启即可。

This mod adds combat rumble to the [Astral Chain PC recompilation](https://github.com/captainj-sparrow/astral-chain-pc-recomp) while keeping the game’s original rumble. Feedback follows weapon and Legion attacks, so you can feel a swing even when it misses.

### Verified on Steam Deck

- **Baton:** Each strike in the starting four-hit combo has its own pulse. The last pulse lands as the baton thrusts forward.
- **Starting Blaster:** Each shot in the three-burst combo has a short pulse timed to the gunshot. Each burst fires three shots.
- **Sword Legion:** Its autonomous triple slash, rising slash and slam have rumble. The spinning slash has four pulses timed to the spin.

Tested with game version `1.0.1` and PC recompilation `1.19.3+fc285fc`, using both the Steam Deck’s built-in controls and an external controller. Windows has not been tested.

**Experimental coverage:** Later Baton and Blaster combos, Gladius attacks, and selected Axe, Arrow, Arm and Beast Legion moves are included but have not been verified move by move. Shared animations may also trigger rumble for enemies. The new moves use different pulse strengths and lengths; the heaviest slams request 100% intensity. Actual feedback depends on the controller and the game’s global rumble settings.

### Installation and removal

1. Quit the game and copy the entire `CombatRumble-Complete` folder into its `mods` directory. The resulting path should be `mods/CombatRumble-Complete/romfs/`.
2. Disable any other mod that replaces `pl/pl.pkz` or `em/em.pkz`, then start the game. If you feel no rumble, look for `CombatRumble-Complete: on, romfs, ok` in the log and check that both archives loaded without being overridden.

**To uninstall:** Quit the game, move `CombatRumble-Complete` out of `mods`, and restart.

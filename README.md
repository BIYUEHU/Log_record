# Log_record行为记录
这是一个基于**Script Engine**的Addon

## 什么是Script Engine？
脚本引擎(Script Engine)简称为"SE"，Minecraft基岩版的脚本引擎系统为**Addon附加包**的一部分，由**JavaScript语言**为载体。
用于制作更多较为复杂的带有逻辑性的作品

不过遗憾的是，Minecraft基岩版的SE目前并未成熟，API接口不完整且仅对WIN10基岩版开放了使用权，所以本Addon仅支持WIN10基岩版。

## 介绍
中文名字：行为记录
英文名字：LOG record
最新版本：
支持MCBE版本：1.16.X
支持平台：WIN10
开源地址：#这里

该插件可用于服务器，且无需使用任何第三方MOD端，原生BDS即可加载使用！
目前一共支持24种玩家行为监听与记录，总计40+种结果！
已支持事件：
``` json
{
  "event": [
         "minecraft:block_interacted_with", 
         "minecraft:block_destruction_started",
         "minecraft:block_destruction_stopped",
         "minecraft:player_placed_block",
         "minecraft:player_destroyed_block",
         "minecraft:piston_moved_block",
         "minecraft:entity_carried_item_changed",
         "minecraft:entity_dropped_item",
         "minecraft:entity_acquired_item",
         "minecraft:entity_equipped_armor",
         "minecraft:entity_use_item",
         "minecraft:entity_death",
         "minecraft:entity_start_riding",
         "minecraft:entity_stop_riding",
         "minecraft:block_exploded",
         "minecraft:entity_sneak",
         "minecraft:entity_attack",
         "minecraft:projectile_hit",
         "minecraft:entity_hurt",
         "minecraft:weather_changed",
         "minecraft:entity_definition_event",
         "minecraft:play_sound",
         "byh:jinrushijie",
         "minecraft:client_entered_world"
       ]
}  
```

部分日志将会在聊天栏内提示，所有事件日志均会保存至：
C:\Users\账号\AppData\Local\Packages\Microsoft.MinecraftUWP_8wekyb3d8bbwe\LocalState\logs


## 更新日志
更新日志：
新增24种监听事件(23种服务端事件,1种客户端事件)
共计40+种结果


## 导入使用
### 单机
方法1.将压缩包**后缀名**更改为.mcaddon接着双击即可
方法2.解压，然后复制到：
C:\Users\账号\AppData\Local\Packages\Microsoft.MinecraftUWP_8wekyb3d8bbwe\LocalState\games\com.mojang\behavior_packs

### 服务器
*仅对BDS端或基于BDS端的第三方MOD端有效
解压，复制到 服务端根目录\behavior_packs 文件夹 与 服务端根目录\worlds\地图名\behavior_packs 文件夹


## 关于
作者：碧月狐dada
在**@Bilibili**关注[我*]()

# 给钟插件

## 简介

`LiteLoaderBDS`菜单插件，菜单的增删改均可在游戏内通过GUI完成，无需手写配置，开箱即用。

目前仅在`1.19.60`测试通过，其他版本未测试。

## 安装

将`xmenu.js`放入`plugins`文件夹后重启服务器即可。

## 功能

- 使用游戏内指令`/xmenu`或`/xm`即可打开菜单。
- 使用游戏内指令`/editxmenu`或`/em`即可编辑菜单。
- 使用游戏内使用***钟***(默认为钟，可自行配置)右键即可打开菜单。

## 配置说明

配置文件路径：`plugins/XMenu/config.json`

```json
{
    // 打开菜单的命令
    "openMenuCommand": "xmenu",
    // 打开菜单的命令别名(效果同上)
    "openMenuCommandAlias": "xm",
    // 编辑菜单的命令
    "editMenuCommand": "editxmenu",
    // 编辑菜单的命令别名(效果同上)
    "editMenuCommandAlias": "em",
    // 使用指定物品右键后打开菜单(和下面的二选一配置即可)
    "openMenuByUseItem": "minecraft:clock",
    // 使用指定物品对方块右键后打开菜单(和上面的二选一配置即可)
    "openMenuByUseItemOn": "",
    // 主菜单页名称
    "menuName": "主菜单"
}
```

## 开源地址

[开源地址(gitee)](https://gitee.com/xclhove/LiteLoaderBDSPlugins-XMenu)

[开源地址(github)](https://github.com/xclhove/LiteLoaderBDSPlugins-XMenu)

## 最新版下载链接

[gitee](https://gitee.com/xclhove/LiteLoaderBDSPlugins-XMenu/releases/download/v1.2.0/GiveClock.js)

[github](https://github.com/xclhove/LiteLoaderBDSPlugins-XMenu/releases/latest/download/GiveClock.js)

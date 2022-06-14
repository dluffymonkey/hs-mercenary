# 全自动炉石佣兵插件
本插件为全自动佣兵插件，目标做到全自动，自动练级，自动做任务，自动升级，自动换佣兵。
## 特别声明
本插件为学习C#所制，免费使用，不可用于盈利目的。在你下载了该插件之后代表你同意本声明
## 使用说明
下载[最新的版本](https://codeload.github.com/jimowushuang/hs-mercenary/zip/refs/heads/main) 解压放到炉石根目录。
打开炉石自动推门进入证明插件安装成功。

插件默认会使用名称为PVE的队伍，会自动刷2-5这个图，会自动选择距离神秘人最近的路径，会自动根据当前任务更换佣兵，自动做任务，佣兵满级会自动更换未满级的佣兵，当然这些逻辑都可以修改，配置文件的路径如下。
```
BeplnEx/config/io.github.jimowushuang.hs.cfg
```

## 配置列表  

|  配置项   | 说明  | 默认值|
|  ----  | ----  | ---- |
| 使用的队伍名称  | 刷图使用的队伍名称 | PVE  |
| 要刷的地图  | 要刷的地图|  2-5   | 
| 自动升级技能  | 开启之后如果可以升级技能会自动升级 |  true   | 
| 自动制作佣兵  | 开启之后如果硬币足够会自动制作新佣兵 |  true   | 
| 刷图模式  | 0: 刷图 1: 刷神秘人 2: 全自动,自动接任务做任务 |  0   | 
| 队伍人数  | 队伍人数不够的时候插件会自动填充队伍人数 |  6   | 
| 核心队伍人数  | 前n个核心队伍人数不会被自动更换 |  0   | 


## 辅助工具
[炉石监控程序](https://github.com/jimowushuang/hs-control/releases/tag/v1.0.0) 可以在炉石异常退出的时候重启炉石
## 交流群
QQ群: 792054397


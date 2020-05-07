### 1.6.5 [2020/04/29]
**美化皮肤**  
修复了与 11.38 的兼容性问题  

**进度追踪**  
自动交接任务按键默认关闭（最近看直播发现很多人连移动一下都不愿意）  

### 1.6.4 [2020/04/22]
**核心**  
添加了通用的永久去除文字阴影函数  
添加了通用的数据库参数的文字风格渲染函数  
添加了 ElvUI 设定面板中的版本提示

**聊天条**  
修复了切换配置时可能导致的数据库读取错误  
修复了世界频道条的频道设置错误导致后续按键无法生成的问题  
调整世界频道默认为不加载  
调整初始材质为 Melli  
添加聊天条的社群功能，开启前请先设定频道名，并在社群中添加到聊天框  

**腐化等级**  
修复启用SLE观察增强时看不到对方腐蚀的问题

**好友列表增强**  
使用更新后的好友 API 完全重写了模块  
从暴雪官网提取了最新游戏的图标  
怀旧服的阵营，职业，等级，所在地现在可以显示了  
角色好友现在也会进行美化了  
调整了好友名的显示模版，适应较长 ID 的玩家  
添加了好友名的游戏染色设定  
添加了好友名的职业染色设定  
添加了好友名的满级隐藏等级设定  
支持自定义所在地文字的颜色  

### 1.6.3 [2020/04/21]
**核心**  
更换条材质设定的获取方式，以尝试兼容其他增强  

**美化皮肤**  
添加聊天面板数据条的美化  
添加动作栏背景的美化  
修复了在特写框体无背景时依旧执行美化的问题  

**自动物品按键**  
添加禁用装备按键的功能（仅用于任务物品）  

**腐化等级**   
修复观察他人腐化信息的提示  

**聊天条**  
修复了聊天条背景启用时无法应用 Wind 美化外观的问题  

### 1.6.2 [2020/04/19]
**核心**  
界面库回退到正式版  

**修复神器幻化**  
新增模块，修复神器无法保存到幻化的问题

### 1.6.1 [2020/04/19]
**核心**  
添加设定用的界面库  

**聊天条**  
添加鼠标滑过显示设定  

### 1.6.0 [2020/04/17]
**核心**  
补上一些遗漏的翻译  
填补部分 ElvUI 未创建的翻译条目  
减少污染  

**巅峰声望**  
修复巅峰和崇拜文字显示不正确的问题    

**Tab 切换频道** -> **聊天窗口增强**  
为了容纳更多功能，更名之~

* 为链接添加信息显示（新）  
（新）可选添加图示    
（新）可选添加等级  
（新）可选添加护甲分类  
（新）可选添加武器分类  
（新）可选添加腐化等级  

* 使用 Tab 切换频道   
修复了一些情况下切换目标不正常的问题  
将历史数据存在 ElvUI 数据库中，换号，重载界面都不会清理  

* 表情（新）  
（新）自动识别聊天框和聊天气泡中的表情代码并美化  
（新）可选开启表情面板（这个设定新模块 聊天条 也有联通）  
（新）可设置的表情显示大小  
（新）可拖拽的表情面板，初始位置可用 ElvUI 调整  

* 输入修正（新）  
（新）可选开启顿号到斜杠的转换  

**聊天条**（新）  
新增模块，支持块状风格和文字风格的切换。
位置可在 ElvUI 设定中调整  

* 通用设定  
（新）可选开启聊天条的背景  
（新）可选开启智能隐藏（根据公会和队伍情况）  
（新）可设置的边距（同样作用于按钮的间距）  
（新）可设置的对齐方向，水平或是垂直  
（新）可设置的按钮大小  
（新）可设置的频道颜色  
（新）可设置的世界频道名，适应各个服务器的习惯（或者自己车队的频道）  
（新）可选的世界频道自动加入  

* 块状风格设定  
（新）可选开启按钮的阴影    
（新）可设置的按钮材质  

* 文字风格设定  
（新）可设置的频道缩写  
（新）可设置的字体，大小，渲染风格  
（新）可选的表情和投掷可用图标替代文字功能  

**腐化等级**（新，移植自 NDui）  
添加鼠标提示腐化等级的提示

**通告系统**  
添加了延迟播报感谢的功能  

**暴雪框体增强**  
采用 BlizzMove 的函数重写了模块  
支持更多的框体移动  
支持 Ctrl+滚轮 放大缩小，Ctrl+点击 恢复  
支持 Shift+点击 恢复位置  
为插件和模块兼容提供更多提示  

**美化皮肤**  
调整美化进度条的背景为透明  
修复成就进度追踪的图标美化问题  
修复 AddOnSkins 美化的一些问题  
修正初次点击物品浮动提示的美化  
修正浮动提示血条的美化  
完善了特写窗口的美化  
添加了奖励目标的美化  
添加了邮件收发界面的美化  
添加了搜寻公会界面的美化  
添加了社群界面的美化  
添加了冒险指南的美化  
添加了美发界面的美化  
添加了聊天频道设定的美化  
添加 PvP 天赋选择页面的美化  
添加了新建宏命令界面的美化  
添加了物品讯息界面的美化  
添加了场景任务阶段提示的美化  
添加了 Immersion 文字，奖励背景的美化  
修正了 Immersion 的对话框大小  
修正了 Immersion 有时候会去除对话图标的问题  

**光速拾取（加快拾取速度）**  
优化代码  
修复无法设定拾取检查频率的问题  

**删除增强**  
添加了之前 Wind 工具箱增强模式（经典版？）  

**浮动提示增强**  
修复一个可能的数据库报错  

**进度追踪**  
修复了交接任务按钮大小设定问题  

**关闭视频通话** -> **关闭特写框架**  
支持配置的热更新  

### 1.5.12 [2020/04/09]
**核心**  
添加专用的 ElvUI 元素移动分类【Wind工具箱】  
补上一些遗漏的简体翻译  
修改一些繁体中文的翻译  

**解锁过滤器**  
新增模块，来源EKE@NGA  
URL: https://nga.178.com/read.php?tid=21171325  

**Tab 切换频道**  
重写切换逻辑  
自动记录10分钟内自己发出密语的对象和接收密语的对象  
*开启独立密语循环选项*  
当前频道为战网或是密语 | 自动循环(战网+密语记录中的玩家)  
当前频道为常规频道 | 自动循环(常规频道)  
*没有开启独立密语循环选项*(此为默认)  
自动进行(常规频道+战网+密语记录中的玩家)循环  

**美化皮肤**  
优化美化性能  
修复部分框体可能出现的阴影错位问题  
修复 AddOnSkins 部分插件美化层层级不正确的问题  
添加跳过剧情动画提示框的美化  
添加 ElvUI 提示框的美化  
添加 PvP 遗漏天赋提示的美化  
添加任务详情及奖励界面美化  
自动对齐声望详情框架  
分开左右聊天面板的美化设定  

**艾泽利特特质鼠标提示**  
添加了锚点设定 
修复了图标显示不正确的问题  
对图标进行一些改动以节约提示框架空间  

**进出战斗提示**  
重写模块  
重新设计了全新的动画控制系统，可达满帧  
修复了设定文字不起作用的问题  
修复了切换配置文件时导致的错误  
修复了可能出现的数据库报错  

**浮动提示增强**  
修复了对比装备时提示错位的问题  

**进度追踪**  
自动交接任务按键现在可以在 ElvUI 中移动了  
添加自动交接任务按键文字设定  
添加自动交接任务按键颜色设定  

**团队标记**  
修复第一次进入世界时无法显示阴影的问题  

### 1.5.11 [2020/04/07]
**核心**  
修复一个翻译错误    

**小地图按钮**  
修复与 S&L 的兼容性问题  

**团队标记**  
修复与 S&L 的兼容性问题  

**美化皮肤**  
添加 Immersion 美化功能  

### 1.5.10 [2020/04/07]
**小地图按钮**  
修正数据库问题  

**团队标记**  
修正数据库问题  
更换刷新钩子  

**美化皮肤**  
将 AddOnSkins 皮肤转为 ElvUI 风格  
采用透明风格美化标签页  
接管 Ace3 插件的按键，背景，标签页，滚动条  
添加等待进入团队时候的鼠标提示美化  

**浮动提示增强**  
添加浮动提示的血条和文字移动功能  

**进度追踪**  
添加自动任务交接功能  
添加自动交接任务按键，大小字体位置可自定义  

### 1.5.9 [2020/04/06]
**删除增强**  
解决误触问题  

**美化皮肤**  
修正世界地图的边框阴影位置  

**小地图按钮**  
修正数据库问题  

**团队标记**  
修正数据库问题  
阴影美化进一步修正  

### 1.5.8 [2020/04/05]
**自动摧毁** --> **删除增强**  
重写模块，消除游戏污染  
更换为了点击确认模式  
添加了 Delete 按键删除物品的功能  

**Tab 切换频道**  
重写模块，消除游戏污染  
增加更多选项和战场频道  

**美化皮肤**  
为 WindTools 的功能框架提供阴影支持  
添加特写框架的阴影  
修复 BigWigs 阴影不适用的问题  

**小地图按钮**  
重新移植，来源 ElvUI_Enhanced  
修复报错  

### 1.5.7 [2020/04/03]
**美化皮肤**  
添加保镖界面美化  
添加离开载具按钮美化  
添加失去控制美化  
添加输入框和输入法指示器美化  
完善好友界面的美化  
完善对 Ace3 插件的支持  

**浮动提示增强**  
添加麦卡贡的支持  
添加尼奥罗萨的支持  

**声望追踪**  
新增模块，需手动开启  

**通告系统**  
添加了副本重置的通告  

**好友列表增强**  
修复新游戏导致的图标错误  

### 1.5.6 [2020/03/29]
**美化皮肤**  
紧急修复一个变量报错  

### 1.5.5 [2020/03/29]
**核心**  
采用了新的 Logo 样式和插件名样式  
修复了新版 ElvUI 中部分翻译无效的问题  

**暴雪框体增强**  
移除了登录游戏时的一个报错    

**好友列表增强**  
修复在线时间错误导致的报错  

**Tag 增强**  
增加了一个开关来控制额外的 Tag  

**屏幕景深**  
修改模块说明  

**进度追踪**  
微调百分比位置  

**世界地图增强**  
迷雾去除更新到全部新地图  

**美化皮肤**  
修复 WeakAura2 美化  
添加 ElvUI 设定界面的美化  

### 1.5.4 [2020/03/23]
**美化皮肤**  
修复世界任务重复描边问题  
添加拍卖行界面的美化  

**暴雪框体增强**  
添加拍卖行界面的移动    

### 1.5.3 [2020/01/31]
**核心**  
适配了 ElvUI 11.33 版本新布局  

**Tag 增强**  
去除了中文万亿功能，ElvUI 已经支持  

**好友列表增强**  
修复一处 API 调用错误  

### 1.5.2 [2020/01/22]
**核心**  
支持版本号更新  

**好友列表增强**  
修复一处 API 调用错误  
删除冗余代码（感谢 404Polaris@Github）  

### 1.5.1 [2019/10/05]

**核心**  
支持版本号更新  

**团队标记模块**  
修复世界标记错位的问题  

**好友列表增强**  
错误修复（感谢 404Polaris@Github）  

**美化皮肤**  
移除了过时 AlertSystem 的 hook，并新增两项（感谢 404Polaris@Github）  

**暴雪框体增强**  
为移动功能增加了检测，与 Shadow & Light 同功能选项冲突时将有所提示（感谢 404Polaris@Github）  

-----
### 1.5.0 [2019/8/29]

**核心**  
支持版本号更新  
补充修复多处错误  
修复了几处引入热更新后出现的错误  

**好友列表增强**  
修复以及优化好友列表增强模块。  

**团队标记模块**  
完善功能，现在可以添加、移除单个标记，也可以同时移除全部标记。  

**艾泽利特特质鼠标提示**  
同步最新版艾泽利特特质鼠标提示。  

**浮动提示增强**  
在中加入永恒王宫支持（感谢 @LiangYuxuan）  

**新功能**  
现在（部分）支持配置文件的热更新。  

-----
### 1.4.7 [2019/7/8]

**暴雪框体增强**  
同步SLE，并添加艾泽利特特质、精华、重铸界面的支持。  

**新功能**  
添加团队标记模块 （源于SLE，感谢 @mcc1 的移植）  

-----
### 1.4.6 [2019/6/6]

**美化皮肤**  
添加开关音效文字美化  
添加试衣间美化  
修復模组可能出现的報錯  

-----
### 1.4.5 [2019/5/15]

**核心**  
添加多语言切换支持  

**Tag 增强**  
更加高效的自动转换 W,Y 为万亿  
支持全新的 ElvUI 缩写函数  

**通告系统**  
修复了感谢复活时非同服玩家出现找不到玩家的问题  

**美化皮肤**  
更新公会面板美化  
添加日历面板美化  
添加飞行地图美化  
添加跳过动画美化  
添加飞出按钮美化  
优化模块占用  

-----
### 1.4.4 [2019/4/17]

**任务列表增强** -> **进度追踪**  
新模块，为了替换被删除的模块任务列表增强  
可更高效的修改进度追踪框体之中的字体，大小及描边  
支持职业色染色，或是自定义标题颜色，高亮颜色  
完善世界任务，其他进度追踪染色失败的问题

**艾泽里特特质提示**
更新移植的功能
修复报错
优化性能

**任务通告**  
暂时去除了完成任务后不追踪的功能

**通告系统**  
修复了一个可能会在非团队中使用团队频道的错误  
删除了复活感谢中的一个多余开关  
调整了嘲讽技能通告的默认设定，玩家嘲讽为开启  
调整了战斗技能通告的默认设定，在独自一人情况下不会发送  

**浮动提示增强**  
移植了 NDui 之中的浮动提示图标功能  

**简单阴影** -> **美化皮肤**  
全新制作的美化皮肤模块，不仅仅局限于阴影添加  
精简美化设置，分类更加贴心，方便大家快速设定  
移植 BenikUI 之中的 Weakauras 美化  
移植 BenikUI 之中的 BigWigs 美化  
移植 BenikUI 之中的 AddOnSkins 美化  
更换了原 Wind 工具箱函数为 ElvUI 自带函数来生成阴影  
更换了原移植自 NDui 的任务物品美化为 ElvUI 自带函数美化  
修复了单位框体的光环美化  
修复了许多阴影大小不一致错位的问题  
在仇恨阴影存在时，自动隐藏美化  
添加要塞面板，职业大厅任务，阵营任务美化  
添加人物面板，天赋面板，法术书面板美化  
添加冒险指南面板，收藏面板美化  
添加公会面板，聊天频道选择框，下拉框美化  
添加插件面板，游戏特色面板。按鍵绑定面板美化  
添加商人界面，职业大厅条，复活天使姐姐框架美化  
添加传奇地城框架，右键框架，团队控制框架美化  
添加 ElvUI 数据条美化  
添加 ElvUI 额外能量条美化  
添加 ElvUI 背包框架美化  
添加输入法选词美化  
添加错误框架美化  
性能大幅优化  

-----
### 1.4.3 [2019/3/30]

**通告系统**  
自定义通报文字  
自定义频道设置  
新增了副本结束说感谢再见功能  
当队友宠物打断时也能通报其主人打断  
当队友宠物嘲讽时也能通报其主人相关信息  
增加了新的法师传送门  
更新了武僧最新的嘲讽法术  
武僧的群嘲不再会刷屏了  
可为玩家及其他玩家分开设置  
设定页面改为多页面样式  
移除了部分随着版本失效的法术列表  
通告系统的实用技能部分及战斗技能部分将遵从团队权限单人通告

**Tag 增强**  
新增 [classcolor:demonhunter] 的恶魔猎手职业颜色 Tag  
[classcolor:demonhunter] 可用 [classcolor:dh] 代替  
[classcolor:deathknight] 可用 [classcolor:dk] 代替  
新增 [range] 距离 Tag，显示如（25-30）  
新增 [range:expect] 预测距离 Tag，显示如（27），请注意这是预估的！  
适应了 ElvUI 新版本的更高位数单位缩写的支持  
尝试适配了 ElvUI 新版本的姓名板  
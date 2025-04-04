# 希沃窥屏检测器
众所周知，希沃管家可以让老师偷看你在干什么，为了防止摸鱼被老师发现的悲剧，我、[Bedrock510K](https://github.com/Bedrock510K)和[DeepSeek](deepseek.com)完成了这个程序。在我们之前，已经有大佬开发出了[SeewoMonitorSystem](https://github.com/DengHanxu/SeewoMonitorSystem?tab=readme-ov-file#seewomonitorsystem)。不过该项目已经略微过时，所以我们才开发了这个项目~~明明是直接开写没查搜索引擎做出来的轮子~~
# 功能介绍
📢 弹窗提醒：在老师监视你屏幕的时候弹出提示弹窗，弹窗显示的时间可以在更多设置中修改，默认3秒。当提示“screenCapture.exe已启动”时，代表老师正在观察你的屏幕，同时程序创建的托盘图标中心会变成黄色。当提示“rtcRemoteDesktop.exe已启动”时，说明你已经被老师远程控制，此时程序的托盘图标会显示红色\
🔝 弹窗置顶：设置“弹窗提醒”功能的弹窗是否置顶显示\
⌨️ 全局热键：当上述任意一个程序启动时，自动新建桌面，程序退出时删除新建的桌面\
💤 睡眠功能：当上述任意一个程序启动时，自动使电脑进入睡眠状态\
✏️ 更多设置：你可以在这里修改程序检测的时间间隔和弹出弹窗的显示时间
# 关于托盘图标
**中心圆点**
当老师没有在观察你的屏幕的时候，它显示为绿色；当老师正在观察你的屏幕时，它显示为黄色；当老师远程控制你是，它显示为红色\
**内圈**内圈用于表示弹窗置顶和睡眠功能的状态，当弹窗置顶功能启用时显示为全环亮绿色，当只有睡眠功能启用时显示为全环橙色，两个功能都开启时显示为上半环亮绿色(弹窗置顶)下半环橙色(睡眠功能)\
**外圈**外圈用于表示弹窗提醒和全局热键功能的状态，当只有弹窗提醒开启时显示为全环亮蓝色，当只有全局热键开启时显示为全环黄色，两个功能都开启时显示为上半环亮绿色(弹窗置顶)下半环橙色(睡眠功能)
# 注意：此项目99%的代码都由[DeepSeek](deepseek.com)生成

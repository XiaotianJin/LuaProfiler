## xLua的性能分析器组件


### 部署安装
目前支持XLua、SLua、ToLua
把LuaProfiler文件夹Copy到Assets 非Plugin、Editor目录下。
<br/>
XLua取消 "LuaProfiler/HookSetup/XLuaHookSetup.cs" 第10行的注释
<br/>
SLua取消 "LuaProfiler/HookSetup/SLuaHookSetup.cs" 第10行的注释
<br/>
ToLua取消 "LuaProfiler/HookSetup/SLuaHookSetup.cs" 第10行的注释
<br/>
当然你也可以在对应版本的Lua里面把LuaProfiler文件夹导入到你的工程目录中

### 使用教程
点击 "Window->Lua Profiler Window"在弹出窗口上打开 Deep Profiler,然后正常进入游戏即可
<br/>
效果如下
![](doc/profiler.png)
<br/>
#### 小tips
如果GC显示的不平稳，可以stop gc

### 使用项目
![](doc/ljjc.jpg)

---
有什么BUG可以联系QQ 345036769，觉得好用可以捐赠点小钱
<br/>
![](doc/zfb.png)

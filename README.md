# lab3.4
实验三UI组件第四个小题
实验截图https://github.com/1234567Olive/lab3.4/blob/master/3.4.jpg
使用上下文操作模式。此模式是 ActionMode 的系统实现，它将在屏幕顶部显示上下文操作栏，其中包括影响所选项的操作项目。当此模式处于活动状态时，用户可以同时对多项执行操作（如果应用允许）。
使用ListView或者ListActivity创建 为List Item创建ActionMode形式的上下文菜单
使用ListView或者ListActivity创建
为List Item创建ActionMode形式的上下文菜单
使用ActionMode需要两步骤：
1、实现ActionMode.Callback接口，并处理ActionMode的生命周期，
2、事件触发时，调用startActionMode()方法

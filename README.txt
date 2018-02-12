项目名称： 两个frame之间通讯
知识范围： html css js postMessage BroadcastChannel localStorage
版本号  ： 1.1

程序说明：一个frame进行操作后另一个frame同步操作
功能说明：
    1、一个frame操作，另外的frame能同步
辅助说明：
    （默认） 1、一个frame点击，另外的frame进行操作（√）
    （默认） 2、父页面点击，子frame进行操作（√）

文件说明：
    两个子frame之间通讯
        father1.html           父级界面
        father1_children1.html 一个子界面  （发送信息）
        father1_children2.html 另一个子界面（接收信息）
    父子frame之间通讯
        father2.html           父级界面    （发送信息）
        father2_children1.html 一个子界面  （接收信息）
    类似广播的通讯
        father3.html           父级界面
        father3_children1.html 一个子界面  （发送信息）
        father3_children2.html 一个子界面  （接收信息）
        father3_children3.html 一个子界面  （接收信息）
    简单通讯
        father4_1.html         一个界面    （发送信息）
        father4_2.html         另一个界面  （接收信息）
使用说明：
    两个子frame之间通讯
        打开father1.html页面，在页面1中点击，在页面2中就能看到消息
    父子frame之间通讯
        打开father2.html，点击按钮就能看到内容改变
    类似广播的通讯
        打开father3.html，在页面1中点击，在页面2 3中就能看到消息
    简单通讯
        打开father4.html点击1，再点击2
引用说明：
    仅做参考
其他说明：无

问题：无
注意：无

-----------------------初次修改-----------------------
编写时间： 2018/2/6~2018/2/6
编写人员： 石婧宜
版本号  ： 1.1
修改内容：
	两个子frame之间通讯
        father1.html           父级界面
        father1_children1.html 一个子界面  （发送信息）
        father1_children2.html 另一个子界面（接收信息）
    父子frame之间通讯
        father2.html           父级界面    （发送信息）
        father2_children1.html 一个子界面  （接收信息）
    类似广播的通讯
        father3.html           父级界面
        father3_children1.html 一个子界面  （发送信息）
        father3_children2.html 一个子界面  （接收信息）
        father3_children3.html 一个子界面  （接收信息）
    简单通讯
        father4_1.html         一个界面    （发送信息）
        father4_2.html         另一个界面  （接收信息）
修改后的引用说明：仅做参考
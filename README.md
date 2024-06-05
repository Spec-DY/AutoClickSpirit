# Apex自动挂机
这是一个基于OpenCV的简易Python脚本，支持一次输入多个Apex英雄并规定每个英雄的跳伞次数，然后开始自动挂机。
<br>适用于最新的21赛季。
## 使用说明

 - 1.打开游戏
 - 2.必须切换成`1920*1080`分辨率，全屏、窗口皆可
 - 3.进入主菜单界面(有准备按钮的界面)
 - 4.下载Release中的文件
 - 5.双击`开刷` (bat文件出错的情况下打开`files\dist\good\good.exe`)
 - 6.第2个弹窗中输入:`英雄名+空格+刷的次数` 例如:`baolei 2` 也可以什么也不输入直接回车，那么会以当前选择的英雄进行游戏

这里英雄名请参考同文件夹内的另一张截图，上面列出了每个英雄名的缩写，去掉.png结尾即可。<br>
可以一次输入多个英雄和次数的组合，每个以空格分隔<br>
例如:`waji 4 baolei 12 mingmai 1` <br>
这个意思是瓦机刷4次，然后切换成暴雷刷12次，然后切换命脉刷1次。<br>
这个任务执行完毕后，程序不会停止直到手动关闭，程序会继续刷最后一个英雄 <br>

## 注意事项
程序打开后会显示用户行为，关闭这个窗口会关闭程序。<br>
程序可能意外停止，比如apex游戏结束后的随机调查问卷，将在未来修复。<br>
如果程序意外停止，可通过查看终端信息了解问题，或复制信息(ctrl + shift + c)并上传。<br>
比赛开始且进入地图后可以移动鼠标，但是死亡后脚本会开始操作界面，如果中途打断鼠标必须重新打开脚本。<br>
目前仅中文界面可用

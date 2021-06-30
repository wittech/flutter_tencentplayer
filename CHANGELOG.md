#
## 1.2.0
1. 更新sdk android: 8.8.10254  ios: 8.8.10257有视频旋转问题暂不升级
2. 修复Android播放无效链接时卡住
3. 修复eventCode为null时赋值报错
3. 更新demo apk

## 1.1.0
1. 新增视频帧率回调

## 1.0.0
1. 更新sdk android: 8.6.10097  ios: 8.6.10094

## 0.16.0
1. fix sign判空

## 0.15.0
1. fix网络视频旋转

## 0.14.0
1. 添加参数sign
2. 支持Null safety

## 0.13.0
1. 更新sdk android: 8.2.9809  ios: 8.2.9808
2. 修复android progressIntervald单位
3. 新增播放器事件监听的eventCode,参考[官方文档](https://cloud.tencent.com/document/product/881/20216#.E4.BA.8B.E4.BB.B6.E7.9B.91.E5.90.AC)

## 0.12.0
修复android进度回弹问题

## 0.11.0
1. 优化抖音demo
2. 修复ios列表播放

## 0.10.0
1. 修复本地视频旋转问题


## 0.9.0
1. 修复yaml指定包名类名

## 0.8.0
1. 修复ios autoPlay:false导致不能播放bug
2. 修复ios不能下载视频bug
3. 更新sdk android: 7.6.9376  ios: 7.6.9355

4. 优化value赋值

## 0.7.0
1. 更新sdk
ios: 7.4.9203
android: 7.4.9211
2. 修复https://github.com/qq326646683/flutter_tencentplayer/issues/43
3. 修改ios文件名防止和video_player冲突


## 0.6.0
1. 更新sdk
ios: 7.2.8932
android: 7.2.8927
2. 修复progressInterval参数，单位：秒
3. Demo 添加自动切换下一集

## 0.5.0
修复ios设置progressInterval无效

## 0.4.0
1. 更新sdk:
ios: 7.2.8927
android: 7.2.8925
2. TencentPlayerValue 添加手机旋转角度属性orientation (android only,ios有已知bug)
3. Demo补充小窗、全屏切换
4. Demo支持随手机旋转；🔒（icon）添加锁定旋转功能(android only,ios有已知bug)

## 0.3.0
1.PlayerConfig添加是否后台播放supportBackground

## 0.2.0
1. 支持androidX
2. 升级腾讯播放器sdk
3. 优化demo

## 0.1.0
代码格式化，提升库的health

## 0.0.4
修复直播初始化bug

## 0.0.3 
1. 解决IOS切换视频黑屏
2. 解决IOS设置loop属性无效问题
3. 修复autoPlay为false的bug
4. 升级IOS/Android  LiteAVSDK 6.8.7969
5. 修复退出播放页面还有声音

## 0.0.2
关闭android播放时默认缓存
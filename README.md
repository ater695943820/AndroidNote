Android学习笔记  
===

![image](https://raw.githubusercontent.com/CharonChui/Pictures/master/note.jpg)

> 十年生死两茫茫，不思量，自难忘，华年短暂，陈辞岁月悠悠伤，        
> 满腔热血已芜荒，展未来，后生强，战战兢兢，如履薄冰心彷徨，            
> 青丝化雪、鬓角成霜，已是英雄迟暮，人生怎慷慨激昂？


目录
===  

- [源码解析][43] 
    - [自定义View详解][1]
    - [Activity界面绘制过程详解][2]
    - [Activity启动过程][3]
    - [Android Touch事件分发详解][4]
    - [AsyncTask详解][5]
    - [butterknife源码详解][6]
    - [InstantRun详解][7]
    - [ListView源码分析][8]
    - [VideoView源码分析][9]
    - [View绘制过程详解][10]
    - [网络部分][11]
        - [HttpURLConnection详解][12]
        - [HttpURLConnection与HttpClient][13]
        - [volley-retrofit-okhttp之我们该如何选择网路框架][14]
        - [Volley源码分析][15]
        - [Retrofit详解(上)][16]
        - [Retrofit详解(下)][17]

- [音视频开发][44]
    - [搭建nginx+rtmp服务器][18]
    - [视频播放相关内容总结][19]
    - [视频解码之软解与硬解][20]
    - [音视频基础知识][21]
    - [Android WebRTC简介][22]
    - [Android音视频开发知识(未完)][23]
    - [DLNA简介][24]

-  [图片加载][45]
    - [Glide简介(上)][25]
    - [Glide简介(下)][26]
    - [图片加载库比较][27]


- [RxJava][46]
    - [RxJava详解(上)][28]
    - [RxJava详解(中)][29]
    - [RxJava详解(下)][30]
    - [RxJava系列全家桶][31]

- [开发工具][47]
    - [目前流行的开发组合][32]
    - [性能优化相关工具][33]
    - [Android开发工具及类库][34]
    - [Github个人主页绑定域名][35]
    - [Markdown学习手册][36]
    - [MAT内存分析][37]

- [Kotlin学习][48]
    - [Kotlin学习教程(一)][38]

- [Gradle&Maven][49]
    - [Gradle专题][39]
    - [发布library到Maven仓库][40]

- [应用发布][50]
    - [Android应用发布][41]
    - [Zipalign优化][42]

- [Android Studio使用教程][51]
    - [AndroidStudio使用教程(第一弹)][55]
    - [AndroidStudio使用教程(第二弹)][56]    
    - [AndroidStudio使用教程(第三弹)][57]
    - [AndroidStudio使用教程(第四弹)][58]
    - [AndroidStudio使用教程(第五弹)][59]
    - [AndroidStudio使用教程(第六弹)][60]
    - [AndroidStudio使用教程(第七弹)][61]   
    - [Android Studio你可能不知道的操作][62]
    - [AndroidStudio提高Build速度][63]
    - [AndroidStudio中进行ndk开发][64]

- [进阶部分][52]  
    - [布局优化][65]
    - [屏幕适配之百分比方案详解][66]
    - [热修复实现(未完)][67]
    - [如何让Service常驻内存][68]
    - [通过Hardware Layer提高动画性能][69]
    - [性能优化][70]
    - [注解使用][71]
    - [Android6.0权限系统][72]
    - [Android开发不申请权限来使用对应功能][73]
    - [Android开发中的MVP模式详解][74]
    - [Android启动模式详解][75]
    - [Android卸载反馈][76]
    - [ApplicationId vs PackageName][77]
    - [ART与Dalvik][78]
    - [BroadcastReceiver安全问题][79]
    - [Handler导致内存泄露分析][80]
    - [Library项目中资源id使用case时报错][81]
    - [Mac下配置adb及Android命令][82]
    - [MaterialDesign使用][83]
    - [RecyclerView专题][84]

- [Java基础及算法][53]
    - [常用命令行大全][85]
    - [单例的最佳实现方式][86]
    - [单链表][87]
    - [获取今后多少天后的日期][88]
    - [剑指Offer(上)][89]
    - [剑指Offer(下)][90]
    - [强引用、软引用、弱引用、虚引用][91]
    - [生产者消费者][92]
    - [数据加密及解密][93]
    - [死锁][94]
    - [算法][95]
    - [网络请求相关内容总结][96]
    - [线程池的原理][97]
    - [原子性、可见性以及有序性][98]
    - [Base64加密][99]
    - [Git命令][100]
    - [hashCode与equals][101]
    - [HashMap实现原理分析][102]
    - [Java基础面试题][103]
    - [JVM垃圾回收机制][104]
    - [MD5加密][105]
    - [MVC与MVP及MVVM][106]
    - [RMB大小写转换][107]
    - [Vim使用教程][108]
    - [volatile和Synchronized区别][109]
- [基础部分][54] 
    - [安全退出应用程序][110]
    - [病毒][111]
    - [超级管理员(DevicePoliceManager)][112]
    - [程序的启动、卸载和分享][113]
    - [代码混淆][114]
    - [读取用户logcat日志][115]
    - [短信广播接收者][116]
    - [多线程断点下载][117]
    - [黑名单挂断电话及删除电话记录][118]
    - [横向ListView][119]
    - [滑动切换Activity(GestureDetector)][120]
    - [获取联系人][121]
    - [获取手机及SD卡可用存储空间][122]
    - [获取手机中所有安装的程序][123]
    - [获取位置(LocationManager)][124]
    - [获取应用程序缓存及一键清理][125]
    - [开发中异常的处理][126]
    - [开发中Log的管理][127]
    - [快捷方式工具类][128]
    - [来电号码归属地提示框][129]
    - [来电监听及录音][130]
    - [零权限上传数据][131]
    - [内存泄漏][132]
    - [屏幕适配][133]
    - [任务管理器(ActivityManager)][134]
    - [手机摇晃][135]
    - [竖着的Seekbar][136]
    - [数据存储][137]
    - [搜索框][138]
    - [锁屏以及解锁监听][139]
    - [文件上传][140]
    - [下拉刷新ListView][141]
    - [修改系统组件样式][142]
    - [音量及屏幕亮度调节][143]
    - [应用安装][144]
    - [应用后台唤醒后数据的刷新][145]
    - [知识大杂烩][146]
    - [资源文件拷贝的三种方式][147]
    - [自定义背景][148]
    - [自定义控件][149]
    - [自定义状态栏通知][150]
    - [自定义Toast][151]
    - [adb logcat使用简介][152]
    - [Android编码规范][153]
    - [Android动画][154]
    - [Android基础面试题][155]
    - [Android入门介绍][156]
    - [Android四大组件之ContentProvider][157]
    - [Android四大组件之Service][158]
    - [Ant打包][159]
    - [Bitmap优化][160]
    - [Fragment专题][161]
    - [Home键监听][162]
    - [HttpClient执行Get和Post请求][163]
    - [JNI_C语言基础][164]
    - [JNI基础][165]
    - [ListView专题][166]
    - [Parcelable及Serializable][167]
    - [PopupWindow细节][168]
    - [Scroller简介][169]
    - [ScrollingTabs][170]
    - [SDK Manager无法更新的问题][171]
    - [Selector使用][172]
    - [SlidingMenu][173]
    - [String格式化][174]
    - [TextView跑马灯效果][175]
    - [WebView总结][176]
    - [Widget(窗口小部件)][177]
    - [Wifi状态监听][178]
    - [XmlPullParser][179]
    

[1]: https://github.com/CharonChui/AndroidNote/blob/master/SourceAnalysis/%E8%87%AA%E5%AE%9A%E4%B9%89View%E8%AF%A6%E8%A7%A3.md        "自定义View详解" 
[2]: https://github.com/CharonChui/AndroidNote/blob/master/SourceAnalysis/Activity%E7%95%8C%E9%9D%A2%E7%BB%98%E5%88%B6%E8%BF%87%E7%A8%8B%E8%AF%A6%E8%A7%A3.md  "Activity界面绘制过程详解" 
[3]: https://github.com/CharonChui/AndroidNote/blob/master/SourceAnalysis/Activity%E5%90%AF%E5%8A%A8%E8%BF%87%E7%A8%8B.md    "Activity启动过程"
[4]: https://github.com/CharonChui/AndroidNote/blob/master/SourceAnalysis/Android%20Touch%E4%BA%8B%E4%BB%B6%E5%88%86%E5%8F%91%E8%AF%A6%E8%A7%A3.md    "Android Touch事件分发详解"
[5]: https://github.com/CharonChui/AndroidNote/blob/master/SourceAnalysis/AsyncTask%E8%AF%A6%E8%A7%A3.md   "AsyncTask详解"
[6]: https://github.com/CharonChui/AndroidNote/blob/master/SourceAnalysis/butterknife%E6%BA%90%E7%A0%81%E8%AF%A6%E8%A7%A3.md   "butterknife源码详解"
[7]: https://github.com/CharonChui/AndroidNote/blob/master/SourceAnalysis/InstantRun%E8%AF%A6%E8%A7%A3.md   "InstantRun详解"
[8]: https://github.com/CharonChui/AndroidNote/blob/master/SourceAnalysis/ListView源码分析.md   "ListView源码分析"
[9]: https://github.com/CharonChui/AndroidNote/blob/master/SourceAnalysis/VideoView%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90.md   "VideoView源码分析"
[10]: https://github.com/CharonChui/AndroidNote/blob/master/SourceAnalysis/View%E7%BB%98%E5%88%B6%E8%BF%87%E7%A8%8B%E8%AF%A6%E8%A7%A3.md   "View绘制过程详解"
[11]: https://github.com/CharonChui/AndroidNote/tree/master/SourceAnalysis/Netowork   "网络部分"
[12]: https://github.com/CharonChui/AndroidNote/blob/master/SourceAnalysis/Netowork/HttpURLConnection%E8%AF%A6%E8%A7%A3.md   "HttpURLConnection详解"
[13]: https://github.com/CharonChui/AndroidNote/blob/master/SourceAnalysis/Netowork/HttpURLConnection%E4%B8%8EHttpClient.md   "HttpURLConnection与HttpClient"
[14]: https://github.com/CharonChui/AndroidNote/blob/master/SourceAnalysis/Netowork/volley-retrofit-okhttp%E4%B9%8B%E6%88%91%E4%BB%AC%E8%AF%A5%E5%A6%82%E4%BD%95%E9%80%89%E6%8B%A9%E7%BD%91%E8%B7%AF%E6%A1%86%E6%9E%B6.md   "volley-retrofit-okhttp之我们该如何选择网路框架"
[15]: https://github.com/CharonChui/AndroidNote/blob/master/SourceAnalysis/Netowork/Volley%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90.md   "Volley源码分析"
[16]: https://github.com/CharonChui/AndroidNote/blob/master/SourceAnalysis/Netowork/Retrofit%E8%AF%A6%E8%A7%A3(%E4%B8%8A).md   "Retrofit详解(上)"
[17]: https://github.com/CharonChui/AndroidNote/blob/master/SourceAnalysis/Netowork/Retrofit%E8%AF%A6%E8%A7%A3(%E4%B8%8B).md   "Retrofit详解(下)"
[18]: https://github.com/CharonChui/AndroidNote/blob/master/VideoDevelopment/%E6%90%AD%E5%BB%BAnginx%2Brtmp%E6%9C%8D%E5%8A%A1%E5%99%A8.md   "搭建nginx+rtmp服务器"
[19]: https://github.com/CharonChui/AndroidNote/blob/master/VideoDevelopment/%E8%A7%86%E9%A2%91%E6%92%AD%E6%94%BE%E7%9B%B8%E5%85%B3%E5%86%85%E5%AE%B9%E6%80%BB%E7%BB%93.md   "视频播放相关内容总结"
[20]: https://github.com/CharonChui/AndroidNote/blob/master/VideoDevelopment/%E8%A7%86%E9%A2%91%E8%A7%A3%E7%A0%81%E4%B9%8B%E8%BD%AF%E8%A7%A3%E4%B8%8E%E7%A1%AC%E8%A7%A3.md   "视频解码之软解与硬解"
[21]: https://github.com/CharonChui/AndroidNote/blob/master/VideoDevelopment/%E9%9F%B3%E8%A7%86%E9%A2%91%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86.md   "音视频基础知识"
[22]: https://github.com/CharonChui/AndroidNote/blob/master/VideoDevelopment/Android%20WebRTC%E7%AE%80%E4%BB%8B.md   "Android WebRTC简介"
[23]: https://github.com/CharonChui/AndroidNote/blob/master/VideoDevelopment/Android%E9%9F%B3%E8%A7%86%E9%A2%91%E5%BC%80%E5%8F%91.md   "Android音视频开发知识"
[24]: https://github.com/CharonChui/AndroidNote/blob/master/VideoDevelopment/DLNA%E7%AE%80%E4%BB%8B.md   "DLNA简介"
[25]: https://github.com/CharonChui/AndroidNote/blob/master/ImageLoaderLibrary/Glide%E7%AE%80%E4%BB%8B(%E4%B8%8A).md   "Glide简介(上)"
[26]: https://github.com/CharonChui/AndroidNote/blob/master/ImageLoaderLibrary/Glide%E7%AE%80%E4%BB%8B(%E4%B8%8B).md   "Glide简介(下)"
[27]: https://github.com/CharonChui/AndroidNote/blob/master/ImageLoaderLibrary/%E5%9B%BE%E7%89%87%E5%8A%A0%E8%BD%BD%E5%BA%93%E6%AF%94%E8%BE%83.md   "图片加载库比较"
[28]: https://github.com/CharonChui/AndroidNote/blob/master/RxJavaPart/RxJava%E8%AF%A6%E8%A7%A3(%E4%B8%8A).md   "RxJava详解(上)"
[29]: https://github.com/CharonChui/AndroidNote/blob/master/RxJavaPart/RxJava%E8%AF%A6%E8%A7%A3(%E4%B8%AD).md   "RxJava详解(中)"
[30]: https://github.com/CharonChui/AndroidNote/blob/master/RxJavaPart/RxJava%E8%AF%A6%E8%A7%A3(%E4%B8%8B).md   "RxJava详解(下)"
[31]: https://github.com/CharonChui/AndroidNote/blob/master/RxJavaPart/RxJava%E7%B3%BB%E5%88%97%E5%85%A8%E5%AE%B6%E6%A1%B6.md   "RxJava系列全家桶"
[32]: https://github.com/CharonChui/AndroidNote/blob/master/Tools%26Library/%E7%9B%AE%E5%89%8D%E6%B5%81%E8%A1%8C%E7%9A%84%E5%BC%80%E5%8F%91%E7%BB%84%E5%90%88.md   "目前流行的开发组合"
[33]: https://github.com/CharonChui/AndroidNote/blob/master/Tools%26Library/%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96%E7%9B%B8%E5%85%B3%E5%B7%A5%E5%85%B7.md   "性能优化相关工具"
[34]: https://github.com/CharonChui/AndroidNote/blob/master/Tools%26Library/Android%E5%BC%80%E5%8F%91%E5%B7%A5%E5%85%B7%E5%8F%8A%E7%B1%BB%E5%BA%93.md   "Android开发工具及类库"
[35]: https://github.com/CharonChui/AndroidNote/blob/master/Tools%26Library/Github%E4%B8%AA%E4%BA%BA%E4%B8%BB%E9%A1%B5%E7%BB%91%E5%AE%9A%E5%9F%9F%E5%90%8D.md   "Github个人主页绑定域名"
[36]: https://github.com/CharonChui/AndroidNote/blob/master/Tools%26Library/Markdown%E5%AD%A6%E4%B9%A0%E6%89%8B%E5%86%8C.md   "Markdown学习手册"
[37]: https://github.com/CharonChui/AndroidNote/blob/master/Tools%26Library/MAT%E5%86%85%E5%AD%98%E5%88%86%E6%9E%90.md   "MAT内存分析"
[38]: https://github.com/CharonChui/AndroidNote/blob/master/KotlinCourse/Kotlin%E5%AD%A6%E4%B9%A0%E6%95%99%E7%A8%8B(%E4%B8%80).md   "Kotlin学习教程(一)(未完)"
[39]: https://github.com/CharonChui/AndroidNote/blob/master/Gradle%26Maven/Gradle%E4%B8%93%E9%A2%98.md   "Gradle专题"
[40]: https://github.com/CharonChui/AndroidNote/blob/master/Gradle%26Maven/%E5%8F%91%E5%B8%83library%E5%88%B0Maven%E4%BB%93%E5%BA%93.md   "发布library到Maven仓库"
[41]: https://github.com/CharonChui/AndroidNote/blob/master/AppPublish/Android%E5%BA%94%E7%94%A8%E5%8F%91%E5%B8%83.md   "Android应用发布"
[42]: https://github.com/CharonChui/AndroidNote/blob/master/AppPublish/Zipalign%E4%BC%98%E5%8C%96.md   "Zipalign优化"
[43]: https://github.com/CharonChui/AndroidNote/tree/master/SourceAnalysis   "源码解析"
[44]: https://github.com/CharonChui/AndroidNote/tree/master/VideoDevelopment   "音视频开发"
[45]: https://github.com/CharonChui/AndroidNote/tree/master/ImageLoaderLibrary   "图片加载"
[46]: https://github.com/CharonChui/AndroidNote/tree/master/RxJavaPart   "RxJava"
[47]: https://github.com/CharonChui/AndroidNote/tree/master/Tools%26Library   "开发工具"
[48]: https://github.com/CharonChui/AndroidNote/tree/master/KotlinCourse   "Kotlin学习"
[49]: https://github.com/CharonChui/AndroidNote/tree/master/Gradle%26Maven   "Gradle&Maven"
[50]: https://github.com/CharonChui/AndroidNote/tree/master/AppPublish   "应用发布"
[51]: https://github.com/CharonChui/AndroidNote/tree/master/AndroidStudioCourse   "Android Studio使用教程"
[52]: https://github.com/CharonChui/AndroidNote/tree/master/AdavancedPart   "进阶部分"
[53]: https://github.com/CharonChui/AndroidNote/tree/master/JavaKnowledge   "Java基础及算法"
[54]: https://github.com/CharonChui/AndroidNote/tree/master/BasicKnowledge   "基础部分"
[55]: https://github.com/CharonChui/AndroidNote/blob/master/AndroidStudioCourse/AndroidStudio%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B(%E7%AC%AC%E4%B8%80%E5%BC%B9).md   "AndroidStudio使用教程(第一弹)"
[56]: https://github.com/CharonChui/AndroidNote/blob/master/AndroidStudioCourse/AndroidStudio%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B(%E7%AC%AC%E4%BA%8C%E5%BC%B9).md   "AndroidStudio使用教程(第二弹)"
[57]: https://github.com/CharonChui/AndroidNote/blob/master/AndroidStudioCourse/AndroidStudio%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B(%E7%AC%AC%E4%B8%89%E5%BC%B9).md   "AndroidStudio使用教程(第三弹)"
[58]: https://github.com/CharonChui/AndroidNote/blob/master/AndroidStudioCourse/AndroidStudio%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B(%E7%AC%AC%E5%9B%9B%E5%BC%B9).md   "AndroidStudio使用教程(第四弹)"
[59]: https://github.com/CharonChui/AndroidNote/blob/master/AndroidStudioCourse/AndroidStudio%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B(%E7%AC%AC%E4%BA%94%E5%BC%B9).md   "AndroidStudio使用教程(第五弹)"
[60]: https://github.com/CharonChui/AndroidNote/blob/master/AndroidStudioCourse/AndroidStudio%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B(%E7%AC%AC%E5%85%AD%E5%BC%B9).md   "AndroidStudio使用教程(第六弹)"
[61]: https://github.com/CharonChui/AndroidNote/blob/master/AndroidStudioCourse/AndroidStudio%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B(%E7%AC%AC%E4%B8%83%E5%BC%B9).md   "AndroidStudio使用教程(第七弹)"
[62]: https://github.com/CharonChui/AndroidNote/blob/master/AndroidStudioCourse/Android%20Studio%E4%BD%A0%E5%8F%AF%E8%83%BD%E4%B8%8D%E7%9F%A5%E9%81%93%E7%9A%84%E6%93%8D%E4%BD%9C.md   "Android Studio你可能不知道的操作"
[63]: https://github.com/CharonChui/AndroidNote/blob/master/AndroidStudioCourse/AndroidStudio%E6%8F%90%E9%AB%98Build%E9%80%9F%E5%BA%A6.md   "AndroidStudio提高Build速度"
[64]: https://github.com/CharonChui/AndroidNote/blob/master/AndroidStudioCourse/AndroidStudio%E4%B8%AD%E8%BF%9B%E8%A1%8Cndk%E5%BC%80%E5%8F%91.md   "AndroidStudio中进行ndk开发"
[65]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/%E5%B8%83%E5%B1%80%E4%BC%98%E5%8C%96.md   "布局优化"
[66]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/%E5%B1%8F%E5%B9%95%E9%80%82%E9%85%8D%E4%B9%8B%E7%99%BE%E5%88%86%E6%AF%94%E6%96%B9%E6%A1%88%E8%AF%A6%E8%A7%A3.md   "屏幕适配之百分比方案详解"
[67]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/%E7%83%AD%E4%BF%AE%E5%A4%8D%E5%AE%9E%E7%8E%B0.md   "热修复实现"
[68]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/%E5%A6%82%E4%BD%95%E8%AE%A9Service%E5%B8%B8%E9%A9%BB%E5%86%85%E5%AD%98.md   "如何让Service常驻内存"
[69]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/%E9%80%9A%E8%BF%87Hardware%20Layer%E6%8F%90%E9%AB%98%E5%8A%A8%E7%94%BB%E6%80%A7%E8%83%BD.md   "通过Hardware Layer提高动画性能"
[70]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96.md   "性能优化"
[71]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/%E6%B3%A8%E8%A7%A3%E4%BD%BF%E7%94%A8.md   "注解使用"
[72]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/Android6.0%E6%9D%83%E9%99%90%E7%B3%BB%E7%BB%9F.md   "Android6.0权限系统"
[73]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/Android%E5%BC%80%E5%8F%91%E4%B8%8D%E7%94%B3%E8%AF%B7%E6%9D%83%E9%99%90%E6%9D%A5%E4%BD%BF%E7%94%A8%E5%AF%B9%E5%BA%94%E5%8A%9F%E8%83%BD.md   "Android开发不申请权限来使用对应功能"
[74]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/Android%E5%BC%80%E5%8F%91%E4%B8%AD%E7%9A%84MVP%E6%A8%A1%E5%BC%8F%E8%AF%A6%E8%A7%A3.md   "Android开发中的MVP模式详解"
[75]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/Android%E5%90%AF%E5%8A%A8%E6%A8%A1%E5%BC%8F%E8%AF%A6%E8%A7%A3.md   "Android启动模式详解"
[76]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/Android%E5%8D%B8%E8%BD%BD%E5%8F%8D%E9%A6%88.md   "Android卸载反馈"
[77]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/ApplicationId%20vs%20PackageName.md   "ApplicationId vs PackageName"
[78]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/ART%E4%B8%8EDalvik.md   "ART与Dalvik"
[79]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/BroadcastReceiver%E5%AE%89%E5%85%A8%E9%97%AE%E9%A2%98.md   "BroadcastReceiver安全问题"
[80]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/Handler%E5%AF%BC%E8%87%B4%E5%86%85%E5%AD%98%E6%B3%84%E9%9C%B2%E5%88%86%E6%9E%90.md   "Handler导致内存泄露分析"
[81]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/Library%E9%A1%B9%E7%9B%AE%E4%B8%AD%E8%B5%84%E6%BA%90id%E4%BD%BF%E7%94%A8case%E6%97%B6%E6%8A%A5%E9%94%99.md   "Library项目中资源id使用case时报错"
[82]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/Mac%E4%B8%8B%E9%85%8D%E7%BD%AEadb%E5%8F%8AAndroid%E5%91%BD%E4%BB%A4.md   "Mac下配置adb及Android命令"
[83]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/MaterialDesign%E4%BD%BF%E7%94%A8.md   "MaterialDesign使用"
[84]: https://github.com/CharonChui/AndroidNote/blob/master/AdavancedPart/RecyclerView%E4%B8%93%E9%A2%98.md   "RecyclerView专题"
[85]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/%E5%B8%B8%E7%94%A8%E5%91%BD%E4%BB%A4%E8%A1%8C%E5%A4%A7%E5%85%A8.md   "常用命令行大全"
[86]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/%E5%8D%95%E4%BE%8B%E7%9A%84%E6%9C%80%E4%BD%B3%E5%AE%9E%E7%8E%B0%E6%96%B9%E5%BC%8F.md   "单例的最佳实现方式"
[87]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/%E5%8D%95%E9%93%BE%E8%A1%A8.md   "单链表"
[88]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/%E8%8E%B7%E5%8F%96%E4%BB%8A%E5%90%8E%E5%A4%9A%E5%B0%91%E5%A4%A9%E5%90%8E%E7%9A%84%E6%97%A5%E6%9C%9F.md   "获取今后多少天后的日期"
[89]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/%E5%89%91%E6%8C%87Offer(%E4%B8%8A).md   "剑指Offer(上)"
[90]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/剑指Offer(下).md   "剑指Offer(下)"
[91]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/%E5%BC%BA%E5%BC%95%E7%94%A8%E3%80%81%E8%BD%AF%E5%BC%95%E7%94%A8%E3%80%81%E5%BC%B1%E5%BC%95%E7%94%A8%E3%80%81%E8%99%9A%E5%BC%95%E7%94%A8.md   "强引用、软引用、弱引用、虚引用"
[92]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/%E7%94%9F%E4%BA%A7%E8%80%85%E6%B6%88%E8%B4%B9%E8%80%85.md   "生产者消费者"
[93]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/%E6%95%B0%E6%8D%AE%E5%8A%A0%E5%AF%86%E5%8F%8A%E8%A7%A3%E5%AF%86.md   "数据加密及解密"
[94]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/%E6%AD%BB%E9%94%81.md   "死锁"
[95]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/%E7%AE%97%E6%B3%95.md   "算法"
[96]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/%E7%BD%91%E7%BB%9C%E8%AF%B7%E6%B1%82%E7%9B%B8%E5%85%B3%E5%86%85%E5%AE%B9%E6%80%BB%E7%BB%93.md   "网络请求相关内容总结"
[97]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/%E7%BA%BF%E7%A8%8B%E6%B1%A0%E7%9A%84%E5%8E%9F%E7%90%86.md   "线程池的原理"
[98]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/%E5%8E%9F%E5%AD%90%E6%80%A7%E3%80%81%E5%8F%AF%E8%A7%81%E6%80%A7%E4%BB%A5%E5%8F%8A%E6%9C%89%E5%BA%8F%E6%80%A7.md   "原子性、可见性以及有序性"
[99]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/Base64%E5%8A%A0%E5%AF%86.md   "Base64加密"
[100]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/Git%E5%91%BD%E4%BB%A4.md   "Git命令"
[101]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/hashCode%E4%B8%8Eequals.md   "hashCode与equals"
[102]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/HashMap%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86%E5%88%86%E6%9E%90.md   "HashMap实现原理分析"
[103]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/Java%E5%9F%BA%E7%A1%80%E9%9D%A2%E8%AF%95%E9%A2%98.md   "Java基础面试题"
[104]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/JVM%E5%9E%83%E5%9C%BE%E5%9B%9E%E6%94%B6%E6%9C%BA%E5%88%B6.md   "JVM垃圾回收机制"
[105]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/MD5%E5%8A%A0%E5%AF%86.md   "MD5加密"
[106]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/MVC%E4%B8%8EMVP%E5%8F%8AMVVM.md   "MVC与MVP及MVVM"
[107]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/RMB%E5%A4%A7%E5%B0%8F%E5%86%99%E8%BD%AC%E6%8D%A2.md   "RMB大小写转换"
[108]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/Vim%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B.md   "Vim使用教程"
[109]: https://github.com/CharonChui/AndroidNote/blob/master/JavaKnowledge/volatile%E5%92%8CSynchronized%E5%8C%BA%E5%88%AB.md   "volatile和Synchronized区别"
[110]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E5%AE%89%E5%85%A8%E9%80%80%E5%87%BA%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F.md   "安全退出应用程序"
[111]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E7%97%85%E6%AF%92.md   "病毒"
[112]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E8%B6%85%E7%BA%A7%E7%AE%A1%E7%90%86%E5%91%98(DevicePoliceManager).md   "超级管理员(DevicePoliceManager)"
[113]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E7%A8%8B%E5%BA%8F%E7%9A%84%E5%90%AF%E5%8A%A8%E3%80%81%E5%8D%B8%E8%BD%BD%E5%92%8C%E5%88%86%E4%BA%AB.md   "程序的启动、卸载和分享"
[114]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E4%BB%A3%E7%A0%81%E6%B7%B7%E6%B7%86.md   "代码混淆"
[115]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E8%AF%BB%E5%8F%96%E7%94%A8%E6%88%B7logcat%E6%97%A5%E5%BF%97.md   "读取用户logcat日志"
[116]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E7%9F%AD%E4%BF%A1%E5%B9%BF%E6%92%AD%E6%8E%A5%E6%94%B6%E8%80%85.md   "短信广播接收者"
[117]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E5%A4%9A%E7%BA%BF%E7%A8%8B%E6%96%AD%E7%82%B9%E4%B8%8B%E8%BD%BD.md   "多线程断点下载"
[118]: xhttps://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E9%BB%91%E5%90%8D%E5%8D%95%E6%8C%82%E6%96%AD%E7%94%B5%E8%AF%9D%E5%8F%8A%E5%88%A0%E9%99%A4%E7%94%B5%E8%AF%9D%E8%AE%B0%E5%BD%95.md   "黑名单挂断电话及删除电话记录"
[119]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E6%A8%AA%E5%90%91ListView.md   "横向ListView"
[120]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E6%BB%91%E5%8A%A8%E5%88%87%E6%8D%A2Activity(GestureDetector).md   "滑动切换Activity(GestureDetector)"
[121]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E8%8E%B7%E5%8F%96%E8%81%94%E7%B3%BB%E4%BA%BA.md   "获取联系人"
[122]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E8%8E%B7%E5%8F%96%E6%89%8B%E6%9C%BA%E5%8F%8ASD%E5%8D%A1%E5%8F%AF%E7%94%A8%E5%AD%98%E5%82%A8%E7%A9%BA%E9%97%B4.md   "获取手机及SD卡可用存储空间"
[123]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E8%8E%B7%E5%8F%96%E6%89%8B%E6%9C%BA%E4%B8%AD%E6%89%80%E6%9C%89%E5%AE%89%E8%A3%85%E7%9A%84%E7%A8%8B%E5%BA%8F.md   "获取手机中所有安装的程序"
[124]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E8%8E%B7%E5%8F%96%E4%BD%8D%E7%BD%AE(LocationManager).md   "获取位置(LocationManager)"
[125]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E8%8E%B7%E5%8F%96%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F%E7%BC%93%E5%AD%98%E5%8F%8A%E4%B8%80%E9%94%AE%E6%B8%85%E7%90%86.md   "获取应用程序缓存及一键清理"
[126]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E5%BC%80%E5%8F%91%E4%B8%AD%E5%BC%82%E5%B8%B8%E7%9A%84%E5%A4%84%E7%90%86.md   "开发中异常的处理"
[127]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E5%BC%80%E5%8F%91%E4%B8%ADLog%E7%9A%84%E7%AE%A1%E7%90%86.md   "开发中Log的管理"
[128]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E5%BF%AB%E6%8D%B7%E6%96%B9%E5%BC%8F%E5%B7%A5%E5%85%B7%E7%B1%BB.md   "快捷方式工具类"
[129]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E6%9D%A5%E7%94%B5%E5%8F%B7%E7%A0%81%E5%BD%92%E5%B1%9E%E5%9C%B0%E6%8F%90%E7%A4%BA%E6%A1%86.md   "来电号码归属地提示框"
[130]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E6%9D%A5%E7%94%B5%E7%9B%91%E5%90%AC%E5%8F%8A%E5%BD%95%E9%9F%B3.md   "来电监听及录音"
[131]: https://github.com/CharonChui/AndroidNote/blob/master/BasicKnowledge/%E9%9B%B6%E6%9D%83%E9%99%90%E4%B8%8A%E4%BC%A0%E6%95%B0%E6%8D%AE.md   "零权限上传数据"
[132]: x   ""
[133]: x   ""
[134]: x   ""
[135]: x   ""
[136]: x   ""
[137]: x   ""
[138]: x   ""
[139]: x   ""
[140]: x   ""
[141]: x   ""
[142]: x   ""
[143]: x   ""
[144]: x   ""
[145]: x   ""
[146]: x   ""
[147]: x   ""
[148]: x   ""
[149]: x   ""
[150]: x   ""
[151]: x   ""
[152]: x   ""
[153]: x   ""
[154]: x   ""
[155]: x   ""
[156]: x   ""
[157]: x   ""
[158]: x   ""
[159]: x   ""
[160]: x   ""
[161]: x   ""
[162]: x   ""
[163]: x   ""
[164]: x   ""
[165]: x   ""
[166]: x   ""
[167]: x   ""
[168]: x   ""
[169]: x   ""
[170]: x   ""
[171]: x   ""
[172]: x   ""
[173]: x   ""
[174]: x   ""
[175]: x   ""
[176]: x   ""
[177]: x   ""
[178]: x   ""
[179]: x   ""


Developed By
===

 * Charon Chui - <charon.chui@gmail.com>


License
===

    Copyright (C) 2013 Charon Chui <charon.chui@gmail.com>

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
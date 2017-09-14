Android学习笔记  
===

![image](https://raw.githubusercontent.com/CharonChui/Pictures/master/note.jpg)

> 十年生死两茫茫，不思量，自难忘，华年短暂，陈辞岁月悠悠伤，        
> 满腔热血已芜荒，展未来，后生强，战战兢兢，如履薄冰心彷徨，            
> 青丝化雪、鬓角成霜，已是英雄迟暮，人生怎慷慨激昂？


目录
===  

- 源码解析 
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

- 音视频开发
    - [搭建nginx+rtmp服务器]()
    - [视频播放相关内容总结]()
    - [视频解码之软解与硬解]()
    - [音视频基础知识]()
    - [Android WebRTC简介]()
    - [Android音视频开发知识(未完)]()
    - [DLNA简介]()

-  图片加载
    - [Glide简介(上)]()
    - [Glide简介(下)]()
    - [图片加载库比较]()


- `RxJava`
    - [RxJava详解(上)]()
    - [RxJava详解(中)]()
    - [RxJava详解(下)]()
    - [RxJava系列全家桶]()

- 开发工具
    - [目前流行的开发组合]()
    - [性能优化相关工具]()
    - [Android开发工具及类库]()
    - [Github个人主页绑定域名]()
    - [Markdown学习手册]()
    - [MAT内存分析]()

- `Kotlin`学习
    - [Kotlin学习教程(一)]()

- `Gradle&Maven`
    - [Gradle专题]()
    - [发布library到Maven仓库]()

- `应用发布`
    - [Android应用发布]()
    - [Zipalign优化]()

- `Android Studio使用教程`
    - [AndroidStudio使用教程(第一弹)]()
    - [AndroidStudio使用教程(第二弹)]()    
    - [AndroidStudio使用教程(第三弹)]()
    - [AndroidStudio使用教程(第四弹)]()    
    - [AndroidStudio使用教程(第五弹)]()    
    - [AndroidStudio使用教程(第六弹)]()
    - [AndroidStudio使用教程(第七弹)]()    
    - [Android Studio你可能不知道的操作]()
    - [AndroidStudio提高Build速度]()    
    - [AndroidStudio中进行ndk开发]()    

- 进阶部分  
    - [布局优化]()
    - [屏幕适配之百分比方案详解]()
    - [热修复实现]()
    - [如何让Service常驻内存]()
    - [通过Hardware Layer提高动画性能]()
    - [性能优化]()
    - [注解使用]()
    - [Android6.0权限系统]()
    - [Android开发不申请权限来使用对应功能]()
    - [Android开发中的MVP模式详解]()
    - [Android启动模式详解]()
    - [Android卸载反馈]()
    - [ApplicationId vs PackageName]()
    - [ART与Dalvik]()
    - [BroadcastReceiver安全问题]()
    - [Handler导致内存泄露分析]()
    - [Library项目中资源id使用case时报错]()
    - [Mac下配置adb及Android命令]()
    - [MaterialDesign使用]()
    - [RecyclerView专题]()

- `Java`基础及算法
    - [常用命令行大全]()
    - [单例的最佳实现方式]()
    - [单链表]()
    - [获取今后多少天后的日期]()
    - [剑指Offer(上)]()
    - [剑指Offer(下)]()
    - [强引用、软引用、弱引用、虚引用]()
    - [生产者消费者]()
    - [数据加密及解密]()
    - [死锁]()
    - [算法]()
    - [网络请求相关内容总结]()
    - [线程池的原理]()
    - [原子性、可见性以及有序性]()
    - [Base64加密]()
    - [Git命令]()
    - [hashCode与equals]()
    - [HashMap实现原理分析]()
    - [Java基础面试题]()
    - [JVM垃圾回收机制]()
    - [MD5加密]()
    - [MVC与MVP及MVVM]()
    - [RMB大小写转换]()
    - [Vim使用教程]()
    - [volatile和Synchronized区别]()
- 基础部分 
    - [安全退出应用程序]()
    - [病毒]()
    - [超级管理员(DevicePoliceManager)]()
    - [程序的启动、卸载和分享]()
    - [代码混淆]()
    - [读取用户logcat日志]()
    - [短信广播接收者]()
    - [多线程断点下载]()
    - [黑名单挂断电话及删除电话记录]()
    - [横向ListView]()
    - [滑动切换Activity(GestureDetector)]()
    - [获取联系人]()
    - [获取手机及SD卡可用存储空间]()
    - [获取手机中所有安装的程序]()
    - [获取位置(LocationManager)]()
    - [获取应用程序缓存及一键清理]()
    - [开发中异常的处理]()
    - [开发中Log的管理]()
    - [快捷方式工具类]()
    - [来电号码归属地提示框]()
    - [来电监听及录音]()
    - [零权限上传数据]()
    - [内存泄漏]()
    - [屏幕适配]()
    - [任务管理器(ActivityManager)]()
    - [手机摇晃]()
    - [竖着的Seekbar]()
    - [数据存储]()
    - [搜索框]()
    - [锁屏以及解锁监听]()
    - [文件上传]()
    - [下拉刷新ListView]()
    - [修改系统组件样式]()
    - [音量及屏幕亮度调节]()
    - [应用安装]()
    - [应用后台唤醒后数据的刷新]()
    - [知识大杂烩]()
    - [资源文件拷贝的三种方式]()
    - [自定义背景]()
    - [自定义控件]()
    - [自定义状态栏通知]()
    - [自定义Toast]()
    - [adb logcat使用简介]()
    - [Android编码规范]()
    - [Android动画]()
    - [Android基础面试题]()
    - [Android入门介绍]()
    - [Android四大组件之ContentProvider]()
    - [Android四大组件之Service]()
    - [Ant打包]()
    - [Bitmap优化]()
    - [Fragment专题]()
    - [Home键监听]()
    - [HttpClient执行Get和Post请求]()
    - [JNI_C语言基础]()
    - [JNI基础]()
    - [ListView专题]()
    - [Parcelable及Serializable]()
    - [PopupWindow细节]()
    - [Scroller简介]()
    - [ScrollingTabs]()
    - [SDK Manager无法更新的问题]()
    - [Selector使用]()
    - [SlidingMenu]()
    - [String格式化]()
    - [TextView跑马灯效果]()
    - [WebView总结]()
    - [Widget(窗口小部件)]()
    - [Wifi状态监听]()
    - [XmlPullParser]()
    

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
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""
[5]: x   ""


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
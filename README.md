## 致力于集结各类优秀的开源UI控件，功能框架，快速开发和建立应用架构（已亲测）
### 一、Native应用开发框架
#### 一种轻量级的应用开发方案，由一个Activity与多个Fragment的开发框架。

- 内含仿知乎，今日头条，微信的界面框架。
- MVC设计模型
- 可快速开发原生应用
- 支持栈层查询
- 支持外部其他框架接入
- 支持 Material Design，包括DrawerLayout、NavigationView、ToolBar、RecycleView等。
- 源码：https://github.com/YoKeyword/Fragmentation

### 二、基于Apach Cordova 的Hybrid 应用开发框架
#### 一种前后端分离的开发框架。可由H5,JS,CSS组成界面应用界面，由原生端提供前端接口完成对手机设备和其他第三方框架集成，例如：前端调起手机摄像头，或者前端调起手机支付宝或微信支付等

- 可快速开发混合应用
- 可集成腾讯TBSX5内核浏览器，提高兼容性
- 支持拦截
- 完整的Cordova插件开发教程
- 可插件化构建应用，提高复用率
- 源码及教程：https://github.com/nihaohebin/CordovaPluginDevelopment_Android

### 三、AgentWeb，H5与原生混合开发
#### AgentWeb 是一个基于的 Android WebView ，极度容易使用以及功能强大的库，提供了 Android WebView 一系列的问题解决方案 ，并且轻量和极度灵活.
- 开发使用简单
- 支持JS与Native Java通信
- 支持X5接入
- 源码：https://github.com/Justson/AgentWeb

### 四、手机摄像头，IP摄像头（海康为例），USB摄像头（罗技为例）开发
#### 一个基于深度学习CNN卷积神经网络的在线人脸识别。深入了解各类摄像头研发，如何将YUV数据转成RGB565再转Bitmap位图，并涉及NDK相关开发，JNI接口编写与调用等（公司已倒闭，人脸检测是本地的）。
- 可实时完成人脸识别
- 可实时监测人脸并通过抠图和压缩在性能上优化
- 手机摄像头源码： https://github.com/nihaohebin/FaceDetect_Thinkjoy
- IP摄像头源码：https://github.com/nihaohebin/IPCamera
- USB摄像头源码：https://github.com/nihaohebin/usbCamera

### 五、OkGo
#### 将Okhttp封装好的请求框架，包括缓存机制，doGet,doPost，上传下载等功能封装。
 - 使用方便，可按要求配置开发
 - 支持RxJava
 - 支持RxJava2
 - 支持自定义缓存策略
 - 支持下载管理
 - 支持上传管理
 - 源码：https://github.com/jeasonlzy/okhttp-OkGo

### 六、Rxjava2+RxAndroid+Retrofit2
#### 基于Okhttp的链式请求框架。并用当前比较流行的resful风格。
 - 使用方便，可按要求配置开发
 - 对retrofit进行了封装
 - 支持下载管理
 - 支持上传管理
 - 源码：https://github.com/lygttpod/RxHttpUtils

 ### 七、AndroidUT
 #### android单元测试
 - 源码文档：https://github.com/simplezhli/AndroidUT/tree/master

 ### 八、GSYVideoPlayer
 #### 视频播放器，支持ijk内核和exo内核切换，建议使用exo稳定，轻量，毕竟是google亲儿子
 - 很好的封装了一套视频播放器的API
 - 支持多种视频处理
 - 源码文档：https://github.com/CarGuo/GSYVideoPlayer
 
  ### 九、objectbox
 #### android本地数据库
 - greenrobot组织开源的优秀数据库，基于之前的greenDAO而来。
 - 源码文档：https://github.com/objectbox/objectbox-java
  
### 十、DesignMode
#### 常用android开发设计模型学习
 - 有详细源码样例
 - 源码：https://github.com/youlookwhat/DesignPattern
 
### 十一、FastBle
#### android低功耗蓝牙开发
 - 有详细源码样例
 - 源码：https://github.com/Jasonchenlijian/FastBle

### 十二、其他常用开发
|   |   |
| :------------ | :------------ |
|  [fastjson](https://github.com/alibaba/fastjson) / [gson](https://github.com/google/gson)  | json 数据解析，可结合AndroidStudio GsonFormat插件快速解析生成bean容器  | 
| [Butterknife](https://github.com/JakeWharton/butterknife)  |  UI注解，可结合AS Butterknife zelezny插件可快速开发控件注解  |
|  XmlPullParser/[dom4j](https://dom4j.github.io/) |  xml文件解析，其中dom4j为java常用解析器，XmlPullParser为androidSDK自带常用xml解析器  |
| [Glide](https://github.com/bumptech/glide) / [Universal-Image-Loader](https://github.com/nostra13/Android-Universal-Image-Loader)  |  图片加载，缓存。[封装](https://blog.csdn.net/bighuan/article/details/58992524) |
| [glide-transformations](https://github.com/wasabeef/glide-transformations) |图片加载处理|
| [LeakCanary](https://github.com/square/leakcanary) |检测内存泄漏，优化应用内存性能。|
| [TaskScheduler](https://github.com/SilenceDut/TaskScheduler) |android线程池管理|
| [logger](https://github.com/orhanobut/logger) | 日志管理器|
| [QMUI_Android](https://github.com/Tencent/QMUI_Android)|腾讯UI控件集合|
| [XUI](https://github.com/xuexiangjys/XUI)|UI控件集合|
| [SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout)|刷新控件|
| [XRecyclerView](https://github.com/XRecyclerView/XRecyclerView)|上拉刷新，下拉加载|
| [BaseRecyclerViewAdapterHelper](https://github.com/CymChad/BaseRecyclerViewAdapterHelper)|列表适配器|
| [banner](https://github.com/youth5201314/banner)| 广告页轮播 |
| [android_zxing](https://github.com/yuzhiqiang1993/zxing)| android二维码扫描工具 |
| [permission](https://github.com/yanzhenjie/AndPermission)|权限管理工具 |
| [easypermissions](https://github.com/googlesamples/easypermissions)|权限管理工具 |
| [CircleImageView](https://github.com/hdodenhof/CircleImageView)|圆形图片控件 |
| [PictureSelect](https://github.com/LuckSiege/PictureSelector)|图片选择器 |
| [EasyPhoto](https://github.com/HuanTanSheng/EasyPhotos)|图片选择工具 |
| [BigImageViewPager](https://github.com/SherlockGougou/BigImageViewPager)|大图片浏览器 |
| [PopWindow](https://github.com/HMY314/PopWindow)|底部弹出选择控件 |
| [WheelView](https://github.com/Bigkoo/Android-PickerView)|滚轮控件 |
| [AndroidUtilCode](https://github.com/Blankj/AndroidUtilCode/blob/master/lib/utilcode/README-CN.md)|android常用工具类 |
| [DanmakuFlameMaster](https://github.com/Bilibili/DanmakuFlameMaster)|视频弹幕框架 |
| [apkupdate](https://github.com/azhon/AppUpdate)|应用内升级工具 |
| [ProgressView](https://github.com/Moosphan/Material-ProgressView)|进度条 |
| [Lighter](https://github.com/samlss/Lighter)|新手引导界面工具 |
| [ProgressView](https://github.com/Moosphan/Material-ProgressView)|进度条工具|
| [StateView](https://github.com/nukc/StateView)|状态界面工具|
| [materialratingbar](https://github.com/zhanghai/MaterialRatingBar)|五星好评控件|
| [count-down-timer](https://github.com/dengyuhan/CountDownTimerSupport)|倒计时工具|
| [HokoBlur](https://github.com/HokoFly/HokoBlur)|高斯模糊工具|
| [treeView](https://github.com/Jasongq/TreeRecyclerView)|树形控件|
| [treeView2](https://github.com/shineM/TreeView)|树形控件2|
| [xpop](https://github.com/li-xiaojun/XPopup)|弹窗控件|
| [Linkage-RecyclerView](https://github.com/KunMinX/Linkage-RecyclerView?utm_source=gold_browser_extension)|外卖菜单列表|
| [CityProject](https://github.com/Tencent/QMUI_Android)|城市选择列表，带定位|
| [SmartTabLayout](https://github.com/ogaclejapan/SmartTabLayout)|导航栏控件|
| [tinker](https://github.com/Tencent/tinker)|腾讯热更新|
| [AndroidViewAnimations](https://github.com/daimajia/AndroidViewAnimations)|androidView动画|
| [vlayout](https://github.com/alibaba/vlayout)|阿里复杂列表控件|
| [MinaManager](https://github.com/jiezongnewstar/MinaManager)|mina简单长连接|
| [okdownload](https://github.com/lingochamp/okdownload)|离线视频下载引擎|
| [skin](https://github.com/ximsfei/Android-skin-support)|app换肤框架|
| [CalendarView](https://github.com/huanghaibin-dev/CalendarView)|日历工具|
| [EventBus](https://github.com/greenrobot/EventBus)|观察者模式事件总线|
| [Search_Layout](https://github.com/Carson-Ho/Search_Layout)|搜索导航栏工具|
| [ImmersionBar](https://github.com/gyf-dev/ImmersionBar)|沉浸式状态栏和沉浸式导航栏管理|

# 进阶学习的开源完整项目
###  1、组件化综合案例，包含微信新闻，头条视频，美女图片，百度音乐，干活集中营，玩Android，豆瓣读书电影，知乎日报等等模块。架构模式：组件化+MVP+Rx+Retrofit+Desgin+Dagger2+阿里VLayout+腾讯X5+腾讯bugly。融合开发中需要的各种小案例！
####  源码：https://github.com/yangchong211/LifeHelper

### 2、简单便捷 快速开发Android项目，集合流行框架封装mvp + rxjava2 + retrofit2 + rxlifecycle3 + arouter...
#### 源码：https://github.com/wobiancao/sugar

### 3、基于谷歌最新AAC架构，MVVM设计模式的一套快速开发库，整合Okhttp+RxJava+Retrofit+Glide等主流模块，满足日常开发需求。使用该框架可以快速开发一个高质量、易维护的Android应用。
#### 源码：https://github.com/goldze/MVVMHabit

### 4、Material Design学习
#### 源码：https://github.com/rey5137/material

### 5、云阅：一款基于网易云音乐UI，使用玩安卓、Gank.Io及时光网api开发的符合Google Material Design的Android客户端。项目采取的是MVVM-DataBinding架构开发，主要包括：玩安卓区、干货区和电影区三个子模块。
#### 源码：https://github.com/youlookwhat/CloudReader




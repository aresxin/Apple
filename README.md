# Apple

- [Foundation](#Foundation)
- [Core ML](#Core-ML)
- [ARKit](#ARkit)
- [Vision](#Vision)
- [UIKit](#UIKit)
- [WebKit](#WebKit)
- [GroupActivities](#GroupActivities)
- [Core Image](#Core-mage)
- [APP Icon](#APP-Icon)
- [App Clip](#App-Clip)
- [App Documents Share](#App-Documents-Share)
- [Network](#Network)
- [StoreKit](#StoreKit)
- [Certificates](#Certificates)
- [Dispatch](#Dispatch)
- [DocC](#DocC)
- [Dynamic Type](#Dynamic-Type)
- [On-Demand Resources Essentials](On-Demand-Resources-Essentials)
- [LLVM](#LLVM)
- [CallKit](#CallKit)
- [Push to Talk iOS 16.0+](#Push-to-Talk-iOS)
- [ActivityKit](#ActivityKit)
- [SPM](#SPM)
- [AST](#AST-Abstract-Syntax-Tree)
- [Image I/O](#Image-I/O)
- [iOS APP添加桌面快捷方式](#iOS-APP添加桌面快捷方式)
- [ReplayKit](#ReplayKit)
- [AVFoundation](#AVFoundation)



## Foundation

### Data Formatting

#### Sample Code
>https://developer.apple.com/documentation/foundation/formatter/displaying_human-friendly_content
#### ListFormatter&PersonNameComponentsFormatter
>https://www.swiftbysundell.com/articles/exploring-some-of-the-lesser-known-formatter-types/ <br>
https://developer.apple.com/videos/play/wwdc2020/10160/ <br>
https://developer.apple.com/documentation/foundation/data_formatting <br>
#### Stringsdict File Format
>https://developer.apple.com/library/archive/documentation/MacOSX/Conceptual/BPInternational/StringsdictFileFormat/StringsdictFileFormat.html <br>
https://www.hackingwithswift.com/example-code/strings/how-to-display-different-strings-based-on-available-space-using-variantfittingpresentationwidth <br>
https://www.jianshu.com/p/a271347324de <br>

#### Formatter API
>https://developer.apple.com/documentation/foundation/date/3766588-formatted <br>
>[WWDC 2021新Formatter API：新老比较及如何自定义](https://mp.weixin.qq.com/s?__biz=MzU1Njg1NDg5NQ==&mid=2247484045&idx=1&sn=650999efc80b7574b5fcb9f597d360c1&chksm=fc3ff98dcb48709bd875f445f44cbe08598f93fb83007bb6f5a9b466472a081bf7bb852364cc&cur_album_id=2007510232968593415&scene=189#rd) <br>

### Codable
>https://www.andyibanez.com/posts/the-mysterious-codablewithconfiguration-protocol/ <br>
>[深入 Decodable —— 写一个超越原生的 JSON 解析器](https://kemchenj.github.io/2018-06-03/) <br>

### AttributedString
>[AttributedString](https://developer.apple.com/documentation/foundation/attributedstring) <br>
>[AttributedString——不仅仅让文字更漂亮](https://mp.weixin.qq.com/s?__biz=MzU1Njg1NDg5NQ==&mid=2247484058&idx=1&sn=c1e476c641e1d5cfb1183098bb7fda86&chksm=fc3ff99acb48708cc9215117681940bc99d2f720e3f67d9bd8e756c0e20cee735bd4fc5e46c8&cur_album_id=2007510232968593415&scene=189#rd) <br>

### NotificationCenter
> [Typed Notifications](https://talk.objc.io/episodes/S01E27-typed-notifications-part-1) <br>

> 通过block接口添加通知NotificationCenter.addObserver(forName: object: queue: using:)，需要手动删除，否则内存泄漏
> ``` swift
> let token = addObserver(forName: name, object: obj, queue: queue, using: block)
> NotificationCenter.default.removeObserver(token as Any)
> ```


### Notification
> [Using Critical Alerts in iOS applications](https://blog.kulman.sk/using-critical-alerts-on-ios/) <br>

---
---


## Core-ML
>[Core ML](https://developer.apple.com/documentation/coreml) <br>
>[Awesome-CoreML-Models](https://likedan.github.io/Awesome-CoreML-Models/) <br>

---
---


## ARkit
>[Awesome-ARKit](https://github.com/olucurious/Awesome-ARKit) <br>

---
---

## Vision
>[Detecting Hand Poses with Vision](https://developer.apple.com/documentation/vision/detecting_hand_poses_with_vision) <br>
>[Detecting Human Body Poses in an Image](https://developer.apple.com/documentation/coreml/detecting_human_body_poses_in_an_image) <br>


### VisionKit
>[VisionKit](https://developer.apple.com/documentation/visionkit) <br>
>[isionKit document scanner](https://github.com/hansemannn/titanium-scanner) <br>
>[用苹果官方 API 实现 iOS 备忘录的扫描文稿功能](https://www.fatbobman.com/posts/docScaner/) <br>
>[【WWDC22 10025】VisionKit 的机器视觉方案，更智能的捕获文本与条码](https://xiaozhuanlan.com/topic/8205316479) <br>

---
---

## UIKit

### UIView
>[ios UIView的mask属性,view和layer的关系](https://blog.csdn.net/u014600626/article/details/99854281) <br>

### Autolayout
>[iOS9下代码创建约束](https://blog.csdn.net/u014084081/article/details/52174504) <br>
>[Align UIButton and UILabel text with different font sizes](https://stackoverflow.com/questions/61907854/align-uibutton-and-uilabel-text-with-different-font-sizes) <br>
>[IOS AutoLayout 详解](https://www.jianshu.com/p/4ef0277e9c5e) <br>
>[Adventures in iOS Programming: Self-Sizing Cells](https://www.biteinteractive.com/adventures-in-ios-programming-self-sizing-cells/) <br>
>[setNeedsLayout VS layoutIfNeeded](https://www.jianshu.com/p/58f53e600a94) <br>
>[Editing Multiple Constraints](https://useyourloaf.com/blog/editing-multiple-constraints/) <br>
>[YW浣熊的iOS— Size Class — Compact vs Regular](https://medium.com/@yw.raccoon/yw%E6%B5%A3%E7%86%8A%E7%9A%84ios-size-class-compact-vs-regular-16a07431a3cb) <br>
>[Auto Layout Guide](https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/AutolayoutPG/index.html#//apple_ref/doc/uid/TP40010853-CH7-SW1) <br>
>[Demo](https://github.com/aresxin/AutoLayout) <br>

> [iOS safeAreaInsets相关知识](https://juejin.cn/post/6844903958205431815) 
> 修改安全区域, 如果对系统所提供的安全区域不满意， 还可以通过additionalSafeAreaInsets属性来修改安全区域
> ```
> - (void)viewDidLoad {
>     [super viewDidLoad];
>     self.view.backgroundColor = UIColor.redColor;
>     //修改安全区域  
>     self.additionalSafeAreaInsets = UIEdgeInsetsMake(100, 30, 100, 40);
> }
> 输出结果：
> self.view.safeAreaInsets.top = 144.000000
> self.view.safeAreaInsets.left = 30.000000
> self.view.safeAreaInsets.bottom = 134.000000
> self.view.safeAreaInsets.right = 40.000000 
> ```
> 从输出接口可以看出：<br>
> (1)通过additionalSafeAreaInsets可以修改安全区域的大小；<br>
> (2)修改的安全区域的大小时，是在原来的安全区域的基础上做出修改的；<br>


---
---

### UICollectionView
#### iOS 13 Compositional Layouts
>[iOS 13 Compositional Layouts in CollectionView](https://betterprogramming.pub/ios-13-compositional-layouts-in-collectionview-90a574b410b8) <br>
>[Compositional Layout 詳解　讓你簡單操作 CollectionView！](https://www.appcoda.com.tw/compositional-layout/) <br>


#### ios 13 diffable data source
>[Advances in UI Data Sources](https://developer.apple.com/videos/play/wwdc2019/220/) -Apple Session <br>
>[NSDiffableDataSourceSnapshot](https://developer.apple.com/documentation/uikit/nsdiffabledatasourcesnapshot) -Apple Doc <br>
>[iOS开发之DiffableDataSource](https://cloud.tencent.com/developer/article/1639759) <br>

#### Customizing Collection View Layouts
>[Customizing Collection View Layout](https://developer.apple.com/documentation/uikit/views_and_controls/collection_views/layouts/customizing_collection_view_layouts) <br>
>[uicollectionview-layouts-kit](https://github.com/jVirus/uicollectionview-layouts-kit) A set of custom layouts for UICollectionView with examples <br>
>[Longpress drag and drop using UICollectionView with Animation](https://mobikul.com/ios-longpress-drag-and-drop-using-uicollectionview-with-animation/) 拖拽cell排序，删除cell，动画<br>

### UIViewPropertyAnimator
>[UIViewPropertyAnimator](https://developer.apple.com/documentation/uikit/uiviewpropertyanimator) <br>
>[使用 UIViewPropertyAnimator 做动画](https://swift.gg/2017/04/20/quick-guide-animations-with-uiviewpropertyanimator/) <br>



### Drawing&UIBezierPath
>[運用 UIBezierPath 繪製各種形狀](https://medium.com/%E5%BD%BC%E5%BE%97%E6%BD%98%E7%9A%84-swift-ios-app-%E9%96%8B%E7%99%BC%E5%95%8F%E9%A1%8C%E8%A7%A3%E7%AD%94%E9%9B%86/%E9%81%8B%E7%94%A8-uibezierpath-%E7%B9%AA%E8%A3%BD%E5%BD%A2-3c858e194676) <br>
>[利用 mask 設計特別形狀的圖片](https://medium.com/%E5%BD%BC%E5%BE%97%E6%BD%98%E7%9A%84-swift-ios-app-%E9%96%8B%E7%99%BC%E5%95%8F%E9%A1%8C%E8%A7%A3%E7%AD%94%E9%9B%86/%E5%88%A9%E7%94%A8-uiview-%E7%9A%84-mask-%E8%A8%AD%E8%A8%88%E7%89%B9%E5%88%A5%E5%BD%A2%E7%8B%80%E7%9A%84%E5%9C%96%E7%89%87-4e22cd7c3fbe) <br>

---
---

## WebKit
### WKWebView
>[干货：探秘WKWebView](https://mp.weixin.qq.com/s/l9D4V0ON3uJ0HfsJ7bpJiQ) <br>
>[webview NSURLErrorCancelled](https://developer.aliyun.com/article/37066) <br>
>[WKWebView get Javascript Errors](https://stackoverflow.com/questions/50229935/wkwebview-get-javascript-errors) <br>
>[Enabling the Inspection of Web Content in Apps](https://webkit.org/blog/13936/enabling-the-inspection-of-web-content-in-apps/) <br>
>[Enabling Web Inspector](https://webkit.org/web-inspector/enabling-web-inspector/) <br>

---
---

## GroupActivities
>[GroupActivities](https://developer.apple.com/documentation/GroupActivities) <br>
>[SharePlay for Developers](https://developer.apple.com/shareplay/) <br>

---
---

## Core-Image
>[Core Image](https://developer.apple.com/documentation/coreimage) <br>
>[Core Image Filter Reference](https://developer.apple.com/library/archive/documentation/GraphicsImaging/Reference/CoreImageFilterReference/index.html#//apple_ref/doc/uid/TP40004346) <br>
>[Core Image Tutorial for iOS: Custom Filters](https://www.raywenderlich.com/25658084-core-image-tutorial-for-ios-custom-filters) <br>
>[Native QR Code Generation in Swift with CIFilter](https://digitalbunker.dev/native-barcode-qr-code-generation-in-swift/) <br>

---
---

## APP-Icon
>[Xcode 配置多套 App 图标的方法 --- AppStore 图标 A/B Test 实践](https://mp.weixin.qq.com/s?__biz=MzAxMzE2Mjc2Ng==&mid=2652167886&idx=1&sn=f807bba7f970f2e99f4f524d80bb7905&scene=21#wechat_redirect) <br>

---
---

## App-Clip
>[App Clip 新特性](https://mp.weixin.qq.com/s?__biz=MzI2NTAxMzg2MA==&mid=2247493399&idx=1&sn=d8451a8205f6c60f54a9da2075ab7369&scene=21#wechat_redirect) <br>

---
---

## App-Documents-Share
>[App Documents Share](https://qiita.com/ShingoFukuyama/items/e85d34360f3f951ca612) <br>

---
---

## [Network](https://developer.apple.com/documentation/network)
### [NWPathMonitor](https://developer.apple.com/documentation/network/nwpathmonitor) 
>An observer that you use to monitor and react to network changes.
>[Native Network Monitoring In Swift](https://digitalbunker.dev/native-network-monitoring-in-swift/) <br>
>[Observe Your iOS App’s Network Connection Using Combine](https://betterprogramming.pub/observe-your-ios-apps-network-connection-using-combine-d96864111b83) <br>

---
---

## StoreKit
>[iOS StoreKit 2 新特性解析](https://mp.weixin.qq.com/s/RrkK5M3qYTs2cMi7sWTqrA) <br>
>[StoreKit 配置文件和搭建本地测试环境](https://xiaozhuanlan.com/topic/5842093617) <br>

---
---

## [Certificates](https://developer.apple.com/support/certificates/)
>[iOS | 图解iOS签名背后的原理](https://mp.weixin.qq.com/s?__biz=Mzg3MjcxNzUxOQ==&mid=2247484901&idx=1&sn=83fcf34b5b4b7a63c17742efa3ee20a8&chksm=ceea4845f99dc1537003bdebd2a93d09c9b413ad0cc8c5108cd93d5b84e63e65a30ce0f6c019&token=996185752&lang=zh_CN#rd) <br>

---
---

## [Dispatch](https://developer.apple.com/documentation/dispatch)
### [DispatchWorkItem](https://developer.apple.com/documentation/dispatch/dispatchworkitem) 
> [A Deep Dive Into Swift’s DispatchWorkItem](https://betterprogramming.pub/a-deep-dive-into-dispatchworkitem-274548357dea) <br>
> ```
> 1.可以跟定时器配合取消任务
> 2.可以用来任务通知
> ```

> [不改一行业务代码，飞书 iOS 低端机启动优化实践](https://mp.weixin.qq.com/s/KQJ5QXHdhwHRN65KdD45qA) 调整GCD的优先级，不抢占主线程资源从而提高启动时间<br>

---
---

## DocC
[DocC](https://developer.apple.com/documentation/docc) <br>
> [Create great documentation with DocC](https://developer.apple.com/news/?id=xa4ak3qr) <br>
> [swift-docc](https://github.com/apple/swift-docc) <br>
> [swift-docc-plugin](https://github.com/apple/swift-docc-plugin) <br>
> [【老司机精选】DocC: 未曾设想的苹果文档](https://juejin.cn/post/7083677416119336974) <br>

---
---

## Dynamic-Type
> [Scaling Fonts Automatically](https://developer.apple.com/documentation/uikit/uifont/scaling_fonts_automatically) <br>
> [13 | 功能组件：如何设置动态字体，提升视力辅助功能？](https://www.jianshu.com/p/70f2519a10b3) <br>
> [由使用者決定 App 文字大小的 Dynamic Type](https://medium.com/%E5%BD%BC%E5%BE%97%E6%BD%98%E7%9A%84-swift-ios-app-%E9%96%8B%E7%99%BC%E5%95%8F%E9%A1%8C%E8%A7%A3%E7%AD%94%E9%9B%86/%E7%94%B1%E4%BD%BF%E7%94%A8%E8%80%85%E6%B1%BA%E5%AE%9A-app-%E6%96%87%E5%AD%97%E5%A4%A7%E5%B0%8F%E7%9A%84-dynamic-type-dffeb6df90d7) <br>
> [UIFontMetrics](https://developer.apple.com/documentation/uikit/uifontmetrics)A utility object for obtaining custom fonts that scale to support Dynamic Type. <br>

---
---


## On-Demand-Resources-Essentials
> [On-Demand Resources Essentials](https://developer.apple.com/library/archive/documentation/FileManagement/Conceptual/On_Demand_Resources_Guide/index.html#//apple_ref/doc/uid/TP40015083-CH2-SW1) <br>
> [iOS On-Demand Resource 按需加载资源](https://www.jianshu.com/p/bacedd8a3ad8) <br>
> [Alibaba.com App瘦身实践——iOS包大小技术与ROI总结](https://juejin.cn/post/7117074938577551368) <br>

---
---

## LLVM
> [使用 LLVM](https://ming1016.github.io/2022/06/10/use-llvm/) <br>

---
---

## [CallKit](https://developer.apple.com/documentation/callkit)
>[微信重磅功能回归，终于解禁](https://www.sohu.com/a/471434225_116600) <br>

---
---

## [Push-to-Talk](https://developer.apple.com/documentation/pushtotalk) <br>
>[Push to Talk 实现“对讲机”](https://xiaozhuanlan.com/topic/2863915470) <br>

---
---

## [ActivityKit](https://developer.apple.com/documentation/activitykit)
> With the ActivityKit framework, you can start a Live Activity to share live updates from your app on the Lock Screen <br>
> ActivityKit可以在锁屏画面添加App的活动 <br>
> [iOS 16 锁定屏幕的实时活动现在可供具有最新测试版的开发人员使用](https://behmaster.com/zh-CN/ios-16-live-activities-for-the-lock-screen-now-available-for-developers-with-latest-beta/) <br>

### Dynamic Island(灵动岛)
>[Dynamic Island (and Live Activities): Quick start tutorial](https://nemecek.be/blog/171/dynamic-island-and-live-activities-quick-start-tutorial) <br>
>[Dynamic-Islands](https://github.com/jordibruin/Dynamic-Islands) About
A sample of dynamic island designs recreated for inspiration <br>
>[iOS灵动岛开发实践](https://juejin.cn/post/7153236337074634788) <br>
>[盒马 iOS Live Activity &“灵动岛”配送场景实践](https://mp.weixin.qq.com/s?__biz=Mzg4MjE5OTI4Mw==&mid=2247497758&idx=1&sn=3cb172fcddbca8dc686dc32d0dc5cd94&chksm=cf58e782f82f6e943426565fa79129ab3536ecbe7bdf86f52543fc861734205b720909cff0a6&token=1317516175&lang=zh_CN#rd) <br>

---
---

## SPM 
### Swift Package plugins 
> [Swift Package plugins 初探](https://xiaozhuanlan.com/topic/7316598402) <br>
> 命令 plugins 可以运行一些自定义的操作，例如代码格式化，代码扫描等。 <br>
> 构建工具 plugins 扩展了构建系统的依赖关系图，可以直接在构建过程中生成源代码或资源 <br>
> [SwiftGenPlugin](https://github.com/canius/PluginTool/blob/fa3f890cbf26c095fd2a358b3c89b849f7bc4380/Plugins/SwiftGenPlugin/plugin.swift) 使用Command plugin在project prebuild时执行swiftgen命令<br>
> [使用 Swift Package 插件生成代码](https://mp.weixin.qq.com/s/0ZHfaTiJXAXrWj5qTunhLg) <br>
> [Meet Swift Package plugins](https://developer.apple.com/videos/play/wwdc2022/110359/) <br>
> [Xcode 中使用 SPM 和 Build Configuration 的一些坑](https://onevcat.com/2022/10/spm-in-xcode/) <br>
> [Swift Package Manager工程实践](https://mp.weixin.qq.com/s/q7jolU99K7FI9JvAxjwRwg) <br>
> [Binary Targets in Swift Package Manager](https://www.avanderlee.com/optimization/binary-targets-swift-package-manager/#the-upsides-of-binary-targets)   利用SwiftPackag 管理xcframework<br>
> [How to Use Swift Package Manager to Save Gigabytes of Network Traffic and Disk Space](https://betterprogramming.pub/how-to-use-swift-package-manager-saving-gigabytes-of-network-traffic-and-disk-space-998bd148ad56) <br>

---
---

## AST-Abstract-Syntax-Tree
> [SourceKitten](https://github.com/jpsim/SourceKitten) <br>
> [利用 Jazzy + SourceKitten 生成多依赖库的在线文档](https://juejin.cn/post/6844904197524029453) <br>
> [SwiftSyntax](https://swift.gg/2019/01/25/nshipster-swiftsyntax/) 抽象语法树（Abstract Syntax Tree，AST）<br>
> [sourcekit-lsp](https://github.com/apple/sourcekit-lsp) <br>

---
---

## Image-I/O
> [Image I/O](https://developer.apple.com/documentation/imageio) <br>
> [探秘越来越复杂的 ImageIO 框架](https://mp.weixin.qq.com/s/nbPIScJEZ3ReMSFuvNLkzQ) <br>

---
---


## iOS-APP添加桌面快捷方式
> [iOS APP添加桌面快捷方式](https://mp.weixin.qq.com/s/z_CfthCni7m1mKtM0KzH6g) <br>

---
---

## ReplayKit
> [iOS ReplayKit 与 屏幕录制](https://mp.weixin.qq.com/s/NbT1BE0CmYkyMXeVIekCpQ) <br>

---
---


## AVFoundation
> [淘宝iOS拍立淘微距能力探索与实现](https://mp.weixin.qq.com/s/4tG4BTx54rXIdHbXKqI_cQ) <br>

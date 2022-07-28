# Apple

* Foundation
* SwiftUI
* Core ML
* Combine
* ARkit
* Vision
* VisionKit
* UIKit
* WebKit
* GroupActivities
* Core Image
* APP Icon
* App Clip
* App Documents Share
* Network
* StoreKit
* Certificates
* Dispatch
* DocC
* Dynamic Type
* Swift Charts
* On-Demand Resources Essentials
* LLVM
* CallKit
* Push to Talk iOS 16.0+ 
* ActivityKit

# Foundation
## Data Formatting
### Sample Code
>https://developer.apple.com/documentation/foundation/formatter/displaying_human-friendly_content
### ListFormatter&PersonNameComponentsFormatter
>https://www.swiftbysundell.com/articles/exploring-some-of-the-lesser-known-formatter-types/ <br>
https://developer.apple.com/videos/play/wwdc2020/10160/ <br>
https://developer.apple.com/documentation/foundation/data_formatting <br>
### Stringsdict File Format
>https://developer.apple.com/library/archive/documentation/MacOSX/Conceptual/BPInternational/StringsdictFileFormat/StringsdictFileFormat.html <br>
https://www.hackingwithswift.com/example-code/strings/how-to-display-different-strings-based-on-available-space-using-variantfittingpresentationwidth <br>
https://www.jianshu.com/p/a271347324de <br>

### Formatter API
>https://developer.apple.com/documentation/foundation/date/3766588-formatted <br>
>[WWDC 2021新Formatter API：新老比较及如何自定义](https://mp.weixin.qq.com/s?__biz=MzU1Njg1NDg5NQ==&mid=2247484045&idx=1&sn=650999efc80b7574b5fcb9f597d360c1&chksm=fc3ff98dcb48709bd875f445f44cbe08598f93fb83007bb6f5a9b466472a081bf7bb852364cc&cur_album_id=2007510232968593415&scene=189#rd) <br>

## Codable
>https://www.andyibanez.com/posts/the-mysterious-codablewithconfiguration-protocol/ <br>
>[深入 Decodable —— 写一个超越原生的 JSON 解析器](https://kemchenj.github.io/2018-06-03/) <br>

## AttributedString
>[AttributedString](https://developer.apple.com/documentation/foundation/attributedstring) <br>
>[AttributedString——不仅仅让文字更漂亮](https://mp.weixin.qq.com/s?__biz=MzU1Njg1NDg5NQ==&mid=2247484058&idx=1&sn=c1e476c641e1d5cfb1183098bb7fda86&chksm=fc3ff99acb48708cc9215117681940bc99d2f720e3f67d9bd8e756c0e20cee735bd4fc5e46c8&cur_album_id=2007510232968593415&scene=189#rd) <br>

## NotificationCenter
[Typed Notifications](https://talk.objc.io/episodes/S01E27-typed-notifications-part-1) <br>

通过block接口添加通知NotificationCenter.addObserver(forName: object: queue: using:)，需要手动删除，否则内存泄漏
``` swift
let token = addObserver(forName: name, object: obj, queue: queue, using: block)
NotificationCenter.default.removeObserver(token as Any)
```
---
---

# SwiftUI
>https://cs193p.sites.stanford.edu/

---
---

# Core ML
>[Core ML](https://developer.apple.com/documentation/coreml) <br>
>[Awesome-CoreML-Models](https://likedan.github.io/Awesome-CoreML-Models/) <br>

---
---

# Combine
>https://developer.apple.com/documentation/combine <br>
https://theswiftdev.com/urlsession-and-the-combine-framework/ <br>
https://onevcat.com/2020/01/customize-publisher/ <br>
https://www.jianshu.com/p/df8535b40079 <br>
https://www.jianshu.com/p/a9c04a84d911 <br>
https://github.com/cx-org/CombineX <br>
https://github.com/yanglfree/SwiftUI-Combine-Coding <br>
https://learnku.com/articles/36322 <br>
https://zhuanlan.zhihu.com/p/343631974 <br>
[深入浅出 Apple 响应式框架 Combine](https://www.infoq.cn/article/eaq01u5jevuvqfghlqbs) <br>
[Apple 官方异步编程框架：Swift Combine 简介](https://nemocdz.github.io/post/apple-%E5%AE%98%E6%96%B9%E5%BC%82%E6%AD%A5%E7%BC%96%E7%A8%8B%E6%A1%86%E6%9E%B6swift-combine-%E7%AE%80%E4%BB%8B/) <br>
[Apple 官方异步编程框架：Swift Combine 应用](https://nemocdz.github.io/post/apple-%E5%AE%98%E6%96%B9%E5%BC%82%E6%AD%A5%E7%BC%96%E7%A8%8B%E6%A1%86%E6%9E%B6swift-combine-%E5%BA%94%E7%94%A8/) <br>
[Combine 框架，从0到1 —— 5.Combine 提供的发布者(Publishers)](https://www.cnblogs.com/ficow/p/13728001.html) <br>
[UIKit Combine](https://www.jianshu.com/p/b98f3e9c610c) <br>
[Combine 简明教程一： Publisher、Subscriber](https://keisme.cn/Combine-%E7%AE%80%E6%98%8E%E6%95%99%E7%A8%8B%E4%B8%80%EF%BC%9APublisher%E3%80%81Subscriber.html) <br>
[Combine 简明教程二：自定义 Subscriber、Publisher](https://keisme.cn/Combine-%E7%AE%80%E6%98%8E%E6%95%99%E7%A8%8B%E4%BA%8C%EF%BC%9A%E8%87%AA%E5%AE%9A%E4%B9%89-Subscriber%E3%80%81Publisher.html) <br>
[Combine 简明教程三：Subject](https://keisme.cn/Combine-%E7%AE%80%E6%98%8E%E6%95%99%E7%A8%8B%E4%B8%89%EF%BC%9ASubject.html) <br>
[Combine 简明教程四：Operators](https://keisme.cn/Combine-%E7%AE%80%E6%98%8E%E6%95%99%E7%A8%8B%E5%9B%9B%EF%BC%9AOperators.html) <br>
[从响应式编程到 Combine 实践](https://mp.weixin.qq.com/s?__biz=MzI1MzYzMjE0MQ==&mid=2247495012&idx=1&sn=89b85dd6e2e85d708a2415b78343e9a0&scene=21#wechat_redirect) <br>

---
---

# ARkit
>[Awesome-ARKit](https://github.com/olucurious/Awesome-ARKit) <br>

---
---

# Vision
>[Detecting Hand Poses with Vision](https://developer.apple.com/documentation/vision/detecting_hand_poses_with_vision) <br>
>[Detecting Human Body Poses in an Image](https://developer.apple.com/documentation/coreml/detecting_human_body_poses_in_an_image) <br>

---
---

# VisionKit
>[VisionKit](https://developer.apple.com/documentation/visionkit) <br>
>[isionKit document scanner](https://github.com/hansemannn/titanium-scanner) <br>
>[用苹果官方 API 实现 iOS 备忘录的扫描文稿功能](https://www.fatbobman.com/posts/docScaner/) <br>
>[【WWDC22 10025】VisionKit 的机器视觉方案，更智能的捕获文本与条码](https://xiaozhuanlan.com/topic/8205316479) <br>

---
---

# UIKit

## UIView
[ios UIView的mask属性,view和layer的关系](https://blog.csdn.net/u014600626/article/details/99854281) <br>

## Autolayout
>[iOS9下代码创建约束](https://blog.csdn.net/u014084081/article/details/52174504) <br>
>[Align UIButton and UILabel text with different font sizes](https://stackoverflow.com/questions/61907854/align-uibutton-and-uilabel-text-with-different-font-sizes) <br>
>[IOS AutoLayout 详解](https://www.jianshu.com/p/4ef0277e9c5e) <br>
>[Adventures in iOS Programming: Self-Sizing Cells](https://www.biteinteractive.com/adventures-in-ios-programming-self-sizing-cells/) <br>
>[setNeedsLayout VS layoutIfNeeded](https://www.jianshu.com/p/58f53e600a94) <br>
>[Editing Multiple Constraints](https://useyourloaf.com/blog/editing-multiple-constraints/) <br>
---
>[YW浣熊的iOS— Size Class — Compact vs Regular](https://medium.com/@yw.raccoon/yw%E6%B5%A3%E7%86%8A%E7%9A%84ios-size-class-compact-vs-regular-16a07431a3cb) <br>
>[Auto Layout Guide](https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/AutolayoutPG/index.html#//apple_ref/doc/uid/TP40010853-CH7-SW1) <br>
>[Demo](https://github.com/aresxin/AutoLayout) <br>
---

---
>[iOS safeAreaInsets相关知识](https://juejin.cn/post/6844903958205431815) <br>
>修改安全区域, 如果对系统所提供的安全区域不满意， 还可以通过additionalSafeAreaInsets属性来修改安全区域 <br>
```
- (void)viewDidLoad {
    [super viewDidLoad];
    self.view.backgroundColor = UIColor.redColor;
    //修改安全区域  
    self.additionalSafeAreaInsets = UIEdgeInsetsMake(100, 30, 100, 40);
}

输出结果：
self.view.safeAreaInsets.top = 144.000000
self.view.safeAreaInsets.left = 30.000000
self.view.safeAreaInsets.bottom = 134.000000
self.view.safeAreaInsets.right = 40.000000 
```
>从输出接口可以看出：
>(1)通过additionalSafeAreaInsets可以修改安全区域的大小；
>(2)修改的安全区域的大小时，是在原来的安全区域的基础上做出修改的；
---

## UICollectionView
iOS 13 Compositional Layouts
---
>[iOS 13 Compositional Layouts in CollectionView](https://betterprogramming.pub/ios-13-compositional-layouts-in-collectionview-90a574b410b8) <br>
>[Compositional Layout 詳解　讓你簡單操作 CollectionView！](https://www.appcoda.com.tw/compositional-layout/) <br>
---
ios 13 diffable data source
---
>[Advances in UI Data Sources](https://developer.apple.com/videos/play/wwdc2019/220/) -Apple Session <br>
>[NSDiffableDataSourceSnapshot](https://developer.apple.com/documentation/uikit/nsdiffabledatasourcesnapshot) -Apple Doc <br>
>[iOS开发之DiffableDataSource](https://cloud.tencent.com/developer/article/1639759) <br>
---
Customizing Collection View Layouts
>[Customizing Collection View Layout](https://developer.apple.com/documentation/uikit/views_and_controls/collection_views/layouts/customizing_collection_view_layouts) <br>
>[uicollectionview-layouts-kit](https://github.com/jVirus/uicollectionview-layouts-kit) A set of custom layouts for UICollectionView with examples <br>
>[Longpress drag and drop using UICollectionView with Animation](https://mobikul.com/ios-longpress-drag-and-drop-using-uicollectionview-with-animation/) 拖拽cell排序，删除cell，动画<br>

## UIViewPropertyAnimator
>[UIViewPropertyAnimator](https://developer.apple.com/documentation/uikit/uiviewpropertyanimator) <br>
>[使用 UIViewPropertyAnimator 做动画](https://swift.gg/2017/04/20/quick-guide-animations-with-uiviewpropertyanimator/) <br>

---
---

## Drawing&UIBezierPath
>[運用 UIBezierPath 繪製各種形狀](https://medium.com/%E5%BD%BC%E5%BE%97%E6%BD%98%E7%9A%84-swift-ios-app-%E9%96%8B%E7%99%BC%E5%95%8F%E9%A1%8C%E8%A7%A3%E7%AD%94%E9%9B%86/%E9%81%8B%E7%94%A8-uibezierpath-%E7%B9%AA%E8%A3%BD%E5%BD%A2-3c858e194676) <br>
>[利用 mask 設計特別形狀的圖片](https://medium.com/%E5%BD%BC%E5%BE%97%E6%BD%98%E7%9A%84-swift-ios-app-%E9%96%8B%E7%99%BC%E5%95%8F%E9%A1%8C%E8%A7%A3%E7%AD%94%E9%9B%86/%E5%88%A9%E7%94%A8-uiview-%E7%9A%84-mask-%E8%A8%AD%E8%A8%88%E7%89%B9%E5%88%A5%E5%BD%A2%E7%8B%80%E7%9A%84%E5%9C%96%E7%89%87-4e22cd7c3fbe) <br>

---
---

# WebKit
## WKWebView
>[干货：探秘WKWebView](https://mp.weixin.qq.com/s/l9D4V0ON3uJ0HfsJ7bpJiQ) <br>
>[webview NSURLErrorCancelled](https://developer.aliyun.com/article/37066) <br>
>[WKWebView get Javascript Errors](https://stackoverflow.com/questions/50229935/wkwebview-get-javascript-errors) <br>

---
---

# GroupActivities
>[GroupActivities](https://developer.apple.com/documentation/GroupActivities) <br>
>[SharePlay for Developers](https://developer.apple.com/shareplay/) <br>

---
---

# Core Image
>[Core Image](https://developer.apple.com/documentation/coreimage) <br>
>[Core Image Filter Reference](https://developer.apple.com/library/archive/documentation/GraphicsImaging/Reference/CoreImageFilterReference/index.html#//apple_ref/doc/uid/TP40004346) <br>
>[Core Image Tutorial for iOS: Custom Filters](https://www.raywenderlich.com/25658084-core-image-tutorial-for-ios-custom-filters) <br>
>[Native QR Code Generation in Swift with CIFilter](https://digitalbunker.dev/native-barcode-qr-code-generation-in-swift/) <br>

---
---

# APP Icon
>[Xcode 配置多套 App 图标的方法 --- AppStore 图标 A/B Test 实践](https://mp.weixin.qq.com/s?__biz=MzAxMzE2Mjc2Ng==&mid=2652167886&idx=1&sn=f807bba7f970f2e99f4f524d80bb7905&scene=21#wechat_redirect) <br>

---
---

# App Clip
[App Clip 新特性](https://mp.weixin.qq.com/s?__biz=MzI2NTAxMzg2MA==&mid=2247493399&idx=1&sn=d8451a8205f6c60f54a9da2075ab7369&scene=21#wechat_redirect) <br>

---
---

# App Documents Share
[App Documents Share](https://qiita.com/ShingoFukuyama/items/e85d34360f3f951ca612) <br>

---
---

# [Network](https://developer.apple.com/documentation/network)
## [NWPathMonitor](https://developer.apple.com/documentation/network/nwpathmonitor) 
An observer that you use to monitor and react to network changes.
>[Native Network Monitoring In Swift](https://digitalbunker.dev/native-network-monitoring-in-swift/) <br>
>[Observe Your iOS App’s Network Connection Using Combine](https://betterprogramming.pub/observe-your-ios-apps-network-connection-using-combine-d96864111b83) <br>

---
---

# StoreKit
>[iOS StoreKit 2 新特性解析](https://mp.weixin.qq.com/s/RrkK5M3qYTs2cMi7sWTqrA) <br>
>[StoreKit 配置文件和搭建本地测试环境](https://xiaozhuanlan.com/topic/5842093617) <br>

---
---

# [Certificates](https://developer.apple.com/support/certificates/)
>[iOS | 图解iOS签名背后的原理](https://mp.weixin.qq.com/s?__biz=Mzg3MjcxNzUxOQ==&mid=2247484901&idx=1&sn=83fcf34b5b4b7a63c17742efa3ee20a8&chksm=ceea4845f99dc1537003bdebd2a93d09c9b413ad0cc8c5108cd93d5b84e63e65a30ce0f6c019&token=996185752&lang=zh_CN#rd) <br>

---
---

# [Dispatch](https://developer.apple.com/documentation/dispatch)
## [DispatchWorkItem](https://developer.apple.com/documentation/dispatch/dispatchworkitem) 

>[A Deep Dive Into Swift’s DispatchWorkItem](https://betterprogramming.pub/a-deep-dive-into-dispatchworkitem-274548357dea) <br>
```
1.可以跟定时器配合取消任务
2.可以用来任务通知
```

---
---

# DocC
[DocC](https://developer.apple.com/documentation/docc) <br>
[Create great documentation with DocC](https://developer.apple.com/news/?id=xa4ak3qr) <br>
[swift-docc](https://github.com/apple/swift-docc) <br>
[swift-docc-plugin](https://github.com/apple/swift-docc-plugin) <br>
[【老司机精选】DocC: 未曾设想的苹果文档](https://juejin.cn/post/7083677416119336974) <br>

---
---

# Dynamic Type
[Scaling Fonts Automatically](https://developer.apple.com/documentation/uikit/uifont/scaling_fonts_automatically) <br>
[13 | 功能组件：如何设置动态字体，提升视力辅助功能？](https://www.jianshu.com/p/70f2519a10b3) <br>
[由使用者決定 App 文字大小的 Dynamic Type](https://medium.com/%E5%BD%BC%E5%BE%97%E6%BD%98%E7%9A%84-swift-ios-app-%E9%96%8B%E7%99%BC%E5%95%8F%E9%A1%8C%E8%A7%A3%E7%AD%94%E9%9B%86/%E7%94%B1%E4%BD%BF%E7%94%A8%E8%80%85%E6%B1%BA%E5%AE%9A-app-%E6%96%87%E5%AD%97%E5%A4%A7%E5%B0%8F%E7%9A%84-dynamic-type-dffeb6df90d7) <br>
[UIFontMetrics](https://developer.apple.com/documentation/uikit/uifontmetrics)A utility object for obtaining custom fonts that scale to support Dynamic Type. <br>

---
---

# Swift Charts
[Swift Charts](https://developer.apple.com/documentation/Charts)Construct and customize charts on every Apple platform. <br>

---
---

# On-Demand Resources Essentials
[On-Demand Resources Essentials](https://developer.apple.com/library/archive/documentation/FileManagement/Conceptual/On_Demand_Resources_Guide/index.html#//apple_ref/doc/uid/TP40015083-CH2-SW1) <br>
[iOS On-Demand Resource 按需加载资源](https://www.jianshu.com/p/bacedd8a3ad8) <br>
[Alibaba.com App瘦身实践——iOS包大小技术与ROI总结](https://juejin.cn/post/7117074938577551368) <br>

---
---

# LLVM
[使用 LLVM](https://ming1016.github.io/2022/06/10/use-llvm/) <br>

---
---

# [CallKit](https://developer.apple.com/documentation/callkit)
>[微信重磅功能回归，终于解禁](https://www.sohu.com/a/471434225_116600) <br>

---
---

# [Push to Talk](https://developer.apple.com/documentation/pushtotalk) <br>
>[Push to Talk 实现“对讲机”](https://xiaozhuanlan.com/topic/2863915470) <br>

---
---

# [ActivityKit](https://developer.apple.com/documentation/activitykit)
ActivityKit可以在锁屏画面添加App的活动
[iOS 16 锁定屏幕的实时活动现在可供具有最新测试版的开发人员使用](https://behmaster.com/zh-CN/ios-16-live-activities-for-the-lock-screen-now-available-for-developers-with-latest-beta/) <br>

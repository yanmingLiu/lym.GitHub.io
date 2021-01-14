
# iOS葵花宝典之Swift

### 网络篇

**[Alamofire](https://github.com/Alamofire/Alamofire)**
swift版本的AFNetworking , 都是matt大神作品。

**[Moya](https://github.com/Moya/Moya)**
Moya是一个将Alamofire进行封装的网络抽象库。由几个模块：
- provider 是一个提供网络请求服务的提供者
- Request  直接用provider来发起request。
- Response Response这个类对于请求结果，提供了一些加工方法，比如data转json,图片转换等。
- Plugins Moya提供了一个插件协议PluginType，协议里规定了几种方法，阐明了插件的应用区域。


### 解析篇

**[SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON)**
SwiftyJSON 老牌的 JSON 解析库，对于嵌套复杂的 JSON 数据依然能非常灵活地取值。

**[HandyJSON](https://github.com/alibaba/HandyJSON)**
HandyJSON是由阿里巴巴出品swift解析库，上手容易，能让你找到类似oc中使用YYModel MJExtension的手感。

**[KakaJSON](https://github.com/kakaopensource/KakaJSON)**
 MJ老师出品。

### 缓存篇

**[YYCache](https://github.com/ibireme/YYCache)**
即便swift轻量级缓存依然推荐使用YYCache，YYKit影响力相信国内iOS开发者无人不知。

**[WCDB](https://github.com/Tencent/wcdb/wiki#wcdb-for-iosmacos)**
腾讯微信出品，这个就是理由。WCDB是一个高效、完整、易用的移动数据库框架，支持iOS, macOS和Android。

**[Cache](https://github.com/hyperoslo/Cache)**
Cache除了缓存，它什么也没做，但它做得很好。它提供了一个很好的公共API，具有现成的实现和巨大的自定义可能性。Cache利用Codable执行序列化。

### 图片篇

**[Kingfisher](https://github.com/onevcat/Kingfisher)**
喵神 onevcat 开源及维护。 swift版的 SDWebImage。

**[Lantern](https://github.com/fcbox/Lantern)**
丰巢研发团队开发维护的图片浏览器。

**[ZLPhotoBrowser](https://github.com/longitachi/ZLPhotoBrowser)**
纯Swift多功能图片库，你想要的应有尽有。

**[R.swift](https://github.com/mac-cain13/R.swift)**
Swift强大资源管理库，图片、字体、xib/storyboard、颜色等资源管理。

### 布局篇

**[SnapKit](https://github.com/SnapKit/SnapKit)**
swift版的 Masonry.

### 工具篇

**[fastlane](https://github.com/fastlane/fastlane)** 
自动打包发布蒲公英，上架app。

**[RxSwift](https://github.com/ReactiveX/RxSwift)**
如果你在oc中使用ReactiveObjC，那swift你也必然会使用它。

**[CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift)**
非常流行的加密解密库，项目中常用的加密解密都可以用这个库。

**[SwiftDate](https://github.com/malcommac/SwiftDate)**
非常好用的帮助处理 Date 相关的库。灵活运用了 swift 的重载操作符、扩展等特性，使得时间可以直观的进行算术运算：比较大小，直接加减等。

**[IQKeyboardManagerSwift](https://github.com/hackiftekhar/IQKeyboardManager)**
键盘管理

**[URLNavigator](https://github.com/devxoul/URLNavigator)**
⛵️URLNavigator提供了一种优雅的方式来通过URL在视图控制器之间进行导航。可以使用URLNavigator.register(_:_:)功能映射URL模式。

### UI篇

**[ESPullToRefresh](https://github.com/eggswift/pull-to-refresh)**
ESPullToRefresh是一个非常易于开发者使用的下拉刷新和加载更多组件。

**[SkeletonView](https://github.com/Juanpe/SkeletonView)**
骨架屏,demo中collection cell未加载出子视图是因为demo中子视图是添加到cell上，改为  contentView.addSubview(imageView)即可。

**[EmptyStateKit](https://github.com/alberdev/EmptyStateKit)**
空白页灵活性和易用性，在任何具有刷新内容功能的UIView或UITableView / UICollectionView中显示出色的占位符为空状态。

**[FSPagerView](https://github.com/WenchaoD/FSPagerView)**
FSPagerView是一个优雅的轮播库，主要通过UICollectionView实现。

**[AutoInch](https://github.com/lixiang1994/AutoInch)**
优雅的iPhone等比例/全尺寸精准适配工具

**[CollectionViewWaterfallLayout](https://github.com/ecerney/CollectionViewWaterfallLayout)**
**[WaterfallMultiSectionFlowLayout](https://github.com/RoganZheng/WaterfallMultiSectionFlowLayout)**
瀑布流基于 UICollectionViewFlowLayout 实现，支持多 section 场景下瀑布流、线性排列、九宫格样式。

**[SwiftyAttributes](https://github.com/eddiekaiger/SwiftyAttributes)**  
先进的 API ，操作 attributed 字符串的利器。

**[Toast-Swift](https://github.com/scalessec/Toast-Swift)**  
使用简单弹窗提示。

**[TextFieldEffects](https://github.com/raulriera/TextFieldEffects)**   
带动画输入框。

**[NVActivityIndicatorView](https://github.com/ninjaprox/NVActivityIndicatorView)** 3
2种loading加载动画。


**[UIDrawer-modalPresentationStyle](https://github.com/Que20/UIDrawer)**
**[HWPanModal-modalPresentationStyle](https://github.com/HeathWang/HWPanModal)**
仿iOS13交互式的弹出视图


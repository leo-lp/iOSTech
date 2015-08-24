##iOSTech

A useful tools or tips list for iOS application developing

这个项目收集iOS开发所需要的一些资源与小技巧

不管是在湖南，还是在外地的湖南人，学生，或者已经工作的偏移，都可以加入**一起来学iOS（HN）**

**QQ群：483103713**

申请须知：此群有地域限制，申请时需要告知你的家乡是否在湖南省内，属于哪个县市区。

----

##为什么你要拒绝我

- [Why-Reject](https://github.com/jcccn/Why-Reject) ----- *苹果AppStore被拒理由大全*

##工具类

- [SimPholders2](http://simpholders.com/) ----- *模拟器文件目录埋的太深，用这个工具可以直接定位到模拟器目录。*
- [Makeappicon](http://makeappicon.com/) ----- *上传一张1024x1024的图片，自动生成Icon Png。*
- [Appscreens](https://appscreens.io/) ----- *提交AppStore时所需要的截图，可以使用此工具。*
- [Reveal](http://revealapp.com/) ----- *调试UI可以用的工具，在运行时动态修改，不用重新编译，非常方便。*
- [PixelWinch](http://www.ricciadams.com/projects/pixel-winch) ----- *这个工具可以测量像素。*
- [DHC](https://www.sprintapi.com/dhcs.html) ----- *这个工具主要来测试网络请求。*
- [JSON格式化](http://www.runoob.com/tool/json/index.html) ----- *格式化JSON，看起来不会很吃力。*
- [TinyPNG](https://tinypng.com/) ----- *这个工具可以用来压缩图片质量*
- [Pixelmator](http://support.pixelmator.com/) ----- *这个工具可以用来切图或者查看设计稿*

##Xcode 插件类

- [Alcatraz](https://github.com/supermarin/Alcatraz) ----- *这个差距可以用来管理Xcode其他所有的插件。*
- [KSImageNamed-Xcode](https://github.com/ksuther/KSImageNamed-Xcode) ----- *使用UIImage时可以自动提示已经导入的图片。*
- [ColorSense-for-Xcode](https://github.com/omz/ColorSense-for-Xcode) ----- *使用UIColor时可以弹出Xcode的颜色选择器。*
- [SCXcodeMiniMap](https://github.com/stefanceriu/SCXcodeMiniMap) ----- *给Xcode增加一个mini小地图。*
- [VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode) ----- *快捷的编写文档注释。*
- [XToDo](https://github.com/trawor/XToDo) ----- *快速的查看To Do列表。*
- [XAlign](https://github.com/qfish/XAlign) ----- *可以快速的使代码对其。*
- [cocoapods-xcode-plugin](https://github.com/kattrali/cocoapods-xcode-plugin) ----- *方法查看和管理pod安装的第三方库。*
- [Ciapre-Xcode-theme](https://github.com/vinhnx/Ciapre-Xcode-theme) ----- *这是我个人非常喜欢的一个主题。*

##Xcode 操作类

快速阅读

- [14个Xcode中常用的快捷键操作](http://www.cocoachina.com/ios/20141224/10752.html)
- [Objective-C常用代码片段](https://github.com/Xcode-Snippets/Objective-C)
- [Swift常用代码片段](https://github.com/burczyk/XcodeSwiftSnippets)

深入全面的阅读

- [iOS开发进阶，从Xcode开始](http://www.cocoachina.com/special/xcode/) ----- *这是一个非常全面的专题，Xcode 6.0+ 的使用。*

##编程风格与最佳实践

编程风格

- [Google Objective-C编程风格指南](http://zh-google-styleguide.readthedocs.org/en/latest/google-objc-styleguide/contents/)
- [RayWenderlich 官方 Swift 编程风格指南](http://swift.gg/2015/08/11/raywenderlich-swift-style-guide/)
- [Google C++编程风格指南](http://zh-google-styleguide.readthedocs.org/en/latest/google-cpp-styleguide/contents/)

最佳实践

- [禅与 Objective-C 编程艺术](https://github.com/oa414/objc-zen-book-cn)
- [C 语言常见问题集](http://c-faq-chn.sourceforge.net/ccfaq/index.html)

##CocoaPods中国源

- [https://gitcafe.com/akuandev/Specs.git](https://gitcafe.com/akuandev/Specs.git)
- [http://git.oschina.net/akuandev/Specs.git](http://git.oschina.net/akuandev/Specs.git)

安装CocaoPods时所使用的源

- [http://ruby.taobao.org/](http://ruby.taobao.org/)

关于使用，可以阅读[用CocoaPods做iOS程序的依赖管理](http://blog.devtang.com/blog/2014/05/25/use-cocoapod-to-manage-ios-lib-dependency/)

##iOS尺寸，适配的问题

关于尺寸可以阅读一下译文。

- [图标和图像尺寸](http://deeper29.com/2015/04/29/icon-and-image-sizes/)
- [移动端尺寸基础知识](http://colachan.com/post/3435)

现在的iOS开发适配都开始使用Auto Layout来描述布局，苹果官方也非常推荐使用。

- [iOS 开发实践之 Auto Layout](http://xuexuefeng.com/autolayout/)

当然，深入到具体，大家都用Masonry代码的方式来做布局，因为苹果的约束布局非常繁琐。

- [Masonry介绍与使用实践(快速上手Autolayout)](http://adad184.com/2014/09/28/use-masonry-to-quick-solve-autolayout/)

也有朋友习惯使用storyboard来绘制和约束UI，可以阅读一下一个系列文章

- [Auto Layout 使用心得（一）—— 初体验](http://lvwenhan.com/ios/430.html)
- [Auto Layout 使用心得（二）—— 实现三等分](http://lvwenhan.com/ios/431.html)
- [Auto Layout 使用心得（三）—— 自定义 cell 并使用 Auto Layout](http://lvwenhan.com/ios/441.html)
- [Auto Layout 使用心得（四）—— 22 行代码实现拖动回弹](http://lvwenhan.com/ios/442.html)
- [Auto Layout 使用心得（五）—— 根据文字、图片自动计算 UITableViewCell 高度](http://lvwenhan.com/ios/449.html)
- [Auto Layout 使用心得（六）—— 制造炫酷的下拉刷新动画](http://lvwenhan.com/ios/450.html)

关于切图和适配方面可以阅读一下两个攻略

- [fitview-iOS切图攻略-关于适配的一些方式](fitview)

##分离TableView

为了减轻ViewController的代码量与工作量，实现的思路是把TableView的datasource和delegate分离成一个类去处理，通过注册的方式把UITableViewCell注册到TableView中。

	-(void)registerCellClassUsingCellIdentifier:(NSArray *)cellClassArray
	{
    	for (Class identifier in cellClassArray) {
        	[self registerClass:identifier forCellReuseIdentifier:NSStringFromClass(identifier)];
    }
	}

	-(void)registerForTableViewAtExtend:(id)tableViewExtend
	{
    	self.dataSource = tableViewExtend;
    	self.delegate = tableViewExtend;
	}

TableView分离的类：

	#import <Foundation/Foundation.h>

	@class POITable;
	@class POIModelManager;

	@interface POITableExtend : NSObject<UITableViewDataSource,UITableViewDelegate>

	@property(copy,nonatomic) NSString *identifier;
	@property(strong,nonatomic) POITable *tableView;
	@property(strong,nonatomic) POIModelManager *manager;

	- (id)initWithTableView:(POITable*)tableView cellIdentifier:(Class)cellIdentifier;

	@end

- [简单实现的Demo](https://github.com/icepy/withoutMe/tree/master/MVVMTableView)
- [更轻量的 View Controllers](http://objccn.io/issue-1-1/)
- [整洁的 Table View 代码](http://objccn.io/issue-1-2/)

##关于BaseViewController

一般在定义ViewController的时候都习惯于定义一个BaseViewController作为基类，这样做的好处是可以把公共属性提取出来，这样的代码结构会更清晰。

某些情况下，其他的类无法继承于BaseViewController，而又想拥有它的属性或方法。

- [关于iOS“多继承”的实现方式](http://www.jianshu.com/p/2e9382be43b)
- [Objective-C 的“多继承”](http://blog.csdn.net/yiyaaixuexi/article/details/8970734)

一些好用的BaseViewController源代码

在模拟器的调试模式下运行时，将自动模拟内存警告。

	- (void)viewDidAppear:(BOOL)animated
	{
  		[super viewDidAppear:animated];

    	#if TARGET_IPHONE_SIMULATOR
        	#ifdef DEBUG
            	// If we are running in the simulator and it's the DEBUG target
            	// then simulate a memory warning. Note that the DEBUG flag isn't
            	// defined by default. To define it add this Preprocessor Macro for
            	// the Debug target: DEBUG=1
            	[self simulateMemoryWarning];
        	#endif
    	#endif
	}

	- (void)simulateMemoryWarning
	{
    	#if TARGET_IPHONE_SIMULATOR
        	#ifdef DEBUG
            	CFNotificationCenterPostNotification(CFNotificationCenterGetDarwinNotifyCenter(), (CFStringRef)@"UISimulatedMemoryWarningNotification", NULL, NULL, true);
        	#endif
    	#endif
	}

设置导航控制器的标题

	- (void)setTitle
	{
		UILabel *titleLabel = [[UILabel alloc] initWithFrame:CGRectZero];
    	titleLabel.font = [UIFont boldSystemFontOfSize:18.0f];
    	titleLabel.backgroundColor = [UIColor clearColor];
    	titleLabel.textColor = [UIColor blackColor];
    	titleLabel.text = title;
    	[titleLabel sizeToFit];
    	self.navigationItem.titleView = titleLabel;
	}
	
设置返回按钮

	- (void)setLeftBackBtn
	{
    	UIButton *backBtn = [UIButton buttonWithType:UIButtonTypeCustom];
    	backBtn.frame = CGRectMake(0, 0, 20, 20);
    	[backBtn setImage:[UIImage imageNamed:@"global_back_white"] forState:UIControlStateNormal];
    	[backBtn addTarget:self action:@selector(backBarClick) forControlEvents:UIControlEventTouchUpInside];
    	self.navigationItem.leftBarButtonItem = [[UIBarButtonItem alloc]initWithCustomView:backBtn];
	}
	
	- (void)backBarClick
	{
    	if (self.navigationController.viewControllers.count > 1) {
        	[self.navigationController popViewControllerAnimated:YES];
    	}
	}

> 定义一个block typedef void (^Normalblock)(void)
	
设置自定义左边按钮与标题

	- (void)setLeftButtonTitle:(NSString *)title clickCallBack:(Normalblock)block
	{
    	UIButton *leftBtn = [UIButton buttonWithType:UIButtonTypeCustom];
    	leftBtn.frame = CGRectMake(0, 0, 50, 20);
    	leftBtn.titleLabel.font = [UIFont systemFontOfSize:16];
    	[leftBtn setTitleColor:[UIColor blackColor] forState:UIControlStateNormal];
    	[leftBtn setTitle:title forState:UIControlStateNormal];
    	[leftBtn addTarget:self action:@selector(leftBtnClick) forControlEvents:UIControlEventTouchUpInside];
    	UIBarButtonItem *left = [[UIBarButtonItem alloc]initWithCustomView:leftBtn];
    	self.navigationItem.leftBarButtonItem = left;
    	_LeftBlock = block;
	}
	
	- (void)leftBtnClick
	{
    	if (_LeftBlock == nil) {
        	[self.navigationController popViewControllerAnimated:YES];
        	return;
    	}
    	_LeftBlock();
	}

设置自定义右边按钮与标题

	- (void)setRightButtonTitle:(NSString *)title clickCallBack:(Normalblock)block
	{
    	UIButton *rightBtn = [UIButton buttonWithType:UIButtonTypeCustom];
    	rightBtn.frame = CGRectMake(0, 0, 50, 20);
    	rightBtn.titleLabel.font = [UIFont systemFontOfSize:16];
    	[rightBtn setTitleColor:[UIColor blackColor] forState:UIControlStateNormal];
    	[rightBtn setTitle:title forState:UIControlStateNormal];
    	[rightBtn addTarget:self action:@selector(rightBtnClick) forControlEvents:UIControlEventTouchUpInside];
    	UIBarButtonItem *right = [[UIBarButtonItem alloc]initWithCustomView:rightBtn];
    	self.navigationItem.rightBarButtonItem = right;
    	_RightBlock = block;
	}
	
	- (void)rightBtnClick{
    	_RightBlock();
	}

##Mantle使用

[Mantle](https://github.com/Mantle/Mantle)可以快速的将JSON转化成Model类，节省了很多重复编码的时间。

- [Mantle 初步使用](http://ourui.github.io/blog/2014/01/22/mantle-use/)
- [工具篇：Mantle](http://southpeak.github.io/blog/2015/01/11/gong-ju-pian-:mantle/)
- [使用Mantle处理Model层对象](http://blog.codingcoder.com/use-mantle-to-model/)

三步走即可，第一步继承MTLModel并且实现MTLJSONSerializing协议

	@interface JSONDataModel : MTLModel<MTLJSONSerializing>

	@property (nonatomic, strong) NSDate *date;
	
	@end
	
第二步，在.m文件中实现MTLJSONSerializing协议的+ (NSDictionary *)JSONKeyPathsByPropertyKey方法

	@implementation JSONDataModel
	
	+ (NSDictionary *)JSONKeyPathsByPropertyKey 
	{
		return @{
			@"data":@"trueData" //JSON与Model一个一对应
		}
	}
	@end
	
第三步，如果有特殊需求，比如类型转换，Mantle也提供了很多便捷的方法（可选实现）

	+ (NSValueTransformer *)dateJSONTransformer {
    	return [MTLValueTransformer reversibleTransformerWithForwardBlock:^(NSNumber *dateNum) {
        	return [NSDate dateWithTimeIntervalSince1970:dateNum.floatValue];
    	} reverseBlock:^(NSDate *date) {
        	return [NSString stringWithFormat:@"%f",[date timeIntervalSince1970]];
    	}];
	}
	
##Debug UI Reveal

Reveal 是一个界面调试工具，使用Reveal，我们可以在iOS开发时动态地查看和修改应用程序的界面。它类似Chrome的“审查元素”功能，我们不但可以在运行时看到iOS程序的界面层级关系，还可以实时地修改程序界面，不用重新运行程序就可以看到修改之后的效果。

请阅读

- [Reveal：分析iOS UI的利器](http://security.ios-wiki.com/issue-3-4/)
- [Reveal查看任意app的高级技巧](http://c.blog.sina.com.cn/profile.php?blogid=cb8a22ea89000gtw)

使用pod安装一下它的SDK，就可以连接了。

	pod 'Reveal-iOS-SDK', '~> 1.5.1'
	
##Category添加属性

有时候写了一个分类，发现属性不够用，那怎么办？这时候可以使用Runtime特性了。

	#import <objc/runtime.h>
	
建立一个Category头文件

	@interface ClassTest (CategoryTest)
	
	@property (nonatomic, strong) NSString *testString;
	
	@end
	
在实现文件中添加testString的getter和setter方法
	
	
	static const void *IndieBandNameKey = &IndieBandNameKey;
	@implementation ClassTest (CategoryTest) 
	
	@dynamic testString;
	
	-(void)setTestString:(NSString *)str  
	{  
    	objc_setAssociatedObject(self, IndieBandNameKey, str, OBJC_ASSOCIATION_COPY);  
	}	  

	-(NSString *)testString  
	{  
    	return objc_getAssociatedObject(self, IndieBandNameKey);  
	}
	
	@end
	
	
`objc_setAssociatedObject`方法有四个参数：源对象，关联时的用来标记是哪一个属性的key（因为你可能要添加很多属性），关联的对象和一个关联策略。

关联策略枚举

	enum {
    	OBJC_ASSOCIATION_ASSIGN = 0, //关联对象的属性是弱引用 

    	OBJC_ASSOCIATION_RETAIN_NONATOMIC = 1, //关联对象的属性是强引用并且关联对象不使用原子性

    	OBJC_ASSOCIATION_COPY_NONATOMIC = 3, //关联对象的属性是copy并且关联对象不使用原子性

    	OBJC_ASSOCIATION_RETAIN = 01401, //关联对象的属性是copy并且关联对象使用原子性

    	OBJC_ASSOCIATION_COPY = 01403 //关联对象的属性是copy并且关联对象使用原子性
	};
	
##判断UIScrollView是向上滚动还是向下滚动

25 可以是任意数字，可根据自己的需要来设定。

	int _lastPosition;    //A variable define in headfile  

	- (void)scrollViewDidScroll:(UIScrollView *)scrollView
	{  
    	int currentPostion = scrollView.contentOffset.y;  
    	if (currentPostion - _lastPosition > 25) {  
        	_lastPosition = currentPostion;  
        	NSLog(@"ScrollUp now");  
    	}  else if (_lastPosition - currentPostion > 25){  
        	_lastPosition = currentPostion;  
        	NSLog(@"ScrollDown now");  
    	}  
	}

到达顶部或底部时不会反弹

	- (void)scrollViewDidScroll:(UIScrollView *)scrollView
	{
    	int currentPostion = scrollView.contentOffset.y;

    	if (currentPostion - _lastPosition > 20  && currentPostion > 0) {        //这个地方加上 currentPostion > 0 即可）
        	_lastPosition = currentPostion;

        	NSLog(@"ScrollUp now");
    	}else if ((_lastPosition - currentPostion > 20) && (currentPostion  <= scrollView.contentSize.height-scrollView.bounds.size.height-20) ){
       		_lastPosition = currentPostion;
	
        	NSLog(@"ScrollDown now");
    	}
	}
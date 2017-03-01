NSLog\(@"启程～"\);

###### 1.\[NSNotificationCenter defaultCenter\]postNotificationName:&lt;\#\(nonnull NSNotificationName\)\#&gt; object:&lt;\#\(nullable id\)\#&gt;

###### object 也可以传东西

###### 

###### 2.infoPlist不能随便乱存放位置

###### 3.在工程里丢文件夹的时候选择group

###### 4.&lt;\# \#&gt;代码块

###### 5.man ascii

###### 6.如果注册了cell，那么在dequ后，cell就有了，就永远进入不了 cell =nil;

###### 

###### 7.@property\(nonatomic,copy\)subViewTouchCallBackcallBack;

###### 8.如果是return\[\[NSBundlemainBundle\]loadNibNamed:NSStringFromClass\(self\)owner:niloptions:nil\].firstObject;这种形式去创建，则block就只能在其他对象方法中去赋值；否则，在创建后，block始终为nil，

###### 9.OS\_ACTIVITY\_MODE  disable xcode8LOG

10,从一个vc pop到另一个vc后，要拿到  
self.tabBarController;

要到- \(void\)viewWillAppear:\(BOOL\)animated

而在- \(void\)viewDidLoad是拿不到的，

\(void\)viewWillAppear:\(BOOL\)animated晚于\(void\)viewDidLoad

11.imgv上加子视图，imgv只有设置了  
userInteractionEnabled=yes后，子视图才能接受手势

12.设置屏幕旋转方向使用kvo，

NSNumber\*orientation = \[NSNumbernumberWithInt:UIInterfaceOrientationLandscapeRight\];

 \[\[UIDevicecurrentDevice\]setValue:

 orientationforKey:@"orientation"\];

13.使用 colorWithPatternImage 的 iOS 中拉伸图像


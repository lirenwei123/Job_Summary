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

###### 7.@property\(nonatomic,copy\)subViewTouchCallBack  callBack;

###### 8.如果是return\[\[NSBundle mainBundle\]loadNibNamed:NSStringFromClass\(self\) owner:nil options:nil\].firstObject;这种形式去创建，则block就只能在其他对象方法中去赋值；否则，在创建后，block始终为nil，

###### 9.OS\_ACTIVITY\_MODE  disable xcode8LOG  Xcode8 屏蔽日志

10,从一个vc pop到另一个vc后，要拿到  
self.tabBarController;

要到- \(void\)viewWillAppear:\(BOOL\)animated

而在- \(void\)viewDidLoad是拿不到的，

\(void\)viewWillAppear:\(BOOL\)animated晚于\(void\)viewDidLoad

11.imgv上加子视图，imgv只有设置了  
userInteractionEnabled=yes后，子视图才能接受手势

12.设置屏幕旋转方向使用kvo，

NSNumber\*orientation = \[NSNumber numberWithInt:UIInterfaceOrientationLandscapeRight\];

\[\[UIDevicecurrentDevice\]setValue:

orientationforKey:@"orientation"\];

13.使用 colorWithPatternImage 的 iOS 中拉伸图像

14

int\*size ;

\*size =0;

char buffer\[1024\];

bzero\(buffer,1024\);

//char\*类型可以在函数里传值，但是int类型为什么不能传？

//因为char\*传地址int传值把int变换成int \*就可以传值了

\[selfReturnRequestData:MarketTypeSortType:SortTypeStockType:StockTypeOrderFlag:0Number:reqNumbuffer:buffersize:size\];

15.

swich里不能直接定义类型，但是可以使用函数代替

16.

![](/assets/import.png)

在创建appID的时候，用精确id才能勾选下方更多服务，如果选模糊id有些服务不能勾选

17.如果要设置TABLEVIEW的顶部菜单在上拉时不滚动，可以设置sectionHeader;

1. addEntriesFromDictionary 合并字典里的所有信息

18.导航控制器里添加控制器视图，容易导致顶部自动添加一个类似导航栏的视图

19.XIB控制器，必须要等待XIB控制器出来后才能加载出里面的XIB控件



20.C++:

    cell向上取整floor向下取整


ArchGeo建筑几何(第 6 期): 参数曲面

> 开源(GitHub: [WWmore/ArchGeo](https://github.com/wwmore/ArchGeo)),同步微信公众号(WWmore).
>
> 记录以建筑几何AG(Architectural Geometry)为主的相关信息, 和值得分享的内容.
> 本杂志(月更)每月月底更新.

Images from the internet. If there is any copyright infringement, please notify me at once and I'll delete it.

------



## Architecture建筑

- #### [太原植物园](https://www.dezeen.com/2021/06/02/taiyuan-botanical-garden-delugan-meissl-china/)

  太原植物园去年完成了建设对外开放，其主要部分的是由奥地利建筑公司DMAA2016年开始设计完成的。植物园中的三个醒目的单独温室园分别构成凸曲面，平面玻璃镶嵌在两族钢梁而成的网格中，网格是曲面的共轭网（conjugate net）。因为网格存在某些区域夹角不是90度，故网格在该区域不是曲面的主法曲率网。内部双弯曲的木质框架形成可展曲面，如果两族可展曲面是正交的关系，则形成主法曲率网。如果可展曲面是垂直于外表面的，则可展曲面和外表面的交线是凸曲面的主法曲率线。

  ![taiyuan](/asset/2021-6/taiyuan.png)

  DMAA主要作品包括[维也纳游客中心](https://www.dmaa.at/work/tourist-info-vienna)和斯图加特保时捷博物馆。

  ![dmaa](/asset/2021-6/dmaa.png)

  

- #### [Sculpture by sea 海边雕塑](https://sculpturebythesea.com/gallery/)

  封面是由[Office Feuerman](https://archello.com/de/project/succah-by-the-sea) 为澳大利亚Bondi2019海边展设计的A-net shell(渐近网壳)结构.整体呈对称结构,能明显看出由四个主体部分拼接而成. 两族木质薄板拼接嵌套在一起,每条薄板都发生了不同程度的扭转(可展曲面挠率非零),边缘线沿着外表面的渐近线,构成了整体渐近线网(A-net).所有节点都是4价的,出现奇异点的地方是5价的,构造上在这些位置没有连续. 具体理论应该参考了建在TU Munich的['Inside\Out Gridshell'](https://eikeschling.com/2017/11/06/insideout/).

  ![shell](/asset/2021-6/shell1.png)

  'Sculpture by sea' 今年在Bondi海滩展出时间是10月21日-11月7日,号称世界上最大的公共雕塑展. 由来自世界各地的100多个作品,分布在2km长的海岸线上.

  ![sculpture](/asset/2021-6/sculpture.png)

  

- #### [螺旋面景观亭](https://mooool.com/da-hua-zi-yue-mansion-by-gm-landscape-design.html)

  位于番禺老城区新建的一个商业项目景观亭. 由主法曲率网构成的螺旋面网壳结构.

  ![spiral](/asset/2021-6/spiral.png)

------



## Math数学

- #### [参数曲面和体](http://www.3d-meier.de/tut3/Seite0.html)

  德语网站，整理了20多年的经典参数曲面，分类清晰，页面简单，直接给出参数表达式，定义域，图形. 有python源文件和Cinema源文件可以下载.

  部分结果被[<Encyclopedia of Analytical Surfaces>](https://www.springer.com/gp/book/9783319117720)书籍引用，它也实现了很多书中的结果.

  ![para](/asset/2021-6/parametrische.png)

  

- #### [极小曲面](https://minimalsurfaces.blog/home/repository/symmetrizations/)

  整个界面全是关于极小曲面, 有不同分类. 界面清新流畅, 有PovRay , Mathematica 文件下载.

  ![minimal](/asset/2021-6/minimal.png)

  

- #### [多面体纸模型](https://www.polyhedra.net/zh/pictures.php?type=a)

  集合和实现了多种多面体纸质模型.

  ![polyhedra](/asset/2021-6/polyhedra.png)

  

- #### [Perspectiva Corporum Regularium](https://digital.slub-dresden.de/werkansicht/dlf/12830/5)

  规则透视体木版画，介绍多种奇异的多面体，1568年出版. 作者Wenzel Jamnitzer生于维也纳，是神圣罗马帝国的宫廷金匠. 高清扫描书籍可以免费下载.

  ![regular](/asset/2021-6/regularium.png)

  

- #### [Mathematical Art Galleries](http://gallery.bridgesmathart.org/exhibitions/2021-Bridges-Conference)

  整合了几个数学与艺术结合的会议作品, 包括'JAMM2021', 'Bridges2021'等.

  ![mag](/asset/2021-6/mag.png)

  

- #### [Mathematical Research Institute of Oberwolfach](https://opc.mfo.de/)

  上沃尔法赫数学研究所， 位于德国上沃尔法，世界各地数学家组织的研讨会, 每周举办数学研讨会. 很多大数学家都会在广场的Boy's surface雕塑前留影并作为个人主页头像,甚至出版物头像. 该雕像由奔驰1991年捐赠, Boy's surface是由Mobius带变化而来, 具有极小化Willmore energy.

  ![oberwolfach](/asset/2021-6/oberwolfach.png)

  

- #### [MacTutor](https://mathshistory.st-andrews.ac.uk/)

  罗列了历史上有名的数学家照片和简介. 有按照国家, 地图, 年代, 字母表等方式分类.  中国数学家信息非常少. 也单独介绍曲线信息.

  ![mactutor](/asset/2021-6/mactutor.png)

  

- #### [MIT 微分几何在线书籍](http://web.mit.edu/hyperbook/Patrikalakis-Maekawa-Cho/)

------



## Software工具

- #### [Eigen线性代数函数包](https://eigen.tuxfamily.org/index.php?title=Main_Page)

   C++语言编写的线性代数包.

  

- #### [Libigl几何处理函数包](https://libigl.github.io/tutorial/)

  C++语言编写,也有部分Python. 当前最热门的几何处理函数包. 基于Eigen.

   

- #### [Libhedra多边形网函数包](https://avaxman.github.io/libhedra/)

   C++语言编写, 从Libigl只针对三角网的局限扩展到处理多边形网格. 

   

- #### [Lionfish](https://www.food4rhino.com/en/app/lion-fish#lg=1&slide=4)

  转化Nicholas Sharp的[Geometry Central](http://geometry-central.net/)函数包为Grasshopper插件, 实现网格面上的向量域构造, 提取geodesic(测地线), 计算曲率等几何量.

------



## Reading阅读

1. #### <笑翻中国简史>--马伯庸

    > 1687年,耶稣会士柏应理撰写了<中国哲学家孔子>一书, 其中共计用了十三页对伏羲八卦图做了介绍. 坊间传闻,德国哲学家,数学家莱布尼茨买来一本一翻,我的天,这不是我正在研究的二进制嘛! 二进制的发明从此就归功于莱布尼茨了,而最早制定<周易>系统的中国原始数学家则淹没在了历史的浩瀚海洋中. 没办法,他那一套太形而上了,几千年来没几个人能搞得懂.

    > "五德始终说"可是个大大的好东西,因为这套理论包容性特别高,谁都可以按照自己的需求去修改. 按他的本意,只有拥有正经德性的势力才能推翻前朝创立新政权,但是此后大家全都反着用,先捏掉前朝,然后再给自己配一个合适的"德",以证明自己是受命于天的合法政权.这就好像是先上车后补票,先生孩子再领结婚证,先打下伊拉克再找大规模杀伤性武器一样, 古今道理全都相通.

2. #### <烧火工>--刘慈欣

   > 他们沉默地看着灿烂的星河，烧火工突然指向一个方向：“看！”. 萨沙看到了一道弧光划过星空，那是一颗流星。“那就是一般人的死法，他们的星星化成流星，大部分在落地前就烧光了，有些剩下的部分落到地上，也不过是一块平淡无奇的石头.

3. #### <微纪元>--刘慈欣

   > 那时人们常谈起一个笑话，说的是一个人同上帝的对话：
   >
   > "上帝啊，一万年对你是多么短啊！"
   >
   > 上帝说：就一秒钟.
   >
   > "上帝啊，一亿元对你是多么少啊！"
   >
   > 上帝说：就一分钱.
   >
   > "上帝啊，给我一分钱吧！"
   >
   > 上帝说：请等一秒钟.

   > 您的眼睛像黑色的大海...是博物馆...是放大了上亿倍的忧郁！

4. #### <白痴>--陀思妥耶夫斯基

    > 一个有心而没有头脑的傻瓜，跟一个有头脑而没有心的傻瓜一样，都是可怜的傻瓜.

------



## Miscellaneous其他

1. #### [Felix Semper折纸雕像](http://felixsemper.com/index.html)

   ![ps](/asset/2021-6/paper_sculpture.png)
   
2. #### [德累斯顿数字馆藏](https://digital.slub-dresden.de/kollektionen)

   免费扫描书籍下载.


------




ArchGeo建筑几何(第 8 期): SIGGRAPH会议

> 开源(GitHub: [WWmore/ArchGeo](https://github.com/wwmore/ArchGeo)),同步微信公众号(WWmore).
>
> 记录以建筑几何AG(Architectural Geometry)为主的相关信息, 和值得分享的内容.
> 本杂志(月更)每月月底更新.

Images from the internet. If there is any copyright infringement, please notify me at once and I'll delete it.

------



## Architecture建筑

- #### [第十届中国花卉博览会竹藤馆](https://www.archdaily.cn/cn/966527/di-shi-jie-zhong-guo-hua-hui-bo-lan-hui-zhu-teng-guan-hua-jian-ji-tuan-shang-hai-jian-zhu-ke-chuang-zhong-xin-chuang-zuo-yan-jiu-zhong-xin)

  位于上海,由上海建筑科创中心设计. 由许多直木条构成的具有负高斯曲率的外表面, 存在两族相交网, 每族由几根直木条组装而成. 两族相交的节点位置做了特殊连接处理. 靠近中间位置, 交线近似直线,即两族支撑结构形成无挠结构, 越靠近边线位置, 两族结构近乎相切.

  ![竹藤](/asset/2021-8/zhuteng.png)

  

- #### [Casamia 社区大跨度拱形竹梁](https://www.archdaily.cn/cn/965993/da-kua-du-gong-xing-zhu-liang-casamia-she-qu-zhi-jia-vtn-architects?ad_medium=office-landing&ad_name=featured-image)

  位于越南, 由武重义建筑所设计的又一竹梁结构. 竹梁是武重义建筑的标志. 如2018年建在越南的Vinata亭子和在意大利的竹钟乳石亭. 所用竹子有两种: 直的和弯的. 为了增加耐久性和防虫作用, 会对左右竹子做特殊的处理, 先水泡再烟熏,再上釉.

  ![casamia](/asset/2021-8/casamia.png)

  

- #### [流线步行桥](https://www.archdaily.cn/cn/966414/liu-xian-xing-qiao-volkan-alkanoglu)

  位于美国, 由Volkan Alkanoglu设计.内表面由可展平木条拼接组成双弯曲形状, 提供流动, 多变的细腻感. 结构本身还在桥中间内部形成长椅.

  ![bridge](/asset/2021-8/bridge.png)

  

- #### [LivMatS 研究展亭](https://www.archdaily.cn/cn/966296/livmats-yan-jiu-zhan-ting-si-tu-jia-te-da-xue-icd-itke)

  位于德国弗莱堡大学校园内, 由斯图加特大学ICD/ITKE研究组设计. 这也是他们使用机械臂和纤维材料制造的又一个实用项目. 纤维在表面的走向并非沿着主法曲率方向, 是近似关于其对称的.

  ![livmats](/asset/2021-8/livmats.png)

  

- #### [褶皱纸张外墙](https://www.archdaily.cn/cn/925255/gao-zhong-wai-qiang-gai-zao-zhe-zhou-de-zhang-bai-zhi-wiesflecker-architecture)

  位于奥地利,是一所高中新改造的外墙. 由WIESFLECKER ARCHITECTURE建筑所设计. 一味追求平整的反面也可以成为一种设计.

  ![crumple](/asset/2021-8/crumple.png)



------



## Math数学

- #### [SIGGRAPH 2021 会议](https://s2021.siggraph.org/)

  8月9-13日举办, 仍然完全线上会议. 包含了很多大厂的最新技术,成果交流, 技术报告, 艺术报告, 展报等. 今年技术文章投稿444篇,接收149篇. 新增艺术文章14篇(投稿93篇),并发表在ACM的PACMCGIT特别期刊. 特别今年展报也放在了相关小组报告里一起参加. 今年邀请了图灵奖获得者Ed Catmull 和 Pat Hanrahan的会谈, 3Blue1Brown的直播报告.

  ![siggraph](/asset/2021-8/siggraph.png)

  

- #### [3Blue1Brown](https://github.com/3b1b/manim)

  斯坦福研究生Grant Sanderson创办的Youtube频道, i.e. 用python编写并开源的Manim软件讲解高等数学等知识. 这次SIGGRAPH会议上,讲解了quaternions(四元数).

  ![3blue1brown](/asset/2021-8/3blue1brown.png)

  

- #### [Polytopia 手工多面体模型](https://www.polytopia.eu/en/glossar)

  收集了很多手工制作的不同凸多面体，包括规则的和不规则的，对称的和不对称的. 使用计算方法，模拟3D多面体剪开，平铺形成多边网，再粘合，形成多面体的过程.

  ![polytopia](/asset/2021-8/polytopia.png)

  

- #### [Tegula 几何贴图库](https://www.wsi.uni-tuebingen.de/lehrstuehle/algorithms-in-bioinformatics/software/tegula)

  由图宾根大学研发，实现二维周期平铺的开源程序，有近24亿个贴图(tiling). 有三个数据集文件，包括欧式平面，球面，双曲几何贴图. 软件界面展示所有可能图形，可以设置数量和大小参数，调节基本域改变设计结果，可以交互拖拽，可得到对偶图形，最大对称图形，可以保存打印.

  ![tegula](/asset/2021-8/tegula.png)



------



## Software工具

- #### [Polyscope可视化窗口](https://github.com/nmwsharp/intrinsic-triangulations-tutorial)

  由Keenan Crane课题组Nicholas Sharp博士制作的Python语言可视化窗口. 可以处理曲面网格，体网格，曲线，点云等数据结构并可视化.

  ![polyscope](/asset/2021-8/polyscope.png)

  

- #### [Slager在线Latex编辑器](https://www.slager.cn/home)

  功能同Overleaf, 由中奥智能工业研究院开发, 有不少期刊, 论文,报告,简历等模板使用.

  ![slager](/asset/2021-8/slager.png)

  

------



## Reading阅读

1. #### <三体>

> 无限长的曲线就是宇宙的抽象，一头连着无限的过去，另一头连着无限的未来，中间只有无规律无生命的随机起伏，一个个高低错落的波峰就像一粒粒大小不等的沙子，整条曲线就像是所有沙粒排成行形成的一维沙漠，荒凉寂寥，长得更令人无法忍受. 你可以沿着它向前向后走无限远，但永远找不到归宿.

------




------




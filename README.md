# 文小刚
## 0.物理心得笔记

  物理学中的所有概念，都是通过实验设计的。

  不是给一个数学定义，而是设计一个物理实验，包括思想实验。

  你想要搞清楚一个物理概念，不要想数学定义，不要想数学公式，是想你怎么设计一个实验，这个物理实验是怎样把物理概念反映出来的。

  设计实验，反映概念，从而定义物理概念。

  物理的所有概念都是通过实验来定义的。
  
## 1.对称保护平凡序-笔记
  
  不同拓扑空间中的基态简并度不同(宏观上).
  
  长程量子纠缠(微观上).
  
  拓扑序，新结构。
  
  直积态，短程相互作用量子纠缠也是一种直积态，是一种平凡态。
  
  不是短程纠缠的东西，就是长程纠缠。
  
  能通过幺正变换变过去的都是短程纠缠，不能的就是长程纠缠，想变只能相变。
  
  自旋向上 1 为背景，自旋向下 0 为弦。
  
  
## 2.范畴论
  ### 2.0.0范畴是一个简化的数学世界
  
  普适的，固定范围的数学对象。
  
  比如，所有的群；所有的阿贝尔群；所有的环；所有的拓扑空间......
  
  一堆特定的对象，比如，所有的正整数。
  
  以及对象与对象之间的特殊关系，对象与对象的关系。
  
  范畴描述的是一种单向关系。比如　A　和　B　是好朋友就不是单向关系，我爱你是一种单向关系，因为你不一定爱我。
  
  一种映射就是一种关系，可以有多种映射，也就有多种关系。
  
  #### 2.0.1特例
        1. 所有的正整数.   整除 |    n|m  m|k  -->  n|k
        2. 偏序集.  <=   n <= m  m <= k  -->  n <= k
        3. 所有集合构成的世界.  映射(多种) = 关系(多种)  f:A-->B ; g:B-->C ;  复合映射 g。f:A-->C
        4. 所有 R 上的开集. 连续函数
        5. 所有的拓扑空间. 连续映射
        6. 所有的群(群与群之间的同态)
        7. 所有的实线性空间(实线性空间之间的线性映射，或称线性变换)

  ### 2.1.0范畴的定义
  
  #### 范畴由两个要素和一个运算构成。
  
  0.1 要素  对象(a,b,c;A,B,C)
  
  0.2 要素  态射集合 : 任意两个对象 a,b. 唯一集合 hom(a,b), 从 a 到 b 的一个态射.
  
         态射 f:a-->b,  a 是 f 的定义域为 dom f ; b 是 f 的值域为 cod f .
         恒等态射 I_a 属于 hom(a,a) . a = b 时， 集合 hom(a,a) 非空，有唯一 I_a .
         
  0.3 运算  复合运算  hom(a,b) 直乘 hom(b,c) --> hom(a,c)
  
  #### 公理：
  
  0.1 不相交性公理：除非 a = a', b = b',否则 hom(a,b) 与 hom(a',b') 永不相交.
  
  0.2 结合公理：a --f--> b --g--> c --h--> d     h。(g。f) = (h。g)。f
  
  0.3 单位公理：对于任何态射 f = a-->b    f。I_a = f = I_b。f 

        范畴只关注对象以及对象与对象间的关系.
        一个范畴中的所有对象不一定构成一个集合，可能是一个大的东西.
        集合范畴的对象是所有集合.
        如果所有集合构成一个集合，就会导致罗素悖论.
        集合范畴是比所有集合都大的一个东西.
        如果一个范畴中的所有对象能构成一个集合，那称其为小范畴.
        
        (所有的对象构成一个抽象，一个抽象可以产生很多对象)
        重要的不是对象本身，而是对象与对象之间的关系.
        这些关系就给出了各种各样的公式(数学或物理的).
        这些关系是抽象的，而公式是具体的，是物理公式，形式是数学.
        范畴关系只给出对象与对象之间存在抽象关系.
        具体关系由物理概念给出.
        具体关系的形式由数学给出.
        
        由抽象原子到抽象弦.
        
        原子论，原子作为唯一抽象，以数不同构造不同对象，不同对象的关系产生性质.
        
        弦论，弦作为唯一抽象，弦的不同振动生成不同粒子，产生无穷多对象.
        抽象弦产生对象粒子，由抽象产生对象，对象再产生关系，若此，粒子这个对象的性质不是来自振动，而是来自关系.
        
        一堆原子构成的物体，你可以从中抓一把原子出来.(局域幺正变换连接，短程纠缠)
        一堆弦丝织成的物体，形象比喻是'毛衣''面条'，你从局部抓取一戳弦，你会拉出多根很长的弦丝.
        除非你从局部抓取时，把局部的弦丝剪断，被你剪断了一部分弦丝的'毛衣'，它的品相也就变化了.
        
        你不能把异类量自然地写在等式的两边.
        你必须把异类量放在等式的同一边，然后定义它们的关系.
        利用定义的新类量，你才能把异类量写在等式两边.

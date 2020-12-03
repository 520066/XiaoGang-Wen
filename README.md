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
  
  ### 2.0.1特例
      1. 所有的正整数.   整除 |    n|m  m|k  -->  n|k
      2. 偏序集.  <=   n <= m  m <= k  -->  n <= k
      3. 所有集合构成的世界.  映射(多种) = 关系(多种)  f:A-->B ; g:B-->C ;  复合映射 g。f:A-->C
      4. 所有 R 上的开集. 连续函数
      5. 所有的拓扑空间. 连续映射
      6. 所有的群(群与群之间的同态)
      7. 所有的实线性空间(实线性空间之间的线性映射，或称线性变换)

  ### 2.1.0范畴的定义
  
  范畴由两个要素和一个运算构成。
  
  0.1 要素  对象(a,b,c;A,B,C)
  0.2 要素  态射集合 : 任意两个对象 a,b. 唯一集合 hom(a,b), 从 a 到 b 的一个态射.
         态射 f:a-->b,  a 是 f 的定义域，为 dom f ; b 是 f 的值域，为 cod f .
         恒等态射 I_a 属于 hom(a,a) . a = b 时， 集合 hom(a,a) 非空，有唯一 I_a .
  0.3 运算  复合运算  hom(a,b) 直乘 hom(b,c) --> hom(a,c)
  
  公理：
  
  0.1 不相交性：除非 a = a', b = b',否则 hom(a,b) 与 hom(a',b') 永不相交.
  0.2 结合公理：
  0.3 单位公理：

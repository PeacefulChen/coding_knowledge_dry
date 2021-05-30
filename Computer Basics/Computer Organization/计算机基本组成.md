
## 概述

### 计算机基本组成

1. 冯诺伊曼计算机特点
   <br/>为什么要了解冯诺伊曼计算机？以说,冯·诺依曼体系架构确立了我们现在每天使用的计算机硬件的基础架构。因此,学习计算机组成原理,其实就是学习冯·诺依曼体系结构。</br>
   * 计算机五大部分组成
   * **指令**和**数据**同等低温存于寄存器
   * 指令和数据都以二进制形式
   * 指令 = 操作码 + 地址码
   * **存储程序**，具有这个特点都叫冯诺伊曼计算机
   * 以运算器为中心
   
2. 冯诺伊曼计算机硬件框架图

    黑色线表示数据通路、输入输出都需要经过运算器，核心啊

    * 运算器：算数运算、逻辑运算
    * 存储器：存放程序和数据
    * 控制器：指挥功能

<img src="https://github.com/PeacefulChen/coding_knowledge_dry/blob/main/image/%E5%86%AF%E8%AF%BA%E4%BC%8A%E6%9B%BC%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%A1%AC%E4%BB%B6%E5%9B%BE.png" width = "500" height = "300" alt="冯诺伊曼计算机框架" align=center />


  以上结构有两个问题：
    * 运算器为中心，导致运算器成为计算机系统的瓶颈
    * 图比较乱，不具有层次的划分

3. 对以上的作出改进的硬件图
    * 针对中心做一个改进，变成以存储器为中心，但是这样也是很乱

<img src="https://github.com/PeacefulChen/coding_knowledge_dry/blob/main/image/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BB%93%E6%9E%84%E6%94%B9%E8%BF%9B%E7%89%88V1.png" width = "500" height = "300" alt="改进之后计算机框架" align=center />

4. 现代计算机硬件
<img src="" height = "300" alt="现代计算机硬件架构分层" align=center />

+ ACC : 累加器
 
      

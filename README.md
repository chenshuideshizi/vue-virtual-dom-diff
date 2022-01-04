# Vitrual Dom & Diff

**相关知识点:**

- 虚拟DOM(Virtual DOM):
    - 什么是虚拟dom
    - 为什么要使用虚拟dom
    - 虚拟DOM库
- DIFF算法:
    - snabbDom源码
        - init函数
        - h函数
        - patch函数
        - patchVnode函数
        - updateChildren函数


### 虚拟DOM(Virtual DOM)

**什么是虚拟DOM**

虚拟DOM就是一个用来描述真实DOM的javaScript对象

**为什么要使用虚拟DOM**

- 跨平台使用
- 性能下限
    - 真实DOM的属性很多，创建DOM节点开销很大
    - 复杂视图情况下提升渲染性能(操作dom性能消耗大,减少操作dom的范围可以提升性能)

### Diff算法

**patch函数**




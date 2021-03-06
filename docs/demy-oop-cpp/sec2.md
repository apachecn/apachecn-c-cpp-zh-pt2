# 第二部分：在 C++ 中实现面向对象的概念

本节的目标是了解如何使用 c 语言功能和成熟的编程技术来实现 OO 设计。C 可以用于许多编码范例; 程序员必须努力在 C 中以 OO 方式编程 (这不是自动的)。这是本书中最大的部分，因为了解如何将语言特征和实现技术映射到 OO 概念至关重要。

本节的第一章非常详细地探讨了类，首先描述了封装和信息隐藏的 OO 概念。深入审查了成员函数、this 指针、详细访问区域、详细构造函数 (包括复制构造函数) 、析构函数、成员函数的限定符 (const、static、inline) 和数据成员的限定符 (const、static) 等语言功能。

本节的下一章用泛化和专业化的 OO 概念来处理单一继承基础，通过成员初始化列表详细介绍继承的构造函数，构造和破坏的顺序，并了解继承的访问区域。本章通过探索公共与受保护和私有基类以及这些语言功能如何改变继承的 OO 含义来深入研究。

下一章深入研究了多态性的 OO 概念，以理解该概念及其在 C 中使用虚拟函数的实现。研究了方法与操作的动态绑定。探索虚拟函数表来解释运行时绑定。下一章详细解释抽象类，将 OO 概念与其使用纯虚函数的实现进行配对。介绍了接口的 OO 概念 (未在 C 中明确显示)，并回顾了实现方法。继承层次结构的上下转换完成本章。

下一章将探讨多重继承以及使用此功能可能引起的潜在问题。虚拟基类以及鉴别器的 OO 概念进行了详细说明，以帮助确定多个继承是否是给定场景的最佳设计，或者是否存在另一个。

本节的最后一章介绍了关联、聚合和组合的概念，以及如何使用指针或引用、指针集或嵌入对象来实现这些常见的对象关系。

本节包括以下章节:

*   [*第五章*](05.html#_idTextAnchor199)*，详细探究类*
*   [*第六章*](06.html#_idTextAnchor262)*，实现单一继承的层次结构*
*   [*第七章*](07.html#_idTextAnchor298)*，通过多态性利用动态结合*
*   [*第八章*](08.html#_idTextAnchor335)*，掌握抽象类*
*   [*第九章*](09.html#_idTextAnchor361)*，探索多重继承*
*   [*第十章*](10.html#_idTextAnchor386)*，实现关联、聚合和组合*
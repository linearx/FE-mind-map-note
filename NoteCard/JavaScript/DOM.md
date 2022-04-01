## DOM

DOM，Document Object Model文档对象模型，为HTML和XML文档的编程接口，表示多层节点构成的文档。

- 通过DOM可以添加、删除、修改页面的各个部分
- 跨平台、语言无关的表示和操作页面的办法



### DOM Level1

提供基本文档解构和查询的接口。

#### 节点层级

任何HTML和XML文档均可以用DOM表示一个由节点构成的层级结构。

- 节点分为很多种类性能，每种类型对应文档的不同信息和标记，也有不同的特性、数据和方法。

DOM Level1描述了Node接口，Node接口为所有DOM节点类型都必须实现的，在JavaScript中被实现为了Node类型。

##### Node类型

DOM中总共有12种节点类型，浏览器并不支持所有节点类型。开发者常用的为元素节点和文本节点。

- Node.ELEMENT_NODE (1)
- Node.ATTRIBUTE_NODE(2)
- Node.TEXT_NODE (3)
- Node.CDATA_SECTION_NODE (4)
- Node,ENTITY_REFERENCE_NODE

##### 节点关系
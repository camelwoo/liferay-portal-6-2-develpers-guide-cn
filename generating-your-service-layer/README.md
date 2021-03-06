#生成服务层（Service Layer）代码

_服务（service）_有很多含义，但通常是指“一个有价值的活动”。每个人都会有些体会。无论是朋友或陌生人友善的行为还是你购买的服务，所有这些都是你有需求，而有人提供服务来满足需求。

数据驱动（Data-driven）的应用自然需要访问某些服务来保存或获取数据。在设计优秀的应用中，应用请求数据，服务来获取数据。然后应用将数据呈现给用户，用户阅读或编辑数据。如果数据修改了，应用将数据传回服务，服务保存修改后的数据。应用不用关心服务是怎么做的，它相信服务能够正确操作数据。应用只需要做它应该做的，这使得应用更健壮。

这就是“解耦（loose coupling）”，设计优秀应用的标志。如果你的服务层是独立的，就可以在不修改应用的情况下将它替换为更好地实现。

更好的实现已经有了，它就是服务生成器（Service Builder）。利用 _Hibernate_ 的对象-关系映射（Object-Relational Mapping，O-R Mapping，ORM）引擎和功能强大的代码生成器，服务生成器（Service Builder，后面都会直接使用英文）可以让你事办功倍。但这并不是普通的服务层：Servic Builder 还可以生成多种协议的远程服务，如 JSON 和 SOAP（*译注：估计是指 SOAP 和 REST 吧*）。如果你想玩点悬的，它还提供了直接写 SQL 的方法。

感兴趣吗？希望是的。后面的章节包括以下内容，先来仔细研究一下 Service Builder：

- [Service Builder 是什么？](what-is-service-builder.md)
- [定义对象-关系映射（ORM）](defining-your-object-relational-map.md)
- [生成服务](generating-services.md)
- [写本地服务类](writing-local-service-classes.md)
- [调用本地服务](calling-local-services.md)- 
- Understanding the Service Builder-generated Code
- [创建用户界面](creating-user-interfaces-for-service-builder-portlets.md)
- [调用 Liferay 的内置服务](calling-liferay-services.md)
- [使用 Model Hints](using-model-hints.md)
- Writing Remote Service Classes
- Developing Custom SQL Queries
- Configuring service.properties
- Summary

UBA is short for Univeral Business Architecture，
是一些通用技术架构的收集整合，

每个技术架构抽象并描述了一个特定业务功能点，支撑该业务的基本运行需求，
并且，提供和预留了足够灵活的扩展能力，以应对需求变化。

每个技术架构是一个工程，称为一个业务构建原型（Business Archetype），
使用Maven对这些工程进行项目信息管理。
通过Git进行版本控制，利于分支开发，多版本建立。

可直接在此基础之上扩展、重构使之成为某个业务需求的技术方案。

如何参与开发：

1、在本地clone仓库：git clone http://github.com/shiyunlai/UBA.git
   此时会在本地建立UBA目录。
   
2、以UBA为工作空间启动eclipse。

3、通过Import --> Maven --> Existing Maven Projects 逐个导入这些项目。
   （注：需要自己安装eclipse的Maven插件）

# Mkdocs
中文文档： https://markdown-docs-zh.readthedocs.io/zh_CN/latest/

## 优势
mkdocs 的优势在于：

* 十分方便简单
* mkdocs serve 直接起服务很方便（sphinx有了auto-rebuild之后这个优势不明显）
* mkdocs gh-pages 内置 github 部署直接
* mkdown 语法简洁（双刃剑）

## 缺点
但是好像有几个缺点，还不是太实用。

* 搜索不支持中文
* 路径不支持中文
* 链接语法太简单，只支持 ``[project license](about.md#license)`` 这样最简单的相对路径和锚点链接。
* 自动生成的head的id也不支持中文。
* 图片大小设置都只能用``<img>``标签


总之，全部的笔记决定暂不从 sphinx 迁移到 mkdocs，除非后面发现自己真的需要迁移。

但是 ，对于新起的小型的，全英文的文档，用mkdocs是非常好的选择。



## 内部链接
```
[页链接](markdown.md)
[页内链接](markdown.md#table)
```

[页链接](markdown.md) 
[页内链接](markdown.md#table) 


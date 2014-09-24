## EFE Blog

作为EFE团队Blog仓库。

### Blog提交要求

我们鼓励更多地提交Blog，各团队请自行规范具体的提交要求。推荐如下：

- 所有T6及以上工程师，每季度至少提交一篇原创或翻译。
- 所有T5工程师，鼓励每季度提交一篇原创或翻译。
- 对于所有工程师，可通过[Issue](https://github.com/ecomfe/blog/issues)进行参与。

### Blog接受类型

所有Blog应当与前端技术有所关联，包括但不局限于：

- 前端技术，如CSS、JavaScript、Web性能优化等。
- 与前端有较强关联的后端、运维等技术，如Web Server、Nginx、NodeJS等。
- 与前端有关的脚本技术，如通过Python、Ruby、NodeJS、Java Ant等对前端代码进行构建，使用各种包管理工具等。
- UE、UX相关的内容，如色彩、布局、视觉、首屏、用户体验等。

Blog的内容应该具有原创性和独到性，我们接受以下类型的内容作为Blog：

- 对于一个细节点进行深入探讨，例如《文本居中在各种场合下的方案》、《HTTP缓存全面解析》等，重点在于深入、详细。
- 对于一个体系型话题的描述，例如《Web性能优化的基本过程和方法》、《前端构建》等，重点在于对一个体系的各方面均有涉及。
- 对项目工作中的（非保密的）经验的分享，如针对某系统的一次代码整顿，发现大家经常会犯的编码、设计错误等。
- 对于某个工具、框架、库的使用，此类应当包含一个实战示例，便于上手，如《使用各MVC框架开发TODO工具》等。
- 对有价值的外文文章的翻译，需保持翻译的质量，并且在文章中附带原文链接。

同时，对于质量不高、话题无关或者其它原因产生的低质量的文章，我们将根据具体情况不予采编或者直接移除，包括但不限于：

- *不得* 直接使用他人的文章，如有发现直接移除。
- *不得* 涉及公司保密信息，尽量不要出现直接的项目代码，如有发现后果自负。
- *不推荐* 搜索引擎、社区中已经广泛存在且有定论的内容，比如《如何使带Alpha通道的PNG32图片在IE6下显示半透明效果》这类的话题。

### 如何参与

#### 直接提交文章

我们创建了ecomfe/blogger组，包含所有T5及以上工程师，此组的成员将有权限直接push代码至仓库中， **请遵守以下规则** ：

- 需要发布的文章放到`_posts`目录下，临时草稿放到`_drafts`目录下。
- 文件名请以`日期-标题`的形式命名，其中日期是`YYYY-MM-DD`形式，标题使用 **全小写英文和数字组合，使用`-`分隔** 的形式，尽量避免出现需要URL编码的字符。
- 文件格式请参考[2014-09-23-empty.md](https://github.com/ecomfe/blog/blob/master/_posts/2014-09-23-empty.md)文件，注意请不要编辑此文件。

如果你已经有了自己的独立博客，则可以在提交至仓库的文章中只提供个人博客的对应链接，不需要全文，我们会进行采编。

##### 图片及资料存放

请将图片放在`img`目录里，每篇文章的图片应当单独存放在以文章文件名为名的目录下，在文章中的引用方式为：

```markdown
![图片标题](/img/{文章名}/foo.png)
```

同样的，如PPT、代码包等也可以存放在`img`目录中，可以通过如下方式引用：

```markdown
[链接文字](/img/{文章名}/foo.pptx)
```

我们推荐使用[OneDrive](http://onedrive.live.com)、[SlideShare](http://slideshare.net)等存放PPT资源，使用[GitHub](https://github.com)或[Gist](https://gist.github.com)存放代码片段，避免使用本仓库放置此类内容。

##### 文章封面

建议每篇文章有一个封面图标，图标必须满足以下要求：

- 大小尺寸为280x150。
- 需放置在`img/{文章名}/cover.jpg`中。

##### 作者信息

对于每一位贡献者，请先编辑`_data/authors.yml`文件加入自己的信息，具体请参考文件现有内容。

#### 通过Issue参与

对于没有代码权限的工程师，我们欢迎通过[Issue](https://github.com/ecomfe/blog/issues)进行参与，你可以通过[新建Issue](https://github.com/ecomfe/blog/issues/new)来提供以下内容：

- 自己原创或翻译的文章，对于符合质量要求的我们将吸收至仓库中进行采编。
- 自己希望学习、阅读的话题，作为话题池可以由他人来完成对应的文章。

同时，我们 **推荐** 在撰写文章时，在[Issue](https://github.com/ecomfe/blog/issues)中留下相关的话题，可以供大家讨论，如果有开始未考虑但大家后来提出的内容，也可补充到文章中，使文章显得更加丰满。

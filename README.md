# html-viewer-for-obsidian
在 Obsidian 内查看html文件的解决方案


## 为何会有此插件？

简短回答：  
现有插件不够好用。

详细回答：  
最近做了个[微信公众号文章导出](https://github.com/jooooock/wechat-article-exporter)工具，为了样式还原度及复杂性考虑，只支持导出 html 格式，其中内部资源(图片、样式等)都是采用相对路径引用。

搜了下 Obsidian 查看 html 的相关插件，发现 [HTML Reader](https://github.com/nuthrash/obsidian-html-plugin) 可以在 Obsidian 中打开并查看 html 文件，但是不支持引用相对路径的资源文件(详情查看[known-issues](https://github.com/nuthrash/obsidian-html-plugin?tab=readme-ov-file#known-issues))。
还有一个 [Html Server](https://github.com/Pr0dt0s/obsidian-html-server) 插件通过启动一个 http 服务器，以 url 的方式访问仓库内文件，但是不支持直接在 Obsidian 内打开并查看 html 文件。

因此，我就在想，如果把这两个功能做在一起不就可以了嘛，因此，本插件集成了以上两款插件的功能于一体，实现在 Obsidian 内完美查看 html 文件的需求。

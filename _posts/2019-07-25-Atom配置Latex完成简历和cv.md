会尽力更新，如有任何问题和建议请发邮件给我：）
# Atom 配置Latex完成简历和cv
Atom 是 GitHub 开源的文本编辑器，拥有丰富的主题和插件，可以快速简洁的完成日常生活中的文本编辑任务。



### Atom 安装
可以直接在Atom官网进行下载： [Atom官网](https://atom.io)

### 插件配置方法及推荐插件
在菜单栏中找到 `Atom -> Preferences` 打开设置页面，找到`install`，可以搜索想要下载的package。

推荐插件(在本教程中不需要使用)：
实时预览markdown文档：**markdown-preview-enhanced**
- 强烈推荐，整个Atom中最好用的markdown文件预览器，可以进一步配置在markdown中实时显示latex数学公式。


### Atom 配置 Latex    

下载插件：`LaTeX`， `pdf-view`


### Latex 简历模板    
模版网站： [Latex Template](http://www.latextemplates.com/)      
Latex templates 里有很多不同类型的模版，可以找到`CV&Resume`， 下载好喜欢的模版之后，用Atom打开，效果如下：

![temp](https://github.com/xwen1765/xwen1765.github.io/raw/master/post_images/latex_temp.png)    


这样就可以更改生成的文件，想要在Atom中预览生成之后的pdf，可以装插件 `pdf-view`。打开`Settings -> latex (之前的package) -> opener`下拉菜单更改为`pdf-view`。

回到编辑器页面，快捷键`shift + command + P`打开菜单，输入latex，找到 **latex：build**，回车，生成的pdf会出现在屏幕右边。如下图：

![](https://github.com/xwen1765/xwen1765.github.io/raw/master/post_images/latex_final.png)

生成的pdf也会直接存在存放latex文件的文件夹里。

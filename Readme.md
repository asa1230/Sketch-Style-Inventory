*****
**注意:** 请用Sketch 3.3及以上版本
*****

# sketch-设计规范样式管理器

设计往往需要不受限制的发挥,有的甚至从杂乱中来获得灵感。但是对于设计项目本身，设计师需要进行设计文件的组织和整理的。相比而言，Sketch在这些方面做的很好！ 但如果你想移动或整理文本样式或统一调整某个UI的颜色，sketch还是有点难搞定。比如：清理sketch样式列表,或者是保存已经用的，清理掉没有用的样式. 这款插件就可以帮助大家解决这个问题.他可以快速列出所有已经用过的样式并帮助合并风格类似的样式设定.

![插件面板](http://f.cl.ly/items/3c1N0F3K0i2T1x3z0F2X/Bildschirmfoto%202015-04-26%20um%2022.05.10.png)
## 快捷键
#### 调用插件-快捷键
* 快捷键 `ctrl` + `⌘` + `⌥` + `I`

#### 快速选择对象-快捷键
* 颜色/通过颜色选择所有图层 `shift` + `ctrl` + `⌘` + `C`
* 颜色/通过颜色选择当前画布上的图层 `ctrl` + `⌘` + `C`
* 名称/通过名称选择所有图层 `shift` + `ctrl` + `⌘` + `N`
* 名称/通过名称选择当前画布上的图层  `ctrl` + `⌘` + `N`
* 字符/替换字符 `shift` + `⌘` + `K`
* 字体风格/通过字体风格选择所有图层 `shift` + `ctrl` + `⌘` + `T`
* 字体风格/通过字体风格选择当前画布上的图层 `⌘` + `control` + `T`


#### 如何设置键盘快捷键

许多插件都默认好了基本的快捷键，你可以依据自己的习惯去设置这些快捷键.如果遇到快捷键无效的时候，可能就是快捷键冲突，需要重新设定一下。这里举个例子：
比如,第一行是 `Duplicate Artboard.sketchplugin`:

> // Duplicates the current artboard right next to it. (shift command d)

你可以修改快捷键为 `option`, `command`, `control`, `shift`

## 功能介绍

### 1.生成视觉样式规范内容

这个功能可以帮助设计师快速生成颜色，字体风格或文档中的视觉规范组件。设定好你想输出的内容配置，画板会自动生成一个名为“style inventory”的画布

**快捷键:** `ctrl` + `⌘` + `⌥` + `I`

![功能演示](https://dl.dropboxusercontent.com/u/974773/_keepalive/Style%20Inventory/generate.gif)


### 2.导出 Metadata
当你选这个选项的时候，sketch将会导出项目中的图片和metadata两种类型。metadata是开发喜欢的一种类型，他把颜色色值，元件名称及属性，文字风格样式等信息都写入JSON文件，免去了他们的切图烦恼

**快捷键:** `ctrl` + `⌘` + `⌥` + `I`

![功能演示](http://f.cl.ly/items/3944230o3a0V1u2u463t/export%20metadata.gif)

### 3.在当前画板中，通过颜色选择图层

选中一个图层，当前画板中，填充色或文本色与选中匹配的图层都会被一起选中。

**快捷键:** `ctrl` + `⌘` + `C`

![功能演示](https://dl.dropboxusercontent.com/u/974773/_keepalive/Style%20Inventory/Select%20by%20Color.gif)


### 4.通过颜色选中图层

`实验中的功能` 选中一个图层，当前文档中，填充色或文本色与选中匹配的图层都会被一起选中。

### 5.通过名称选择图层
选中一个图层，名称与选中图层相匹配的图层都会被一起选中。说明一下，对于复制后产生的图层，一样会被选中。如（矩形1；矩形1副本1；矩形1副本2；）

**快捷键:** `ctrl` + `⌘` + `N`


### 6.替换字符

查找和替换选中文本图层中的所有重复性的文字

**快捷键:** `shift` + `⌘` + `K`

![Selection Animation](https://dl.dropboxusercontent.com/u/974773/_keepalive/Style%20Inventory/Select%20by%20Name.gif)


### 7.通过颜色选择下一个图层

`实验中的功能` 选中一个图层，填充色或文本色与之匹配下一个图层会被单独选中。

### 8.通过字体风格选择下一个图层

`实验中的功能` 选中一个图层，字体风格与之匹配下一个图层会被单独选中.

![Screenshot](https://dl.dropboxusercontent.com/u/974773/_keepalive/Style%20Inventory/Select%20Layer%20by%20Similar%20Style.png)

### 9.样式清理
快速把界面中用的所有的颜色或风格生成一个可视化的图片。他可以帮助设计师快速浏览所有的样式并合并一些样式上比较接近的风格。他也可以一键导出字体风格的CSS文件。

### 10.在新画板上-生成所有文字样式
在新画板上快速生成文档中使用到的所有的文字样式
![Selection Animation](https://dl.dropboxusercontent.com/u/974773/_keepalive/Style%20Inventory/Sketch%20CSS.gif)


### 11.生成所有颜色值
在新画板上快速生成当前画板中使用到的所有色值

![Screenshot](https://dl.dropboxusercontent.com/u/974773/_keepalive/Style%20Inventory/Colors.png)

### 12.快速重命名图层
`实验中的功能` 帮你在不知道如何标准命名的情况下，简单快速的处理好图层命名。好处就是如果你是前端或开发者，能够通过生成的SASS或JSON文件获得更多信息。


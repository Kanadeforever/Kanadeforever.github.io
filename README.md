# 这里什么都没有
只有一部分闹着玩的工具，有兴趣可以试试

## [Simple Markdown Editor](ToolTest/simplemarkdowneditor/index.html)
- 测试VSCode+Continue+DeepSeek编程的产物；
- 非常基础，markdown的编写、预览、载入、保存都正常运作；
- 单文件，一个Html文件用浏览器打开就能用；
- 一句话需求的我，DeepSeek编写的代码。

## [Simple Kanban](ToolTest/simplekanban/index.html)
- 被上面测试后对DeepSeek的编程能力进步感到震惊后的产物；
- 基础的支持Markdown的简单看板工具；
- 因为到处都没有符合我需求（markdown明文本地储存的看板软件），所以尝试DS手搓，没想到一发成型……；
- 本版代码一个字都没改，只是提供了一个参照目标的网址，然后让ds复刻，最后测完了把代码粘贴过来得到的；
- it just works！
- D老师牛哔————！

## [Markdown Kanban (WIP)](ToolTest/mdkanban/index.html)
这玩意是我最开始四处寻找却找不到的轮子，我就是想要一个功能齐全、数据明文储存的本地看板工具。

但是大部分看板工具，要么功能搞得很杂要么对工具本身依赖项极高，要么就得丢到docker或者linux服务器上

本来打算放弃的，直到看到[这个项目](https://github.com/quclo/markdown-kanban)，让我觉得有一丝可能性了。

大D老师则在我一句话下就做出了原型，于是决定正儿八经开始搞，完成了以后多半要么搭配自制前端，要么搭配Electron打包成本地应用，也算完成了我一个小心愿。

- [Simple Kanban](ToolTest/simplekanban/index.html)的超绝进化版，是被D老师震惊后认真起来搞的产物；
- 最初版的图标是使用[Font Awesome 6](https://fontawesome.com/versions)，现在以迁移到了[Remix icon](https://remixicon.com/)上，虽然没以前那么好看但这套图标也是开源的；
- 目前支持markdown明文储存和相对进阶的看板功能；
- 导出的数据可直接在各种支持markdown的编辑器/查看器中阅览，其中本项目使用的各种专有参数储存在文件末尾。
- 专有数据计划在1.0发行版以后进行迭代，最终希望包括专有数据在内都可以被markdown编辑器支持，做到即使本工具坏了也不会丢失数据。
- 已经可以用于日常使用和生产阶段
- 有些体验上的小BUG正在解决
- EA版，细节待打磨。

## [CusBro](https://github.com/Kanadeforever/CusBro)

- 多此一举的本地webui应用的浏览器；
  - 作用是在你想打开这个应用但又不想打开浏览器的时候，让你用它；
  - 可以给nas控制台、nas的各种web端应用做显示窗口；
  - docker程序，又或者像syncthing单独启动这样的情况下，webui的显示窗口；
- 功臣依然是大D老师，新的功臣是Electron和nodejs。
- 依然是bug比较多的状态，需要修改所以目前是预览版
- "it just works!"
















----

by Luminous 2025

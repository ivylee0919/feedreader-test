# 订阅阅读器测试

## 项目说明

这是 Udacity 前端进阶纳米学位的项目二：订阅阅读器测试。
此项目中的大部分基础代码是 Udacity 提供，是一个基于 Web 的 RSS 反馈阅读应用程序。其中包含了使用 Jasmine 编写的第一个测试套件。
我在此项目中需要完成的内容有：

- 编写一个测试遍历 `allFeeds` 对象里面的所有的源来保证有链接字段而且链接不是空的。
- 编写一个测试遍历 `allFeeds` 对象里面的所有的源来保证有名字字段而且不是空的。
- 写一个叫做 `"The menu"` 的测试用例
- 写一个测试用例保证菜单元素默认是隐藏的。你需要分析 html 和 css 来搞清楚我们是怎么实现隐藏/展示菜单元素的。
- 写一个测试用例保证当菜单图标被点击的时候菜单会切换可见状态。这个测试应该包含两个 expectation：当点击图标的时候菜单是否显示，再次点击的时候是否隐藏。
- 写一个叫做 `"Initial Entries"` 的测试用例
- 写一个测试保证 `loadFeed` 函数被调用而且工作正常，即在 `.feed` 容器元素里面至少有一个 `.entry` 的元素。
- 写一个叫做 `"New Feed Selection"` 的测试用例
- 写一个测试保证当用 `loadFeed` 函数加载一个新源的时候内容会真的改变。
- 每个测试都不应该依赖别的测试的结果。
- 回调函数应该用来保证在测试运行之前源已经被加载。
- 实现未定义变量和数组越界的错误处理。
- 当完成所有任务的时候，所有的测试也应该通过。
- 写一个 README 文件来详细说明运行应用的步骤。

## 运行应用的步骤

- 浏览器打开 `index.html` 即可运行所有测试用例
- 如需修改测试用例，可以修改 `feedreader.js` 的相关内容。
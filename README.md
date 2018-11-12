1. 测试遍历 allFeeds 对象里面的所有的源来保证有链接字段而且链接不是空的
2. 测试遍历 allFeeds 对象里面的所有的源来保证有名字字段而且不是空的
3. "The menu" 的测试用例
4. 测试用例保证菜单元素默认是隐藏的。你需要分析 html 和 css 来搞清楚我们是怎么实现隐藏/展示菜单元素的。
5. 测试用例保证当菜单图标被点击的时候菜单会切换可见状态。这个测试应该包含两个 expectation ： 当点击图标的时候菜单是否显示，再次点击的时候是否隐藏。
6. Initial Entries 第一次进入时title时‘Udacity Blog’
7. 测试保证 loadFeed 函数被调用而且工作正常，即在 .feed 容器元素里面至少有一个 .entry 的元素。
8. "New Feed Selection" 的测试用例 第一次进入时title时‘Udacity Blog’
9. 测试保证当用 loadFeed 函数加载一个新源的时候内容会真的改变。
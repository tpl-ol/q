# 歧语言 (文档)

<https://github.com/tpl-ol/q>

无歧义中文编程语言, 简称 "歧语言" (Q)。

![`~歧`](./logo/q-logo-1024.png)


## 栗子

```sh 歧
# 第一个程序.歧
# 这是注释

输出 666。
```

```sh 歧
# 第一个程序2.歧

循环 3 次:
  写 6。

换行。
```

```sh 歧
# 测试_窝吃饭.歧

定义类型吃货:
  定义变量昵称(文本)。
  定义变量已吃标记(二)。

  定义吃, 参数自己、东西(文本):
    若自己饿:
      输出 “{{自己的昵称}}吃了{{东西}}”。
      自己的已吃标记是 1。
    另:
      输出 “吃饱了”。

  定义饿(二), 参数自己:
    非(自己的已吃标记)。

# 窝是吃货
定义变量窝, 吃货。
窝的昵称是 “喵喵”。

定义变量饭, “汤面条”。

# 测试
窝吃饭。  # 喵喵吃了汤面条
# 再吃
窝吃饭。  # 吃饱了
```


## 歧语言特点

+ 从 0 设计的中文编程语言。

+ 充分利用现代汉语 (简体中文, `zh_CN`) 的部分语法。

+ 使用简单的语法规则 “解决” 歧义 (遇到歧义则编译错误), 并进行分词。

+ 无空格语法 (除了行首的空格都会被忽略), 参考 Python 的语法设计 (缩进)。

+ 编译为 JavaScript, 具有大部分 JavaScript 的特性, 且能够与 JavaScript 互操作。

TODO


## 致敬

- 文言文编程语言
  <https://github.com/wenyan-lang/wenyan>

- Python 编程语言
  <https://www.python.org/>


## 友情链接

TODO


## LICENSE

[`CC-BY-SA 4.0+`](https://creativecommons.org/licenses/by-sa/4.0/)

本仓库的内容使用 创意共享-署名-相同方式共享 (CC-BY-SA 4.0) 许可证 (LICENSE).
This repository is released under Creative Common (CC-BY-SA 4.0) license.

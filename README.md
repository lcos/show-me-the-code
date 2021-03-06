# Python 练习册

- Python 练习册，一些比较有意思的题目，题目搜集自互联网，感谢各位的分享。

> Talk is cheap. Show me the code.--Linus Torvalds

--------

**第 0000 题：**将你的 QQ 头像（或者微博头像）右上角加上红色的数字，类似于微信未读信息数量那种提示效果。
类似于图中效果

![头像](http://7xp5pe.com1.z0.glb.clouddn.com/result1.jpg)

**第 0001 题：**做为 Apple Store App 独立开发者，你要搞限时促销，为你的应用**生成激活码**（或者优惠券），使用 Python 如何生成 200 个激活码（或者优惠券）？

**第 0002 题**：将 0001 题生成的 200 个激活码（或者优惠券）保存到 **MySQL** 关系型数据库中。 

**第 0003 题：**将 0001 题生成的 200 个激活码（或者优惠券）保存到 **Redis** 非关系型数据库中。 

**第 0004 题：**任一个英文的纯文本文件，统计其中的单词出现的个数。

**第 0005 题：**你有一个目录，装了很多照片，把它们的尺寸变成都不大于 iPhone5 分辨率的大小。

**第 0006 题：**你有一个目录，放了你一个月的日记，都是 txt，为了避免分词的问题，假设内容都是英文，请统计出你认为每篇日记最重要的词。

**第 0007 题：**有个目录，里面是你自己写过的程序，统计一下你写过多少行代码。包括空行和注释，但是要分别列出来。

**第 0008 题：**一个HTML文件，找出里面的**正文**。

**第 0009 题：**一个HTML文件，找出里面的**链接**。

**第 0010 题：**使用 Python 生成类似于下图中的**字母验证码图片**,同时写出识别验证码的程序。

![字母验证码](http://i.imgur.com/aVhbegV.jpg)

- [阅读资料](http://stackoverflow.com/questions/2823316/generate-a-random-letter-in-python) 

**第 0011 题：** 敏感词文本文件 filtered_words.txt，里面的内容为以下内容，当用户输入敏感词语时，则打印出 Freedom，否则打印出 Human Rights。

    北京
    程序员
    公务员
    领导
    牛比
    牛逼
    你娘
    你妈
    love
    sex
    jiangge
    
**第 0012 题：** 敏感词文本文件 filtered_words.txt，里面的内容 和 0011题一样，当用户输入敏感词语，则用 星号 * 替换，例如当用户输入「北京是个好城市」，则变成「**是个好城市」。

**第 0013 题：** 用 Python 写一个爬图片的程序,爬[这个链接](https://www.zhihu.com/question/24340705)的壁纸

**第 0014 题：** 纯文本文件 student.txt为学生信息, 里面的内容（包括花括号）如下所示：

    {
        "1":["张三",150,120,100],
        "2":["李四",90,99,95],
        "3":["王五",60,66,68]
    }

请将上述内容写到 student.xls 文件中，如下图所示：

![student.xls](http://i.imgur.com/nPDlpme.jpg)

- [阅读资料](http://www.cnblogs.com/skynet/archive/2013/05/06/3063245.html) 腾讯游戏开发 XML 和 Excel 内容相互转换

**第 0015 题：** 纯文本文件 city.txt为城市信息, 里面的内容（包括花括号）如下所示：

    {
        "1" : "上海",
        "2" : "北京",
        "3" : "成都"
    }

请将上述内容写到 city.xls 文件中，如下图所示：

![city.xls](http://i.imgur.com/rOHbUzg.png)


**第 0016 题：** 纯文本文件 numbers.txt, 里面的内容（包括方括号）如下所示：

    [
        [1, 82, 65535], 
        [20, 90, 13],
        [26, 809, 1024]
    ]

请将上述内容写到 numbers.xls 文件中，如下图所示：

![numbers.xls](http://i.imgur.com/iuz0Pbv.png)

**第 0017 题：** 将第 0014 题中的 student.xls 文件中的内容写到 student.xml 文件中，如

下所示：

    <?xml version="1.0" encoding="UTF-8"?>
    <root>
    <students>
    <!-- 
        学生信息表
        "id" : [名字, 数学, 语文, 英文]
    -->
    {
        "1" : ["张三", 150, 120, 100],
        "2" : ["李四", 90, 99, 95],
        "3" : ["王五", 60, 66, 68]
    }
    </students>
    </root>


**第 0018 题：** 将 第 0015 题中的 city.xls 文件中的内容写到 city.xml 文件中，如下所示：

    <?xmlversion="1.0" encoding="UTF-8"?>
    <root>
    <citys>
    <!-- 
        城市信息
    -->
    {
        "1" : "上海",
        "2" : "北京",
        "3" : "成都"
    }
    </citys>
    </root>

**第 0019 题：** 将 第 0016 题中的 numbers.xls 文件中的内容写到 numbers.xml 文件中，如下

所示：

    <?xml version="1.0" encoding="UTF-8"?>
    <root>
    <numbers>
    <!-- 
        数字信息
    -->
    
    [
        [1, 82, 65535],
        [20, 90, 13],
        [26, 809, 1024]
    ]
    
    </numbers>
    </root>

**第 0020 题：** 使用 Python 语言开发服务器端口扫描器，用来检测目标服务器上有哪些端口开放。

**第 0021 题：** 通常，登陆某个网站或者 APP，需要使用用户名和密码。密码是如何加密后存储起来的呢？请使用 Python 对密码加密。

- 阅读资料 [用户密码的存储与 Python 示例](http://zhuoqiang.me/password-storage-and-python-example.html)

- 阅读资料 [Hashing Strings with Python](http://www.pythoncentral.io/hashing-strings-with-python/)

- 阅读资料 [Python's safest method to store and retrieve passwords from a database](http://stackoverflow.com/questions/2572099/pythons-safest-method-to-store-and-retrieve-passwords-from-a-database)


**第 0022 题：** 使用 Python 的 Web 框架，做一个 Web 版本 留言簿 应用。

[阅读资料：Python 有哪些 Web 框架](http://v2ex.com/t/151643#reply53)

- ![留言簿参考](http://static.zybuluo.com/WuLiangchao/5kyegv0hnooqxzsxjdy1cm48/image_1aoqu2cj46e018hhp4g27d1fs19.png)


**第 0023 题：** 通过有道翻译提供的API写一个支持命令行翻译单词的工具，效果如下图：

![][1]

**第 0024 题：** 实现一个简单的 HTTP 服务器，能够响应GET，POST等请求


  [1]: http://static.zybuluo.com/WuLiangchao/qzhby9favu907s2m4spm7hon/image_1atfr8u7f180e1lm61ns91321qsr9.png
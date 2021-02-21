# classtable-private-hitsz-ics

将ics文件托管在GitHub上,以便iOS添加已订阅的日历.

## Background

笔者就读的学校系统不支持课表一键导入日历,又不支持导出ics,同时导出的excel文件主要适用于打印使用;而在制作了ics文件后,iOS系统中以本地文件形式导入日历的途径笔者并未找到.因此建立此订阅日历的仓库.

课表2021-spring-class.ics文件的制作程序出自 [GillBlog@陈某豪](https://chanjh.com/post/0031/ "又到了每年此刻，教你把课程表导入日历") .

>在Python 2的基础上通过谷歌搜索修改为Python 3适用.但孩子还没学过Python,excel也不是特别熟练,太难了/(ㄒoㄒ)/.

之后的ics文件将根据 [GitHub@SunsetYe66](https://github.com/SunsetYe66/ClasstableToIcal/ "ClasstableToIcal") 提供的程序制作.

>不知为何详细教程中提到的搭建HTTP服务器这一方法,实践过程中笔者无法打开ics文件.

## Usage

* **使用订阅URL**

复制以下URL,然后添加到相应的日历中.

```
https://raw.githubusercontent.com/cattail5/classtable-private-hitsz-ics/master/2021-spring-class.ics
```

## Credit

本日历由 [陈某豪](https://chanjh.com/post/0031/) 以及 [SunsetYe66](https://github.com/SunsetYe66/ClasstableToIcal/) 项目制作而成,在此对原作者表示感谢.

# vs2010中git配置
***
关键字： *VS* *git*

## 1.git for window 的安装和设置：
    使用git你首先要有个账号，没有的自己先去申请一个，记住你的邮箱

    安装参照下面的这个博客，介绍的很到位,照着文章上说的做：
    我建议除安装路径外，其他全部默认
    [http://blog.csdn.net/laogong5i0/article/details/10974285](http://blog.csdn.net/laogong5i0/article/details/10974285)
    还有一些设置：
    [http://blog.csdn.net/softwave/article/details/7957938](http://blog.csdn.net/softwave/article/details/7957938)

## 2.不能push的问题解决：
    但可能你不能提交项目，接下来需要从下面的方法去尝试解决：
    1.配置你的git，按照下面的博客进行设置：
    git bash 按照上面我建议的安装后在桌面右键后会有
    [http://blog.csdn.net/hustpzb/article/details/8230454/](http://blog.csdn.net/hustpzb/article/details/8230454/)
    2.配置好以后你可能也不行，那就可能是你在新建项目时候自动生成的README.md造成的，那你
    就需要先pull一下，这个在vs的push是上面，下面是参考源：
    [http://jingyan.baidu.com/article/f3e34a12a25bc8f5ea65354a.html](http://jingyan.baidu.com/article/f3e34a12a25bc8f5ea65354a.html)

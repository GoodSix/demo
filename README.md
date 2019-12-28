使用docker快速配置
```shell
git clone https://github.com/eoogo/Hello && docker run -itd -v `pwd`/Hello/:/var/www/ -p 80:80 --restart always --name hello eoogo/devt:ed /bin/bash devt-init
```

```
~ 标题声明 ~
详情介绍，不会被读取

# 分类声明
分类的介绍，不会被读取。

    该分类下的某个被说明的对象，必须使用4个空格表示缩进
        参数形参名 参数类型> 参数介绍
        返回值类型< 返回值介绍
        + 对于被说明对象的详细介绍
        + 可以有多行
        + 但必须按照语法规定继续
        ```
            // 表示代码块，代码块第一行的任何内容不会被记录
            public class Hello {
                public static void main(String[] args) {
                    System.out.println("Hello world");
                }
            }
        ```

## 多层级分类增加一个#
必须按照层级 + 1，否则不仅无效，解析也是不通过的

    tips
        + 即使是多层级分类下的对象，也是按照4个空格来缩进
        + 分类只会影响该对象的位置但是对该对象本身并不会产生影响

    tips 2
        + 需要使用单个文件介绍某个命令
        + 即使虽然在解析后不会产生影响
        + 但是还是推荐以 @# 作为分类标识符
```

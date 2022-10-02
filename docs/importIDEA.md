## 导入IDEA

看源码第一步自然就是将项目源代码导入到本地IDEA中。当然可能大家会觉得这步骤不是太简单了吗？干嘛还需要写出来。如果你要真要这么问...那我不跟你缰。

> **:rotating_light:** 本章节仅针对Windows系统哈！！！Linux，mac的参考官网即可。

### 第一步：Fork项目之后直接将项目导入到本地IDEA

如果还不知道如何`Fork`，不知道如何IDEA拉去`Github`上的项目的话，我这有两个绝对好使的网站，肯定能够帮助你。

[链接1](https://www.google.com/search)  [链接2](https://www.baidu.com/)



### 第二步：编译和打包项目

请参考使用以下命令进行编译打包：

```shell
mvn clean install package -Prelease -Dmaven.test.skip=true -Dmaven.javadoc.skip=true
```

结束之后，打包好的部署安装包就在`dolphinscheduler-dist\target`目录下



剩余步骤请参考官网：https://dolphinscheduler.apache.org/zh-cn/docs/latest/user_doc/contribute/development-environment-setup.html

[Gradle配置文件详解](https://blog.csdn.net/niuba123456/article/details/81073639)
[解析build.gradle文件](https://www.cnblogs.com/pkangping/p/9496769.html)

【两个properties文件】
1、gradle.properties：位于项目根目录下，主要设置Gradle后台进程JVM内存大小、日记级别等等
2、local.properties：为Gradle配置环境变量，例如sdk、ndk路径

【3个.gradle文件】
1、setting.gradle：此配置文件位于根目录下，用于指示Gradle在构建应用时应将哪些模块包含在内，多个模块之间用空格隔开
2、build.gradle(Project: remusic)：顶级配置作用于所有子项目和子模块。配置要用的代码仓库（如jCenter，google）
3、build.gradle(Module: app)：模块的配置
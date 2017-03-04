# TheGoProgrammingLanguage
**《Go语言编程》---许式伟**读书纪录

[Go语言编程github](https://github.com/qiniu/gobook)

[Go语言编程书籍](https://www.amazon.cn/dp/B00932YRPA/ref=sr_1_1?ie=UTF8&qid=1486914755&sr=8-1&keywords=GO语言编程)

**环境**：

[MAC](http://www.apple.com/cn/mac)

[LiteIDE源码](https://github.com/visualfc/liteide)

[LiteIDE下载](http://www.golangtc.com/download/liteide)

[马克飞象](https://maxiang.io)

补充：
* 原书中有一些错误
* 必须操作但未在书中说明

### 目录
* [前言](https://github.com/Lynn--/TheGoProgrammingLanguage/blob/master/Introduction/introduction.md)
* [第一章 初识Go语言](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/One.LearnGoLanguage)
	* [1.1 语言简史](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/One.LearnGoLanguage/LanguageHistory1.md)
	* [1.2 语言特性](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/One.LearnGoLanguage/LanguageFeatures2.md)
		* 1.2.1 自动垃圾回收
		* 1.2.2 更丰富的那只类型
		* 1.2.3 函数多返回值
		* 1.2.4 错误处理
		* 1.2.5 匿名函数和闭包
		* 1.2.6 类型和接口
		* 1.2.7 并发编程
		* 1.2.8 反射
		* 1.2.9 语言交互性
   * [1.3 第一个Go程序](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/One.LearnGoLanguage/FirstGoProgram3.md)
		* 1.3.1 代码解读
		* 1.3.2 编译环境准备
		* 1.3.3 编译程序
    * [1.4 开发工具的选择](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/One.LearnGoLanguage/ChooseTools4.md)
    * [1.5工程管理](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/One.LearnGoLanguage/EngineeringManagement5.md)
    * [1.6 问题追踪和调试](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/One.LearnGoLanguage/ProblemTrackingAndDebugging6.md)
		* 1.6.1 打印日志
		* 1.6.2 GDB调试
    * [1.7 如何寻求帮助](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/One.LearnGoLanguage/AskForHelp7.md)
	    * 1.7.1 邮件列表
	    * 1.7.2 网站资源
	* [1.8 小结](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/One.LearnGoLanguage/Summary8.md)
* [第二章 顺序编程](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Two.SequentialProgramming)
	* [2.1 变量](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Two.SequentialProgramming/Variable1.md)
		* 2.1.1 变量声明
		* 2.1.2 变量初始化
		* 2.1.3 变量赋值
		* 2.1.4 匿名变量
	* [2.2 常量](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Two.SequentialProgramming/Constant2.md)
		* 2.2.1 字面常量
		* 2.2.2 常量定义
		* 2.2.3 预定义常量
		* 2.2.4 枚举	
	* [2.3 类型](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Two.SequentialProgramming/Type3.md)
		* 2.3.1 布尔类型
		* 2.3.2 整型
		* 2.3.3 浮点型
		* 2.3.4 复数类型
		* 2.3.5 字符串
		* 2.3.6 自负类型
		* 2.3.7 数组
		* 2.3.8 数组切片
		* 2.3.9 map	
	* [2.4 流程控制](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Two.SequentialProgramming/ControlFlow4.md)
		* 2.4.1 条件语句
		* 2.4.2 选择语句
		* 2.4.3 循环语句
		* 2.4.4 跳转语句	
	* [2.5 函数](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Two.SequentialProgramming/Fuction5.md)
		* 2.5.1 函数定义
		* 2.5.2 函数调用
		* 2.5.3 不定参数
		* 2.5.4 多返回值
		* 2.5.5 匿名函数与闭包		
	* [2.6 错误处理](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Two.SequentialProgramming/ErrorHandling6.md)
		* 2.6.1 error接口
		* 2.6.2 defer
		* 2.6.3 panic()和recover()
	* [2.7 完整示例](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Two.SequentialProgramming/CompleteExample7.md)
		* 2.7.1 程序结构
		* 2.7.2 主程序
		* 2.7.3 算法实现
		* 2.7.4 主程序
		* 2.7.5 构建
	* [2.8 小结](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Two.SequentialProgramming/Summary8.md)
* [第三章 面向对象编程](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Three.ObjectOrientedProgramming)
	* [3.1  类型系统](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Three.ObjectOrientedProgramming/TypeSystem1.md)
		* 3.1.1 为类型添加方法
		* 3.1.2 值语义和引用语义
		* 3.1.3 结构体
	* [3.2 初始化](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Three.ObjectOrientedProgramming/Initialization2.md)
	* [3.3 匿名组合](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Three.ObjectOrientedProgramming/AnonymousCombination3.md)
	* [3.4 可见性](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Three.ObjectOrientedProgramming/Visibility4.md)
	* [3.5 接口](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Three.ObjectOrientedProgramming/Interface5.md)
		* 3.5.1 其他语言的接口
		* 3.5.2 非侵入式接口
		* 3.5.3 接口赋值
		* 3.5.4 接口查询
		* 3.5.5 类型查询
		* 3.5.6 接口组合
		* 3.5.7 Any类型
	* [3.6 完整示例](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Three.ObjectOrientedProgramming/CompleteExample6.md)
		* 3.6.1 音乐库
		* 3.6.2 音乐播放
		* 3.6.3 主程序
		* 3.6.4 构建运行
		* 3.6.5 遗留问题
	* [3.7 小结](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Three.ObjectOrientedProgramming)		
* [第四章 并发编程](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Four.ConcurrentProgramming)
	* [4.1 并发基础](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Four.ConcurrentProgramming/ConcurrentBasis1.md)
	* [4.2 协程](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Four.ConcurrentProgramming/Routine2.md)
	* [4.3 goroutine](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Four.ConcurrentProgramming/Goroutine3.md)
	* [4.4 并发通信](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Four.ConcurrentProgramming/ConcurrentCommunication4.md)
	* [4.5 channel](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Four.ConcurrentProgramming/Channel5.md)
		* 4.5.1 基本语法
		* 4.5.2 select
		* 4.5.3缓冲机制
		* 4.5.4 超时机制
		* 4.5.5 channel的传递
		* 4.5.6 单向channel
		* 4.5.7 关闭channel
	* [4.6 多核并行化](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Four.ConcurrentProgramming/Multi-coreParallelization6.md)
	* [4.7 出让时间片](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Four.ConcurrentProgramming/TransferTime7.md)
	* [4.8 同步](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Four.ConcurrentProgramming/)
		* 4.8.1 同步锁
		* 4.8.2 全局唯一性操作
	* [4.9 完整示例](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Four.ConcurrentProgramming/Synchronization8.md)
		* 4.9.1 简单IPC狂减
		* 4.9.2 中央服务器
		* 4.9.3 主程序
		* 4.9.4 运行程序
	* [4.10 小结](https://github.com/Lynn--/TheGoProgrammingLanguage/tree/master/Four.ConcurrentProgramming/CompleteExample9.md)
			
		
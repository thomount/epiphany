# 《python 入阵曲：初级》
###    1、课程概述
		课程框架简介
		课程特色与亮点
		编程思维与传统理科思维的区别
		程序员的生存现状
		自己眼中的计算机领域的发展前景
		自我介绍

###    2、编程环境的配置
		python环境的部署
		好的编辑器是成功的一半
		python各种库的安装和使用
		程序：设计、编写、运行、调试 基本流程
		举例：写作、解谜游戏

###    3、输入与输出
		算法：输入、处理、输出 基本流程
		泛谈：输入途径、输出途径
		分析常见场景中的输入输出模式
		优秀设计模式：输入、处理、输出分离
		举例：游戏输入输出方式的进化

###    4、变量与常量
		程序中的变量和算式中的变量
		变量与常量
		变量的意义：临时存储
		常量的意义：规则参数
		生活中的变量与常量

###    5、数据类型
		大数据时代：何谓数据
		生活中的数据思维
		常见的数据类型：数字（整数、实数、复数？）、文字（字符串）
		示例：一个王者荣耀账户里的数据
	
###	5.1、进阶：数据存储与01
		整数的存储与二进制
		数值bug是怎么产生的
		为何实数也叫浮点数
		真和假也算数据类型么
		文字如何存储

###    6、基本语句三板斧：赋值、条件、循环
		赋值语句：数据加工	向前走
		条件语句：分情况讨论	分岔路
		循环语句：重复任务
		缩进：层次代码块
		三板斧的基本应用小例子

###	6.1、拓展：框图？流图？
		框图：直观的呈现算法流程
		流图、用例图，blabla
		编程中的形式主义？
		宗旨：详略得当，提醒的恰到好处即可

###	6.2、进阶：三板斧还不够细？进一步拆解成三幻神
		赋值语句(a = oper(b, c))
		比较语句(flag = comp(b, c))
		跳转语句(if flag goto x)
		对比：三幻神与三板斧
		
###    7、小游戏实践：猜数游戏
		输入输出
		算法流程设计
		使用三板斧设计核心算法
		如何调试代码
		debug阶段与release阶段

###	7.1、拓展：浅谈编程与游戏
		游戏组成结构：骨架（代码：画面、后台）、内容（文案、数值、系统设计）
		游戏的互动过程：

			玩家 -(操作)-> 画面 -(玩家操作数据)-> 后台
			(决策)        (渲染)                (计算)
			玩家 <-(呈现)- 画面 <-(游戏状态更新)- 后台

###	8、数据的容器
		为什么需要容器？
		不同形状与功能的容器：列表、字典、集合
		案例：排队--列表
		案例：记分册--字典
		案例：候选人名单--集合
		容器的通用功能：增、删、改、查
		容器的特有功能：
			列表：排序、截取
			集合：交、并
			字典：分离

###	8.1、进阶：说到效率
		例题：排序算法
		算法1：插入法排序
		算法2：冒泡法排序
		算法3：归并法排序
		算法4：计数法排序
		时间复杂度与性能实验
		算法性能与估算艺术
		容器通用功能的效率

###    9、函数
		函数：各司其职的“有关部门”
		函数的输入和输出
		复杂代码：各个函数的合体变身，谁来组成头部？
		函数应用：语、数、英、总分排名
		函数的意义：模块化、可复用

###	10、类
		类：从细胞到生命
		生命的记忆：成员变量
		生命的行为：成员函数
		物种与个体：类与实例
		分析：植物大战僵尸中的植物
		实例：电子动物园

###	10.1、进阶：类的高级用法
		灵长类与智人：类的继承
		继承与创新：成员函数的继承和重写
		家丑不可外扬：类的权限与安全性

###	10.2、拓展：禁止套娃
		函数套娃：为什么函数不允许套娃？
		类套娃：为什么类是允许套娃的？
	
###	11、编程中常见的报错
		语法错误：熟练拼写
		用错函数：背熟常见函数含义，不常见函数可以用help功能
		死循环：卡死、解决方法、注意事项
		无穷递归：溢出、解决方法、注意事项
		调用错误：正确填写申请表
		逻辑错误：分析语义，明确每一个变量、每一个语句块的含义、多加注释

###	11.1、拓展：注释的艺术
		工程向注释：描述函数的功能，约定输入与输出
		过程向注释：描述一个代码块在做什么事情
		草稿向注释：描述自己运算时打草稿的过程
		文艺向注释：描述写代码时的心情
		遗迹向注释：把本应删除的垃圾代码用注释的方式“封印”起来

###	11.2、拓展：如何自学编程
		初期：做简单的小题积累手感和经验，培养思维习惯
		中期：做各类题目积累算法、做小的项目培养码力
		算法修炼：历年noi、省选题目，leetcode
		工程修炼：开发点简单的完整小项目培养自己的组织能力，使用git管理代码的能力
		搜索引擎：最懂你的大老师
		github：走投无路时的模板库
		其他大佬的博客：随叫随到的专题讲座

###	12、课程总结
		为什么讲的是python而不是C++
		漫谈各种编程语言
		学会编程你能做什么
		课程回顾

###	13、进阶课程预告
		数据结构
		数据处理
		爬虫
		机器学习
		网络通信
		多进程
		图形界面
		设计模式

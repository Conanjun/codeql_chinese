# codeql_chinese

机器翻译，阅读不是很舒服，不喜勿star

定期更新中，后期计划更新javascript , python等语言的文档，便于大家阅读.

欢迎大家一起来贡献！或者提issue! 我会把我知道尽可能回复给大家 以便快速入门。 毕竟codeQL官方文档真的是……无力吐槽

# 2020.08.06更新翻译
当前版本都是Java的

codeQL中文教程(重新翻译版).pdf  -> 讲解codeQL的语法。就是官网的tutorial
  
codeql_中文文档.pdf -> 讲解codeQL java下的语法(codeQL对每个语言的类定义范围是不一样的)




可以加我微信txsser 交流更多的codeQL技术


# 2020.10.20 更新一些编写codeQL规则的小技巧


additionalTaintStep(过程间调用).pdf  

RemoteFlowSource类.pdf

Smtm模块.pdf 

CodeQL常见语法解释.pdf

以Apache kylin为例编写命令执行检查规则.pdf


====================================================================================
# Q&A
Q:codeQL可以扫描jar classes之类的文件吗？


A:The general answer is: Yes, CodeQL can be used to analyze the Java source code for the JRE.

Like for any CodeQL analysis you need to have a build system in place that actually builds the runtime .jar from the source code you want to analyze. Most of this content in this thread are attempts to help the original poster with that part.




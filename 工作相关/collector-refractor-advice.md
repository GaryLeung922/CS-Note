1. 函数太长
2. 全局变量 范围大小？  扩大范围
3. lastDuration + lastBoottimes  对象， 充血模型
4. 逻辑太绕
5. API细节暴漏太多
6. 充血模型---与对象关联度高的 需要充血


7.get set  重复代码
8.get set 可扩展性

9. mci 命令行， 暴露太多细节给用户
10. bccollector 逻辑简单，需要这么多代码？？？

11. 接口只关注某一个点。(SOLID的接口隔离原则)
12. 内存占用？ 内存分配？ 常量配置不变的字符串？
13. 耦合业务 如何拆分？

---
# bug
1. http 连接问题，http请求多，是否有注意相关的设置和配置？
2. 哪怕是一个很小的功能，单元测试也需要做

ut-workshop
===========

workshop内容： 用TDD（Test Driven Development）开发一个简单的猜数字游戏：

- 游戏开始后，系统会随机给出四个不重复的数字。由用户输入自己猜测的四个数字。
- 如果数字猜对而且位置也对，就是1一个A。
- 如果数字猜对但位置不对，就是一个B。
- 返回结果是如“2A1B”这样的字串。

例如：

- 系统给出"1234"，用户输入"1234"
 - 返回"4A0B"
- 系统给出"1234"，用户输入"4321"
 - 返回"0A4B"

workshop过程
- 共有三问
- 每一问先写代码，然后展示代码，大家集体讨论，然后开始下一问（具体内容到现场提供）

需要准备的：

- 自带笔记本
- IntelliJ CE 装好
- clone本项目，执行mvn test能通过

#test git
now modify readme file for add.
now modify readme file again for observe status.

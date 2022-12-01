---
title: 编码规约
---

编码规约
---

### 命名

 - 使用 `PascalCase` 为类型命名
 - 使用 `I` 做为接口名前缀
 - 使用 `PascalCase` 为枚举值命名
 - 使用 `camelCase` 为函数命名
 - 使用 `camelCase` 为属性或本地变量命名
 - 不要为私有属性名添加 `_` 前缀
 - 尽可能使用完整的单词拼写命名
 - 文件夹/文件命名统一使用小写 `get-custom-data.ts`

### 组件

 - 一个文件对应一个组件或类

### 类型

 - 不要随意导出类型/函数，除非你要在不同的组件中共享它
 - 不要在全局命名空间内定义类型/值
 - 共享的类型应该在 `types.ts` 里定义
 - 在一个文件里，类型定义应该出现在顶部
 - interface 和 type 很类似，原则上能用 interface 实现，就用 interface , 如果不能才用 type 

### 注释

 - 为函数，接口，枚举类型和类使用 JSDoc 风格的注释

### 字符串

 - 使用单引号 `''`

### 单元测试

 - 单元测试文件根据文件目录结构来放置
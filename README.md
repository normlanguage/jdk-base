# jdk-base

`jdk.base` 为 Norm 模块提供 `java.base` 日期、时间、精确小数和区域设置类型的统一绑定。公开入口以 [模块声明](jdk/base/module.norm) 为准；[测试](jdk/base/tests/platform_test.norm)验证日历运算和十进制精度。

需要支持 `jdkModule` 的 Norm 构建。绑定来自运行 JDK 的公开模块 API，并通过规范化 ABI 指纹验证；方法体、私有实现与调试信息不影响指纹，公开签名不匹配时会明确失败。

```powershell
norm resolve jdk/base
norm check jdk/base
norm test jdk/base --filter jdk.base.calendarArithmeticAndExactDecimals
norm package jdk/base --output build/repository
```

此模块不包含替代 JDK 的日期或数值实现。组件、存储和其它库应依赖这里的类型所有权，避免重复生成同一个 Java 类型的公开 Norm 身份。

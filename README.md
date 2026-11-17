# Java 后端学习笔记

按天拆解的 Java 后端学习笔记，每一天一页**交互式动画讲解**：可单步推演、可自动播放。

纯静态站点，零依赖、零构建，克隆下来双击 `index.html` 就能离线看。

## 在线访问

https://yhl-1.github.io/java-learning-map/

## 目录

```
index.html                     站点首页（学习路径总览）
w05-index.html                 W05 本周索引
w05-d01-java-oop.html          D1 环境、语法与 OOP
w05-d02-object-core.html       D2 Object 与核心类
w05-d03-collections.html       D3 集合框架入门
w05-d04-generics-exceptions.html  D4 泛型与异常
w05-d05-reflection-proxy.html  D5 反射、注解与代理
w05-d06-maven-testing.html     D6 Maven 与单元测试
w05-d07-review-project.html    D7 周复盘与周项目
```

## W05 · Java 基础与面向对象

| 天 | 主题 | 核心内容 |
|---|---|---|
| D1 | 环境、语法与 OOP | JDK/JRE/JVM、编译链路、栈与堆、值传递、多态原理、接口 vs 抽象类 |
| D2 | Object 与核心类 | equals/hashCode 契约、HashMap 查找、String 常量池、Integer 缓存、BigDecimal |
| D3 | 集合框架入门 | 集合全景、ArrayList 扩容、HashMap 八步 put、高低位扩容、fail-fast、Top-N |
| D4 | 泛型与异常 | 类型擦除、桥接方法、PECS、`Result<T>`、异常体系、finally 陷阱、suppressed 异常 |
| D5 | 反射、注解与代理 | Class 对象、反射代价、自定义注解、JDK 动态代理、CGLIB、字段映射器 |
| D6 | Maven 与单元测试 | 依赖冲突调解、scope、生命周期、多模块、JUnit 5、Mockito、测试金字塔 |
| D7 | 周复盘与周项目 | 六天知识串联、自检表、订单 CLI 设计、15 分钟项目自述脚本 |

## 设计说明

- **单文件**：每页的样式与脚本全部内联，不依赖 CDN、字体或任何外部资源。
- **动画**：演示区用「步骤」驱动，未到达的步骤不占位，切换时有淡入过渡。
- **深色主题**：每天一个主题色（D1 橙 / D2 青 / D3 绿 / D4 紫 / D5 玫红 / D6 蓝 / D7 金）。

## 本地查看

```bash
git clone https://github.com/YHL-1/java-learning-map.git
cd java-learning-map
# 直接双击 index.html，或起个静态服务器
python -m http.server 8080
```

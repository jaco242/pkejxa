最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：实现限流之后友好业务返回处理
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://book.lrdkoi.asia/blog/8006350.sHtMl

原标题：本地运行正常线上报错排查
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://book.lrdkoi.asia/blog/8154852.sHtMl

原标题：Practice：模拟热点key，验证缓存防护策略
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://book.lrdkoi.asia/blog/8696763.sHtMl

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.lrdkoi.asia/blog/1312063.sHtMl

原标题：golang redis 五种数据结构实战
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://book.lrdkoi.asia/blog/7566968.sHtMl

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://book.lrdkoi.asia/blog/0126323.sHtMl

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://book.lrdkoi.asia/blog/8732201.sHtMl

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://book.lrdkoi.asia/blog/9119299.sHtMl

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://book.lrdkoi.asia/blog/0633853.sHtMl

原标题：Nginx 缓冲区调优大文件上传
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://book.lrdkoi.asia/blog/5657311.sHtMl

原标题：golang 系统设计消息体序列化选型对比
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.lrdkoi.asia/blog/0048967.sHtMl

原标题：方案设计：批量大数据导出系统架构拆解
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.lrdkoi.asia/blog/7374091.sHtMl

原标题：golang 系统设计代码安全审计简单思路
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.lrdkoi.asia/blog/5334574.sHtMl

原标题：跨域偶现失败配置修复
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.lrdkoi.asia/blog/4938434.sHtMl

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://book.lrdkoi.asia/blog/6462903.sHtMl

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.lrdkoi.asia/blog/2347679.sHtMl

原标题：golang 系统设计架构图绘制规范简单建议
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://book.lrdkoi.asia/blog/9573230.sHtMl

原标题：golang 系统设计限流服务架构讲解
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://book.lrdkoi.asia/blog/4591782.sHtMl

原标题：golang 系统设计缓存预热缓存降级实现
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.lrdkoi.asia/blog/1450231.sHtMl

原标题：Practice：实现熔断降级组件简单原型代码
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.lrdkoi.asia/blog/1773852.sHtMl

原标题：调优方案：容器CPU内存参数压测后调优
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://book.lrdkoi.asia/blog/4903479.sHtMl

原标题：golang ci 流水线代码质量扫描集成
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.lrdkoi.asia/blog/3336569.sHtMl

原标题：调优方案：CDN优化静态资源访问延迟
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.lrdkoi.asia/blog/6803093.sHtMl

原标题：极简方式搭建个人技术文档站点
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.lrdkoi.asia/blog/7064767.sHtMl

原标题：架构笔记：多数据源架构设计事务处理难点
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://book.lrdkoi.asia/blog/1899920.sHtMl

原标题：记一次字符集编码不一致乱码问题全排查
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.lrdkoi.asia/blog/9127485.sHtMl

原标题：golang 系统设计分布式会话方案对比
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.lrdkoi.asia/blog/3134498.sHtMl

原标题：入门实践：项目配置文件多环境管理方案
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.lrdkoi.asia/blog/5773936.sHtMl

原标题：零基础理解模块化与组件化基础思想
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://book.lrdkoi.asia/blog/6675742.sHtMl

原标题：golang 单元测试 mock http 请求
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.lrdkoi.asia/blog/7720378.sHtMl

原标题：golang 系统设计字段命名类型选择最佳实践
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.lrdkoi.asia/blog/6612471.sHtMl

原标题：定时任务重复执行分布式锁
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://book.lrdkoi.asia/blog/8146899.sHtMl

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.lrdkoi.asia/blog/7908152.sHtMl

原标题：golang 静态文件服务搭建教程
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://book.lrdkoi.asia/blog/8033915.sHtMl

原标题：简易日志收集集中管理方案
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://book.lrdkoi.asia/blog/2308580.sHtMl

原标题：golang 系统设计数据库基准压测简单思路
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://book.lrdkoi.asia/blog/4336600.sHtMl

原标题：时间精度统一业务判断修复
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://book.lrdkoi.asia/blog/5366581.sHtMl

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://book.lrdkoi.asia/blog/6050999.sHtMl

原标题：golang 系统设计多租户数据隔离方案
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://book.lrdkoi.asia/blog/5365915.sHtMl

原标题：Architecture：API网关核心能力与组件拆分
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://book.lrdkoi.asia/blog/6473990.sHtMl


二、踩坑排错｜Troubleshooting
原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://book.lrdkoi.asia/blog/7435450.sHtMl

原标题：安全实践：最小权限原则数据库账号管控
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.lrdkoi.asia/blog/8848472.sHtMl

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.lrdkoi.asia/blog/2302299.sHtMl

原标题：入门实践：简易进度条CLI工具实现demo
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://book.lrdkoi.asia/blog/4944318.sHtMl

原标题：OOMKilled 容器被杀完整排查
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.lrdkoi.asia/blog/3993745.sHtMl

原标题：实战项目：GitHubAction自动测试构建实践
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://book.lrdkoi.asia/blog/9001726.sHtMl

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.lrdkoi.asia/blog/3975740.sHtMl

原标题：入门实践：Git分支创建切换合并完整演示
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.lrdkoi.asia/blog/8931640.sHtMl

原标题：golang prometheus 指标暴露实现
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://book.lrdkoi.asia/blog/6495109.sHtMl

原标题：golang html 模板渲染简单示例
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.lrdkoi.asia/blog/0478579.sHtMl

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://book.lrdkoi.asia/blog/1350872.sHtMl

原标题：方案设计：统一错误处理架构全链路方案
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://book.lrdkoi.asia/blog/2747124.sHtMl

原标题：golang 集成测试启动测试数据库
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://book.lrdkoi.asia/blog/8668625.sHtMl

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://book.lrdkoi.asia/blog/3276990.sHtMl

原标题：golang 系统设计缓存大 key 拆分优化实操
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.lrdkoi.asia/blog/2143393.sHtMl

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://book.lrdkoi.asia/blog/3882631.sHtMl

原标题：从零搭建本地开发环境完整教程
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.lrdkoi.asia/blog/8394353.sHtMl

原标题：golang 系统设计测试环境预发环境生产环境隔离
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.lrdkoi.asia/blog/4201432.sHtMl

原标题：golang 系统设计容量评估简单方法论
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.lrdkoi.asia/blog/9661491.sHtMl

原标题：服务器时钟同步任务错乱修复
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.lrdkoi.asia/blog/7124053.sHtMl

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.lrdkoi.asia/blog/6082403.sHtMl

原标题：前端工程化 webpack 打包优化
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.lrdkoi.asia/blog/4037493.sHtMl

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://book.lrdkoi.asia/blog/6485079.sHtMl

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://book.lrdkoi.asia/blog/9322494.sHtMl

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://book.lrdkoi.asia/blog/2988358.sHtMl

原标题：golang 系统设计联合索引设计避坑要点
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://book.lrdkoi.asia/blog/0684439.sHtMl

原标题：golang 大文件读取内存优化
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.lrdkoi.asia/blog/9742011.sHtMl

原标题：golang k8s 监控 prometheus 部署
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://book.lrdkoi.asia/blog/3393617.sHtMl

原标题：golang redis 布隆过滤器安装使用
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.lrdkoi.asia/blog/7091863.sHtMl

原标题：包管理器依赖缓存清理
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://book.lrdkoi.asia/blog/8515459.sHtMl

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://book.lrdkoi.asia/blog/3002346.sHtMl

原标题：golang excel 简单读写操作示例
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://book.lrdkoi.asia/blog/6360291.sHtMl

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.lrdkoi.asia/blog/1955236.sHtMl

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://book.lrdkoi.asia/blog/4281255.sHtMl

原标题：golang k8s rbac 权限控制配置示例
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.lrdkoi.asia/blog/9051472.sHtMl

原标题：方案对比：定时任务框架选型与架构对比
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.lrdkoi.asia/blog/4132971.sHtMl

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://book.lrdkoi.asia/blog/4422026.sHtMl

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.lrdkoi.asia/blog/5291898.sHtMl

原标题：新手向：开源项目fork与同步上游代码
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.lrdkoi.asia/blog/0860647.sHtMl

原标题：golang es 分页深分页性能优化
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.lrdkoi.asia/blog/7541236.sHtMl

三、实战开发｜Practice
原标题：golang mysql 时间类型选型避坑
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://book.lrdkoi.asia/blog/5518695.sHtMl

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.lrdkoi.asia/blog/8225467.sHtMl

原标题：快速入门日志打印与日志分级基础用法
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://book.lrdkoi.asia/blog/8257751.sHtMl

原标题：golang docker 部署 prometheus 整套
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.lrdkoi.asia/blog/5554154.sHtMl

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://book.lrdkoi.asia/blog/3442296.sHtMl

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.lrdkoi.asia/blog/6108536.sHtMl

原标题：Docker Compose 一键搭建本地栈
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://book.lrdkoi.asia/blog/6839407.sHtMl

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://book.lrdkoi.asia/blog/5757832.sHtMl

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://book.lrdkoi.asia/blog/3543211.sHtMl

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.lrdkoi.asia/blog/2067516.sHtMl

原标题：开发记录：接口请求日志记录完整中间件实现
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.lrdkoi.asia/blog/7215164.sHtMl

原标题：快速上手简易网关转发逻辑模拟
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.lrdkoi.asia/blog/6196399.sHtMl

原标题：Mock 接口服务快速搭建实操
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.lrdkoi.asia/blog/4659499.sHtMl

原标题：部署实践：服务器时间同步chrony配置
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.lrdkoi.asia/blog/3127389.sHtMl

原标题：前端 pdf 预览渲染方案对比
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.lrdkoi.asia/blog/7814754.sHtMl

原标题：设计思考：API网关和BFF职责边界划分
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://book.lrdkoi.asia/blog/3486757.sHtMl

原标题：程序预加载加快服务启动速度
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.lrdkoi.asia/blog/6143386.sHtMl

原标题：Architecture：大文件上传下载系统架构设计
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.lrdkoi.asia/blog/1798466.sHtMl

原标题：新手教程：Gittag版本标签打标签实操
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://book.lrdkoi.asia/blog/8385173.sHtMl

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.lrdkoi.asia/blog/0220230.sHtMl

原标题：用户敏感数据脱敏代码实现
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://book.lrdkoi.asia/blog/4841416.sHtMl

原标题：golang 系统设计 git 分支流程 gitflow 实操
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.lrdkoi.asia/blog/6493449.sHtMl

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.lrdkoi.asia/blog/5317492.sHtMl

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.lrdkoi.asia/blog/8827893.sHtMl

原标题：多环境配置中心灵活切换方案
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.lrdkoi.asia/blog/6182964.sHtMl

原标题：Practice：模拟第三方接口超时服务降级验证
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://book.lrdkoi.asia/blog/5286297.sHtMl

原标题：golang 系统设计 api 文档 swagger redoc 落地
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://book.lrdkoi.asia/blog/9006202.sHtMl

原标题：项目脚手架模板生成工具
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.lrdkoi.asia/blog/4821435.sHtMl

原标题：快速入门OpenAPI文档生成基础实践
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://book.lrdkoi.asia/blog/3839467.sHtMl

原标题：快速上手简易网关转发逻辑模拟
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.lrdkoi.asia/blog/1780851.sHtMl

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://book.lrdkoi.asia/blog/1612579.sHtMl

原标题：golang git 提交信息规范校验
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.lrdkoi.asia/blog/7517778.sHtMl

原标题：golang prometheus metrics 埋点开发
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://book.lrdkoi.asia/blog/7770835.sHtMl

原标题：超大数据集分页性能优化方案
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://book.lrdkoi.asia/blog/0541405.sHtMl

原标题：快速入门简单签名校验实现思路
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.lrdkoi.asia/blog/8328526.sHtMl

原标题：部署复盘：容器OOM问题完整排查流程
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://book.lrdkoi.asia/blog/7847350.sHtMl

原标题：Hands‑on：简易网关路由转发组件开发
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.lrdkoi.asia/blog/2191189.sHtMl

原标题：前端静态缓存更新生效处理
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.lrdkoi.asia/blog/5678498.sHtMl

原标题：开源项目构建失败排查步骤
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.lrdkoi.asia/blog/3532211.sHtMl

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://book.lrdkoi.asia/blog/5682579.sHtMl

四、架构设计｜Architecture
原标题：nodejs 单元测试 jest 实操教程
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://book.lrdkoi.asia/blog/9154350.sHtMl

原标题：golang 系统设计开发环境本地调试最佳实践
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.lrdkoi.asia/blog/0129544.sHtMl

原标题：项目实践：多环境配置管理组件设计与实现
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://book.lrdkoi.asia/blog/7122642.sHtMl

原标题：DevOps：WSL2生产环境使用风险提示
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.lrdkoi.asia/blog/6288643.sHtMl

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://book.lrdkoi.asia/blog/4231274.sHtMl

原标题：容器内存扩容 OOM 被杀死修复
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://book.lrdkoi.asia/blog/5095022.sHtMl

原标题：golang redis 分布式计数器开发
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://book.lrdkoi.asia/blog/5417347.sHtMl

原标题：Practice：批量异步任务处理系统设计实现
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://book.lrdkoi.asia/blog/9351972.sHtMl

原标题：实战：Nginx负载均衡多种策略配置实践
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://book.lrdkoi.asia/blog/4248566.sHtMl

原标题：设计思考：API网关和BFF职责边界划分
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.lrdkoi.asia/blog/8150973.sHtMl

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://book.lrdkoi.asia/blog/0190869.sHtMl

原标题：程序信号中断退出处理逻辑
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.lrdkoi.asia/blog/5622138.sHtMl

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://book.lrdkoi.asia/blog/5025168.sHtMl

原标题：Architecture：监控告警架构避免告警风暴设计
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.lrdkoi.asia/blog/5803963.sHtMl

原标题：Architecture：文件处理服务架构大文件内存规避
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.lrdkoi.asia/blog/4668098.sHtMl

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://book.lrdkoi.asia/blog/6895105.sHtMl

原标题：golang redis hyperloglog 基数统计
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://book.lrdkoi.asia/blog/1766552.sHtMl

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.lrdkoi.asia/blog/5377162.sHtMl

?

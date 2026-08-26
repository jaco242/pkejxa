最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.etuhdi.asia/arts/980971.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.etuhdi.asia/arts/453250.Doc

原标题：Architecture：大文件上传下载系统架构设计
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.etuhdi.asia/arts/133984.Doc

原标题：golang docker 私有仓库搭建使用
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.etuhdi.asia/arts/374111.Doc

原标题：操作系统内核版本适配服务
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.etuhdi.asia/arts/833952.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.etuhdi.asia/arts/566925.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.etuhdi.asia/arts/359407.Doc

原标题：容器内存扩容 OOM 被杀死修复
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.etuhdi.asia/arts/424918.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.etuhdi.asia/arts/947345.Doc

原标题：运维笔记：CI流水线缓存策略加速构建速度
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.etuhdi.asia/arts/673873.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.etuhdi.asia/arts/991731.Doc

原标题：golang es 聚合统计查询实现
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.etuhdi.asia/arts/042814.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.etuhdi.asia/arts/238376.Doc

原标题：数据库分表存储大表优化方案
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.etuhdi.asia/arts/589777.Doc

原标题：golang 系统设计多级缓存架构落地
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.etuhdi.asia/arts/942474.Doc

原标题：Practice：模拟主从延迟业务兼容方案实践
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.etuhdi.asia/arts/853522.Doc

原标题：golang redis stream 消息队列实践
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.etuhdi.asia/arts/049146.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.etuhdi.asia/arts/882111.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.etuhdi.asia/arts/890952.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.etuhdi.asia/arts/828163.Doc

原标题：架构复盘：多实例部署业务状态无状态改造
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.etuhdi.asia/arts/615543.Doc

原标题：nodejs redis 缓存业务实战
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.etuhdi.asia/arts/688772.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.etuhdi.asia/arts/947306.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.etuhdi.asia/arts/660008.Doc

原标题：数据库分表路由写入分片修正
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.etuhdi.asia/arts/128017.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.etuhdi.asia/arts/423991.Doc

原标题：golang redis 批量 pipeline 实践
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.etuhdi.asia/arts/371455.Doc

原标题：多实例部署 Session 共享方案
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.etuhdi.asia/arts/896147.Doc

原标题：golang k8s 监控 prometheus 部署
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.etuhdi.asia/arts/148714.Doc

原标题：容器资源限制防止宿主机过载
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.etuhdi.asia/arts/976293.Doc

原标题：golang 系统设计消息大小限制业务处理方案
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.etuhdi.asia/arts/826536.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.etuhdi.asia/arts/493574.Doc

原标题：复盘总结：技术选型对比文档模板实践
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.etuhdi.asia/arts/018751.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.etuhdi.asia/arts/353759.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.etuhdi.asia/arts/637668.Doc

原标题：线程调度优化减少上下文切换
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.etuhdi.asia/arts/129552.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.etuhdi.asia/arts/776849.Doc

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://wiki.etuhdi.asia/arts/456813.Doc

原标题：golang 系统设计内部服务契约测试简单思路
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.etuhdi.asia/arts/927800.Doc

原标题：golang 系统设计分布式事务业务选型决策思路
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.etuhdi.asia/arts/266171.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计 traceId 全链路透传完整方案
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.etuhdi.asia/arts/620763.Doc

原标题：实战：搭建日志收集分析简易完整演示环境
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.etuhdi.asia/arts/170959.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.etuhdi.asia/arts/045096.Doc

原标题：Hands‑on：简易验证码生成校验后端实践
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.etuhdi.asia/arts/657762.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.etuhdi.asia/arts/114555.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.etuhdi.asia/arts/853269.Doc

原标题：优化实践：多级缓存减少下游服务调用压力
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.etuhdi.asia/arts/915223.Doc

原标题：数据库读写分离性能优化
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.etuhdi.asia/arts/208777.Doc

原标题：前端图片懒加载性能优化
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.etuhdi.asia/arts/263398.Doc

原标题：Hands‑on：简易短链接服务完整开发实践
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.etuhdi.asia/arts/457446.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.etuhdi.asia/arts/808564.Doc

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.etuhdi.asia/arts/657232.Doc

原标题：golang 系统设计分布式会话方案对比
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.etuhdi.asia/arts/158805.Doc

原标题：TCP 长连接参数优化 TIME_WAIT
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.etuhdi.asia/arts/040627.Doc

原标题：新手教程：Gittag版本标签打标签实操
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.etuhdi.asia/arts/604756.Doc

原标题：DevOps：WSL2生产环境使用风险提示
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.etuhdi.asia/arts/213811.Doc

原标题：配置外部化线上部署防错误
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.etuhdi.asia/arts/931274.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.etuhdi.asia/arts/686830.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.etuhdi.asia/arts/299802.Doc

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.etuhdi.asia/arts/843377.Doc

原标题：RPC 接口字段增减兼容处理
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.etuhdi.asia/arts/915454.Doc

原标题：设计思考：业务系统中什么时候不要用微服务
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.etuhdi.asia/arts/714066.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.etuhdi.asia/arts/061494.Doc

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.etuhdi.asia/arts/357953.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.etuhdi.asia/arts/019020.Doc

原标题：前端静态缓存更新生效处理
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.etuhdi.asia/arts/273793.Doc

原标题：golang grpc protobuf 开发实操
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.etuhdi.asia/arts/442739.Doc

原标题：golang 系统设计消息大小限制业务处理方案
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.etuhdi.asia/arts/903684.Doc

原标题：golang 消息死信处理业务逻辑
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.etuhdi.asia/arts/990675.Doc

原标题：golang context 上下文传参讲解
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.etuhdi.asia/arts/866877.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.etuhdi.asia/arts/499698.Doc

原标题：golang 系统设计技术文档编写最佳实践
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.etuhdi.asia/arts/694648.Doc

原标题：golang 系统设计 webhook 回调处理架构
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.etuhdi.asia/arts/860703.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.etuhdi.asia/arts/796464.Doc

原标题：nodejs 流处理大文件不占内存
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.etuhdi.asia/arts/783944.Doc

原标题：golang 系统设计 git 钩子自动化校验实现
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://wiki.etuhdi.asia/arts/572788.Doc

原标题：golang 速率限制令牌桶实现
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.etuhdi.asia/arts/296688.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://wiki.etuhdi.asia/arts/026257.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.etuhdi.asia/arts/912307.Doc

原标题：golang 系统设计开源项目 release 发布流程
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.etuhdi.asia/arts/024078.Doc

三、实战开发｜Practice
原标题：磁盘 inode 耗尽文件创建失败
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.etuhdi.asia/arts/302708.Doc

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.etuhdi.asia/arts/597512.Doc

原标题：本地简易配置中心动态管理
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.etuhdi.asia/arts/964081.Doc

原标题：express 中间件开发业务实践
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.etuhdi.asia/arts/571858.Doc

原标题：nestjs 框架模块化项目搭建
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.etuhdi.asia/arts/375789.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.etuhdi.asia/arts/272764.Doc

原标题：开发记录：分布式锁超时业务安全处理实践
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.etuhdi.asia/arts/833289.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.etuhdi.asia/arts/596265.Doc

原标题：多套环境灵活切换配置方案
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.etuhdi.asia/arts/382849.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.etuhdi.asia/arts/409706.Doc

原标题：golang redis 位图用户签到统计
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.etuhdi.asia/arts/417161.Doc

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.etuhdi.asia/arts/235353.Doc

原标题：DevOps：容器健康探针livenessreadiness配置
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.etuhdi.asia/arts/193029.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.etuhdi.asia/arts/450818.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.etuhdi.asia/arts/433694.Doc

原标题：部署复盘：容器OOM问题完整排查流程
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://wiki.etuhdi.asia/arts/914134.Doc

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.etuhdi.asia/arts/946584.Doc

原标题：前端打包产物体积压缩优化
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.etuhdi.asia/arts/188456.Doc

原标题：golang 系统设计定时任务动态启停配置方案
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.etuhdi.asia/arts/309808.Doc

原标题：golang excel 简单读写操作示例
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.etuhdi.asia/arts/452874.Doc

原标题：数据库索引重建提升查询速度
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.etuhdi.asia/arts/607239.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.etuhdi.asia/arts/974339.Doc

原标题：多版本开发环境共存配置
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.etuhdi.asia/arts/015187.Doc

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.etuhdi.asia/arts/592873.Doc

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.etuhdi.asia/arts/671222.Doc

原标题：golang http 请求重试封装工具
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.etuhdi.asia/arts/412959.Doc

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.etuhdi.asia/arts/314188.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.etuhdi.asia/arts/933322.Doc

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.etuhdi.asia/arts/677096.Doc

原标题：数据库连接池参数调优
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.etuhdi.asia/arts/703641.Doc

原标题：数据库事务 ACID 原理讲解
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.etuhdi.asia/arts/648102.Doc

原标题：golang 系统设计本地缓存 redis 缓存多级组合
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.etuhdi.asia/arts/377334.Doc

原标题：golang redis 过期 key 监听业务
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.etuhdi.asia/arts/300216.Doc

原标题：Git 分支切换合并删除完整操作
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.etuhdi.asia/arts/647302.Doc

原标题：动态定时任务业务调度实现
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.etuhdi.asia/arts/049074.Doc

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.etuhdi.asia/arts/180673.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.etuhdi.asia/arts/725145.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.etuhdi.asia/arts/497363.Doc

原标题：Fork 开源项目同步上游代码
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.etuhdi.asia/arts/797996.Doc

原标题：踩坑记录：端口被占用导致服务启动失败
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.etuhdi.asia/arts/591030.Doc

四、架构设计｜Architecture
原标题：数据库排序规则统一结果一致
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.etuhdi.asia/arts/597470.Doc

原标题：WSL 搭建 Windows Linux 开发环境
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.etuhdi.asia/arts/055371.Doc

原标题：快速入门WebSocket，实现简易双向通信demo
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.etuhdi.asia/arts/458757.Doc

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.etuhdi.asia/arts/230931.Doc

原标题：排错：CI流水线构建失败，日志无明确报错
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.etuhdi.asia/arts/985779.Doc

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.etuhdi.asia/arts/822486.Doc

原标题：golang http 请求重试封装工具
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.etuhdi.asia/arts/168743.Doc

原标题：golang redis 五种数据结构实战
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.etuhdi.asia/arts/961605.Doc

原标题：golang 工具函数库封装思路
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.etuhdi.asia/arts/469226.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.etuhdi.asia/arts/448922.Doc

原标题：开发测试生产多环境配置区分
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.etuhdi.asia/arts/260511.Doc

原标题：OOMKilled 容器被杀完整排查
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.etuhdi.asia/arts/416892.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.etuhdi.asia/arts/601173.Doc

原标题：Practice：模拟热点key，验证缓存防护策略
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.etuhdi.asia/arts/063228.Doc

原标题：golang redis 发布订阅简单示例
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.etuhdi.asia/arts/173826.Doc

原标题：新手向：项目目录结构规范与含义解析
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.etuhdi.asia/arts/443955.Doc

原标题：安全复盘：Redis未授权访问漏洞防护
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.etuhdi.asia/arts/227544.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.etuhdi.asia/arts/979165.Doc

?

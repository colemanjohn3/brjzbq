最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计告警升级通知策略配置思路
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.o06ust.asia/arts/618929.Doc

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.o06ust.asia/arts/416696.Doc

原标题：golang kafka 批量发送消费优化
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.o06ust.asia/arts/227724.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.o06ust.asia/arts/031339.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.o06ust.asia/arts/082155.Doc

原标题：golang 系统设计大表加索引线上执行方案
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.o06ust.asia/arts/070626.Doc

原标题：echarts 大数据渲染性能调优
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.o06ust.asia/arts/997585.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://wiki.o06ust.asia/arts/783251.Doc

原标题：golang docker 多阶段构建 go 镜像
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.o06ust.asia/arts/280288.Doc

原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://wiki.o06ust.asia/arts/963289.Doc

原标题：golang 系统设计容器健康检查设计思路
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.o06ust.asia/arts/320137.Doc

原标题：排错：前端缓存304异常更新不及时
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.o06ust.asia/arts/045236.Doc

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.o06ust.asia/arts/816165.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.o06ust.asia/arts/932031.Doc

原标题：方案设计：接口版本管理架构向前兼容策略
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.o06ust.asia/arts/199225.Doc

原标题：golang mongodb 文档结构设计原则
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.o06ust.asia/arts/018125.Doc

原标题：golang docker compose 部署 minio
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.o06ust.asia/arts/948611.Doc

原标题：golang k8s 资源请求限制配置
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.o06ust.asia/arts/474509.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.o06ust.asia/arts/163228.Doc

原标题：文件监控服务自动重启开发
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.o06ust.asia/arts/581651.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.o06ust.asia/arts/975093.Doc

原标题：golang k8s job 一次性任务执行
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.o06ust.asia/arts/689158.Doc

原标题：Performance：数据库join优化，大表join规避
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.o06ust.asia/arts/919871.Doc

原标题：Redis 分布式锁高并发安全实现
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.o06ust.asia/arts/031749.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.o06ust.asia/arts/208748.Doc

原标题：golang 系统设计分布式锁选型对比
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.o06ust.asia/arts/756805.Doc

原标题：golang 系统设计大事务拆分实战思路
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.o06ust.asia/arts/059471.Doc

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://wiki.o06ust.asia/arts/577262.Doc

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.o06ust.asia/arts/862016.Doc

原标题：golang consul 服务发现简单示例
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.o06ust.asia/arts/865767.Doc

原标题：项目目录结构规范化最佳实践
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.o06ust.asia/arts/196284.Doc

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.o06ust.asia/arts/988762.Doc

原标题：golang redis 分布式锁 redisson 思路
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.o06ust.asia/arts/074729.Doc

原标题：快速上手搭建简易内网测试服务
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.o06ust.asia/arts/666988.Doc

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.o06ust.asia/arts/174626.Doc

原标题：golang mysql 时间类型选型避坑
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.o06ust.asia/arts/896587.Doc

原标题：golang 错误处理最佳实践汇总
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.o06ust.asia/arts/163133.Doc

原标题：vite 插件开发自定义构建逻辑
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.o06ust.asia/arts/034664.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.o06ust.asia/arts/002689.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.o06ust.asia/arts/263332.Doc


二、踩坑排错｜Troubleshooting
原标题：极简 API 网关路由转发实现
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.o06ust.asia/arts/418035.Doc

原标题：容器资源限制防止宿主机过载
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.o06ust.asia/arts/678555.Doc

原标题：golang http 代理客户端配置
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://wiki.o06ust.asia/arts/329241.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.o06ust.asia/arts/370522.Doc

原标题：数据库事务 ACID 原理讲解
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.o06ust.asia/arts/191003.Doc

原标题：golang context 上下文传参讲解
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.o06ust.asia/arts/685588.Doc

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.o06ust.asia/arts/004288.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.o06ust.asia/arts/748753.Doc

原标题：快速入门：API接口调试完整实操步骤
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.o06ust.asia/arts/130560.Doc

原标题：golang docker 容器资源限制设置
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.o06ust.asia/arts/268625.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.o06ust.asia/arts/518714.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.o06ust.asia/arts/053904.Doc

原标题：golang 系统设计监控告警阈值设置思路
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.o06ust.asia/arts/306511.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.o06ust.asia/arts/788110.Doc

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.o06ust.asia/arts/072076.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.o06ust.asia/arts/683085.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.o06ust.asia/arts/642628.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.o06ust.asia/arts/791095.Doc

原标题：golang 系统设计容器健康检查设计思路
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.o06ust.asia/arts/898751.Doc

原标题：WSL 内存上限限制防止资源耗尽
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.o06ust.asia/arts/511982.Doc

原标题：golang redis 发布订阅简单示例
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.o06ust.asia/arts/855031.Doc

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.o06ust.asia/arts/784085.Doc

原标题：golang 优雅处理 http 超时设置
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.o06ust.asia/arts/759969.Doc

原标题：golang gorm 批量插入性能调优
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.o06ust.asia/arts/278331.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.o06ust.asia/arts/714217.Doc

原标题：golang redis 事务 multi exec 使用
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.o06ust.asia/arts/619538.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.o06ust.asia/arts/208581.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.o06ust.asia/arts/985390.Doc

原标题：数据库事务 ACID 原理讲解
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.o06ust.asia/arts/493008.Doc

原标题：多套环境灵活切换配置方案
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.o06ust.asia/arts/781380.Doc

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.o06ust.asia/arts/783353.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.o06ust.asia/arts/532338.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.o06ust.asia/arts/966093.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.o06ust.asia/arts/804391.Doc

原标题：限流窗口绕过漏洞修复方案
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.o06ust.asia/arts/411352.Doc

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.o06ust.asia/arts/481922.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.o06ust.asia/arts/041509.Doc

原标题：数据库 utf8mb4 支持 emoji 存储
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.o06ust.asia/arts/033720.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.o06ust.asia/arts/328911.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.o06ust.asia/arts/019979.Doc

三、实战开发｜Practice
原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.o06ust.asia/arts/920584.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.o06ust.asia/arts/682295.Doc

原标题：Practice：实现接口防重提交组件实践
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.o06ust.asia/arts/456976.Doc

原标题：内存广播本地进程消息通知
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.o06ust.asia/arts/486874.Doc

原标题：golang es 分词器选型业务适配
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.o06ust.asia/arts/504756.Doc

原标题：css 动画性能优化 GPU 加速
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://wiki.o06ust.asia/arts/001363.Doc

原标题：golang redis lua 脚本原子操作
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.o06ust.asia/arts/863222.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.o06ust.asia/arts/839713.Doc

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.o06ust.asia/arts/970222.Doc

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.o06ust.asia/arts/571682.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.o06ust.asia/arts/729678.Doc

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.o06ust.asia/arts/248106.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.o06ust.asia/arts/429837.Doc

原标题：vue3 组合式 API 业务开发实战
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.o06ust.asia/arts/229989.Doc

原标题：golang mysql 分表 id 路由逻辑
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.o06ust.asia/arts/244941.Doc

原标题：安全复盘：Redis未授权访问漏洞防护
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.o06ust.asia/arts/896598.Doc

原标题：前后端会话登录状态持久化
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.o06ust.asia/arts/449028.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.o06ust.asia/arts/235770.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.o06ust.asia/arts/045804.Doc

原标题：golang gorm ORM 数据库操作
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.o06ust.asia/arts/667862.Doc

原标题：零基础理解依赖管理与包管理器
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.o06ust.asia/arts/312910.Doc

原标题：磁盘占满服务不可用清理方案
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.o06ust.asia/arts/683625.Doc

原标题：安全复盘：业务登录暴力破解防护完整方案
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.o06ust.asia/arts/129292.Doc

原标题：Docker 容器入门镜像实操教程
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.o06ust.asia/arts/526558.Doc

原标题：Nginx 丢失请求头配置修正
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.o06ust.asia/arts/015196.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.o06ust.asia/arts/426112.Doc

原标题：golang http 代理客户端配置
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.o06ust.asia/arts/210232.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.o06ust.asia/arts/578739.Doc

原标题：golang 容器健康检查接口开发
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.o06ust.asia/arts/547366.Doc

原标题：golang 系统设计灰度发布流量切分实现
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.o06ust.asia/arts/364076.Doc

原标题：golang git 提交信息规范校验
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.o06ust.asia/arts/456851.Doc

原标题：项目实践：消息队列消息确认机制业务实践
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.o06ust.asia/arts/148079.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.o06ust.asia/arts/908068.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.o06ust.asia/arts/148854.Doc

原标题：DevOps：日志标准输出容器日志收集方案
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.o06ust.asia/arts/744363.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.o06ust.asia/arts/765187.Doc

原标题：golang docker 多阶段构建 go 镜像
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.o06ust.asia/arts/188293.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.o06ust.asia/arts/601817.Doc

原标题：Shell 运维脚本服务器效率提升
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.o06ust.asia/arts/330940.Doc

原标题：配置与镜像分离防止信息泄露
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.o06ust.asia/arts/988346.Doc

四、架构设计｜Architecture
原标题：业务错误码完整落地实践
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.o06ust.asia/arts/220874.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.o06ust.asia/arts/897059.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.o06ust.asia/arts/501899.Doc

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.o06ust.asia/arts/534583.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://wiki.o06ust.asia/arts/422485.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.o06ust.asia/arts/153553.Doc

原标题：golang kafka 消费者组原理讲解
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.o06ust.asia/arts/314041.Doc

原标题：golang http 请求重试封装工具
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.o06ust.asia/arts/715281.Doc

原标题：CI 流水线超时时间延长配置
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.o06ust.asia/arts/514900.Doc

原标题：实战：基于DockerCompose搭建本地开发栈
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.o06ust.asia/arts/093857.Doc

原标题：实战：对象存储断点续传下载实践
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://wiki.o06ust.asia/arts/567998.Doc

原标题：集成测试业务流程编写示例
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.o06ust.asia/arts/904446.Doc

原标题：快速入门YAML配置文件语法与示例
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.o06ust.asia/arts/317873.Doc

原标题：golang 系统设计 api 文档 swagger redoc 落地
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.o06ust.asia/arts/059109.Doc

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.o06ust.asia/arts/933200.Doc

原标题：Security：Docker镜像安全扫描漏洞修复
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.o06ust.asia/arts/489114.Doc

原标题：golang gorm 批量插入性能调优
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.o06ust.asia/arts/245098.Doc

原标题：golang excel 简单读写操作示例
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.o06ust.asia/arts/241760.Doc

?

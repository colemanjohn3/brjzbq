最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.etuhdi.asia/arts/222214.Doc

原标题：golang 空接口 interface 使用技巧
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.etuhdi.asia/arts/336121.Doc

原标题：golang 系统设计故障演练简单思路
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.etuhdi.asia/arts/235406.Doc

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.etuhdi.asia/arts/970411.Doc

原标题：实践：前后端分离项目登录状态保持完整方案
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.etuhdi.asia/arts/185280.Doc

原标题：SSH 密钥配置 GitHub 免密登录
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.etuhdi.asia/arts/311102.Doc

原标题：从零搭建简单Mock接口服务
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.etuhdi.asia/arts/458070.Doc

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.etuhdi.asia/arts/533083.Doc

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://wiki.etuhdi.asia/arts/750630.Doc

原标题：golang 结构体 json 序列化坑点
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.etuhdi.asia/arts/204952.Doc

原标题：Mock 接口服务快速搭建实操
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.etuhdi.asia/arts/425299.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.etuhdi.asia/arts/825229.Doc

原标题：golang 系统设计架构图绘制规范简单建议
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.etuhdi.asia/arts/940511.Doc

原标题：Practice：实现简单信号处理优雅停机实践
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.etuhdi.asia/arts/947827.Doc

原标题：golang docker 镜像体积优化技巧
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.etuhdi.asia/arts/342977.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.etuhdi.asia/arts/484403.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.etuhdi.asia/arts/962819.Doc

原标题：实战项目：WSL开发环境完整配置实操
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.etuhdi.asia/arts/140723.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.etuhdi.asia/arts/931163.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.etuhdi.asia/arts/433739.Doc

原标题：项目脚手架模板生成工具
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.etuhdi.asia/arts/387830.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.etuhdi.asia/arts/937133.Doc

原标题：golang 分页查询封装通用工具
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.etuhdi.asia/arts/310521.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.etuhdi.asia/arts/307794.Doc

原标题：程序信号中断退出处理逻辑
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://wiki.etuhdi.asia/arts/604293.Doc

原标题：golang redis 缓存更新策略讲解
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.etuhdi.asia/arts/167005.Doc

原标题：nodejs 流处理大文件不占内存
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.etuhdi.asia/arts/832040.Doc

原标题：时间精度统一业务判断修复
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.etuhdi.asia/arts/014139.Doc

原标题：golang 系统设计序列化性能选型对比
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.etuhdi.asia/arts/132547.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.etuhdi.asia/arts/407592.Doc

原标题：golang 优雅停机服务关闭实现
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.etuhdi.asia/arts/900144.Doc

原标题：方案设计：分布式锁失效风险架构层面规避
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://wiki.etuhdi.asia/arts/370725.Doc

原标题：golang 系统设计短信发送限流降级
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.etuhdi.asia/arts/182345.Doc

原标题：golang viper 配置热更新实操
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.etuhdi.asia/arts/936958.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.etuhdi.asia/arts/455907.Doc

原标题：axios 二次封装请求拦截处理
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.etuhdi.asia/arts/856432.Doc

原标题：WSL 搭建 Windows Linux 开发环境
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.etuhdi.asia/arts/192398.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.etuhdi.asia/arts/643285.Doc

原标题：Practice：模拟主从延迟业务兼容方案实践
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.etuhdi.asia/arts/774352.Doc

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.etuhdi.asia/arts/674061.Doc


二、踩坑排错｜Troubleshooting
原标题：安全实践：接口错误信息不要暴露内部细节
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.etuhdi.asia/arts/054332.Doc

原标题：日志敏感信息脱敏泄露防护
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.etuhdi.asia/arts/428699.Doc

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.etuhdi.asia/arts/427058.Doc

原标题：nodejs 接口限流防刷代码实现
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.etuhdi.asia/arts/933801.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.etuhdi.asia/arts/043281.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://wiki.etuhdi.asia/arts/762693.Doc

原标题：golang k8s configmap secret 配置
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.etuhdi.asia/arts/615887.Doc

原标题：部署实践：DockerCompose管理多服务环境
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.etuhdi.asia/arts/273716.Doc

原标题：文件监控服务自动重启开发
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.etuhdi.asia/arts/539926.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.etuhdi.asia/arts/122610.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.etuhdi.asia/arts/858810.Doc

原标题：多实例部署 Session 共享方案
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.etuhdi.asia/arts/792849.Doc

原标题：从零学习基础的接口请求与参数处理
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://wiki.etuhdi.asia/arts/809178.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.etuhdi.asia/arts/855107.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.etuhdi.asia/arts/560225.Doc

原标题：Practice：模拟第三方接口超时服务降级验证
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.etuhdi.asia/arts/785878.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.etuhdi.asia/arts/077635.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.etuhdi.asia/arts/447149.Doc

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.etuhdi.asia/arts/126980.Doc

原标题：golang html 模板渲染简单示例
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.etuhdi.asia/arts/125035.Doc

原标题：golang es 查询语句 DSL 实操
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.etuhdi.asia/arts/715849.Doc

原标题：设计思考：业务系统中什么时候不要用微服务
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.etuhdi.asia/arts/299886.Doc

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.etuhdi.asia/arts/651711.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.etuhdi.asia/arts/195075.Doc

原标题：webpack chunk 分包策略详解
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.etuhdi.asia/arts/107072.Doc

原标题：数据库排序规则统一结果一致
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.etuhdi.asia/arts/567361.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.etuhdi.asia/arts/040417.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.etuhdi.asia/arts/236301.Doc

原标题：入门实战：搭建简易静态网页项目
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.etuhdi.asia/arts/933608.Doc

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.etuhdi.asia/arts/190497.Doc

原标题：golang rsa 非对称加密签名验签
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.etuhdi.asia/arts/854951.Doc

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.etuhdi.asia/arts/258368.Doc

原标题：版本升级服务启动失败处理
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.etuhdi.asia/arts/829335.Doc

原标题：golang gorm 批量插入性能调优
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.etuhdi.asia/arts/136071.Doc

原标题：批量异步处理系统业务落地
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.etuhdi.asia/arts/176005.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.etuhdi.asia/arts/570028.Doc

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.etuhdi.asia/arts/162185.Doc

原标题：golang mysql 存储过程简单使用
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.etuhdi.asia/arts/269982.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.etuhdi.asia/arts/004991.Doc

原标题：golang kafka offset 提交策略
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.etuhdi.asia/arts/271925.Doc

三、实战开发｜Practice
原标题：golang docker compose 本地开发最佳实践
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.etuhdi.asia/arts/198447.Doc

原标题：nodejs 消息队列消费服务开发
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.etuhdi.asia/arts/933915.Doc

原标题：golang k8s configmap secret 配置
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.etuhdi.asia/arts/236322.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.etuhdi.asia/arts/063759.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.etuhdi.asia/arts/424914.Doc

原标题：文件描述符优化进程卡死修复
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.etuhdi.asia/arts/232647.Doc

原标题：golang 系统设计埋点数据上报方案
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.etuhdi.asia/arts/581911.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.etuhdi.asia/arts/152168.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://wiki.etuhdi.asia/arts/424716.Doc

原标题：golang 跨域处理中间件编写
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.etuhdi.asia/arts/300302.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://wiki.etuhdi.asia/arts/907523.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.etuhdi.asia/arts/228112.Doc

原标题：Dockerfile 编写容器打包实战
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.etuhdi.asia/arts/014705.Doc

原标题：Hands‑on：简易图片压缩处理服务demo
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.etuhdi.asia/arts/000645.Doc

原标题：golang redis 批量 pipeline 实践
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.etuhdi.asia/arts/041756.Doc

原标题：运维笔记：系统文件句柄数调整生产配置
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.etuhdi.asia/arts/451271.Doc

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.etuhdi.asia/arts/080368.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.etuhdi.asia/arts/414337.Doc

原标题：排错：前端缓存304异常更新不及时
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.etuhdi.asia/arts/350583.Doc

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.etuhdi.asia/arts/385909.Doc

原标题：对象存储上传下载权限实操
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.etuhdi.asia/arts/598414.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.etuhdi.asia/arts/869377.Doc

原标题：golang 系统设计数据库死锁分析规避
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.etuhdi.asia/arts/485528.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.etuhdi.asia/arts/552628.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.etuhdi.asia/arts/014585.Doc

原标题：包管理器依赖缓存清理
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.etuhdi.asia/arts/191143.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.etuhdi.asia/arts/196436.Doc

原标题：Git 仓库瘦身加快克隆下载速度
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.etuhdi.asia/arts/087755.Doc

原标题：golang 项目环境变量加载方案
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.etuhdi.asia/arts/861215.Doc

原标题：Practice：实现异步任务结果查询回调实践
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.etuhdi.asia/arts/300780.Doc

原标题：Practice：实现请求body重复读取中间件实践
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.etuhdi.asia/arts/866151.Doc

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.etuhdi.asia/arts/381214.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.etuhdi.asia/arts/373400.Doc

原标题：安全复盘：业务登录暴力破解防护完整方案
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.etuhdi.asia/arts/610128.Doc

原标题：golang docker 基础命令实操汇总
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.etuhdi.asia/arts/721951.Doc

原标题：golang 系统设计延迟消息实现几种方案对比
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.etuhdi.asia/arts/725636.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.etuhdi.asia/arts/937409.Doc

原标题：RPC 接口字段增减兼容处理
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.etuhdi.asia/arts/910160.Doc

原标题：排错：CI流水线构建失败，日志无明确报错
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.etuhdi.asia/arts/803655.Doc

原标题：golang 集成测试启动测试数据库
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.etuhdi.asia/arts/603472.Doc

四、架构设计｜Architecture
原标题：实战项目：GitSubmodule管理多仓库实践
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.etuhdi.asia/arts/193124.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.etuhdi.asia/arts/949657.Doc

原标题：跨库查询性能优化处理
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://wiki.etuhdi.asia/arts/373616.Doc

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.etuhdi.asia/arts/195265.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.etuhdi.asia/arts/899635.Doc

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.etuhdi.asia/arts/291399.Doc

原标题：Performance：大事务拆分，减少锁持有时间
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.etuhdi.asia/arts/094336.Doc

原标题：新手教程：gitstash暂存工作区变更实操
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.etuhdi.asia/arts/206108.Doc

原标题：golang 系统设计分库分表中间件思路
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.etuhdi.asia/arts/970186.Doc

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.etuhdi.asia/arts/047179.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.etuhdi.asia/arts/292381.Doc

原标题：golang jwt 鉴权中间件完整示例
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.etuhdi.asia/arts/787623.Doc

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.etuhdi.asia/arts/458550.Doc

原标题：golang k8s pod 优雅关闭流程讲解
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.etuhdi.asia/arts/863466.Doc

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.etuhdi.asia/arts/720795.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.etuhdi.asia/arts/048105.Doc

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.etuhdi.asia/arts/644427.Doc

原标题：golang 链路 traceId 透传中间件
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.etuhdi.asia/arts/930587.Doc

?

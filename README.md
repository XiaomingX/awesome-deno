# 精选 Deno 资源集合

Deno 是一个安全的 JavaScript/TypeScript 运行时，以下是经过筛选的优质资源，帮助你更好地学习和使用 Deno。


## 官方文档与核心资源
这是学习 Deno 的基础，包含官方指南、API 参考和标准库。
- [Deno 官方网站](https://deno.land) - 主页，可获取最新版本和核心信息
- [Deno 手册](https://deno.land/manual) - 详细教程，从入门到进阶的完整指南
- [Deno API 参考](https://deno.land/api) - 所有内置 API 的详细说明
- [Deno 标准模块](https://deno.land/std) - 官方维护的标准库，包含文件操作、HTTP 等基础功能


## 在线体验平台
无需本地安装，直接在浏览器中尝试 Deno：
- [Deno Playground](https://play.deno.com) - 官方在线编辑器，支持实时运行代码
- [CodeSandbox](https://codesandbox.io/s/y56n2) - 第三方平台的 Deno 环境，适合快速原型开发


## 核心模块与框架
按用途分类的精选工具，涵盖开发中的常见需求。

### Web 框架
- [oak](https://github.com/oakserver/oak) - Deno 最流行的 Web 框架，类似 Express，支持中间件机制，适合构建 API 和 Web 应用
- [hono](https://github.com/honojs/hono) - 超轻量高速框架，不仅支持 Deno，还能运行在 Cloudflare Workers 等环境，适合构建高性能服务
- [fresh](https://github.com/denoland/fresh) - Deno 官方推出的全栈框架，主打服务端渲染（SSR）和零运行时 JavaScript，性能优异
- [alosaur](https://github.com/alosaur/alosaur) - 类似 Nest.js 的企业级框架，支持装饰器语法，适合大型项目架构

### 数据库工具
- [denodb](https://github.com/eveningkid/denodb) - 多数据库 ORM，支持 MySQL、PostgreSQL、SQLite 等，简化数据操作
- [deno_mongo](https://github.com/denodrivers/deno_mongo) - MongoDB 官方兼容驱动，原生支持 Deno 的异步操作
- [deno_mysql](https://github.com/denodrivers/mysql) - 轻量的 MySQL 驱动，适合直接操作 MySQL 数据库

### 身份验证与安全
- [djwt](https://github.com/timonson/djwt) - 生成和验证 JSON Web Token（JWT）的工具，常用于用户身份验证
- [deno_passport](https://github.com/denosaurs/passport) - 类似 Node.js Passport 的认证中间件，支持多种登录方式

### 开发工具
- [vscode-deno](https://github.com/denoland/vscode_deno) - VS Code 官方插件，提供语法高亮、类型检查等功能
- [denon](https://github.com/denosaurs/denon) - 类似 nodemon 的文件监听工具，代码变动时自动重启程序，提升开发效率
- [udd](https://github.com/hayd/deno-udd) - 自动更新依赖的工具，一键升级导入的模块到最新版本
- [cliffy](https://github.com/c4spar/deno-cliffy) - 命令行工具开发框架，支持生成命令行交互、参数解析等

### 实用工具
- [deno-dotenv](https://github.com/pietvanzoen/deno-dotenv) - 加载 `.env` 文件中的环境变量，方便配置管理
- [valibot](https://github.com/fabian-hiller/valibot) - 轻量的数据验证库，适合处理 API 输入校验
- [zod](https://github.com/colinhacks/zod) - 另一个强大的数据验证工具，支持 TypeScript 类型推导

### 静态网站生成
- [lume](https://github.com/lumeland/lume) - 简单灵活的静态网站生成器，类似 Jekyll，支持多种模板语言


## 测试工具
- [deno-puppeteer](https://github.com/lucacasonato/deno-puppeteer) - 控制 Chrome 浏览器的工具，用于端到端（E2E）测试
- [expect](https://github.com/allain/expect) - 类似 Jest 的断言库，简化测试用例编写
- [deno-testify](https://github.com/denoland/testify) - 官方推荐的测试辅助工具，提供更丰富的测试功能


## 学习资源
- [Deno 官方博客](https://deno.com/blog) - 发布新版本特性、最佳实践等官方内容
- [Deno 中文社区](https://deno.js.cn) - 中文教程、文章和社区讨论
- [Deno 实战课程](https://egghead.io/search?q=deno) - Egghead 上的视频教程，适合边学边练


## 实际案例
- [Deno Showcase](https://deno.land/showcase) - 官方展示的基于 Deno 开发的真实项目，包括网站、工具等
- [Supabase CLI](https://github.com/supabase/cli) - 知名后端即服务（BaaS）平台 Supabase 的 CLI 工具，基于 Deno 开发


以上资源均为当前（2025 年）Deno 生态中活跃且实用的项目，可根据需求选择使用。随着 Deno 的发展，建议定期查看官方资源获取最新信息。

```markdown
hugo -h
hugo 是主要命令，用于构建您的 Hugo 网站。

Hugo 是一个快速且灵活的静态网站生成器，
由 spf13 和朋友们用 Go 语言开发。

完整文档请访问 https://gohugo.io/。

用法：
  hugo [flags]
  hugo [command]

可用命令：
  completion  为指定的 shell 生成自动补全脚本
  config      打印网站配置
  convert     转换内容为不同格式
  deploy      部署网站到云提供商
  env         打印 Hugo 版本和环境信息
  gen         多个有用生成器的集合
  help        获取关于任意命令的帮助
  import      从其他平台导入网站
  list        列出各种类型的内容
  mod         各种 Hugo 模块助手
  new         为网站创建新内容
  server      高性能网络服务器
  version     打印 Hugo 版本和环境信息

标志：
  -b, --baseURL string             主机名（及路径），例如 https://spf13.com/
  -D, --buildDrafts                包括标记为草稿的内容
  -E, --buildExpired               包括过期内容
  -F, --buildFuture                包括将来发布的内容
      --cacheDir string            缓存目录的文件系统路径
      --cleanDestinationDir        移除目标目录中不在静态目录中的文件
      --clock string               设置 Hugo 使用的时钟，例如 --clock 2021-11-06T22:30:00.00+09:00
      --config string              配置文件（默认是 hugo.yaml|json|toml）
      --configDir string           配置目录（默认 "config"）
  -c, --contentDir string          内容目录的文件系统路径
      --debug                      调试输出
  -d, --destination string         写入文件的目标目录
      --disableKinds strings       禁用不同类型的页面（首页、RSS 等）
      --enableGitInfo              添加 Git 修订版、日期、作者和 CODEOWNERS 信息到页面
  -e, --environment string         构建环境
      --forceSyncStatic            静态文件更改时复制所有文件
      --gc                         启用以在构建后运行一些清理任务（移除未使用的缓存文件）
  -h, --help                       Hugo 帮助
      --ignoreCache                忽略缓存目录
      --ignoreVendorPaths string   忽略匹配给定 Glob 模式的模块路径中的任何 _vendor
  -l, --layoutDir string           布局目录的文件系统路径
      --logLevel string            日志级别（debug|info|warn|error）
      --minify                     压缩任何支持的输出格式（HTML、XML 等）
      --noBuildLock                不创建 .hugo_build.lock 文件
      --noChmod                    不同步文件的权限模式
      --noTimes                    不同步文件的修改时间
      --panicOnWarning             第一次警告日志时中断
      --poll string                设置轮询间隔，例如 --poll 700ms，以使用基于轮询的方法监视文件系统更改
      --printI18nWarnings          打印缺少的翻译
      --printMemoryUsage           定期打印内存使用情况
      --printPathWarnings          打印重复目标路径的警告等
      --printUnusedTemplates       打印未使用的模板警告
      --quiet                      静默模式构建
      --renderSegments strings     命名要渲染的段（在段配置中配置）
  -M, --renderToMemory             渲染到内存（主要用于运行服务器时）
  -s, --source string              读取文件的源目录
      --templateMetrics            显示模板执行的指标
      --templateMetricsHints       与 --templateMetrics 结合使用时计算一些改进提示
  -t, --theme strings              使用的主题（位于 /themes/THEMENAME/）
      --themesDir string           主题目录的文件系统路径
      --trace file                 将跟踪写入文件（一般不使用）
  -v, --verbose                    详细输出
  -w, --watch                      监视文件系统更改并根据需要重新创建

使用 "hugo [command] --help" 获取关于某命令的更多信息。
```


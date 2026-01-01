每 45 分钟运行一次 (Koyeb 1小时无流量休眠，45分钟是安全范围)

在 GitHub 项目的 Settings > Secrets and variables > Actions 中添加一个名为 KOYEB_URL 的变量，例如https://你的应用名.koyeb.app/

如何确认是否生效？
提交代码并推送到 GitHub 后，点击仓库上方的 Actions 选项卡。
你会看到 "Koyeb Keep Alive" 工作流。
你可以点击 Run workflow 手动测试一次，如果显示绿色打钩，说明 curl 成功访问了你的应用。

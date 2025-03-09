
🔧 技术实现：
- 通过修改注册表项 `HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon`
- 自动请求管理员权限
- BAT版本使用批处理命令实现，VBS版本提供GUI交互

### 安装教程
1. 点击 [Releases](https://github.com/ChitandaEur/Manage_Auto_AdminLogon/releases/) 下载最新版
2. 将Microsoft账户登陆切换为本地账户登录（若已经是本地账户登录，则可跳过该步骤）

        设置-账户-你的信息

        改为本地账户登录，之后按照提示操作即可
3. 运行脚本时选择操作：
   - `1` 开启自动登录：需输入本地用户名和密码
   - `2` 关闭自动登录
   - `3` 退出程序
4. 重启计算机生效

> 📌 免责声明：本工具仅用于技术研究，使用者需自行承担相关风险
⚠️ 本工具仅用于技术研究目的，使用者需知：
1. 自动登录功能会明文存储密码在注册表中
2. 不建议在多人共用或公共设备上使用
3. 使用本脚本造成的数据/安全问题作者不承担责任

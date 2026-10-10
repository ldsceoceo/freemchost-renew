

## 🔐 Secrets 配置说明

| 名称 | 是否必填 | 说明 | 示例 |
|---|---|---|---|
| `FREE_EMAIL` | ✅ 必需*1 | 账号邮箱（与密码配对提供时，优先自动登录） | `your@email.com` |
| `FREE_PASSWORD` | ✅ 必需*1 | 账号密码 | `***` |
| `SERVER_PAGE_URL` | ❌ 可选 | 服务器管理页完整 URL，可填多个（换行/逗号分隔） | `https://freemchost.com/app/servers/YOUR_SERVER_ID` |
| `SERVER_ID` | ❌ 可选 | 仅填写服务器 ID（UUID），自动拼接为完整路径；多个用换行/逗号分隔 | `YOUR_SERVER_ID` |
| `AUTH_STATE` | ❌ 可选 | **cookie
| `GH_TOKEN` | ❌ 可选 | GitHub Personal Access Token（classic），用于回写 `AUTH_STATE` 等 Secret | `ghp_xxx` |
| `TG_BOT_TOKEN` | ❌ 可选 | Telegram Bot Token | `123456:AAA-xxx` |
| `TG_CHAT_ID` | ❌ 可选 | 接收通知的 Chat ID（频道/群组/私聊） | `123456789` |
| `NODE_LINK` | ❌ 可选 | sing-box 节点链接（代理出网，降低封禁风险） | `vless://...` / `hy2://...` / `vmess://...` |
| `PROXY_URL` | ❌ 可选 | 直接指定代理地址（http/socks5 均可），优先级高于 sing-box | `http://127.0.0.1:1080` |



## ⚠️ 免责声明

- 本程序仅供学习与研究，非盈利目的。
- 使用者应遵守所在国家/地区的法律法规及服务商条款。
- 作者不承担因滥用导致的任何后果责任。

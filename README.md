# Bright Data Web Unlocker Python 项目

[![Bright Data 推广](https://github.com/bright-cn/LinkedIn-Scraper/raw/main/Proxies%20and%20scrapers%20GitHub%20bonus%20banner.png)](https://www.bright.cn/)

<a href="https://githubbox.com/bright-cn/bright-data-web-unlocker-python-project?file=index.py" target="_blank">在 CodeSandbox 中打开</a>，使用 GitHub 登录，然后 fork 该仓库以开始修改。

## Bright Data Web Unlocker API 示例

本项目演示如何使用 [Bright Data 的 Web Unlocker API](https://www.bright.cn/products/web-unlocker) 通过 [Bright Data Web Unlocker API](https://www.bright.cn/products/web-unlocker) 访问网站。

## 概览

该脚本通过使用 Bright Data 的 Web Unlocker，帮助你在访问具有反爬虫保护或包含验证码的网站时自动绕过这些障碍。

### 直接配置

1. 将 `BRIGHT_DATA_API_TOKEN` 替换为你的实际 API 令牌
2. 将 `web_unlocker1` 替换为你的 Zone 名称
3. 将 `https://geo.brdtest.com/welcome.txt` 替换为你的目标 URL

## 运行示例

1. 确认已配置好 `API token` 和 `zone`
2. 在终端运行 `python index.py`
3. 在控制台查看输出结果

## 工作原理

1. 脚本向 Bright Data 的 Unlocker API 端点发送一个 POST 请求
2. 请求包含你的认证令牌与目标 URL
3. Bright Data 的 Web Unlocker 访问目标 URL
4. 响应返回到你的脚本，并在控制台展示

## 故障排除

如果遇到错误：

- 确认你的 API 令牌正确无误
- 检查 Zone 名称是否有效
- 确保目标 URL 格式正确

## 修改示例

若要请求不同的 URL：
1. 更新 CONFIG 对象中的 `targetUrl`
2. 重新运行脚本

## 更多资源

- [Bright Data Web Unlocker API](https://docs.brightdata.com/scraping-automation/web-unlocker/introduction)
- [获取 API Token](https://docs.brightdata.com/general/account/api-token)
- [管理 Zones](https://www.bright.cn/cp/zones)

注意：这是一个用于学习的示例实现。在生产环境中，请考虑增加更完善的错误处理、日志记录与安全措施。

<!--
  Domain Name API (domainreseller): ICANN-accredited domain registrar founded by Atak Domain.
  Official registrar modules, SSL & reseller hosting modules and API libraries.
  Website: https://www.domainnameapi.com
  Every animation on this page is a hand-made SVG in ./assets. No external widgets, no trackers.
-->

<p align="center">
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-TR.md"><img src="./assets/lang-tr.svg" height="38" alt="Türkçe"></a>
  <a href="https://github.com/domainreseller"><img src="./assets/lang-en.svg" height="38" alt="English"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-DE.md"><img src="./assets/lang-de.svg" height="38" alt="Deutsch"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-SA.md"><img src="./assets/lang-sa.svg" height="38" alt="العربية"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-NL.md"><img src="./assets/lang-nl.svg" height="38" alt="Nederlands"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-AZ.md"><img src="./assets/lang-az.svg" height="38" alt="Azərbaycanca"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-CN.md"><img src="./assets/lang-cn-on.svg" height="38" alt="中文"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-FR.md"><img src="./assets/lang-fr.svg" height="38" alt="Français"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-IT.md"><img src="./assets/lang-it.svg" height="38" alt="Italiano"></a>
</p>

<a href="https://www.domainnameapi.com/zh/yuming-zhuce"><img src="./assets/hero.svg" width="1200" alt="Domain Name API：成为域名代理商。借助 REST API 以及适用于 WHMCS、WiseCP、Blesta 等系统的现成模块，以您自己的品牌销售 830+ 种域名后缀。"></a>

<h1 align="center">域名代理 API 与模块</h1>

<p align="center">
  <b>Domain Name API</b> 是由 <a href="https://www.atakdomain.com">Atak Domain</a> 创立的 ICANN 认证域名注册商及<b>域名代理（domain reseller）</b>计划。加入<a href="https://www.domainnameapi.com/zh/yuming-zhuce">来自 200+ 个国家的 40,000+ 名域名代理商</a>，以您自己的品牌销售 830+ 种域名后缀，并通过我们的<a href="https://www.domainnameapi.com/zh/domain-api-jicheng">域名代理 API</a>或下方适用于 WHMCS、WiseCP、Blesta、HostBill、ClientExec、FOSSBilling 和 HostFact 的现成模块，自动完成域名注册、转移和续费。
</p>

<p align="center">
  <a href="https://github.com/domainreseller/cli"><img src="./assets/cli-ribbon.svg" width="760" alt="全新推出：dna，Domain Name API 的命令行工具与 MCP 服务器。在终端、Claude Code、Cursor 和 Codex 中管理域名。"></a>
</p>

<img src="./assets/stats.svg" width="1200" alt="830+ 种域名后缀、40,000+ 名活跃域名代理商、200+ 个国家、20+ 年行业经验。">

<img src="./assets/tlds.svg" width="1200" alt="您可以销售的 830+ 种域名后缀中的一部分：.com、.net、.org、.com.tr、.xyz、.shop 等。">

## <img src="./assets/h-cli.svg" width="30" height="30" alt=""> dna CLI：面向 AI 智能体的命令行与 MCP 服务器

我们的最新工具 <b>dna</b> 让您在终端和 AI 智能体中执行 Domain Name API 的全部操作：查询、注册、续费和转移域名，管理 DNS、DNSSEC、SSL 和主机。任何付费操作执行前，安全闸门都会先等待您的确认。

<a href="https://github.com/domainreseller/cli"><img src="./assets/cli.svg" width="1200" alt="dna CLI：单个可执行文件，涵盖 Domain Name API 全部 64 项操作和 65 个 MCP 工具。终端中安装 dna、连接 Claude Code、查询 brandname.com、用 --dry-run 预览付费注册，再用 --yes 完成注册。"></a>

<p align="center">
  <a href="https://github.com/domainreseller/cli/releases/latest"><img src="./assets/btn-cli.svg" height="46" alt="下载 dna CLI"></a>
  <a href="https://github.com/domainreseller/cli#connect-your-ai-agent"><img src="./assets/btn-cli-agent.svg" height="46" alt="将您的 AI 智能体连接到 dna"></a>
  <a href="https://github.com/domainreseller/cli#readme"><img src="./assets/btn-cli-docs.svg" height="46" alt="dna CLI 文档"></a>
</p>

```bash
# 在 Linux / macOS 上安装
curl -fsSL https://raw.githubusercontent.com/domainreseller/cli/main/scripts/install.sh | sh

# 连接 Claude Code（建议先在 OTE 测试环境中使用）
claude mcp add dna -- dna mcp serve --env ote

# 或者直接运行 dna，打开交互式终端
dna
```

```powershell
# 在 Windows 上安装（PowerShell）
irm https://raw.githubusercontent.com/domainreseller/cli/main/scripts/install.ps1 | iex
```

### v1.1 新功能：只需输入 `dna`

交互式终端会在你输入时实时查询名称，让你通过菜单管理域名，并一步步引导你完成注册和续费。每一笔购买都会等待你的确认，**Connect an AI agent** 只需几次按键即可配置 Claude Code、ChatGPT、Cursor 以及 20 多个其他 AI 智能体。

<a href="https://github.com/domainreseller/cli#interactive-shell"><img src="./assets/cli-shell-cn.svg" width="1200" alt="dna 交互式终端：输入 acme 即显示可注册的后缀及价格，用户选择 acme.net，填写简短的注册表单，在确认对话框中确认付费步骤，域名注册完成。"></a>

### 适用于 Claude 和 ChatGPT 的现成提示词

复制一条提示词，粘贴到您的 AI 助手中，让它替您完成工作。每条提示词都从 OTE 测试环境开始，并会在任何付费操作之前停下来等待您的确认。

**在 Claude Code 中设置 dna**

```text
请帮我安装配置 dna CLI (https://github.com/domainreseller/cli)。
1. 使用适合我操作系统的官方安装脚本安装，然后运行 `dna version` 和 `dna doctor`。
2. 用 `dna agent skill --install` 安装 Claude Code 技能，并用
   `claude mcp add dna -- dna mcp serve --env ote` 添加 MCP 服务器。
3. 不要要求我把 API 密钥粘贴到这个对话中。提示我自己运行 `dna auth login --env ote`，
   然后用 `dna --ote account get` 检查连接。
只在 OTE 测试环境中操作，未经我同意，绝不要使用 `--yes`。
```

**在 ChatGPT Codex 中设置 dna**

```text
请帮我安装配置 dna CLI (https://github.com/domainreseller/cli)。
1. 使用适合我操作系统的官方安装脚本安装，然后运行 `dna version` 和 `dna doctor`。
2. 把它作为 MCP 服务器添加到我的 Codex 配置 (`~/.codex/config.toml`) 中：名称为 `dna`，
   命令为 `dna`，参数为 `mcp serve --env ote`。
3. 不要要求我把 API 密钥粘贴到这个对话中。提示我自己运行 `dna auth login --env ote`，
   然后用 `dna --ote account get` 检查连接。
只在 OTE 测试环境中操作，未经我同意，绝不要使用 `--yes`。
```

**没有终端？在 ChatGPT 或 Claude 聊天中提问**

```text
请阅读 https://raw.githubusercontent.com/domainreseller/cli/main/llms.txt 及其中链接的
dna 文档。然后一步一步地给出在 OTE 测试环境中注册域名的确切 dna 命令：安装、登录、查询、
用 `--dry-run` 预览，以及注册。解释每条命令的作用。
```

<details>
<summary><b>更多日常工作提示词</b></summary>
<br>

**查询并注册域名**

```text
用 dna 检查 brandname.com、brandname.net 和 brandname.io 是否可以注册。用表格列出结果
和价格，然后用 `--dry-run` 预览注册其中最便宜的可注册域名。在我同意之前，什么都不要注
册。
```

**近期续费**

```text
用 dna 列出我未来 60 天内到期的域名及其续费价格，按到期日期排序。什么都不要续费。
```

**将域名指向服务器**

```text
用 dna 将 example.com 指向 203.0.113.10：为 `@` 和 `www` 添加 A 记录，然后给我看最终的
DNS 区域。修改或删除任何现有记录之前，先问我。
```

**转入域名**

```text
用 dna 检查 example.org 能否转入我的账户，告诉我还缺什么（授权码、解锁），并用
`--dry-run` 预览转入。
```

**订购 SSL 证书**

```text
用 dna 为 example.com 找到最便宜的 DV SSL 证书，生成 CSR 并预览订单。购买前等待我的确
认。
```

</details>

## <img src="./assets/h-programs.svg" width="30" height="30" alt=""> 域名、SSL 与主机代理计划

一个 Domain Name API 账户，三大代理计划：以您自己的品牌销售域名、SSL 证书和白标主机。

<img src="./assets/programs.svg" width="1200" alt="一个 Domain Name API 账户，三大代理计划：域名代理（830+ 种域名后缀，批发价）、SSL 代理（DV、OV、EV 及通配符证书）和主机代理（白标 cPanel 与 Plesk 主机）。">

<p align="center">
  <a href="https://www.domainnameapi.com/zh/yuming-zhuce"><img src="./assets/btn-domain-reseller.svg" height="46" alt="域名代理计划"></a>
  <a href="https://www.domainnameapi.com/zh/ssl-dailishang"><img src="./assets/btn-ssl-reseller.svg" height="46" alt="SSL 代理计划"></a>
  <a href="https://www.domainnameapi.com/zh/zhuji-dailishang"><img src="./assets/btn-reseller-hosting.svg" height="46" alt="主机代理计划"></a>
</p>

## <img src="./assets/h-flow.svg" width="30" height="30" alt=""> 域名代理 API 的工作原理

<img src="./assets/flow.svg" width="1200" alt="您的客户在您的网站上下单，您的计费系统通过 DNA 模块将请求发送至 Domain Name API，再由 Domain Name API 通过 EPP 与各域名注册局通信。">

## <img src="./assets/h-modules.svg" width="30" height="30" alt=""> 域名分销模块

注册商模块将您的计费系统与 Domain Name API 对接，让您的客户直接在您自己的网站上查询、注册、转移和续费域名。

> [!IMPORTANT]
> **请始终通过下方的 _最新版本_ 链接下载模块。** 发布包均带有版本号、经过测试，可直接用于生产环境。

> [!WARNING]
> **请勿**使用 GitHub 的绿色 **Code → Download ZIP** 按钮；它下载的是未经测试的开发分支。

<table align="center">
<tr>
<td align="center">
<a href="https://github.com/domainreseller/whmcs-dna"><img src="./assets/card-whmcs.svg" width="248" alt="WHMCS 域名代理模块"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/whmcs-dna?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://github.com/domainreseller/whmcs-dna/releases/latest">📥 下载</a> · <a href="https://github.com/domainreseller/whmcs-dna#readme">📝 文档</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/wisecp-dna-v5"><img src="./assets/card-wisecp5.svg" width="248" alt="WiseCP 5 域名代理模块"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/wisecp-dna-v5?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://github.com/domainreseller/wisecp-dna-v5/releases/latest">📥 下载</a> · <a href="https://github.com/domainreseller/wisecp-dna-v5#readme">📝 文档</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/wisecp-dna"><img src="./assets/card-wisecp.svg" width="248" alt="WiseCP 3.x 域名代理模块"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/wisecp-dna?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://github.com/domainreseller/wisecp-dna/releases/latest">📥 下载</a> · <a href="https://github.com/domainreseller/wisecp-dna#readme">📝 文档</a>
</td>
</tr>
<tr>
<td align="center">
<a href="https://github.com/domainreseller/blesta-dna"><img src="./assets/card-blesta.svg" width="248" alt="Blesta 域名代理模块"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/blesta-dna?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://github.com/domainreseller/blesta-dna/releases/latest">📥 下载</a> · <a href="https://github.com/domainreseller/blesta-dna#readme">📝 文档</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/hostbill-dna"><img src="./assets/card-hostbill.svg" width="248" alt="HostBill 域名代理模块"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/hostbill-dna?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://github.com/domainreseller/hostbill-dna/releases/latest">📥 下载</a> · <a href="https://github.com/domainreseller/hostbill-dna#readme">📝 文档</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/clientexec-dna"><img src="./assets/card-clientexec.svg" width="248" alt="ClientExec 域名代理插件"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/clientexec-dna?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://github.com/domainreseller/clientexec-dna/releases/latest">📥 下载</a> · <a href="https://github.com/domainreseller/clientexec-dna#readme">📝 文档</a>
</td>
</tr>
<tr>
<td align="center">
<a href="https://github.com/domainreseller/fossbilling-dna"><img src="./assets/card-fossbilling.svg" width="248" alt="FOSSBilling 域名代理模块"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/fossbilling-dna?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://github.com/domainreseller/fossbilling-dna/releases/latest">📥 下载</a> · <a href="https://github.com/domainreseller/fossbilling-dna#readme">📝 文档</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/hostfact-dna"><img src="./assets/card-hostfact.svg" width="248" alt="HostFact 域名代理模块"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/hostfact-dna?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://github.com/domainreseller/hostfact-dna/releases/latest">📥 下载</a> · <a href="https://github.com/domainreseller/hostfact-dna#readme">📝 文档</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/dna-extended"><img src="./assets/card-extended.svg" width="248" alt="Extended WHMCS 附加模块"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/dna-extended?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://github.com/domainreseller/dna-extended/releases/latest">📥 下载</a> · <a href="https://github.com/domainreseller/dna-extended#readme">📝 文档</a>
</td>
</tr>
</table>

## <img src="./assets/h-sdk.svg" width="30" height="30" alt=""> 域名代理 API 开发库

想自行开发集成？使用我们的 PHP、Node.js、Ruby、Python和Go 开发库直接调用域名代理 API。

<table align="center">
<tr>
<td align="center">
<a href="https://github.com/domainreseller/php-dna"><img src="./assets/card-php.svg" width="248" alt="适用于域名代理 API 的 PHP 开发库"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/php-dna?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://github.com/domainreseller/php-dna/releases/latest">📥 下载</a> · <a href="https://github.com/domainreseller/php-dna#readme">📝 文档</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/nodejs-dna"><img src="./assets/card-nodejs.svg" width="248" alt="适用于域名代理 API 的 Node.js 开发库"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/nodejs-dna?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://github.com/domainreseller/nodejs-dna/releases/latest">📥 下载</a> · <a href="https://github.com/domainreseller/nodejs-dna#readme">📝 文档</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/ruby-dna"><img src="./assets/card-ruby.svg" width="248" alt="适用于域名代理 API 的 Ruby 开发库"></a><br>
<img src="https://img.shields.io/gem/v/domainnameapi?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://rubygems.org/gems/domainnameapi">📥 下载</a> · <a href="https://github.com/domainreseller/ruby-dna#readme">📝 文档</a>
</td>
</tr>
</table>

<table align="center">
<tr>
<td align="center">
<a href="https://github.com/domainreseller/python-dna"><img src="./assets/card-python.svg" width="248" alt="适用于域名代理 API 的 Python 开发库"></a><br>
<img src="https://img.shields.io/pypi/v/domainnameapi?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://pypi.org/project/domainnameapi/">📥 下载</a> · <a href="https://github.com/domainreseller/python-dna#readme">📝 文档</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/go-dna"><img src="./assets/card-go.svg" width="248" alt="适用于域名代理 API 的 Go 开发库"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/go-dna?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://github.com/domainreseller/go-dna/releases/latest">📥 下载</a> · <a href="https://github.com/domainreseller/go-dna#readme">📝 文档</a>
</td>
</tr>
</table>

```bash
composer require domainreseller/php-dna   # PHP
npm install nodejs-dna                    # Node.js
gem install domainnameapi                 # Ruby
pip install domainnameapi                 # Python
go get github.com/domainreseller/go-dna   # Go
```

<details>
<summary><b>快速上手: PHP</b></summary>

```php
require_once __DIR__.'/vendor/autoload.php';

$dna = new \DomainNameApi\DomainNameAPI_PHPLibrary($resellerId, $apiKey);

$dna->CheckAvailability(['hello', 'world123x0'], ['com', 'net'], 1, 'create');
```

</details>

<details>
<summary><b>快速上手: Node.js</b></summary>

```js
const DomainNameApi = require('nodejs-dna');

const api = new DomainNameApi('xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx', 'your-api-key');

const domains = await api.CheckAvailability(['hello', 'world'], ['com', 'net'], 1);
```

</details>

<details>
<summary><b>快速上手: Ruby</b></summary>

```ruby
require 'domainnameapi'

dna = DomainNameApi::Client.new('xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx', 'your-api-key')

dna.check_availability(['hello', 'world123x0'], ['com', 'net'], 1, 'create')
```

</details>

<details>
<summary><b>快速上手: Python</b></summary>

```python
from domainnameapi import DomainNameAPI

dna = DomainNameAPI("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "your-api-key")

dna.check_availability(["hello", "world123x0"], ["com", "net"], 1, "create")
```

</details>

<details>
<summary><b>快速上手: Go</b></summary>

```go
import dna "github.com/domainreseller/go-dna"

client := dna.New("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "your-api-key", false)

result := client.CheckAvailability([]string{"hello", "world123x0"}, []string{"com", "net"}, 1, "create")
```

</details>

## <img src="./assets/h-ssl.svg" width="30" height="30" alt=""> SSL 与主机代理模块

不止销售域名：适用于我们 [SSL 代理](https://www.domainnameapi.com/zh/ssl-dailishang) 和 [主机代理](https://www.domainnameapi.com/zh/zhuji-dailishang) 计划的模块，同一账户即可提供 SSL 证书及 cPanel / Plesk 主机。

<table align="center">
<tr>
<td align="center">
<a href="https://github.com/domainreseller/whmcs-ssl-dna"><img src="./assets/card-ssl-whmcs.svg" width="248" alt="适用于 WHMCS 的 DNA SSL"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/whmcs-ssl-dna?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://github.com/domainreseller/whmcs-ssl-dna/releases/latest">📥 下载</a> · <a href="https://github.com/domainreseller/whmcs-ssl-dna#readme">📝 文档</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/wisecp-ssl-dna"><img src="./assets/card-ssl-wisecp.svg" width="248" alt="适用于 WiseCP 5 的 DNA SSL"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/wisecp-ssl-dna?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://github.com/domainreseller/wisecp-ssl-dna/releases/latest">📥 下载</a> · <a href="https://github.com/domainreseller/wisecp-ssl-dna#readme">📝 文档</a>
</td>
</tr>
<tr>
<td align="center">
<a href="https://github.com/domainreseller/reseller-hosting-whmcs"><img src="./assets/card-hosting-whmcs.svg" width="248" alt="适用于 WHMCS 的 DNA Reseller Hosting"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/reseller-hosting-whmcs?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://github.com/domainreseller/reseller-hosting-whmcs/releases/latest">📥 下载</a> · <a href="https://github.com/domainreseller/reseller-hosting-whmcs#readme">📝 文档</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/reseller-hosting-wisecp"><img src="./assets/card-hosting-wisecp.svg" width="248" alt="适用于 WiseCP 的 DNA Reseller Hosting"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/reseller-hosting-wisecp?label=version&style=flat-square&color=12B385" alt="最新版本"><br>
<a href="https://github.com/domainreseller/reseller-hosting-wisecp/releases/latest">📥 下载</a> · <a href="https://github.com/domainreseller/reseller-hosting-wisecp#readme">📝 文档</a>
</td>
</tr>
</table>

## <img src="./assets/h-key.svg" width="30" height="30" alt=""> API 凭据

<img src="./assets/creds.svg" width="1200" alt="在用户名 (Username) 字段中输入您的 Reseller ID，在密码 (Password) 字段中输入您的 API Key，模块随即连接到 REST API。">

每个模块都需要填写相同的两项：

| 模块字段 | 填写内容 |
|---|---|
| **用户名 (Username)** | Reseller ID，即 UUID 格式，例如 `xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx` |
| **密码 (Password)** | API Key |

> [!TIP]
> 您可以在 Domain Name API 面板的 **API 设置 (API Settings)** 中找到 **Reseller ID** 和 **API Key**。

> [!CAUTION]
> 这些是 **API 凭据**。您的面板登录邮箱和密码在这里**无法**使用。

## <img src="./assets/h-faq.svg" width="30" height="30" alt=""> 域名代理常见问题

<details>
<summary><b>什么是域名代理商？</b></summary>
<br>
域名代理商（又称域名分销商）以自己的品牌和价格向自己的客户销售域名，而由经认证的注册商负责在各注册局完成注册。使用 Domain Name API，您获得的正是这一注册商端：830+ 种域名后缀、代理商面板和域名代理 API，以及适用于您现有计费系统的现成模块。
</details>

<details>
<summary><b>如何通过 Domain Name API 成为域名代理商？</b></summary>
<br>
在<a href="https://www.domainnameapi.com/zh/yuming-zhuce">域名代理页面</a>注册。无需开户费，也没有最低预存款要求。然后在面板的 <b>API 设置 (API Settings)</b> 中获取您的 <b>Reseller ID</b> 和 <b>API Key</b>，从上方列表中为您的计费系统安装对应模块，即可开始销售域名。
</details>

<details>
<summary><b>AI 智能体可以管理我的域名吗？</b></summary>
<br>
可以。<a href="https://github.com/domainreseller/cli">dna CLI</a> 将 Domain Name API 的每项操作都作为 MCP 工具提供给 Claude Code、Cursor、Codex 及其他 MCP 客户端。付费和不可逆的操作会等待您的确认，使用 <code>--env ote</code> 时智能体会先在测试环境中运行。
</details>

<details>
<summary><b>应该下载哪个文件？</b></summary>
<br>
始终下载模块<b>最新版本</b>所附带的安装包（即上方的 📥 下载链接）。绿色的 <b>Code → Download ZIP</b> 按钮下载的是未经测试的开发分支。
</details>

<details>
<summary><b>WiseCP 3.x 还是 WiseCP 5？</b></summary>
<br>
WiseCP 5（PHP 8.2+）请使用 <a href="https://github.com/domainreseller/wisecp-dna-v5">wisecp-dna-v5</a>，WiseCP 3.x 请使用 <a href="https://github.com/domainreseller/wisecp-dna">wisecp-dna</a>。
</details>

<details>
<summary><b>在哪里可以找到我的 Reseller ID 和 API Key？</b></summary>
<br>
在 Domain Name API 面板的 <b>API 设置 (API Settings)</b> 中。面板登录信息无法在模块中使用。
</details>

<details>
<summary><b>上线前可以先测试吗？</b></summary>
<br>
可以。<a href="https://github.com/domainreseller/php-dna">PHP</a>、<a href="https://github.com/domainreseller/nodejs-dna">Node.js</a>、<a href="https://github.com/domainreseller/ruby-dna">Ruby</a>、<a href="https://github.com/domainreseller/python-dna">Python</a>和<a href="https://github.com/domainreseller/go-dna">Go</a> 开发库均可连接测试（OTE）环境，切换方法请参阅各自的文档。
</details>

## <img src="./assets/h-connect.svg" width="30" height="30" alt=""> 联系我们

<p align="center">
  <a href="https://www.domainnameapi.com/zh"><img src="./assets/btn-web.svg" height="46" alt="Domain Name API：域名代理计划"></a>
  <a href="https://www.domainnameapi.com/zh/yuming-zhuce"><img src="./assets/btn-signup.svg" height="46" alt="成为域名代理商"></a>
  <a href="https://www.domainnameapi.com/zh/domain-api-jicheng"><img src="./assets/btn-api.svg" height="46" alt="域名代理 API 与模块"></a>
  <a href="https://www.domainnameapi.com/zh/lianxi-women"><img src="./assets/btn-support.svg" height="46" alt="技术支持"></a>
</p>

<br>

<p align="right">
  <sub>工具</sub><br>
  <a href="https://github.com/domainreseller/Trabis-turkey-tr-domain-registration-tr-domain-kayit"><img src="./assets/pill-trabis.svg" height="34" alt="TRABIS .tr 域名注册"></a>
  <br>
  <sub>关注我们</sub><br>
  <a href="https://www.atakdomain.com"><img src="./assets/pill-atak.svg" height="34" alt="atakdomain.com"></a>
  <a href="https://www.linkedin.com/company/domain-name-reseller/"><img src="./assets/pill-linkedin.svg" height="34" alt="LinkedIn"></a>
  <a href="https://x.com/dna_resellerapi"><img src="./assets/pill-x.svg" height="34" alt="X"></a>
  <a href="https://www.youtube.com/DomainReseller"><img src="./assets/pill-youtube.svg" height="34" alt="YouTube"></a>
</p>

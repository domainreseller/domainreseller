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
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-AZ.md"><img src="./assets/lang-az-on.svg" height="38" alt="Azərbaycanca"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-CN.md"><img src="./assets/lang-cn.svg" height="38" alt="中文"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-FR.md"><img src="./assets/lang-fr.svg" height="38" alt="Français"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-IT.md"><img src="./assets/lang-it.svg" height="38" alt="Italiano"></a>
</p>

<a href="https://www.domainnameapi.com/az/domain-reseller"><img src="./assets/hero.svg" width="1200" alt="Domain Name API: domen satıcısı olun. REST API və WHMCS, WiseCP, Blesta və digərləri üçün hazır modullarla 830+ domen uzantısını öz brendiniz altında satın."></a>

<h1 align="center">Domen Satıcılığı API &amp; Modulları</h1>

<p align="center">
  <b>Domain Name API</b> <a href="https://www.atakdomain.com">Atak Domain</a> tərəfindən yaradılmış ICANN akkreditasiyalı registrator və <b>domen satıcılığı (domain reseller)</b> proqramıdır. <a href="https://www.domainnameapi.com/az/domain-reseller">200+ ölkədən 40.000+ domen satıcısına</a> qoşulun, 830+ domen uzantısını öz brendiniz altında satın, qeydiyyat, transfer və yeniləmə əməliyyatlarını <a href="https://www.domainnameapi.com/az/domain-api-inteqrasiyasi">domen reseller API-miz</a> və ya aşağıdakı WHMCS, WiseCP, Blesta, HostBill, ClientExec, FOSSBilling və HostFact üçün hazır modullar vasitəsilə avtomatlaşdırın.
</p>

<p align="center">
  <a href="https://github.com/domainreseller/cli"><img src="./assets/cli-ribbon.svg" width="760" alt="Yeni: dna, Domain Name API-nin CLI aləti və MCP serveri. Domenlərinizi terminaldan, Claude Code, Cursor və Codex-dən idarə edin."></a>
</p>

<img src="./assets/stats.svg" width="1200" alt="830+ TLD, 40.000+ aktiv domen satıcısı, 200+ ölkə, 20+ illik təcrübə.">

<img src="./assets/tlds.svg" width="1200" alt="Sata biləcəyiniz 830+ uzantıdan bəziləri: .com, .net, .org, .com.tr, .xyz, .shop və daha çoxu.">

## <img src="./assets/h-cli.svg" width="30" height="30" alt=""> dna CLI və AI agentləri üçün MCP server

Ən yeni alətimiz <b>dna</b> Domain Name API-nin bütün əməliyyatlarını terminalınızdan və AI agentlərinizdən icra edir. Domen axtarın, qeydiyyatdan keçirin, yeniləyin və transfer edin; DNS, DNSSEC, SSL və hostinqi idarə edin. Ödənişli əməliyyatdan əvvəl təhlükəsizlik qapısı həmişə təsdiqinizi gözləyir.

<a href="https://github.com/domainreseller/cli"><img src="./assets/cli.svg" width="1200" alt="dna CLI: Domain Name API-nin 64 əməliyyatının hamısını və 65 MCP alətini əhatə edən tək fayl. Terminalda dna quraşdırılır, Claude Code-a qoşulur, brandname.com axtarılır, ödənişli qeydiyyat --dry-run ilə önizlənir və --yes ilə tamamlanır."></a>

<p align="center">
  <a href="https://github.com/domainreseller/cli/releases/latest"><img src="./assets/btn-cli.svg" height="46" alt="dna CLI-ni yükləyin"></a>
  <a href="https://github.com/domainreseller/cli#connect-your-ai-agent"><img src="./assets/btn-cli-agent.svg" height="46" alt="AI agentinizi dna-ya qoşun"></a>
  <a href="https://github.com/domainreseller/cli#readme"><img src="./assets/btn-cli-docs.svg" height="46" alt="dna CLI sənədləri"></a>
</p>

```bash
# Linux / macOS-da quraşdırma
curl -fsSL https://raw.githubusercontent.com/domainreseller/cli/main/scripts/install.sh | sh

# Claude Code-a qoşun (əvvəlcə OTE test mühitində başlayın)
claude mcp add dna -- dna mcp serve --env ote
```

```powershell
# Windows-da quraşdırma (PowerShell)
irm https://raw.githubusercontent.com/domainreseller/cli/main/scripts/install.ps1 | iex
```

### Claude və ChatGPT üçün hazır promptlar

Promptu kopyalayın, AI assistentinizə yapışdırın və işi ona həvalə edin. Hər prompt OTE test mühitində başlayır və ödənişli əməliyyatdan əvvəl dayanıb təsdiqinizi gözləyir.

**dna-nı Claude Code-da quraşdırın**

```text
Mənim üçün dna CLI-ni quraşdır (https://github.com/domainreseller/cli).
1. Onu əməliyyat sistemimə uyğun rəsmi quraşdırma skripti ilə quraşdır, sonra
   `dna version` və `dna doctor` əmrlərini işə sal.
2. Claude Code skill-ini `dna agent skill --install` ilə quraşdır və MCP serverini
   `claude mcp add dna -- dna mcp serve --env ote` ilə əlavə et.
3. API açarımı bu söhbətə yapışdırmağımı istəmə. `dna auth login --env ote` əmrini
   özüm işə salmağımı söylə, sonra bağlantını `dna --ote account get` ilə yoxla.
Yalnız OTE test mühitində işlə və mənim təsdiqim olmadan heç vaxt `--yes`
parametrindən istifadə etmə.
```

**dna-nı ChatGPT Codex-də quraşdırın**

```text
Mənim üçün dna CLI-ni quraşdır (https://github.com/domainreseller/cli).
1. Onu əməliyyat sistemimə uyğun rəsmi quraşdırma skripti ilə quraşdır, sonra
   `dna version` və `dna doctor` əmrlərini işə sal.
2. Onu Codex konfiqurasiyama (`~/.codex/config.toml`) `dna` adlı MCP server kimi əlavə
   et: əmr `dna`, arqumentlər `mcp serve --env ote`.
3. API açarımı bu söhbətə yapışdırmağımı istəmə. `dna auth login --env ote` əmrini
   özüm işə salmağımı söylə, sonra bağlantını `dna --ote account get` ilə yoxla.
Yalnız OTE test mühitində işlə və mənim təsdiqim olmadan heç vaxt `--yes`
parametrindən istifadə etmə.
```

**Terminalınız yoxdur? ChatGPT və ya Claude söhbətində soruşun**

```text
https://raw.githubusercontent.com/domainreseller/cli/main/llms.txt faylını və onun
keçid verdiyi dna sənədlərini oxu. Sonra OTE test mühitində bir domeni qeydiyyatdan
keçirmək üçün lazım olan dəqiq dna əmrlərini addım-addım ver: quraşdırma, giriş,
axtarış, `--dry-run` ilə önizləmə və qeydiyyat. Hər əmrin nə etdiyini izah et.
```

<details>
<summary><b>Gündəlik işlər üçün daha çox prompt</b></summary>
<br>

**Domen tapın və qeydiyyatdan keçirin**

```text
dna ilə brandname.com, brandname.net və brandname.io domenlərinin boş olub-olmadığını
yoxla. Nəticələri qiymətləri ilə birlikdə cədvəldə göstər, sonra boş olanlardan ən
ucuzunun qeydiyyatını `--dry-run` ilə önizlə. Mən hə deyənə qədər heç nəyi
qeydiyyatdan keçirmə.
```

**Yaxınlaşan yeniləmələr**

```text
dna ilə növbəti 60 gün ərzində müddəti bitəcək domenlərimi yeniləmə qiymətləri ilə
birlikdə, bitmə tarixinə görə sıralayaraq sadala. Heç nəyi yeniləmə.
```

**Domeni serverə yönləndirin**

```text
dna ilə example.com domenini 203.0.113.10 ünvanına yönləndir: `@` və `www` üçün A
qeydləri əlavə et, sonra mənə son DNS zonasını göstər. Hər hansı mövcud qeydi
dəyişməzdən və ya silməzdən əvvəl məndən soruş.
```

**Domeni hesabınıza transfer edin**

```text
dna ilə example.org domeninin hesabıma transfer edilə bilib-bilmədiyini yoxla, mənə
hələ nələrin lazım olduğunu de (auth kodu, kilidin açılması) və transferi `--dry-run`
ilə önizlə.
```

**SSL sertifikatı sifariş edin**

```text
dna ilə example.com üçün ən ucuz DV SSL sertifikatını tap, CSR yarat və sifarişi
önizlə. Almazdan əvvəl təsdiqimi gözlə.
```

</details>

## <img src="./assets/h-programs.svg" width="30" height="30" alt=""> Domen, SSL və hostinq satıcılığı proqramları

Bir Domain Name API hesabı, üç satıcılıq proqramı: domen adlarını, SSL sertifikatlarını və white-label hostinqi öz brendiniz altında satın.

<img src="./assets/programs.svg" width="1200" alt="Bir Domain Name API hesabı, üç satıcılıq proqramı: Domen Satıcılığı (topdansatış qiymətlərlə 830+ TLD), SSL Satıcılığı (DV, OV, EV və wildcard sertifikatlar) və Reseller Hostinq (white-label cPanel və Plesk hostinq).">

<p align="center">
  <a href="https://www.domainnameapi.com/az/domain-reseller"><img src="./assets/btn-domain-reseller.svg" height="46" alt="Domen Satıcılığı proqramı"></a>
  <a href="https://www.domainnameapi.com/az/ssl-reseller"><img src="./assets/btn-ssl-reseller.svg" height="46" alt="SSL Satıcılığı proqramı"></a>
  <a href="https://www.domainnameapi.com/az/reseller-hosting"><img src="./assets/btn-reseller-hosting.svg" height="46" alt="Reseller Hostinq proqramı"></a>
</p>

## <img src="./assets/h-flow.svg" width="30" height="30" alt=""> Domen satıcılığı API-si necə işləyir

<img src="./assets/flow.svg" width="1200" alt="Müştəriləriniz saytınızda sifariş verir, billinq paneliniz sorğunu DNA modulu vasitəsilə Domain Name API-yə göndərir, Domain Name API isə EPP üzərindən reyestrlərlə əlaqə saxlayır.">

## <img src="./assets/h-modules.svg" width="30" height="30" alt=""> Domen reseller modulları

Billinq panelinizi Domain Name API-yə qoşan registrator modulları. Bu sayədə müştəriləriniz sizin saytınızda domen axtara, qeydiyyatdan keçirə, transfer edə və yeniləyə bilər.

> [!IMPORTANT]
> **Modulları həmişə aşağıdakı _son buraxılış (latest release)_ linklərindən yükləyin.** Buraxılış paketləri versiyalanıb, test olunub və canlı mühitdə istifadəyə hazırdır.

> [!WARNING]
> GitHub-ın yaşıl **Code → Download ZIP** düyməsindən **istifadə etməyin**; bu düymə test olunmamış inkişaf budağını yükləyir.

<table align="center">
<tr>
<td align="center">
<a href="https://github.com/domainreseller/whmcs-dna"><img src="./assets/card-whmcs.svg" width="248" alt="WHMCS domen satıcılığı modulu"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/whmcs-dna?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://github.com/domainreseller/whmcs-dna/releases/latest">📥 Yüklə</a> · <a href="https://github.com/domainreseller/whmcs-dna#readme">📝 Sənədlər</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/wisecp-dna-v5"><img src="./assets/card-wisecp5.svg" width="248" alt="WiseCP 5 domen satıcılığı modulu"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/wisecp-dna-v5?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://github.com/domainreseller/wisecp-dna-v5/releases/latest">📥 Yüklə</a> · <a href="https://github.com/domainreseller/wisecp-dna-v5#readme">📝 Sənədlər</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/wisecp-dna"><img src="./assets/card-wisecp.svg" width="248" alt="WiseCP 3.x domen satıcılığı modulu"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/wisecp-dna?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://github.com/domainreseller/wisecp-dna/releases/latest">📥 Yüklə</a> · <a href="https://github.com/domainreseller/wisecp-dna#readme">📝 Sənədlər</a>
</td>
</tr>
<tr>
<td align="center">
<a href="https://github.com/domainreseller/blesta-dna"><img src="./assets/card-blesta.svg" width="248" alt="Blesta domen satıcılığı modulu"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/blesta-dna?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://github.com/domainreseller/blesta-dna/releases/latest">📥 Yüklə</a> · <a href="https://github.com/domainreseller/blesta-dna#readme">📝 Sənədlər</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/hostbill-dna"><img src="./assets/card-hostbill.svg" width="248" alt="HostBill domen satıcılığı modulu"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/hostbill-dna?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://github.com/domainreseller/hostbill-dna/releases/latest">📥 Yüklə</a> · <a href="https://github.com/domainreseller/hostbill-dna#readme">📝 Sənədlər</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/clientexec-dna"><img src="./assets/card-clientexec.svg" width="248" alt="ClientExec domen satıcılığı plagini"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/clientexec-dna?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://github.com/domainreseller/clientexec-dna/releases/latest">📥 Yüklə</a> · <a href="https://github.com/domainreseller/clientexec-dna#readme">📝 Sənədlər</a>
</td>
</tr>
<tr>
<td align="center">
<a href="https://github.com/domainreseller/fossbilling-dna"><img src="./assets/card-fossbilling.svg" width="248" alt="FOSSBilling domen satıcılığı modulu"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/fossbilling-dna?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://github.com/domainreseller/fossbilling-dna/releases/latest">📥 Yüklə</a> · <a href="https://github.com/domainreseller/fossbilling-dna#readme">📝 Sənədlər</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/hostfact-dna"><img src="./assets/card-hostfact.svg" width="248" alt="HostFact domen satıcılığı modulu"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/hostfact-dna?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://github.com/domainreseller/hostfact-dna/releases/latest">📥 Yüklə</a> · <a href="https://github.com/domainreseller/hostfact-dna#readme">📝 Sənədlər</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/dna-extended"><img src="./assets/card-extended.svg" width="248" alt="Extended WHMCS addon modulu"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/dna-extended?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://github.com/domainreseller/dna-extended/releases/latest">📥 Yüklə</a> · <a href="https://github.com/domainreseller/dna-extended#readme">📝 Sənədlər</a>
</td>
</tr>
</table>

## <img src="./assets/h-sdk.svg" width="30" height="30" alt=""> Domen reseller API kitabxanaları

Öz inteqrasiyanızı qurursunuz? PHP, Node.js, Ruby, Python və Go kitabxanalarımızla domen satıcılığı API-sini birbaşa çağırın.

<table align="center">
<tr>
<td align="center">
<a href="https://github.com/domainreseller/php-dna"><img src="./assets/card-php.svg" width="248" alt="Domen satıcılığı API-si üçün PHP kitabxanası"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/php-dna?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://github.com/domainreseller/php-dna/releases/latest">📥 Yüklə</a> · <a href="https://github.com/domainreseller/php-dna#readme">📝 Sənədlər</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/nodejs-dna"><img src="./assets/card-nodejs.svg" width="248" alt="Domen satıcılığı API-si üçün Node.js kitabxanası"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/nodejs-dna?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://github.com/domainreseller/nodejs-dna/releases/latest">📥 Yüklə</a> · <a href="https://github.com/domainreseller/nodejs-dna#readme">📝 Sənədlər</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/ruby-dna"><img src="./assets/card-ruby.svg" width="248" alt="Domen satıcılığı API-si üçün Ruby kitabxanası"></a><br>
<img src="https://img.shields.io/gem/v/domainnameapi?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://rubygems.org/gems/domainnameapi">📥 Yüklə</a> · <a href="https://github.com/domainreseller/ruby-dna#readme">📝 Sənədlər</a>
</td>
</tr>
</table>

<table align="center">
<tr>
<td align="center">
<a href="https://github.com/domainreseller/python-dna"><img src="./assets/card-python.svg" width="248" alt="Domen satıcılığı API-si üçün Python kitabxanası"></a><br>
<img src="https://img.shields.io/pypi/v/domainnameapi?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://pypi.org/project/domainnameapi/">📥 Yüklə</a> · <a href="https://github.com/domainreseller/python-dna#readme">📝 Sənədlər</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/go-dna"><img src="./assets/card-go.svg" width="248" alt="Domen satıcılığı API-si üçün Go kitabxanası"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/go-dna?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://github.com/domainreseller/go-dna/releases/latest">📥 Yüklə</a> · <a href="https://github.com/domainreseller/go-dna#readme">📝 Sənədlər</a>
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
<summary><b>Sürətli başlanğıc: PHP</b></summary>

```php
require_once __DIR__.'/vendor/autoload.php';

$dna = new \DomainNameApi\DomainNameAPI_PHPLibrary($resellerId, $apiKey);

$dna->CheckAvailability(['hello', 'world123x0'], ['com', 'net'], 1, 'create');
```

</details>

<details>
<summary><b>Sürətli başlanğıc: Node.js</b></summary>

```js
const DomainNameApi = require('nodejs-dna');

const api = new DomainNameApi('xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx', 'your-api-key');

const domains = await api.CheckAvailability(['hello', 'world'], ['com', 'net'], 1);
```

</details>

<details>
<summary><b>Sürətli başlanğıc: Ruby</b></summary>

```ruby
require 'domainnameapi'

dna = DomainNameApi::Client.new('xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx', 'your-api-key')

dna.check_availability(['hello', 'world123x0'], ['com', 'net'], 1, 'create')
```

</details>

<details>
<summary><b>Sürətli başlanğıc: Python</b></summary>

```python
from domainnameapi import DomainNameAPI

dna = DomainNameAPI("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "your-api-key")

dna.check_availability(["hello", "world123x0"], ["com", "net"], 1, "create")
```

</details>

<details>
<summary><b>Sürətli başlanğıc: Go</b></summary>

```go
import dna "github.com/domainreseller/go-dna"

client := dna.New("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "your-api-key", false)

result := client.CheckAvailability([]string{"hello", "world123x0"}, []string{"com", "net"}, 1, "create")
```

</details>

## <img src="./assets/h-ssl.svg" width="30" height="30" alt=""> SSL və reseller hostinq modulları

Domenlərdən daha çoxunu satın: [SSL Satıcılığı](https://www.domainnameapi.com/az/ssl-reseller) və [Reseller Hostinq](https://www.domainnameapi.com/az/reseller-hosting) proqramlarımız üçün modullar, SSL sertifikatları və cPanel / Plesk hostinq eyni hesabdan.

<table align="center">
<tr>
<td align="center">
<a href="https://github.com/domainreseller/whmcs-ssl-dna"><img src="./assets/card-ssl-whmcs.svg" width="248" alt="WHMCS üçün DNA SSL"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/whmcs-ssl-dna?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://github.com/domainreseller/whmcs-ssl-dna/releases/latest">📥 Yüklə</a> · <a href="https://github.com/domainreseller/whmcs-ssl-dna#readme">📝 Sənədlər</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/wisecp-ssl-dna"><img src="./assets/card-ssl-wisecp.svg" width="248" alt="WiseCP 5 üçün DNA SSL"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/wisecp-ssl-dna?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://github.com/domainreseller/wisecp-ssl-dna/releases/latest">📥 Yüklə</a> · <a href="https://github.com/domainreseller/wisecp-ssl-dna#readme">📝 Sənədlər</a>
</td>
</tr>
<tr>
<td align="center">
<a href="https://github.com/domainreseller/reseller-hosting-whmcs"><img src="./assets/card-hosting-whmcs.svg" width="248" alt="WHMCS üçün DNA Reseller Hosting"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/reseller-hosting-whmcs?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://github.com/domainreseller/reseller-hosting-whmcs/releases/latest">📥 Yüklə</a> · <a href="https://github.com/domainreseller/reseller-hosting-whmcs#readme">📝 Sənədlər</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/reseller-hosting-wisecp"><img src="./assets/card-hosting-wisecp.svg" width="248" alt="WiseCP üçün DNA Reseller Hosting"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/reseller-hosting-wisecp?label=version&style=flat-square&color=12B385" alt="Son versiya"><br>
<a href="https://github.com/domainreseller/reseller-hosting-wisecp/releases/latest">📥 Yüklə</a> · <a href="https://github.com/domainreseller/reseller-hosting-wisecp#readme">📝 Sənədlər</a>
</td>
</tr>
</table>

## <img src="./assets/h-key.svg" width="30" height="30" alt=""> API giriş məlumatları

<img src="./assets/creds.svg" width="1200" alt="İstifadəçi adı (Username) sahəsinə Reseller ID-nizi, Şifrə (Password) sahəsinə isə API Key-inizi daxil edin; modul REST API-yə qoşulur.">

Hər modul eyni iki dəyəri tələb edir:

| Modul sahəsi | Nə daxil etməli |
|---|---|
| **İstifadəçi adı (Username)** | Reseller ID, `xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx` formatında UUID |
| **Şifrə (Password)** | API Key |

> [!TIP]
> **Reseller ID** və **API Key** məlumatlarınızı Domain Name API panelinizdə **API Tənzimləmələri (API Settings)** bölməsində tapa bilərsiniz.

> [!CAUTION]
> Bunlar **API giriş məlumatlarıdır**. Panelə giriş e-poçtunuz və şifrəniz burada **işləməyəcək**.

## <img src="./assets/h-faq.svg" width="30" height="30" alt=""> Domen satıcılığı: tez-tez verilən suallar

<details>
<summary><b>Domen satıcılığı (domen reseller) nədir?</b></summary>
<br>
Domen satıcısı domen adlarını öz brendi və öz qiymətləri ilə öz müştərilərinə satır, hər bir reyestrdə qeydiyyatı isə akkreditasiyalı registrator həyata keçirir. Domain Name API ilə bu registrator tərəfini əldə edirsiniz: 830+ uzantı, satıcı paneli və domen satıcılığı API-si, üstəlik artıq istifadə etdiyiniz billinq paneli üçün hazır modullar.
</details>

<details>
<summary><b>Domain Name API ilə necə domen satıcısı ola bilərəm?</b></summary>
<br>
<a href="https://www.domainnameapi.com/az/domain-reseller">Domen Satıcılığı səhifəsində</a> qeydiyyatdan keçin. Quraşdırma haqqı və minimum depozit tələbi yoxdur. Sonra panelinizdəki <b>API Tənzimləmələri (API Settings)</b> bölməsindən <b>Reseller ID</b> və <b>API Key</b> məlumatlarınızı götürün, yuxarıdakı siyahıdan billinq paneliniz üçün modulu quraşdırın və satışa başlayın.
</details>

<details>
<summary><b>AI agenti domenlərimi idarə edə bilərmi?</b></summary>
<br>
Bəli. <a href="https://github.com/domainreseller/cli">dna CLI</a> Domain Name API-nin hər əməliyyatını Claude Code, Cursor, Codex və digər MCP müştəriləri üçün MCP aləti kimi təqdim edir. Ödənişli və geri qaytarılmaz əməliyyatlar təsdiqinizi gözləyir, <code>--env ote</code> ilə isə agentlər əvvəlcə test mühitində işləyir.
</details>

<details>
<summary><b>Hansı faylı yükləməliyəm?</b></summary>
<br>
Həmişə modulun <b>son buraxılışına (latest release)</b> əlavə olunmuş paketi yükləyin (yuxarıdakı 📥 Yüklə linkləri). Yaşıl <b>Code → Download ZIP</b> düyməsi isə test olunmamış inkişaf budağını yükləyir.
</details>

<details>
<summary><b>WiseCP 3.x, yoxsa WiseCP 5?</b></summary>
<br>
WiseCP 5 (PHP 8.2+) üçün <a href="https://github.com/domainreseller/wisecp-dna-v5">wisecp-dna-v5</a>, WiseCP 3.x üçün isə <a href="https://github.com/domainreseller/wisecp-dna">wisecp-dna</a> modulundan istifadə edin.
</details>

<details>
<summary><b>Reseller ID və API Key məlumatlarımı harada tapa bilərəm?</b></summary>
<br>
Domain Name API panelinizdə <b>API Tənzimləmələri (API Settings)</b> bölməsində. Panelə giriş məlumatlarınız modullarda işləməyəcək.
</details>

<details>
<summary><b>Canlıya keçməzdən əvvəl test edə bilərəmmi?</b></summary>
<br>
Bəli. <a href="https://github.com/domainreseller/php-dna">PHP</a>, <a href="https://github.com/domainreseller/nodejs-dna">Node.js</a>, <a href="https://github.com/domainreseller/ruby-dna">Ruby</a>, <a href="https://github.com/domainreseller/python-dna">Python</a> və <a href="https://github.com/domainreseller/go-dna">Go</a> kitabxanaları test (OTE) mühitinə qoşula bilər; keçid üçün onların sənədlərinə baxın.
</details>

## <img src="./assets/h-connect.svg" width="30" height="30" alt=""> Əlaqə

<p align="center">
  <a href="https://www.domainnameapi.com/az"><img src="./assets/btn-web.svg" height="46" alt="Domain Name API: domen satıcılığı proqramı"></a>
  <a href="https://www.domainnameapi.com/az/domain-reseller"><img src="./assets/btn-signup.svg" height="46" alt="Domen satıcısı olun"></a>
  <a href="https://www.domainnameapi.com/az/domain-api-inteqrasiyasi"><img src="./assets/btn-api.svg" height="46" alt="Domen satıcılığı API-si və modullar"></a>
  <a href="https://www.domainnameapi.com/az/elaqe"><img src="./assets/btn-support.svg" height="46" alt="Dəstək"></a>
</p>

<br>

<p align="right">
  <sub>Alətlər</sub><br>
  <a href="https://github.com/domainreseller/Trabis-turkey-tr-domain-registration-tr-domain-kayit"><img src="./assets/pill-trabis.svg" height="34" alt="TRABIS .tr domen qeydiyyatı"></a>
  <br>
  <sub>Bizi izləyin</sub><br>
  <a href="https://www.atakdomain.com"><img src="./assets/pill-atak.svg" height="34" alt="atakdomain.com"></a>
  <a href="https://www.linkedin.com/company/domain-name-reseller/"><img src="./assets/pill-linkedin.svg" height="34" alt="LinkedIn"></a>
  <a href="https://x.com/dna_resellerapi"><img src="./assets/pill-x.svg" height="34" alt="X"></a>
  <a href="https://www.youtube.com/DomainReseller"><img src="./assets/pill-youtube.svg" height="34" alt="YouTube"></a>
</p>

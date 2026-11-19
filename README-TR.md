<!--
  Domain Name API (domainreseller): ICANN-accredited domain registrar founded by Atak Domain.
  Official registrar modules, SSL & reseller hosting modules and API libraries.
  Website: https://www.domainnameapi.com
  Every animation on this page is a hand-made SVG in ./assets. No external widgets, no trackers.
-->

<p align="center">
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-TR.md"><img src="./assets/lang-tr-on.svg" height="38" alt="Türkçe"></a>
  <a href="https://github.com/domainreseller"><img src="./assets/lang-en.svg" height="38" alt="English"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-DE.md"><img src="./assets/lang-de.svg" height="38" alt="Deutsch"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-SA.md"><img src="./assets/lang-sa.svg" height="38" alt="العربية"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-NL.md"><img src="./assets/lang-nl.svg" height="38" alt="Nederlands"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-AZ.md"><img src="./assets/lang-az.svg" height="38" alt="Azərbaycanca"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-CN.md"><img src="./assets/lang-cn.svg" height="38" alt="中文"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-FR.md"><img src="./assets/lang-fr.svg" height="38" alt="Français"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-IT.md"><img src="./assets/lang-it.svg" height="38" alt="Italiano"></a>
</p>

<a href="https://www.domainnameapi.com/tr/domain-reseller"><img src="./assets/hero.svg" width="1200" alt="Domain Name API: domain bayisi olun. REST API ve WHMCS, WiseCP, Blesta ve daha fazlası için hazır modüllerle 830+ alan adı uzantısını kendi markanızla satın."></a>

<h1 align="center">Domain Bayiliği API ve Modülleri</h1>

<p align="center">
  <b>Domain Name API</b>, <a href="https://www.atakdomain.com">Atak Domain</a> tarafından kurulan ICANN akreditasyonlu bir kayıt kuruluşu ve <b>domain bayiliği (domain reseller)</b> programıdır. <a href="https://www.domainnameapi.com/tr/domain-reseller">200+ ülkedeki 40.000+ domain bayisine</a> katılın, 830+ alan adı uzantısını kendi markanızla satın; kayıt, transfer ve yenileme işlemlerini <a href="https://www.domainnameapi.com/tr/api-entegrasyonu">domain bayiliği API'miz</a> ya da aşağıdaki WHMCS, WiseCP, Blesta, HostBill, ClientExec, FOSSBilling ve HostFact hazır modülleriyle otomatikleştirin.
</p>

<p align="center">
  <a href="https://github.com/domainreseller/cli"><img src="./assets/cli-ribbon.svg" width="760" alt="Yeni: dna, Domain Name API'nin CLI aracı ve MCP sunucusu. Alan adlarınızı terminalden, Claude Code, Cursor ve Codex'ten yönetin."></a>
</p>

<img src="./assets/stats.svg" width="1200" alt="830+ TLD, 40.000+ aktif domain bayisi, 200+ ülke, 20+ yıllık deneyim.">

<img src="./assets/tlds.svg" width="1200" alt="Satabileceğiniz 830+ uzantıdan bazıları: .com, .net, .org, .com.tr, .xyz, .shop ve daha fazlası.">

## <img src="./assets/h-cli.svg" width="30" height="30" alt=""> dna CLI ve AI ajanları için MCP sunucusu

En yeni aracımız <b>dna</b>, Domain Name API'nin tüm işlemlerini terminalinizden ve AI ajanlarınızdan çalıştırır. Alan adı sorgulayın, kaydedin, yenileyin ve transfer edin; DNS, DNSSEC, SSL ve hosting'i yönetin. Ücretli bir işlemden önce güvenlik kapısı her zaman onayınızı bekler.

<a href="https://github.com/domainreseller/cli"><img src="./assets/cli.svg" width="1200" alt="dna CLI: Domain Name API'nin 64 işleminin tamamını ve 65 MCP aracını içeren tek bir dosya. Terminalde dna kuruluyor, Claude Code'a bağlanıyor, brandname.com sorgulanıyor, ücretli kayıt --dry-run ile önizleniyor ve --yes ile tamamlanıyor."></a>

<p align="center">
  <a href="https://github.com/domainreseller/cli/releases/latest"><img src="./assets/btn-cli.svg" height="46" alt="dna CLI'yi indirin"></a>
  <a href="https://github.com/domainreseller/cli#connect-your-ai-agent"><img src="./assets/btn-cli-agent.svg" height="46" alt="AI ajanınızı dna'ya bağlayın"></a>
  <a href="https://github.com/domainreseller/cli#readme"><img src="./assets/btn-cli-docs.svg" height="46" alt="dna CLI dokümantasyonu"></a>
</p>

```bash
# Linux / macOS kurulumu
curl -fsSL https://raw.githubusercontent.com/domainreseller/cli/main/scripts/install.sh | sh

# Claude Code'a bağlayın (önce OTE test ortamında başlayın)
claude mcp add dna -- dna mcp serve --env ote

# Ya da etkileşimli kabuk için sadece dna yazın
dna
```

```powershell
# Windows kurulumu (PowerShell)
irm https://raw.githubusercontent.com/domainreseller/cli/main/scripts/install.ps1 | iex
```

### v1.1’de yeni: sadece `dna` yazın

Etkileşimli kabuk, siz yazarken alan adlarını canlı sorgular, alan adlarınızı menülerden yönetmenizi sağlar ve kayıt ile yenilemede size adım adım eşlik eder. Her satın alma onayınızı bekler; **Connect an AI agent** ise Claude Code, ChatGPT, Cursor ve 20’den fazla AI ajanını birkaç tuşla kurar.

<a href="https://github.com/domainreseller/cli#interactive-shell"><img src="./assets/cli-shell-tr.svg" width="1200" alt="dna etkileşimli kabuğu: acme yazınca boş uzantılar fiyatlarıyla görünür, kullanıcı acme.net’i seçer, kısa kayıt formunu doldurur, ücretli adımı onay kutusunda onaylar ve alan adı kaydedilir."></a>

### Claude ve ChatGPT için hazır promptlar

Bir promptu kopyalayın, AI asistanınıza yapıştırın ve gerisini ona bırakın. Her prompt OTE test ortamında başlar ve ücretli bir işlemden önce onayınızı bekler.

**dna'yı Claude Code'da kurun**

```text
Benim için dna CLI'yi kur (https://github.com/domainreseller/cli).
1. İşletim sistemime uygun resmi kurulum betiğiyle kur, ardından `dna version` ve
   `dna doctor` komutlarını çalıştır.
2. Claude Code skill'ini `dna agent skill --install` ile kur ve MCP sunucusunu
   `claude mcp add dna -- dna mcp serve --env ote` ile ekle.
3. API anahtarımı bu sohbete yapıştırmamı isteme. `dna auth login --env ote` komutunu
   benim çalıştırmamı söyle, sonra bağlantıyı `dna --ote account get` ile kontrol et.
Yalnızca OTE test ortamında çalış ve onayım olmadan asla `--yes` kullanma.
```

**dna'yı ChatGPT Codex'te kurun**

```text
Benim için dna CLI'yi kur (https://github.com/domainreseller/cli).
1. İşletim sistemime uygun resmi kurulum betiğiyle kur, ardından `dna version` ve
   `dna doctor` komutlarını çalıştır.
2. Codex yapılandırmama (`~/.codex/config.toml`) `dna` adında bir MCP sunucusu olarak
   ekle: komut `dna`, argümanlar `mcp serve --env ote`.
3. API anahtarımı bu sohbete yapıştırmamı isteme. `dna auth login --env ote` komutunu
   benim çalıştırmamı söyle, sonra bağlantıyı `dna --ote account get` ile kontrol et.
Yalnızca OTE test ortamında çalış ve onayım olmadan asla `--yes` kullanma.
```

**Terminaliniz yok mu? ChatGPT veya Claude sohbetine sorun**

```text
https://raw.githubusercontent.com/domainreseller/cli/main/llms.txt dosyasını ve
bağlantı verdiği dna dokümanlarını oku. Sonra OTE test ortamında bir alan adı
kaydetmek için gereken dna komutlarını adım adım ve eksiksiz ver: kurulum, giriş,
sorgulama, `--dry-run` ile önizleme ve kayıt. Her komutun ne yaptığını açıkla.
```

<details>
<summary><b>Günlük işler için daha fazla prompt</b></summary>
<br>

**Alan adı bulun ve kaydedin**

```text
dna ile brandname.com, brandname.net ve brandname.io alan adlarının müsait olup
olmadığını kontrol et. Sonuçları fiyatlarıyla bir tabloda göster, ardından müsait
olanlar arasında en ucuzunun kaydını `--dry-run` ile önizle. Ben evet demeden hiçbir
şey kaydetme.
```

**Yaklaşan yenilemeler**

```text
dna ile önümüzdeki 60 gün içinde süresi dolacak alan adlarımı yenileme fiyatlarıyla
birlikte, bitiş tarihine göre sıralı listele. Hiçbir şeyi yenileme.
```

**Alan adını bir sunucuya yönlendirin**

```text
dna ile example.com alan adını 203.0.113.10 adresine yönlendir: `@` ve `www` için A
kayıtları ekle, ardından son DNS bölgesini göster. Mevcut bir kaydı değiştirmeden veya
silmeden önce bana sor.
```

**Alan adı transferi**

```text
dna ile example.org alan adının hesabıma transfer edilip edilemeyeceğini kontrol et,
eksik olanları söyle (auth kodu, kilidin kaldırılması) ve transferi `--dry-run` ile
önizle.
```

**SSL sertifikası sipariş edin**

```text
dna ile example.com için en ucuz DV SSL sertifikasını bul, bir CSR oluştur ve siparişi
önizle. Satın almadan önce onayımı bekle.
```

</details>

## <img src="./assets/h-programs.svg" width="30" height="30" alt=""> Domain, SSL ve hosting bayilik programları

Tek Domain Name API hesabı, üç bayilik programı: alan adlarını, SSL sertifikalarını ve white-label hosting hizmetini kendi markanızla satın.

<img src="./assets/programs.svg" width="1200" alt="Tek Domain Name API hesabı, üç bayilik programı: Domain Bayiliği (toptan fiyatlarla 830+ TLD), SSL Bayiliği (DV, OV, EV ve wildcard sertifikalar) ve Reseller Hosting (white-label cPanel ve Plesk hosting).">

<p align="center">
  <a href="https://www.domainnameapi.com/tr/domain-reseller"><img src="./assets/btn-domain-reseller.svg" height="46" alt="Domain Bayiliği programı"></a>
  <a href="https://www.domainnameapi.com/tr/ssl-reseller"><img src="./assets/btn-ssl-reseller.svg" height="46" alt="SSL Bayiliği programı"></a>
  <a href="https://www.domainnameapi.com/tr/reseller-hosting"><img src="./assets/btn-reseller-hosting.svg" height="46" alt="Reseller Hosting programı"></a>
</p>

## <img src="./assets/h-flow.svg" width="30" height="30" alt=""> Domain bayiliği API'si nasıl çalışır

<img src="./assets/flow.svg" width="1200" alt="Müşterileriniz sitenizden sipariş verir, faturalandırma paneliniz isteği DNA modülü üzerinden Domain Name API'ye iletir, Domain Name API de kayıt otoriteleriyle (registry) EPP üzerinden iletişim kurar.">

## <img src="./assets/h-modules.svg" width="30" height="30" alt=""> Domain bayiliği modülleri

Faturalandırma panelinizi Domain Name API'ye bağlayan registrar modülleri; böylece müşterileriniz kendi sitenizde alan adı sorgulayabilir, kaydedebilir, transfer edebilir ve yenileyebilir.

> [!IMPORTANT]
> **Modülleri her zaman aşağıdaki _son sürüm (latest release)_ bağlantılarından indirin.** Release paketleri sürüm numaralıdır, test edilmiştir ve canlı ortamda kullanıma hazırdır.

> [!WARNING]
> GitHub'ın yeşil **Code → Download ZIP** butonunu **kullanmayın**; bu buton test edilmemiş geliştirme dalını indirir.

<table align="center">
<tr>
<td align="center">
<a href="https://github.com/domainreseller/whmcs-dna"><img src="./assets/card-whmcs.svg" width="248" alt="WHMCS domain bayiliği modülü"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/whmcs-dna?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://github.com/domainreseller/whmcs-dna/releases/latest">📥 İndir</a> · <a href="https://github.com/domainreseller/whmcs-dna#readme">📝 Dokümantasyon</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/wisecp-dna-v5"><img src="./assets/card-wisecp5.svg" width="248" alt="WiseCP 5 domain bayiliği modülü"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/wisecp-dna-v5?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://github.com/domainreseller/wisecp-dna-v5/releases/latest">📥 İndir</a> · <a href="https://github.com/domainreseller/wisecp-dna-v5#readme">📝 Dokümantasyon</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/wisecp-dna"><img src="./assets/card-wisecp.svg" width="248" alt="WiseCP 3.x domain bayiliği modülü"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/wisecp-dna?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://github.com/domainreseller/wisecp-dna/releases/latest">📥 İndir</a> · <a href="https://github.com/domainreseller/wisecp-dna#readme">📝 Dokümantasyon</a>
</td>
</tr>
<tr>
<td align="center">
<a href="https://github.com/domainreseller/blesta-dna"><img src="./assets/card-blesta.svg" width="248" alt="Blesta domain bayiliği modülü"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/blesta-dna?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://github.com/domainreseller/blesta-dna/releases/latest">📥 İndir</a> · <a href="https://github.com/domainreseller/blesta-dna#readme">📝 Dokümantasyon</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/hostbill-dna"><img src="./assets/card-hostbill.svg" width="248" alt="HostBill domain bayiliği modülü"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/hostbill-dna?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://github.com/domainreseller/hostbill-dna/releases/latest">📥 İndir</a> · <a href="https://github.com/domainreseller/hostbill-dna#readme">📝 Dokümantasyon</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/clientexec-dna"><img src="./assets/card-clientexec.svg" width="248" alt="ClientExec domain bayiliği eklentisi"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/clientexec-dna?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://github.com/domainreseller/clientexec-dna/releases/latest">📥 İndir</a> · <a href="https://github.com/domainreseller/clientexec-dna#readme">📝 Dokümantasyon</a>
</td>
</tr>
<tr>
<td align="center">
<a href="https://github.com/domainreseller/fossbilling-dna"><img src="./assets/card-fossbilling.svg" width="248" alt="FOSSBilling domain bayiliği modülü"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/fossbilling-dna?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://github.com/domainreseller/fossbilling-dna/releases/latest">📥 İndir</a> · <a href="https://github.com/domainreseller/fossbilling-dna#readme">📝 Dokümantasyon</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/hostfact-dna"><img src="./assets/card-hostfact.svg" width="248" alt="HostFact domain bayiliği modülü"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/hostfact-dna?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://github.com/domainreseller/hostfact-dna/releases/latest">📥 İndir</a> · <a href="https://github.com/domainreseller/hostfact-dna#readme">📝 Dokümantasyon</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/dna-extended"><img src="./assets/card-extended.svg" width="248" alt="Extended WHMCS addon modülü"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/dna-extended?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://github.com/domainreseller/dna-extended/releases/latest">📥 İndir</a> · <a href="https://github.com/domainreseller/dna-extended#readme">📝 Dokümantasyon</a>
</td>
</tr>
</table>

## <img src="./assets/h-sdk.svg" width="30" height="30" alt=""> Domain bayiliği API kütüphaneleri

Kendi entegrasyonunuzu mu geliştiriyorsunuz? PHP, Node.js, Ruby, Python ve Go kütüphanelerimizle domain bayiliği API'sini doğrudan çağırın.

<table align="center">
<tr>
<td align="center">
<a href="https://github.com/domainreseller/php-dna"><img src="./assets/card-php.svg" width="248" alt="Domain bayiliği API'si için PHP kütüphanesi"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/php-dna?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://github.com/domainreseller/php-dna/releases/latest">📥 İndir</a> · <a href="https://github.com/domainreseller/php-dna#readme">📝 Dokümantasyon</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/nodejs-dna"><img src="./assets/card-nodejs.svg" width="248" alt="Domain bayiliği API'si için Node.js kütüphanesi"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/nodejs-dna?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://github.com/domainreseller/nodejs-dna/releases/latest">📥 İndir</a> · <a href="https://github.com/domainreseller/nodejs-dna#readme">📝 Dokümantasyon</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/ruby-dna"><img src="./assets/card-ruby.svg" width="248" alt="Domain bayiliği API'si için Ruby kütüphanesi"></a><br>
<img src="https://img.shields.io/gem/v/domainnameapi?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://rubygems.org/gems/domainnameapi">📥 İndir</a> · <a href="https://github.com/domainreseller/ruby-dna#readme">📝 Dokümantasyon</a>
</td>
</tr>
</table>

<table align="center">
<tr>
<td align="center">
<a href="https://github.com/domainreseller/python-dna"><img src="./assets/card-python.svg" width="248" alt="Domain bayiliği API'si için Python kütüphanesi"></a><br>
<img src="https://img.shields.io/pypi/v/domainnameapi?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://pypi.org/project/domainnameapi/">📥 İndir</a> · <a href="https://github.com/domainreseller/python-dna#readme">📝 Dokümantasyon</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/go-dna"><img src="./assets/card-go.svg" width="248" alt="Domain bayiliği API'si için Go kütüphanesi"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/go-dna?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://github.com/domainreseller/go-dna/releases/latest">📥 İndir</a> · <a href="https://github.com/domainreseller/go-dna#readme">📝 Dokümantasyon</a>
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
<summary><b>Hızlı başlangıç: PHP</b></summary>

```php
require_once __DIR__.'/vendor/autoload.php';

$dna = new \DomainNameApi\DomainNameAPI_PHPLibrary($resellerId, $apiKey);

$dna->CheckAvailability(['hello', 'world123x0'], ['com', 'net'], 1, 'create');
```

</details>

<details>
<summary><b>Hızlı başlangıç: Node.js</b></summary>

```js
const DomainNameApi = require('nodejs-dna');

const api = new DomainNameApi('xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx', 'your-api-key');

const domains = await api.CheckAvailability(['hello', 'world'], ['com', 'net'], 1);
```

</details>

<details>
<summary><b>Hızlı başlangıç: Ruby</b></summary>

```ruby
require 'domainnameapi'

dna = DomainNameApi::Client.new('xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx', 'your-api-key')

dna.check_availability(['hello', 'world123x0'], ['com', 'net'], 1, 'create')
```

</details>

<details>
<summary><b>Hızlı başlangıç: Python</b></summary>

```python
from domainnameapi import DomainNameAPI

dna = DomainNameAPI("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "your-api-key")

dna.check_availability(["hello", "world123x0"], ["com", "net"], 1, "create")
```

</details>

<details>
<summary><b>Hızlı başlangıç: Go</b></summary>

```go
import dna "github.com/domainreseller/go-dna"

client := dna.New("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "your-api-key", false)

result := client.CheckAvailability([]string{"hello", "world123x0"}, []string{"com", "net"}, 1, "create")
```

</details>

## <img src="./assets/h-ssl.svg" width="30" height="30" alt=""> SSL ve reseller hosting modülleri

Alan adlarından fazlasını satın: [SSL Bayiliği](https://www.domainnameapi.com/tr/ssl-reseller) ve [Reseller Hosting](https://www.domainnameapi.com/tr/reseller-hosting) programlarımızın modülleriyle SSL sertifikaları ve cPanel / Plesk hosting de aynı hesaptan.

<table align="center">
<tr>
<td align="center">
<a href="https://github.com/domainreseller/whmcs-ssl-dna"><img src="./assets/card-ssl-whmcs.svg" width="248" alt="WHMCS için DNA SSL"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/whmcs-ssl-dna?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://github.com/domainreseller/whmcs-ssl-dna/releases/latest">📥 İndir</a> · <a href="https://github.com/domainreseller/whmcs-ssl-dna#readme">📝 Dokümantasyon</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/wisecp-ssl-dna"><img src="./assets/card-ssl-wisecp.svg" width="248" alt="WiseCP 5 için DNA SSL"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/wisecp-ssl-dna?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://github.com/domainreseller/wisecp-ssl-dna/releases/latest">📥 İndir</a> · <a href="https://github.com/domainreseller/wisecp-ssl-dna#readme">📝 Dokümantasyon</a>
</td>
</tr>
<tr>
<td align="center">
<a href="https://github.com/domainreseller/reseller-hosting-whmcs"><img src="./assets/card-hosting-whmcs.svg" width="248" alt="WHMCS için DNA Reseller Hosting"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/reseller-hosting-whmcs?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://github.com/domainreseller/reseller-hosting-whmcs/releases/latest">📥 İndir</a> · <a href="https://github.com/domainreseller/reseller-hosting-whmcs#readme">📝 Dokümantasyon</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/reseller-hosting-wisecp"><img src="./assets/card-hosting-wisecp.svg" width="248" alt="WiseCP için DNA Reseller Hosting"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/reseller-hosting-wisecp?label=version&style=flat-square&color=12B385" alt="Son sürüm"><br>
<a href="https://github.com/domainreseller/reseller-hosting-wisecp/releases/latest">📥 İndir</a> · <a href="https://github.com/domainreseller/reseller-hosting-wisecp#readme">📝 Dokümantasyon</a>
</td>
</tr>
</table>

## <img src="./assets/h-key.svg" width="30" height="30" alt=""> API kimlik bilgileri

<img src="./assets/creds.svg" width="1200" alt="Kullanıcı adı (Username) alanına Reseller ID'nizi, Şifre (Password) alanına API Key'inizi girin; modül REST API'ye bağlanır.">

Her modül aynı iki değeri ister:

| Modül alanı | Girilecek değer |
|---|---|
| **Kullanıcı adı (Username)** | Reseller ID, `xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx` biçiminde bir UUID |
| **Şifre (Password)** | API Key |

> [!TIP]
> **Reseller ID** ve **API Key** bilgilerinizi Domain Name API panelinizde **API Ayarları (API Settings)** bölümünde bulabilirsiniz.

> [!CAUTION]
> Bunlar **API kimlik bilgileridir**. Panel giriş e-postanız ve şifreniz burada **çalışmaz**.

## <img src="./assets/h-faq.svg" width="30" height="30" alt=""> Domain bayiliği hakkında sık sorulan sorular

<details>
<summary><b>Domain bayiliği (alan adı bayiliği) nedir?</b></summary>
<br>
Domain bayisi, alan adlarını kendi markası ve kendi fiyatlarıyla kendi müşterilerine satar; her registry nezdindeki kayıt işlemini ise akreditasyonlu bir kayıt kuruluşu yürütür. Domain Name API ile bu kayıt kuruluşu tarafına sahip olursunuz: 830+ uzantı, bayi paneli ve domain bayiliği API'si, ayrıca halihazırda kullandığınız faturalandırma paneli için hazır modüller.
</details>

<details>
<summary><b>Domain Name API ile nasıl domain bayisi olurum?</b></summary>
<br>
<a href="https://www.domainnameapi.com/tr/domain-reseller">Domain Bayiliği sayfasından</a> kaydolun. Kurulum ücreti yoktur, minimum bakiye yükleme zorunluluğu da yoktur. Ardından panelinizdeki <b>API Ayarları (API Settings)</b> bölümünden <b>Reseller ID</b> ve <b>API Key</b> bilgilerinizi alın, yukarıdaki listeden faturalandırma paneliniz için modülü kurun ve satışa başlayın.
</details>

<details>
<summary><b>AI ajanı alan adlarımı yönetebilir mi?</b></summary>
<br>
Evet. <a href="https://github.com/domainreseller/cli">dna CLI</a>, Domain Name API'nin her işlemini Claude Code, Cursor, Codex ve diğer MCP istemcileri için bir MCP aracı olarak sunar. Ücretli ve geri alınamaz işlemler onayınızı bekler; <code>--env ote</code> ile ajanlar önce test ortamında çalışır.
</details>

<details>
<summary><b>Hangi dosyayı indirmeliyim?</b></summary>
<br>
Her zaman modülün <b>son sürümüne (latest release)</b> ekli paketi indirin (yukarıdaki 📥 İndir bağlantıları). Yeşil <b>Code → Download ZIP</b> butonu ise test edilmemiş geliştirme dalını indirir.
</details>

<details>
<summary><b>WiseCP 3.x mi, WiseCP 5 mi?</b></summary>
<br>
WiseCP 5 (PHP 8.2+) için <a href="https://github.com/domainreseller/wisecp-dna-v5">wisecp-dna-v5</a>, WiseCP 3.x için <a href="https://github.com/domainreseller/wisecp-dna">wisecp-dna</a> modülünü kullanın.
</details>

<details>
<summary><b>Reseller ID ve API Key bilgilerimi nerede bulurum?</b></summary>
<br>
Domain Name API panelinizde <b>API Ayarları (API Settings)</b> bölümünde. Panel giriş bilgileriniz modüllerde çalışmaz.
</details>

<details>
<summary><b>Canlıya geçmeden önce test edebilir miyim?</b></summary>
<br>
Evet. <a href="https://github.com/domainreseller/php-dna">PHP</a>, <a href="https://github.com/domainreseller/nodejs-dna">Node.js</a>, <a href="https://github.com/domainreseller/ruby-dna">Ruby</a>, <a href="https://github.com/domainreseller/python-dna">Python</a> ve <a href="https://github.com/domainreseller/go-dna">Go</a> kütüphaneleri test (OTE) ortamına bağlanabilir; bu geçiş için kütüphanelerin dokümantasyonuna bakın.
</details>

## <img src="./assets/h-connect.svg" width="30" height="30" alt=""> Bağlantılar

<p align="center">
  <a href="https://www.domainnameapi.com/tr"><img src="./assets/btn-web.svg" height="46" alt="Domain Name API: domain bayiliği programı"></a>
  <a href="https://www.domainnameapi.com/tr/domain-reseller"><img src="./assets/btn-signup.svg" height="46" alt="Domain bayisi olun"></a>
  <a href="https://www.domainnameapi.com/tr/api-entegrasyonu"><img src="./assets/btn-api.svg" height="46" alt="Domain bayiliği API'si ve modülleri"></a>
  <a href="https://www.domainnameapi.com/tr/iletisim"><img src="./assets/btn-support.svg" height="46" alt="Destek"></a>
</p>

<br>

<p align="right">
  <sub>Araçlar</sub><br>
  <a href="https://github.com/domainreseller/Trabis-turkey-tr-domain-registration-tr-domain-kayit"><img src="./assets/pill-trabis.svg" height="34" alt="TRABIS .tr alan adı kaydı"></a>
  <br>
  <sub>Bizi takip edin</sub><br>
  <a href="https://www.atakdomain.com"><img src="./assets/pill-atak.svg" height="34" alt="atakdomain.com"></a>
  <a href="https://www.linkedin.com/company/domain-name-reseller/"><img src="./assets/pill-linkedin.svg" height="34" alt="LinkedIn"></a>
  <a href="https://x.com/dna_resellerapi"><img src="./assets/pill-x.svg" height="34" alt="X"></a>
  <a href="https://www.youtube.com/DomainReseller"><img src="./assets/pill-youtube.svg" height="34" alt="YouTube"></a>
</p>

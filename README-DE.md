<!--
  Domain Name API (domainreseller): ICANN-accredited domain registrar founded by Atak Domain.
  Official registrar modules, SSL & reseller hosting modules and API libraries.
  Website: https://www.domainnameapi.com
  Every animation on this page is a hand-made SVG in ./assets. No external widgets, no trackers.
-->

<p align="center">
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-TR.md"><img src="./assets/lang-tr.svg" height="38" alt="Türkçe"></a>
  <a href="https://github.com/domainreseller"><img src="./assets/lang-en.svg" height="38" alt="English"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-DE.md"><img src="./assets/lang-de-on.svg" height="38" alt="Deutsch"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-SA.md"><img src="./assets/lang-sa.svg" height="38" alt="العربية"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-NL.md"><img src="./assets/lang-nl.svg" height="38" alt="Nederlands"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-AZ.md"><img src="./assets/lang-az.svg" height="38" alt="Azərbaycanca"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-CN.md"><img src="./assets/lang-cn.svg" height="38" alt="中文"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-FR.md"><img src="./assets/lang-fr.svg" height="38" alt="Français"></a>
  <a href="https://github.com/domainreseller/domainreseller/blob/main/README-IT.md"><img src="./assets/lang-it.svg" height="38" alt="Italiano"></a>
</p>

<a href="https://www.domainnameapi.com/de/domain-reseller"><img src="./assets/hero.svg" width="1200" alt="Domain Name API: Werden Sie Domain-Reseller. Verkaufen Sie 830+ Domain-Endungen unter Ihrer eigenen Marke, mit der REST API und fertigen Modulen für WHMCS, WiseCP, Blesta und mehr."></a>

<h1 align="center">Domain-Reseller-API &amp; Module</h1>

<p align="center">
  <b>Domain Name API</b> ist ein ICANN-akkreditierter Registrar und <b>Domain-Reseller-Programm</b>, gegründet von <a href="https://www.atakdomain.com">Atak Domain</a>. Schließen Sie sich <a href="https://www.domainnameapi.com/de/domain-reseller">über 40.000 Domain-Resellern in mehr als 200 Ländern</a> an, verkaufen Sie über 830 Domain-Endungen unter Ihrer eigenen Marke und automatisieren Sie Registrierung, Transfer und Verlängerung mit unserer <a href="https://www.domainnameapi.com/de/domain-api-integration">Domain-Reseller-API</a> oder den fertigen Modulen für WHMCS, WiseCP, Blesta, HostBill, ClientExec, FOSSBilling und HostFact weiter unten.
</p>

<p align="center">
  <a href="https://github.com/domainreseller/cli"><img src="./assets/cli-ribbon.svg" width="760" alt="Neu: dna, die CLI und der MCP-Server von Domain Name API. Verwalten Sie Domains im Terminal, in Claude Code, Cursor und Codex."></a>
</p>

<img src="./assets/stats.svg" width="1200" alt="830+ TLDs, 40.000+ aktive Domain-Reseller, 200+ Länder, 20+ Jahre Erfahrung.">

<img src="./assets/tlds.svg" width="1200" alt="Einige der 830+ Domain-Endungen, die Sie verkaufen können: .com, .net, .org, .com.tr, .xyz, .shop und mehr.">

## <img src="./assets/h-cli.svg" width="30" height="30" alt=""> dna CLI & MCP-Server für KI-Agenten

Unser neuestes Werkzeug: <b>dna</b> führt jede Operation der Domain Name API im Terminal und über KI-Agenten aus. Domains suchen, registrieren, verlängern und transferieren, DNS, DNSSEC, SSL und Hosting verwalten – mit einer Sicherheitsschranke, die vor jeder kostenpflichtigen Aktion auf Ihre Freigabe wartet.

<a href="https://github.com/domainreseller/cli"><img src="./assets/cli.svg" width="1200" alt="dna CLI: eine einzige Binärdatei mit allen 64 Operationen der Domain Name API und 65 MCP-Tools. Ein Terminal installiert dna, verbindet es mit Claude Code, sucht brandname.com, zeigt die kostenpflichtige Registrierung mit --dry-run als Vorschau und registriert sie mit --yes."></a>

<p align="center">
  <a href="https://github.com/domainreseller/cli/releases/latest"><img src="./assets/btn-cli.svg" height="46" alt="dna CLI herunterladen"></a>
  <a href="https://github.com/domainreseller/cli#connect-your-ai-agent"><img src="./assets/btn-cli-agent.svg" height="46" alt="KI-Agenten mit dna verbinden"></a>
  <a href="https://github.com/domainreseller/cli#readme"><img src="./assets/btn-cli-docs.svg" height="46" alt="Dokumentation der dna CLI"></a>
</p>

```bash
# Installation unter Linux / macOS
curl -fsSL https://raw.githubusercontent.com/domainreseller/cli/main/scripts/install.sh | sh

# Mit Claude Code verbinden (zuerst in der OTE-Testumgebung)
claude mcp add dna -- dna mcp serve --env ote
```

```powershell
# Installation unter Windows (PowerShell)
irm https://raw.githubusercontent.com/domainreseller/cli/main/scripts/install.ps1 | iex
```

### Fertige Prompts für Claude und ChatGPT

Kopieren Sie einen Prompt, fügen Sie ihn in Ihren KI-Assistenten ein und lassen Sie ihn die Arbeit erledigen. Jeder Prompt beginnt in der OTE-Testumgebung und hält vor jeder kostenpflichtigen Aktion an, bis Sie sie freigeben.

**dna in Claude Code einrichten**

```text
Richte die dna CLI für mich ein (https://github.com/domainreseller/cli).
1. Installiere sie mit dem offiziellen Installationsskript für mein Betriebssystem und
   führe dann `dna version` und `dna doctor` aus.
2. Installiere den Skill für Claude Code mit `dna agent skill --install` und füge den
   MCP-Server mit `claude mcp add dna -- dna mcp serve --env ote` hinzu.
3. Fordere mich nicht auf, meinen API-Key in diesen Chat einzufügen. Sag mir, dass ich
   `dna auth login --env ote` selbst ausführen soll, und prüfe dann die Verbindung mit
   `dna --ote account get`.
Arbeite nur in der OTE-Testumgebung und verwende `--yes` niemals ohne meine Freigabe.
```

**dna in ChatGPT Codex einrichten**

```text
Richte die dna CLI für mich ein (https://github.com/domainreseller/cli).
1. Installiere sie mit dem offiziellen Installationsskript für mein Betriebssystem und
   führe dann `dna version` und `dna doctor` aus.
2. Trage sie in meiner Codex-Konfiguration (`~/.codex/config.toml`) als MCP-Server mit
   dem Namen `dna`, dem Befehl `dna` und den Argumenten `mcp serve --env ote` ein.
3. Fordere mich nicht auf, meinen API-Key in diesen Chat einzufügen. Sag mir, dass ich
   `dna auth login --env ote` selbst ausführen soll, und prüfe dann die Verbindung mit
   `dna --ote account get`.
Arbeite nur in der OTE-Testumgebung und verwende `--yes` niemals ohne meine Freigabe.
```

**Kein Terminal? Fragen Sie ChatGPT oder Claude im Chat**

```text
Lies https://raw.githubusercontent.com/domainreseller/cli/main/llms.txt und die dort
verlinkte dna-Dokumentation. Gib mir dann Schritt für Schritt die genauen dna-Befehle,
um eine Domain in der OTE-Testumgebung zu registrieren: installieren, anmelden,
suchen, mit `--dry-run` als Vorschau anzeigen und registrieren. Erkläre, was jeder
Befehl macht.
```

<details>
<summary><b>Weitere Prompts für die tägliche Arbeit</b></summary>
<br>

**Domain finden und registrieren**

```text
Prüfe mit dna, ob brandname.com, brandname.net und brandname.io verfügbar sind. Zeig
die Ergebnisse mit Preisen in einer Tabelle und zeig dann mit `--dry-run` eine
Vorschau der Registrierung für die günstigste verfügbare Domain. Registriere nichts,
bevor ich Ja sage.
```

**Anstehende Verlängerungen**

```text
Liste mit dna meine Domains auf, die in den nächsten 60 Tagen ablaufen, mit ihren
Verlängerungspreisen und sortiert nach Ablaufdatum. Verlängere nichts.
```

**Domain auf einen Server zeigen lassen**

```text
Lass example.com mit dna auf 203.0.113.10 zeigen: Lege A-Records für `@` und `www` an
und zeig mir anschließend die finale DNS-Zone. Frag mich, bevor du einen bestehenden
Eintrag änderst oder löschst.
```

**Domain in Ihr Konto transferieren**

```text
Prüfe mit dna, ob example.org in mein Konto transferiert werden kann, sag mir, was ich
noch brauche (Auth-Code, Entsperrung), und zeig mit `--dry-run` eine Vorschau des
Transfers.
```

**SSL-Zertifikat bestellen**

```text
Finde mit dna das günstigste DV-SSL-Zertifikat für example.com, erstelle einen CSR und
zeig mir eine Vorschau der Bestellung. Warte vor dem Kauf auf meine Freigabe.
```

</details>

## <img src="./assets/h-programs.svg" width="30" height="30" alt=""> Reseller-Programme für Domains, SSL & Hosting

Ein Konto bei Domain Name API, drei Reseller-Programme: Verkaufen Sie Domainnamen, SSL-Zertifikate und White-Label-Hosting unter Ihrer eigenen Marke.

<img src="./assets/programs.svg" width="1200" alt="Ein Konto bei Domain Name API, drei Reseller-Programme: Domain Reseller (830+ TLDs zu Großhandelspreisen), SSL Reseller (DV-, OV-, EV- und Wildcard-Zertifikate) und Reseller Hosting (White-Label-Hosting mit cPanel und Plesk).">

<p align="center">
  <a href="https://www.domainnameapi.com/de/domain-reseller"><img src="./assets/btn-domain-reseller.svg" height="46" alt="Domain-Reseller-Programm"></a>
  <a href="https://www.domainnameapi.com/de/ssl-reseller"><img src="./assets/btn-ssl-reseller.svg" height="46" alt="SSL-Reseller-Programm"></a>
  <a href="https://www.domainnameapi.com/de/reseller-hosting"><img src="./assets/btn-reseller-hosting.svg" height="46" alt="Reseller-Hosting-Programm"></a>
</p>

## <img src="./assets/h-flow.svg" width="30" height="30" alt=""> So funktioniert die Domain-Reseller-API

<img src="./assets/flow.svg" width="1200" alt="Ihre Kunden bestellen auf Ihrer Website, Ihr Abrechnungssystem sendet die Anfrage über das DNA-Modul an Domain Name API, und Domain Name API kommuniziert per EPP mit den Registries.">

## <img src="./assets/h-modules.svg" width="30" height="30" alt=""> Domain-Reseller-Module

Registrar-Module, die Ihr Abrechnungssystem mit Domain Name API verbinden, damit Ihre Kunden Domains direkt auf Ihrer Website suchen, registrieren, transferieren und verlängern können.

> [!IMPORTANT]
> **Laden Sie Module immer über die Links zum _neuesten Release_ weiter unten herunter.** Release-Pakete sind versioniert, getestet und produktionsreif.

> [!WARNING]
> Verwenden Sie **nicht** den grünen GitHub-Button **Code → Download ZIP**; damit laden Sie den ungetesteten Entwicklungszweig herunter.

<table align="center">
<tr>
<td align="center">
<a href="https://github.com/domainreseller/whmcs-dna"><img src="./assets/card-whmcs.svg" width="248" alt="Domain-Reseller-Modul für WHMCS"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/whmcs-dna?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://github.com/domainreseller/whmcs-dna/releases/latest">📥 Download</a> · <a href="https://github.com/domainreseller/whmcs-dna#readme">📝 Dokumentation</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/wisecp-dna-v5"><img src="./assets/card-wisecp5.svg" width="248" alt="Domain-Reseller-Modul für WiseCP 5"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/wisecp-dna-v5?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://github.com/domainreseller/wisecp-dna-v5/releases/latest">📥 Download</a> · <a href="https://github.com/domainreseller/wisecp-dna-v5#readme">📝 Dokumentation</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/wisecp-dna"><img src="./assets/card-wisecp.svg" width="248" alt="Domain-Reseller-Modul für WiseCP 3.x"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/wisecp-dna?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://github.com/domainreseller/wisecp-dna/releases/latest">📥 Download</a> · <a href="https://github.com/domainreseller/wisecp-dna#readme">📝 Dokumentation</a>
</td>
</tr>
<tr>
<td align="center">
<a href="https://github.com/domainreseller/blesta-dna"><img src="./assets/card-blesta.svg" width="248" alt="Domain-Reseller-Modul für Blesta"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/blesta-dna?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://github.com/domainreseller/blesta-dna/releases/latest">📥 Download</a> · <a href="https://github.com/domainreseller/blesta-dna#readme">📝 Dokumentation</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/hostbill-dna"><img src="./assets/card-hostbill.svg" width="248" alt="Domain-Reseller-Modul für HostBill"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/hostbill-dna?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://github.com/domainreseller/hostbill-dna/releases/latest">📥 Download</a> · <a href="https://github.com/domainreseller/hostbill-dna#readme">📝 Dokumentation</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/clientexec-dna"><img src="./assets/card-clientexec.svg" width="248" alt="Domain-Reseller-Plugin für ClientExec"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/clientexec-dna?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://github.com/domainreseller/clientexec-dna/releases/latest">📥 Download</a> · <a href="https://github.com/domainreseller/clientexec-dna#readme">📝 Dokumentation</a>
</td>
</tr>
<tr>
<td align="center">
<a href="https://github.com/domainreseller/fossbilling-dna"><img src="./assets/card-fossbilling.svg" width="248" alt="Domain-Reseller-Modul für FOSSBilling"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/fossbilling-dna?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://github.com/domainreseller/fossbilling-dna/releases/latest">📥 Download</a> · <a href="https://github.com/domainreseller/fossbilling-dna#readme">📝 Dokumentation</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/hostfact-dna"><img src="./assets/card-hostfact.svg" width="248" alt="Domain-Reseller-Modul für HostFact"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/hostfact-dna?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://github.com/domainreseller/hostfact-dna/releases/latest">📥 Download</a> · <a href="https://github.com/domainreseller/hostfact-dna#readme">📝 Dokumentation</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/dna-extended"><img src="./assets/card-extended.svg" width="248" alt="Erweitertes WHMCS-Addon-Modul"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/dna-extended?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://github.com/domainreseller/dna-extended/releases/latest">📥 Download</a> · <a href="https://github.com/domainreseller/dna-extended#readme">📝 Dokumentation</a>
</td>
</tr>
</table>

## <img src="./assets/h-sdk.svg" width="30" height="30" alt=""> Bibliotheken für die Domain-Reseller-API

Sie entwickeln Ihre eigene Integration? Rufen Sie die Domain-Reseller-API direkt mit unseren Bibliotheken für PHP, Node.js, Ruby, Python und Go auf.

<table align="center">
<tr>
<td align="center">
<a href="https://github.com/domainreseller/php-dna"><img src="./assets/card-php.svg" width="248" alt="PHP-Bibliothek für die Domain-Reseller-API"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/php-dna?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://github.com/domainreseller/php-dna/releases/latest">📥 Download</a> · <a href="https://github.com/domainreseller/php-dna#readme">📝 Dokumentation</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/nodejs-dna"><img src="./assets/card-nodejs.svg" width="248" alt="Node.js-Bibliothek für die Domain-Reseller-API"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/nodejs-dna?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://github.com/domainreseller/nodejs-dna/releases/latest">📥 Download</a> · <a href="https://github.com/domainreseller/nodejs-dna#readme">📝 Dokumentation</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/ruby-dna"><img src="./assets/card-ruby.svg" width="248" alt="Ruby-Bibliothek für die Domain-Reseller-API"></a><br>
<img src="https://img.shields.io/gem/v/domainnameapi?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://rubygems.org/gems/domainnameapi">📥 Download</a> · <a href="https://github.com/domainreseller/ruby-dna#readme">📝 Dokumentation</a>
</td>
</tr>
</table>

<table align="center">
<tr>
<td align="center">
<a href="https://github.com/domainreseller/python-dna"><img src="./assets/card-python.svg" width="248" alt="Python-Bibliothek für die Domain-Reseller-API"></a><br>
<img src="https://img.shields.io/pypi/v/domainnameapi?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://pypi.org/project/domainnameapi/">📥 Download</a> · <a href="https://github.com/domainreseller/python-dna#readme">📝 Dokumentation</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/go-dna"><img src="./assets/card-go.svg" width="248" alt="Go-Bibliothek für die Domain-Reseller-API"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/go-dna?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://github.com/domainreseller/go-dna/releases/latest">📥 Download</a> · <a href="https://github.com/domainreseller/go-dna#readme">📝 Dokumentation</a>
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
<summary><b>Schnellstart: PHP</b></summary>

```php
require_once __DIR__.'/vendor/autoload.php';

$dna = new \DomainNameApi\DomainNameAPI_PHPLibrary($resellerId, $apiKey);

$dna->CheckAvailability(['hello', 'world123x0'], ['com', 'net'], 1, 'create');
```

</details>

<details>
<summary><b>Schnellstart: Node.js</b></summary>

```js
const DomainNameApi = require('nodejs-dna');

const api = new DomainNameApi('xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx', 'your-api-key');

const domains = await api.CheckAvailability(['hello', 'world'], ['com', 'net'], 1);
```

</details>

<details>
<summary><b>Schnellstart: Ruby</b></summary>

```ruby
require 'domainnameapi'

dna = DomainNameApi::Client.new('xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx', 'your-api-key')

dna.check_availability(['hello', 'world123x0'], ['com', 'net'], 1, 'create')
```

</details>

<details>
<summary><b>Schnellstart: Python</b></summary>

```python
from domainnameapi import DomainNameAPI

dna = DomainNameAPI("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "your-api-key")

dna.check_availability(["hello", "world123x0"], ["com", "net"], 1, "create")
```

</details>

<details>
<summary><b>Schnellstart: Go</b></summary>

```go
import dna "github.com/domainreseller/go-dna"

client := dna.New("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "your-api-key", false)

result := client.CheckAvailability([]string{"hello", "world123x0"}, []string{"com", "net"}, 1, "create")
```

</details>

## <img src="./assets/h-ssl.svg" width="30" height="30" alt=""> Module für SSL & Reseller-Hosting

Verkaufen Sie mehr als Domains: Module für unsere Programme [SSL-Reseller](https://www.domainnameapi.com/de/ssl-reseller) und [Reseller-Hosting](https://www.domainnameapi.com/de/reseller-hosting), mit SSL-Zertifikaten und Hosting mit cPanel oder Plesk aus demselben Konto.

<table align="center">
<tr>
<td align="center">
<a href="https://github.com/domainreseller/whmcs-ssl-dna"><img src="./assets/card-ssl-whmcs.svg" width="248" alt="DNA SSL für WHMCS"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/whmcs-ssl-dna?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://github.com/domainreseller/whmcs-ssl-dna/releases/latest">📥 Download</a> · <a href="https://github.com/domainreseller/whmcs-ssl-dna#readme">📝 Dokumentation</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/wisecp-ssl-dna"><img src="./assets/card-ssl-wisecp.svg" width="248" alt="DNA SSL für WiseCP 5"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/wisecp-ssl-dna?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://github.com/domainreseller/wisecp-ssl-dna/releases/latest">📥 Download</a> · <a href="https://github.com/domainreseller/wisecp-ssl-dna#readme">📝 Dokumentation</a>
</td>
</tr>
<tr>
<td align="center">
<a href="https://github.com/domainreseller/reseller-hosting-whmcs"><img src="./assets/card-hosting-whmcs.svg" width="248" alt="DNA Reseller Hosting für WHMCS"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/reseller-hosting-whmcs?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://github.com/domainreseller/reseller-hosting-whmcs/releases/latest">📥 Download</a> · <a href="https://github.com/domainreseller/reseller-hosting-whmcs#readme">📝 Dokumentation</a>
</td>
<td align="center">
<a href="https://github.com/domainreseller/reseller-hosting-wisecp"><img src="./assets/card-hosting-wisecp.svg" width="248" alt="DNA Reseller Hosting für WiseCP"></a><br>
<img src="https://img.shields.io/github/v/release/domainreseller/reseller-hosting-wisecp?label=version&style=flat-square&color=12B385" alt="Neueste Version"><br>
<a href="https://github.com/domainreseller/reseller-hosting-wisecp/releases/latest">📥 Download</a> · <a href="https://github.com/domainreseller/reseller-hosting-wisecp#readme">📝 Dokumentation</a>
</td>
</tr>
</table>

## <img src="./assets/h-key.svg" width="30" height="30" alt=""> API-Zugangsdaten

<img src="./assets/creds.svg" width="1200" alt="Tragen Sie Ihre Reseller ID in das Feld Benutzername (Username) und Ihren API Key in das Feld Passwort (Password) ein; das Modul verbindet sich mit der REST API.">

Jedes Modul fragt dieselben zwei Werte ab:

| Modulfeld | Was Sie eintragen |
|---|---|
| **Benutzername (Username)** | Reseller ID, eine UUID wie `xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx` |
| **Passwort (Password)** | API Key |

> [!TIP]
> Ihre **Reseller ID** und Ihren **API Key** finden Sie in Ihrem Panel bei Domain Name API unter **API-Einstellungen (API Settings)**.

> [!CAUTION]
> Dies sind **API-Zugangsdaten**. Die E-Mail-Adresse und das Passwort für Ihren Panel-Login funktionieren hier **nicht**.

## <img src="./assets/h-faq.svg" width="30" height="30" alt=""> Domain-Reseller-FAQ

<details>
<summary><b>Was ist ein Domain-Reseller?</b></summary>
<br>
Ein Domain-Reseller verkauft Domainnamen unter eigener Marke und zu eigenen Preisen an seine Kunden weiter, während ein akkreditierter Registrar die Registrierung bei der jeweiligen Registry übernimmt. Mit Domain Name API haben Sie diesen Registrar an Ihrer Seite: über 830 Domain-Endungen, ein Reseller-Panel und die Domain-Reseller-API sowie fertige Module für das Abrechnungssystem, das Sie bereits nutzen.
</details>

<details>
<summary><b>Wie kann ich bei Domain Name API Domain-Reseller werden?</b></summary>
<br>
Registrieren Sie sich auf der <a href="https://www.domainnameapi.com/de/domain-reseller">Domain-Reseller-Seite</a>. Es gibt keine Einrichtungsgebühr und keine Mindesteinzahlung. Rufen Sie dann in Ihrem Panel unter <b>API-Einstellungen (API Settings)</b> Ihre <b>Reseller ID</b> und Ihren <b>API Key</b> ab, installieren Sie das Modul für Ihr Abrechnungssystem aus der Liste oben, und schon können Sie Domains weiterverkaufen.
</details>

<details>
<summary><b>Kann ein KI-Agent meine Domains verwalten?</b></summary>
<br>
Ja. Die <a href="https://github.com/domainreseller/cli">dna CLI</a> stellt jede Operation der Domain Name API als MCP-Tool für Claude Code, Cursor, Codex und andere MCP-Clients bereit. Kostenpflichtige und destruktive Aufrufe warten auf Ihre Freigabe, und mit <code>--env ote</code> üben Agenten zuerst in der Testumgebung.
</details>

<details>
<summary><b>Welche Datei soll ich herunterladen?</b></summary>
<br>
Immer das Paket, das dem <b>neuesten Release</b> des Moduls angehängt ist (die 📥 Download-Links oben). Der grüne Button <b>Code → Download ZIP</b> liefert Ihnen den ungetesteten Entwicklungszweig.
</details>

<details>
<summary><b>WiseCP 3.x oder WiseCP 5?</b></summary>
<br>
Verwenden Sie <a href="https://github.com/domainreseller/wisecp-dna-v5">wisecp-dna-v5</a> für WiseCP 5 (PHP 8.2+) und <a href="https://github.com/domainreseller/wisecp-dna">wisecp-dna</a> für WiseCP 3.x.
</details>

<details>
<summary><b>Wo finde ich meine Reseller ID und meinen API Key?</b></summary>
<br>
In Ihrem Panel bei Domain Name API unter <b>API-Einstellungen (API Settings)</b>. Ihre Login-Daten für das Panel funktionieren in den Modulen nicht.
</details>

<details>
<summary><b>Kann ich testen, bevor ich live gehe?</b></summary>
<br>
Ja. Die Bibliotheken für <a href="https://github.com/domainreseller/php-dna">PHP</a>, <a href="https://github.com/domainreseller/nodejs-dna">Node.js</a>, <a href="https://github.com/domainreseller/ruby-dna">Ruby</a>, <a href="https://github.com/domainreseller/python-dna">Python</a> und <a href="https://github.com/domainreseller/go-dna">Go</a> können sich mit der Testumgebung (OTE) verbinden; wie Sie umschalten, steht in der jeweiligen Dokumentation.
</details>

## <img src="./assets/h-connect.svg" width="30" height="30" alt=""> Kontakt

<p align="center">
  <a href="https://www.domainnameapi.com/de"><img src="./assets/btn-web.svg" height="46" alt="Domain Name API: Domain-Reseller-Programm"></a>
  <a href="https://www.domainnameapi.com/de/domain-reseller"><img src="./assets/btn-signup.svg" height="46" alt="Domain-Reseller werden"></a>
  <a href="https://www.domainnameapi.com/de/domain-api-integration"><img src="./assets/btn-api.svg" height="46" alt="Domain-Reseller-API & Module"></a>
  <a href="https://www.domainnameapi.com/de/kontakt"><img src="./assets/btn-support.svg" height="46" alt="Support"></a>
</p>

<br>

<p align="right">
  <sub>Tools</sub><br>
  <a href="https://github.com/domainreseller/Trabis-turkey-tr-domain-registration-tr-domain-kayit"><img src="./assets/pill-trabis.svg" height="34" alt="TRABIS: .tr-Registrierung"></a>
  <br>
  <sub>Folgen Sie uns</sub><br>
  <a href="https://www.atakdomain.com"><img src="./assets/pill-atak.svg" height="34" alt="atakdomain.com"></a>
  <a href="https://www.linkedin.com/company/domain-name-reseller/"><img src="./assets/pill-linkedin.svg" height="34" alt="LinkedIn"></a>
  <a href="https://x.com/dna_resellerapi"><img src="./assets/pill-x.svg" height="34" alt="X"></a>
  <a href="https://www.youtube.com/DomainReseller"><img src="./assets/pill-youtube.svg" height="34" alt="YouTube"></a>
</p>

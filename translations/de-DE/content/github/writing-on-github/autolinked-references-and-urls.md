---
title: Automatisch verknüpfte Verweise und URLs
intro: 'Verweise auf URLs, Issues, Pull Requests und Commits werden automatisch gekürzt und in Links umgewandelt.'
redirect_from:
  - /articles/autolinked-references-and-urls
versions:
  free-pro-team: '*'
  enterprise-server: '*'
---

### URLs

{{ site.data.variables.product.product_name }} erstellt aus Standard-URLs automatisch Links.

`Besuche https://github.com`

![Gerenderte automatisch verlinkte URL](/assets/images/help/writing/url-autolink-rendered.png)

Weitere Informationen zum Erstellen von Links findest Du unter „[Grundlegende Schreib- und Formatierungssyntax](/articles/basic-writing-and-formatting-syntax/#links).“

### Issues und Pull Requests

In Unterhaltungen auf {{ site.data.variables.product.product_name }} werden Verweise auf Issues und Pull Requests automatisch in verkürzte Links umgewandelt. Weitere Informationen findest Du unter „[Informationen zu Unterhaltungen auf {{ site.data.variables.product.prodname_dotcom }}](/articles/about-conversations-on-github).“

{% note %}

**Hinweis:** Automatisch verlinkte Verweise werden in Wikis oder Dateien in einem Repository nicht erstellt.

{% endnote %}

| Verweistyp                                                               | Rohverweis                                     | Kurzlink                                                               |
| ------------------------------------------------------------------------ | ---------------------------------------------- | ---------------------------------------------------------------------- |
| URL des Issues oder Pull Requests                                        | https://github.com/jlord/sheetsee.js/issues/26 | [#26](https://github.com/jlord/sheetsee.js/issues/26)                  |
| `#` und Nummer des Issues oder Pull Requests                             | #26                                            | [#26](https://github.com/jlord/sheetsee.js/issues/26)                  |
| `GH-` und Nummer des Issues oder Pull Requests                           | GH-26                                          | [GH-26](https://github.com/jlord/sheetsee.js/issues/26)                |
| `Username/Repository#` und Nummer des Issues oder Pull Requests          | jlord/sheetsee.js#26                           | [jlord/sheetsee.js#26](https://github.com/jlord/sheetsee.js/issues/26) |
| `Organization_name/Repository#` und Nummer des Issues oder Pull Requests | github/linguist#4039                           | [github/linguist#4039](https://github.com/github/linguist/pull/4039)   |

### Commit-SHAs

Verweise auf den SHA-Hash eines Commits werden automatisch in verkürzte Links zum Commit auf {{ site.data.variables.product.product_name }} umgewandelt.

| Verweistyp                  | Rohverweis                                                                           | Kurzlink                                                                                                          |
| --------------------------- | ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| Commit-URL                  | https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e | [a5c3785](https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e)                   |
| SHA                         | a5c3785ed8d6a35868bc169f07e40e889087fd2e                                             | [a5c3785](https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e)                   |
| Benutzer@SHA                | jlord@a5c3785ed8d6a35868bc169f07e40e889087fd2e                                       | [jlord@a5c3785](https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e)             |
| Benutzername/Repository@SHA | Benutzer/Repository@SHA: jlord/sheetsee.js@a5c3785ed8d6a35868bc169f07e40e889087fd2e  | [jlord/sheetsee.js@a5c3785](https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e) |

{% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2.18" %}
### Benutzerdefinierte automatische Verknüpfungen von externen Ressourcen

{{ site.data.reusables.repositories.autolink-references }}

{% endif %}

### Weiterführende Informationen

- „[Grundlegende Schreib- und Formatierungssyntax](/articles/basic-writing-and-formatting-syntax)“
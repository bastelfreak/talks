# IT Tage 2026

* https://www.ittage.informatik-aktuell.de/

## Bio

Tim „bastelfreak“ Meusel arbeitet seit Juli 2021 als Senior Automation IT Consultant.
Vorher hat er sich um Platform Automatisierung bei Hetzner und Hosteurope/GoDaddy gekümmert.
Seit 2012 ist er aktives Mitglied bei Vox Pupuli und Project Management Committee Gründungsmitglied.

## OpenVox: Wechsel von Top-down-Management zu einer offenen, Community-getriebenen Entwicklung

### Gedanken

* unabhängig von lizenzen
* unabhqngig von US firmen
* freie software vs open source

### Weitere Infos

* 45min
* Themenbereiche Digitale souveränität / Digitalisierung
* Niveau Anfänger / Fortgeschritten
* Zielgruppen Admins / DevOps
* Sprache Deutsch

### Abstract

Immer mehr Firmen, die Ihr Geschäft auf einem Open Source Produkt aufgebaut haben, ändern dessen Lizenz oder stellen die Open Source Version komplett ein.
So veröffentlicht auch Perforce Puppet unter keiner Open Source Lizenz mehr.
In den Jahren zuvor hatte sich bereits mit Vox Pupuli eine lebhafte Community um diese Software herum gebildet, die viele Features und Tools beisteuerte.
Entscheidungen hat Perforce allerdings überwiegend allein getroffen.
Bedingt durch die Lizenzänderung hat sich diese Community entschieden die Entwicklung als Open Source weiterzuführen - mit großem Erfolg.

In diesem Zusammenhang werde ich folgende Fragen beantworten:

* Wie sind wir als Community mit dieser kurzfristigen Änderung umgegangen?
* Wie konnten wir eine nachhaltige Gemeinschaft aufbauen, die die Arbeit bewältigt, und wie können andere die gleichen Probleme  vermeiden?
* Wie baut man ein Open Source Ökosystem mit einer Community auf, um unabhängig von einzelnen Firmen und deren propritären Lizenzen zu sein, und die eigene digitale Souveränität zu erhöhen?

Ich möchte einen detaillierten Einblick in die Erfolge des OpenVoxProjects während der letzten zwei Jahre geben und einen Überblick der anstehenden Themen bieten.

## OpenBolt als Orchestration-Plugin für Foreman

* 45min
* Themenbereiche DevOps / IT-Automatisierung
* Niveau Fortgeschritten
* Zielgruppen Admins / DevOps
* Sprache Deutsch

Foreman als ein Open Source Lifecycle Management Tool erlaubt es Systeme zu provisionieren und mit verschiedenen Tools wie Ansible, OpenVox & Salt weiterführend zu verwalten.
Es ist die Upstream Version von Red Hat Satellite und orcharhino der ATIX AG.

Mit Foreman zusammen wird in den meisten Umgebungen OpenVox/Puppet für das Konfigurationsmanagement eingesetzt.
Wenn dann noch eine Möglichkeit zur Orchestrierung gesucht wird, ergänzen viele Ihr Setup mit Ansible.

Doch das muss nicht sein!

OpenBolt ist eine CLI Anwendung zur Orchestrierung und kann die Foreman Web UI erweitern.
In diesem Vortrag möchte ich euch zeigen was OpenBolt ist, wie die Foreman Integrierung funktioniert und wie man damit seine eigenen Systeme steuert.
Als Transportprotokoll lässt sich neben SSH auch die hoch skalierbare Choria Message-Queue als Alternative verwenden.
Da OpenBolt und OpenVox aus dem selben Ökosystem stamnmen, ist der Code, der die Konfiguration beschreibt, einfach zur Orchestrierung wiederverwendbar.

Somit reduziert man die  Komplexität und spart Ressourcen.

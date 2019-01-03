# DevOps Meetup Karlsruhe

## Final slides

[Online Slides](https://bastelfreak.de/devopsmeetupka)
[pdf](Vox_Pupuli_-_Empowering_the_Puppet_Community_-_Tim_Meusel_devopsmeetup_karlsruhe.pdf)
[Recording](https://www.youtube.com/watch?v=sEEagytj7Q4)

## Bio

Tim (bastelfreak) Meusel ist ein DevOps Engineer bei GoDaddy EMEA in Köln. Er
verantwortet dort eine große Puppet Installation, außerdem entwickelt Tim an
einer großen Public Cloud Platform. Er ist einer der Leiter der
[Puppet Community](https://voxpupuli.org/) und verantwortet dort über 100 Puppet
Module und über 120 regelmäßige Contributors. In seiner Freizeit veranstaltet
er BBQ Events und spielt Eishockey.

## Vox Pupuli - Die Community hinter Puppet

Puppet ist die am weitesten verbreitete Konfigurationsmanagement Lösung. Die
Software wird von Puppet Inc. entwickelt, doch ein Großteil der Komponenten
kommt von Freiwilligen. Wie organisiert man >100 Freiwillige und wie ist die
Community aufgebaut? Wie verwaltet man effektiv 150 git repos und released
regelmäßig Software ohne Semantic Versioning zu missachten? Und die wichtigste
Frage: Was muss man machen damit einem eine 1kg Box Haribo geschickt wird?

## Effizienter Umgang mit über 150 GitHub Repositories in Open Source Communities

*Subset / detailierte Version vom Vox Pupuli talk*

Der Umgang mit einer großen Menge an git Repositories erzeugt eine Menge
Overhead. Regelmäßig alle Projekte nach neuen Issues und Pull Requests
durchsuchen, Releases machen, Versionsnummern verwalten, Abhängigkeiten zu
externen Bibliotheken prüfen. All dies wird komplexer mit der Anzahl der Repos.
In der Puppet Community haben wir einige Tools und Workflows entwickelt um die
Entwicklung zu optimieren und die Qualität zu steigern.

## IPv6

Viele Leute haben Angst vor IPv6 - zu Unrecht! IPv4 Adressen werden immer
knapper, und so langsam sollte man mal IPv6 aktivieren. Zuerst geht es um die
aktuellen Probleme im Datacenter Netzwerk mit IPv4, was überhaupt IPv6 ist, und
zum Schluss geht es um Best Practices die man bei der Einführung beachten
sollte (damit man nicht so viel kaputt macht wie andere).

## Automatische Installation von virtuellen und/oder dedizierten Servern

'mal kurz einen Server installieren' ist leichter gesagt als getan. Wenn
man möchte, dass die Installation automatisiert und möglichst schnell
funktioniert, deterministisch ist und auch noch verschiedene Linux
Distributionen unterstützt, ist das garnicht mehr so einfach. Hier haben
jedoch mehrere große deutscher Hoster Open Source Tools entwickelt, welche
die Installation gut automatisiert und auch auf mehrere 100.000 Server
skaliert.

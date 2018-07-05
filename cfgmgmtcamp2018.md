# Config Management Camp 2018 Ghent

## Slides

Sadly I had no time to attend the conference. The first talk was accepted. The
pdf can be found
[here](Vox_Pupuli_-_The_Funny_Community_Journey_-_Tim_Meusel_cfgmgmtcamp2018.pdf)
and the online version [here](https://bastelfreak.de/cfgcampgent2018/#1).

## Bio

Tim (bastelfreak) Meusel works as a DevOps Engineer for GoDaddy EMEA in Cologne,
Germany where he develops and maintains a big public cloud platform. Tim is
pushing and implementing open source solutions at work. He founded the
VirtAPI-Stack and besides that he is active as a Vox Pupuli Maintainer and
Archlinux community manager. Tim has been doing Sysops stuff since 2009 and
playing with Puppet since 2012. Recently he was elected to serve on the Vox
Pupuli Project Management Committee. He enjoys good BBQ and ice hockey.

## Vox Pupuli - The funny Community Journey Second Edition

Vox Pupuli is a group of more than 110 puppet module/tooling/documentation
authors, all working together to ensure a continuing development process. We
elected our first Project Management Committee with one of its goals being to
include Vox Pupuli as an official project under the Software Conservancy. We do
not only provide a home for every orphaned puppet module, but also proper
tooling and automation for every interested developer. Some of the most
frequently used puppet modules (zabbix, collectd, archive)
are managed by us. Vox Pupuli is in the Top 10 of the most frequent Puppet Forge release
groups. Have a look at our funny journey of hunting broken gems and changing
upstream software! We invite everybody to participate. We will get into the
details of what Vox Pupuli is, how you can interact/contribute/benefit and also
we will share some funny and sad stories about all the bugs we discovered in
the Puppet and Ruby ecosystem!

## CI and CD with Archlinux and Puppet

Who likes to do major upgrades of a distribution that got installed years ago
and has since then got no love? Nobody. Who needs to rely on third party repos or
package stuff themselves because the packages provided by the distributions are too
old?

Not all of us can run their applications in minimalistic containers. Sometimes
we still require traditional operating systems on physical or virtual machines.
Archlinux is a rolling release distribution. It allows us to continuously
upgrade the system. I will walk you through the GoDaddy EMEA way of running and
updating Archlinux on production systems. Including dynamic provisioning of
test- and staging-environments. All tested with Beaker and managed with Puppet.
There are multiple advantages compared to classic Debian/RHEL deployments that
I want to share and discuss with you. Discover if Archlinux is the datacenter
distribution you were looking for!

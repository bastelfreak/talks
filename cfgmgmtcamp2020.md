# Configuration Management Camp 2020

I did two talks here:

## Rollout all your Prometheus exporters with Puppet

### Abstract

Everybody loves Prometheus. Many exporters are available to gather specific
data. You can download the binaries from GitHub, start them and they will
expose data via plain HTTP, without any firewalling or authentication. That
would just complicate the whole setup! A secure and automated rollout of
exporters isn't easy. Also an authenticated connection from the prometheus
server to the exporters requires some preparation. This talk will cover a proper
concept and all details to rollout multiple exporters to many systems, completely
automated with Puppet.

### Notes

* I did this talk in the past at the [OSMC 2019](OSMC2019.md).
* [git repo](https://github.com/bastelfreak/prometheusdemo#deploy-prometheus-exporters-with-puppet-at-scale)
* [online version](https://bastelfreak.de/prometheusdemo#1)
* [pdf version](Rollout_all_your_Prometheus_exporters_with_puppet_-_CFGMGMTCAMP2020.pdf)

## Automating the Vox Pupuli Yak Shaving

### Abstract

Vox Pupuli maintains a huge amount of puppet modules and utilizes Github
heavily for maintenance and daily tasks. We've built an app to support all the
module maintainers in their daily work.

### Description

Vox Pupuli Tasks (VPT) is an web application which summarizes various
informations for easy access about modules which need some attention. This
helps the maintainer to focus more on the actual work rather then figuring out
where attention is missing. Also VPT uses the Github API to create comments and
monitors open pull requests to notify their autors about things they may have
forgotten (merge conflicts, outdated states). We also have big plans for the
tool and want to bring some attention to it and find out what could be added or
changed to enhance it more and more.
See [our GitHub project](https://github.com/voxpupuli/vox-pupuli-tasks#vox-pupuli-tasks---the-webapp-for-community-management) if you are curious about the code or contributing.

### Notes

* I did this talk together with [Robert Müller](https://twitter.com/Was1NicerDude).
* [git repo](https://github.com/bastelfreak/cfgmgmtcamp2020#automating-the-vox-pupuli-yak-shaving)
* [online version](https://bastelfeak.de/cfgmgmtcamp2020)
* [pdf version]()

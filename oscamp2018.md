# OSCamp 2018

## Event info

Just read [the website](https://opensourcecamp.de).

## Author Details

* First Name: Tim
* Last Name: Meusel
* Twitter: BastelsBlog
* Company: GoDaddy EMEA

* Title: DevOps Engineer
* Company: GoDaddy EMEA
* City: Cologne
* Country: Germany
* Location: Amsterdam

### Bio

Tim (bastelfreak) Meusel works as a DevOps Engineer for GoDaddy EMEA in Cologne,
Germany where he develops and maintains a big public cloud platform. Tim is the
driving force behind various open source solutions at work. He founded the
VirtAPI-Stack and is a very active Vox Pupuli Maintainer. Tim has been doing
work in the DevOps area since 2009 and is persuing Puppet solutions since 2012.
Recently he was reelected to serve on the Vox Pupuli Project Management
Committee. He enjoys good BBQ and ice hockey.

## Session 1 Details

* Title: Vox Pupuli - The Community behind Puppet
* Level: Beginner

Vox Pupuli is a group of more than 120 puppet module/tooling/documentation
authors, all working together to ensure a continuing development process. In
2016 we elected our first Project Management Committee with one of its goals
being to include Vox Pupuli as an official project under the Software
Conservancy and to guide the community. We do not only provide a home for every
orphaned puppet module; we also offer proper tooling and automation for every
interested developer. Some of the most frequently used puppet modules (zabbix,
collectd, archive, yum, nginx) are managed by us. Vox Pupuli is in the Top 10
of the most frequent Puppet Forge release groups. Have a look at our funny
journey of hunting broken gems and changing upstream software! We invite
everybody to participate. We will get into the details of what Vox Pupuli is,
how you can interact/contribute/benefit. We will tell you some stories, funny
and sad, about all the bugs we've discovered in the Puppet and Ruby ecosystem!

## Session 2 Details

* Title: Scaling and monitoring your puppetserver for thousands of clients -
  including all pitfalls!
* Level: Advanced

Throwing hardware on your Puppetserver to scale it vertically works up to a
certain level. But how do you proceed once you reach the limit? How do you
distribute your agents over several Puppetservers evenly, but without hardcoded
assignments? How do you handle the massively increased load on your Foreman and
PuppetDB intances, after the Puppetserver isn't the bottleneck anymore? And how
the heck can this all be monitored?

I would like to show you a walkthrough from a small environment with a
single physical server for Puppetserver/Foreman/PostgreSQL and a handful of
agents that got scaled up to several thousand agents. This also includes
probably all common pitfalls that you can find yourself in on this journey!

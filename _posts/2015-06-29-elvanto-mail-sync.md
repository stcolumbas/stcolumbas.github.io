---
layout: post
title: Syncing Elvanto groups to Google mailing lists
published: True
comments: True
---
At [St Columba's](http://stcolumbas.freechurch.org/) we use Google Apps (free for non-profits). One feature that we make very heavy use of are mailing lists.

Pretty much anything that exists within St Columba’s has a mailing list - service groups, city groups, rotas, elders, deacons, etc. However we have found that it can be burdensome to keep these list up to date and the admin UI isn’t very friendly.

We are currently in a phased roll out of [Elvanto](https://www.elvanto.com/) (a church management database) which, among other things, means it’s much easier to keep group information up to date. Now we just needed a way to sync our groups in Elvanto with our mailing lists.

So we built one: [Elvanto Mail Sync](https://github.com/monty5811/elvanto_mail_sync). 

Elvanto Mail Sync is a [Django](https://www.djangoproject.com/) app that pulls in all your [Elvanto](https://www.elvanto.com/) groups, then pushes the emails to your mailing lists.

![Overview](/public/images/2015-06-29-elvanto-overview.png)

## Features

* Pull in all your Elvanto groups and people.
* Push each group to a mailing list.
* Scheduled syncing - sync your lists as often as you want. (You can comfortably sync every half hour on Heroku’s free tier)
* Disable scheduled syncing for different groups.
* Disable an individual on a per group basis - have someone in an Elvanto group that doesn’t want to be on the mailing list? Just disable them.
* Disable an individual on a global basis - have someone who doesn’t want to receive any emails? Disable them completely.
* One click deploy to [Heroku](https://heroku.com/). Just setup your Elvanto and Google accounts and you can click to deploy on Heroku.
* Free to run! Should comfortably fit into Heroku’s new free tier.
* Support for an "override" email in Elvanto - we have some people with multiple email addresses so we have added a custom field to Elvanto. If this field is populated, then this email address will be used.

![Group](/public/images/2015-06-29-elvanto-group.png)

## Current issues

* Only the first 1000 people are loaded from Elvanto. This isn’t a problem for us at St Columba’s, but this limit should be fixed soon
* No support for "roles" on the mailing lists. Currently you must visit the Google admin console to change a person’s role on a mailing list. Again, this should be fixed soon.

We are currently still testing Elvanto Mail Sync, it has not been properly verified, so you may want to hold off pointing it at your real mailing lists right now, but feel free to deploy an instance and play around with it. Any issues you find can be submitted here. Once we are more confident, we will publish proper installation instructions. Feel free to get in touch if you have any issues.

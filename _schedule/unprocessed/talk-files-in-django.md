---
abstract: "Serving files is one of the most basic tasks of any web application. Since\
  \ 1.0 Django has provided an API to abstract over the potpourri of cloud and other\
  \ types of storage providers. We\u2019ll dive into the API, go over some recommended\
  \ configurations and implement a novel storage engine together."
accepted: true
category: talk
date: 2016-07-18 09:00
layout: session-details
permalink: /talk/files-in-django/
presenters:
- bio: ''
  company: ''
  github: ''
  name: Josh Schneier
  photo_url: ''
  twitter: ''
  website: ''
published: true
room: ''
sitemap: true
slides_url: ''
summary: ''
title: Files in Django
track: ''
video_url: ''
---

One of the most confusing parts of Django for newcomers (and some old hands alike!) is the handling of files. Among the 10+ settings, static vs user uploaded distinction, and plethora of deployment options it's no wonder that many people end up cargo-culting their production settings.

1. The API overview
     * Short introduction
     * Go over the difference between static & media files
     * Run through the File abstraction and the various settings
     * Django Storage API, collectstatic etc
2.  Production & Development configuration
     * Whitenoise/dj-static/Nginx for static files
     * Cloud storage providers for media & static files (S3 etc, mention some popular libraries such as django-storages)
     * CDNs
3.  Implement a storage engine together & the future
     * Implementation - practicing what we just learned to solidify understanding
     * Closing remarks and mention possible future Django developments
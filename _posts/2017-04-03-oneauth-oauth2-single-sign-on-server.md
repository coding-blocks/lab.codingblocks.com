---
layout: post
permalink: "projects/oneauth-oauth2-single-sign-on-server/index.html"
title:"oneauth: Oauth2 Single Sign On server"
description: 
categories: [nodejs, postgres, web]
date: 2017-04-03 16:52:13 +0530
tags: [oauth, nodejs, javascript, web]
---

**Oneauth** is a _Single Sign On_ system. An use case, as is at _**Coding Blocks**_ is that
when there are multiple apps/websites, like <http://hackerblocks.com> and
<http://students.codingblocks.com>, we would prefer to do user-management on a single
server, and use the same accounts on all the servers.
This is similar to what large websites like **Google** or **Microsoft** do.
You use the same Google account for Gmail, Youtube, G+,  Chrome and all other Google Services.

We can see **oneauth** deployed and life in action on <http://account.codingblocks.com>

**oneauth** has both -
 - an Oauth consumption interface, so users can login with Facebook/Twitter/Google
 - an Oauth serving interface to all CodingBlocks apps/clients can use it to login.


### Technologies

| **Backend** | [Express](http://expressjs.com) |
|  **Database**  | Postgres 9.6  |


### Information

**Source Code** : <http://github.com/coding-blocks/oneauth>
**Hosted At(Live)** : <http://account.codingblocks.com>

**Maintainers**

- [Arnav Gupta](http://github.com/championswimmer)


### How to get involved

Either pick up an issue/bug from the _**open issues**_ list and start fixing it
or if you want to suggest a new feature, create a new issue, and wait for
the maintainers to discuss it, and once the maintainers give it a go, start
working on it.
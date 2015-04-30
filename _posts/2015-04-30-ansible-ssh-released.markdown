---
layout: post
title: "Ansible joins Hardening Framework"
date:   2015-04-30 18:00:00
image:
      url: /assets/article_images/2015-04-30-ansible/sunrise.png
video: false
comments: true
theme_color: 302F2D

author: 'Christoph Hartmann'
author_image: "/assets/images/b21946d0.chris.jpeg"
author_link: "https://twitter.com/chri_hartmann"
---

The [Hardening Framework](http://hardening.io/) provides best-practice security for DevOps by implementing server hardening with DevOps tools. We are happy to announce that with help of [Sebastian Gumprich](https://www.zufallsheld.de) we were able to implement our first [Ansible](http://www.ansible.com) role: [ansible-ssh-hardening](https://github.com/hardening-io/ansible-ssh-hardening/). Over the last weeks, we worked hard to release version 1.0:

 * Implement ssh hardening to meet our [tests](https://github.com/hardening-io/tests-ssh-hardening)
 * Setup test infrastructure with [kitchen-ansible](https://github.com/neillturner/kitchen-ansible)
 * Implement travis tests[#7](https://github.com/hardening-io/ansible-ssh-hardening/issues/7)
 * Add handlers to restart sshd only when necessary [#6](https://github.com/hardening-io/ansible-ssh-hardening/issues/6)
 * Add support for Oracle Linux [#2](https://github.com/hardening-io/ansible-ssh-hardening/issues/2)

The module is available via [Ansible Galaxy](https://galaxy.ansible.com/list#/roles/3576), now. 

As a next step, we plan to add support more modules. `ansible-os-hardening` is already in the works. Stay tuned and follow us on [Twitter](https://twitter.com/hardening_io).

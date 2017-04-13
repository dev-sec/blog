---
layout: post
title: "Chef Software is contributing OpenStack Baseline"
date:   2017-04-13 09:00:00
video: false
comments: true
theme_color: 302F2D

author: 'Christoph Hartmann'
author_image: "/assets/images/b21946d0.chris.jpeg"
author_link: "https://twitter.com/chri_hartmann"
---

I am happy to announce that the [Chef Partners Team](https://www.chef.io/) contributed a new [OpenStack Baseline]( https://github.com/dev-sec/openstack-baseline) to our DevSec project. This Baseline is implementing the [OpenStack Security Guide](https://docs.openstack.org/security-guide/) in [InSpec](http://inspec.io/). [JJ Asghar](https://github.com/jjasghar) will continue to be a core maintainer.

The baseline is already covering a wide range of checks for:

- block-storage
- compute
- dashboard
- identity
- networking
- orchestration
- telemetry

But we still have some white spots:

- data-processing
- databases
- messaging

The baseline is designed to work hand-in-hand with multiple configuration management tools like Ansible, Chef or Puppet, which allows you to run the baseline easily against existing deployments.

To achieve the our standards, we are looking for more contributors to drive that project forward.

- Chris

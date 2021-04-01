---
layout: post
title: "First Few Weeks"
date: 2021-02-24
author: Lincoln
categories: devblog lincoln
---

The first week or two mostly involved writing GNU Makefile, setting up tooling, setting up the testing framework we're using [Unity](http://www.throwtheswitch.org/unity), setting up the CI [BuildKite](https://buildkite.com/), and our documentation system (consisting of ReadTheDocs and Sphinx). I will be changing the CI software soon though to a FOSS solution. [Change CI](https://trello.com/c/SOmBvYOE/30-fix-change-ci-system). I also have to fix some issues with the Makefiles [Fix Makefiles](https://trello.com/c/NStwnkRg/23-fixing-makefiles-to-allow-folder-directories-for-src-test-and-docs)

I also worked and finished getting a bootable image setup [Software Setup](https://trello.com/c/2IGiEfae/27-setup-cross-compiler-software) and worked on the vga driver as well [vga_driver](https://trello.com/c/wfLaBfU9/5-write-the-vga-driver) as writing automated unit tests for the code [vga_driver Tests](https://trello.com/c/gSDMgKVx/13-writing-tests-for-vgadriver). I also implemented assertions [kassert](https://trello.com/c/8MbfMW2C/19-implement-assertions) [kassert Docs](https://trello.com/c/EN6KmjwB/18-writing-documentation) and some small utility functions from libc [Small Utilities](https://trello.com/c/PBZtG6or/15-implement-core-parts-of-stringh). I also implemented printf format specifiers for integers, characters, and strings.

I'm also working on implementing more printf support currently [kprintf](https://trello.com/c/qhTSlwSf/17-implementing-standard-output-to-terminal-parts-of-stdioh). Next week I will hopefully start working on paging and dynamic memory management [Paging](https://trello.com/c/UJQYSvAa/21-implement-paging) [Dynamic Memory](https://trello.com/c/3R3BLOaX/22-implement-dynamic-memory-management).


![makefile screenshot](/RocketOS_Blog/static/lincoln/makefile-screenshot.png)

![documentation screenshot](/RocketOS_Blog/static/lincoln/documentation-screenshot.png)

![vga driver c file screenshot](/RocketOS_Blog/static/lincoln/vga-driver-c-screenshot.png)

![vga driver header screenshot](/RocketOS_Blog/static/lincoln/vga-driver-header-screenshot.png)

![assertion error message](/RocketOS_Blog/static/lincoln/assertion-error-message.png)

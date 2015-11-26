---
layout: post
title: "Windows command로 USB 초기화하기"
description: ""
category: blog
tags: [windows, command, diskpart, USB]
---

# Windows Command로 USB 초기화하기

```
diskpart
list disk
select disk #(USB drive)
clean
create partition primary
format fs=ntfs quick
```

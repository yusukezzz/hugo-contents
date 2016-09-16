+++
date = "2016-09-16T18:13:31+09:00"
draft = false
title = "gradle のタスクに alias 名を設定する"
tags = [ "gradle" ]
categories = [ "Dev" ]
slug = "gradle-alias-name"

+++

新しい空のタスクを定義し、元タスクを dependsOn で指定します

```
task shortName(dependsOn: veryLongTaskName)
```

---
title: macro
date: 2020-12-08 11:42:40
tags:
---

整理一些实用的宏

开启伤害/治疗数字
```
/console floatingCombatTextCombatDamage 1
/console floatingCombatTextCombatHealing 1
```
关闭伤害/治疗数字
```
/console floatingCombatTextCombatDamage 0
/console floatingCombatTextCombatHealing 0
```

删除所有“角色宏”
```
/script for i=121,138 do DeleteMacro(i) end
```

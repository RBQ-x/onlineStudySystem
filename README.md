---
title: 在线教育平台说明文档
time: 2019-4-23 09:19:42
---

# 文件目录结构
```text
文件夹 PATH 列表
卷序列号为 0B87-0F83
D:.
├─.idea
│  ├─artifacts
│  ├─codeStyles
│  ├─dictionaries
│  ├─inspectionProfiles
│  └─libraries
├─.settings
├─doc
│  └─wiki
│      ├─1-4
│      ├─5
│      ├─6
│      └─7
├─ocCommon
│  ├─.settings
│  ├─src
│  │  └─main
│  │      └─java
│  │          ├─com
│  │          │  └─online
│  │          │      └─college
│  │          │          └─common
│  │          │              ├─orm
│  │          │              ├─page
│  │          │              ├─storage
│  │          │              ├─util
│  │          │              └─web
│  │          │                  ├─auth
│  │          │                  ├─error
│  │          │                  └─shiro
│  │          │                      └─freemarker
│  │          └─META-INF
│  └─target
│      ├─classes
│      │  └─com
│      │      └─online
│      │          └─college
│      │              └─common
│      │                  ├─orm
│      │                  ├─page
│      │                  ├─storage
│      │                  ├─util
│      │                  └─web
│      │                      ├─auth
│      │                      ├─error
│      │                      └─shiro
│      │                          └─freemarker
│      ├─generated-sources
│      │  └─annotations
│      ├─maven-archiver
│      └─maven-status
│          └─maven-compiler-plugin
│              └─compile
│                  └─default-compile
├─ocOperator
│  ├─.settings
│  ├─src
│  │  └─main
│  │      ├─java
│  │      │  └─com
│  │      │      └─online
│  │      │          └─college
│  │      │              └─opt
│  │      │                  ├─business
│  │      │                  │  └─impl
│  │      │                  ├─controller
│  │      │                  └─vo
│  │      ├─resources
│  │      └─webapp
│  │          ├─res
│  │          │  ├─css
│  │          │  ├─i
│  │          │  └─js
│  │          └─WEB-INF
│  │              ├─ftl
│  │              └─pages
│  │                  ├─auth
│  │                  ├─cms
│  │                  │  ├─carousel
│  │                  │  ├─classify
│  │                  │  ├─college
│  │                  │  ├─course
│  │                  │  └─user
│  │                  ├─common
│  │                  └─error
│  └─target
│      ├─classes
│      │  └─com
│      │      └─online
│      │          └─college
│      │              └─opt
│      │                  ├─business
│      │                  │  └─impl
│      │                  ├─controller
│      │                  └─vo
│      ├─generated-sources
│      │  └─annotations
│      ├─maven-archiver
│      ├─maven-status
│      │  └─maven-compiler-plugin
│      │      └─compile
│      │          └─default-compile
│      └─ocOperator
│          ├─META-INF
│          ├─res
│          │  ├─css
│          │  ├─i
│          │  └─js
│          └─WEB-INF
│              ├─classes
│              │  └─com
│              │      └─online
│              │          └─college
│              │              └─opt
│              │                  ├─business
│              │                  │  └─impl
│              │                  ├─controller
│              │                  └─vo
│              ├─ftl
│              ├─lib
│              └─pages
│                  ├─auth
│                  ├─cms
│                  │  ├─carousel
│                  │  ├─classify
│                  │  ├─college
│                  │  ├─course
│                  │  └─user
│                  ├─common
│                  └─error
├─ocPortal
│  ├─.settings
│  ├─src
│  │  ├─main
│  │  │  ├─java
│  │  │  │  └─com
│  │  │  │      └─online
│  │  │  │          └─college
│  │  │  │              └─portal
│  │  │  │                  ├─business
│  │  │  │                  │  └─impl
│  │  │  │                  ├─controller
│  │  │  │                  └─vo
│  │  │  ├─resources
│  │  │  └─webapp
│  │  │      ├─res
│  │  │      │  ├─css
│  │  │      │  ├─i
│  │  │      │  └─js
│  │  │      ├─static
│  │  │      └─WEB-INF
│  │  │          ├─ftl
│  │  │          └─pages
│  │  │              ├─auth
│  │  │              ├─common
│  │  │              ├─error
│  │  │              └─user
│  │  └─test
│  │      └─com
│  │          └─online
│  │              └─college
│  │                  └─service
│  └─target
│      ├─classes
│      │  └─com
│      │      └─online
│      │          └─college
│      │              ├─portal
│      │              │  ├─business
│      │              │  │  └─impl
│      │              │  ├─controller
│      │              │  └─vo
│      │              └─service
│      ├─generated-sources
│      │  └─annotations
│      ├─maven-archiver
│      ├─maven-status
│      │  └─maven-compiler-plugin
│      │      └─compile
│      │          └─default-compile
│      └─ocPortal
│          ├─META-INF
│          ├─res
│          │  ├─css
│          │  ├─i
│          │  └─js
│          ├─static
│          └─WEB-INF
│              ├─classes
│              │  └─com
│              │      └─online
│              │          └─college
│              │              ├─portal
│              │              │  ├─business
│              │              │  │  └─impl
│              │              │  ├─controller
│              │              │  └─vo
│              │              └─service
│              ├─ftl
│              ├─lib
│              └─pages
│                  ├─auth
│                  ├─common
│                  ├─error
│                  └─user
├─ocService
│  ├─.settings
│  ├─src
│  │  ├─main
│  │  │  └─java
│  │  │      ├─com
│  │  │      │  └─online
│  │  │      │      └─college
│  │  │      │          ├─core
│  │  │      │          │  ├─auth
│  │  │      │          │  │  ├─dao
│  │  │      │          │  │  ├─domain
│  │  │      │          │  │  └─service
│  │  │      │          │  │      └─impl
│  │  │      │          │  ├─consts
│  │  │      │          │  │  ├─dao
│  │  │      │          │  │  ├─domain
│  │  │      │          │  │  └─service
│  │  │      │          │  │      └─impl
│  │  │      │          │  ├─course
│  │  │      │          │  │  ├─dao
│  │  │      │          │  │  ├─domain
│  │  │      │          │  │  └─service
│  │  │      │          │  │      └─impl
│  │  │      │          │  ├─statics
│  │  │      │          │  │  ├─dao
│  │  │      │          │  │  ├─domain
│  │  │      │          │  │  └─service
│  │  │      │          │  │      └─impl
│  │  │      │          │  └─user
│  │  │      │          │      ├─dao
│  │  │      │          │      ├─domain
│  │  │      │          │      └─service
│  │  │      │          │          └─impl
│  │  │      │          ├─test
│  │  │      │          │  └─dao
│  │  │      │          └─web
│  │  │      │              └─auth
│  │  │      └─META-INF
│  │  └─test
│  │      └─java
│  │          └─com
│  │              └─online
│  │                  └─college
│  │                      └─service
│  └─target
│      ├─classes
│      │  └─com
│      │      └─online
│      │          └─college
│      │              ├─core
│      │              │  ├─auth
│      │              │  │  ├─dao
│      │              │  │  ├─domain
│      │              │  │  └─service
│      │              │  │      └─impl
│      │              │  ├─consts
│      │              │  │  ├─dao
│      │              │  │  ├─domain
│      │              │  │  └─service
│      │              │  │      └─impl
│      │              │  ├─course
│      │              │  │  ├─dao
│      │              │  │  ├─domain
│      │              │  │  └─service
│      │              │  │      └─impl
│      │              │  ├─statics
│      │              │  │  ├─dao
│      │              │  │  ├─domain
│      │              │  │  └─service
│      │              │  │      └─impl
│      │              │  └─user
│      │              │      ├─dao
│      │              │      ├─domain
│      │              │      └─service
│      │              │          └─impl
│      │              ├─test
│      │              │  └─dao
│      │              └─web
│      │                  └─auth
│      ├─generated-sources
│      │  └─annotations
│      ├─generated-test-sources
│      │  └─test-annotations
│      ├─maven-archiver
│      ├─maven-status
│      │  └─maven-compiler-plugin
│      │      ├─compile
│      │      │  └─default-compile
│      │      └─testCompile
│      │          └─default-testCompile
│      ├─surefire-reports
│      └─test-classes
│          └─com
│              └─online
│                  └─college
│                      └─service
├─ocWechat
│  ├─.settings
│  ├─src
│  │  └─main
│  │      ├─java
│  │      │  └─com
│  │      │      └─online
│  │      │          └─college
│  │      │              └─wechat
│  │      │                  ├─business
│  │      │                  │  └─impl
│  │      │                  ├─controller
│  │      │                  ├─vo
│  │      │                  └─wxapi
│  │      │                      ├─controller
│  │      │                      ├─interceptor
│  │      │                      ├─process
│  │      │                      ├─service
│  │      │                      │  └─impl
│  │      │                      └─vo
│  │      ├─resources
│  │      └─webapp
│  │          ├─res
│  │          │  ├─css
│  │          │  ├─i
│  │          │  └─js
│  │          └─WEB-INF
│  │              ├─ftl
│  │              └─pages
│  │                  ├─common
│  │                  ├─error
│  │                  └─test
│  └─target
│      ├─classes
│      │  └─com
│      │      └─online
│      │          └─college
│      │              └─wechat
│      │                  ├─business
│      │                  │  └─impl
│      │                  ├─controller
│      │                  ├─vo
│      │                  └─wxapi
│      │                      ├─controller
│      │                      ├─interceptor
│      │                      ├─process
│      │                      ├─service
│      │                      │  └─impl
│      │                      └─vo
│      ├─generated-sources
│      │  └─annotations
│      ├─maven-archiver
│      ├─maven-status
│      │  └─maven-compiler-plugin
│      │      └─compile
│      │          └─default-compile
│      └─ocWechat
│          ├─META-INF
│          ├─res
│          │  ├─css
│          │  ├─i
│          │  └─js
│          └─WEB-INF
│              ├─classes
│              │  └─com
│              │      └─online
│              │          └─college
│              │              └─wechat
│              │                  ├─business
│              │                  │  └─impl
│              │                  ├─controller
│              │                  ├─vo
│              │                  └─wxapi
│              │                      ├─controller
│              │                      ├─interceptor
│              │                      ├─process
│              │                      ├─service
│              │                      │  └─impl
│              │                      └─vo
│              ├─ftl
│              ├─lib
│              └─pages
│                  ├─common
│                  ├─error
│                  └─test
└─out
    ├─production
    │  ├─main
    │  │  └─META-INF
    │  └─main2
    │      ├─com
    │      │  └─online
    │      │      └─college
    │      │          ├─core
    │      │          │  ├─auth
    │      │          │  │  └─dao
    │      │          │  ├─consts
    │      │          │  │  └─dao
    │      │          │  ├─course
    │      │          │  │  └─dao
    │      │          │  ├─statics
    │      │          │  │  └─dao
    │      │          │  └─user
    │      │          │      └─dao
    │      │          └─test
    │      │              └─dao
    │      └─META-INF
    └─test
        └─test
```

# 说明
请阅读主项目/doc/wiki文档内容
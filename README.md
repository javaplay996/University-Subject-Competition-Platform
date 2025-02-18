﻿基于Vue.js和SpringBoot的高校学科竞赛平台是一个综合性的在线系统，旨在为高校提供一个管理学科竞赛的数字化解决方案。

项目录屏：https://www.bilibili.com/video/BV1u4421w7XJ

### 1. 管理后台

管理后台是为管理员和教师提供的一个功能强大的管理界面，通常包括以下模块：

#### 教师管理模块

- **教师信息管理**：添加、编辑、删除教师信息。
- **权限分配**：为教师分配不同的权限，如竞赛管理、学生管理等。
- **教师活动记录**：记录教师在平台上的活动，如登录时间、操作记录等。

#### 学生管理模块

- **学生信息管理**：管理学生的基本信息，包括添加、编辑、删除等。
- **学生竞赛参与情况**：跟踪学生的竞赛参与情况，包括报名、参与、获奖等。
- **学生权限管理**：为学生设置不同的访问权限，如查看竞赛信息、提交作品等。

#### 竞赛信息模块

- **竞赛发布**：管理员可以发布新的竞赛信息，包括竞赛名称、时间、规则等。
- **竞赛管理**：管理已发布的竞赛，包括编辑、删除、查看报名情况等。
- **竞赛结果管理**：记录和发布竞赛结果，包括获奖名单、评分标准等。

#### 学院专业模块

- **学院信息管理**：管理学院的基本信息，包括添加、编辑、删除等。
- **专业信息管理**：管理专业信息，包括添加、编辑、删除等。
- **学院与专业关系管理**：设置学院与专业之间的关系，便于管理学生的学院和专业归属。

#### 获奖情况模块

- **获奖信息管理**：记录和管理学生的获奖信息，包括奖项名称、获奖时间、获奖等级等。
- **获奖统计**：提供获奖情况的统计分析，帮助管理员了解竞赛的整体表现。

### 2. 用户网页端

用户网页端是为学生和教师提供的一个交互界面，通常包括以下功能：

#### 竞赛信息浏览

- **竞赛列表**：展示当前可参与的竞赛列表。
- **竞赛详情**：查看竞赛的详细信息，包括规则、时间、报名方式等。

#### 学生参与竞赛

- **报名竞赛**：学生可以在线报名参与竞赛。
- **提交作品**：在指定时间内提交竞赛作品。
- **查看竞赛状态**：查看自己的报名状态、作品提交状态等。

#### 教师管理竞赛

- **查看报名学生**：教师可以查看报名自己负责的竞赛的学生名单。
- **评分与评审**：教师可以对学生提交的作品进行评分和评审。

#### 获奖信息查看

- **查看获奖名单**：学生和教师可以查看竞赛的获奖名单。

### 技术栈

- **前端**：Vue.js，用于构建用户界面和交互逻辑。
- **后端**：Spring Boot，用于处理业务逻辑、数据库操作和API服务。
- **数据库**：通常使用MySQL或PostgreSQL等关系数据库。
- **身份验证**：可能使用Spring Security或JWT（JSON Web Tokens）进行用户身份验证和授权。

这个平台的设计旨在提供一个高效、易用且功能全面的竞赛管理解决方案，以支持高校的学科竞赛活动。
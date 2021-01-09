---
name: 制作镜像（商品生产）
about: 根据产品设计规范制作镜像，依据产品文档（运行规范）进行生产测试和开机测试，通过两项测试才算合格商品
title: '通过自动打包系统在各个云平台制作镜像'
labels: 'enhancement'
assignees: 

---


**Offer ID**
Wordpress5.6-LAMP-centos
- [ ] Azure
- [ ] Aws
- [ ] 阿里云
- [ ] 腾讯云
- [ ] 华为云
- [ ] AlibabaCloud
- [ ] HUWEICloud

**Steps**

- [ ] 确定软件版本、操作系统-在Github阅读产品规范
- [ ] 自动化打包生产
- [ ] 运行出错，在Github提交issue
- [ ] 运行完成，进行生产测试-根据产品文档进行测试，测试商品是否符合设计要求
- [ ] 测试不通过，在Github提交issue
- [ ] 测试通过，确认打包成镜像
- [ ] 开机测试-进入云平台通过镜像创建实例，按生产测试流程测试，通过测试，结束该任务
- [ ] 测试不通过，在Github提交issue

**要求**

- 产品设计规范：https://github.com/websoft9/ansible-wordpress
- 产品运行规范：https://support.websoft9.com/docs/wordpress/zh/stack-installation.html
- 必须经过两轮测试，符合产品运行规范，才算合格商品：生产过程测试运行界面\服务启动\数据库可视化界面；开机测试：生产过程测试+随机密码测试
---
name: 商品生产与上架
about: 依据产品设计规范和运行规范制作镜像，并通过两项测试生产合格商品；将合格商品在各大云平台上架
title: New Offer/SKU on Azure/AWS/阿里云/华为云/腾讯云/AlibabaCloud/HUAWEICLOUD
labels: 
assignees: 

---


**镜像信息**

镜像制作完成，需完善组件信息  

```
示例：Wordpress5.6-LAMP-CentOS7.7  
组件：WordPress5.6, Apache2.4, phpMyAdmin, MySQL  

示例：Gitlab12.4-CentOS7.7  
组件：Gitlab12, PostgreSQL11, pgAdmin  
```

**平台**

- [ ] Azure
- [ ] Aws
- [ ] 阿里云
- [ ] 腾讯云
- [ ] 华为云
- [ ] AlibabaCloud
- [ ] HUWEICloud
- [ ] GoogleCLoud

**生产**

参考：[Github](https://github.com/websoft9/ansible-wordpress), [产品文档](https://support.websoft9.com/docs/wordpress/zh/stack-installation.html) 
测试：必须经过两轮测试，符合产品运行规范，才算合格商品：生产过程测试运行界面\服务启动\数据库可视化界面；开机测试：生产过程测试+随机密码测试

- [ ] 生产前准备：查阅Github项目主页，确认软件和OS版本
- [ ] 安装应用：基于mcloud，安装出错，提交issue，终止
- [ ] 第一轮测试：测试出错或不符合预期，提交issue，终止
- [ ] 打包镜像
- [ ] 第二轮测试：测试出错或不符合预期，提交issue，终止
- [ ] 填写商品组件信息
- [ ] 结束

**上架**

重点关注：所属分类、亮点提炼、主数据核实

- [ ] 填写信息
- [ ] 已提交
- [ ] 主动撤回
- [ ] 被拒
- [ ] 发布中
- [ ] 分发全球中
- [ ] 购买测试成功
- [ ] 购买测试失败
- [ ] 删除镜像和快照

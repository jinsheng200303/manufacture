---
name: 商品生产与上架
about: 依据产品设计规范和运行规范制作镜像，并通过两项测试生产合格商品；将合格商品在各大云平台上架
title: New Offer/SKU on Azure/AWS/阿里云/华为云/腾讯云/AlibabaCloud/HUAWEICLOUD
labels: 
assignees: 

---


**商品信息**

#### nodejs13-mongo4.2-CentOS7.9

```
完成商品制作后，此处增加版本信息
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

参考：[Github项目主页](https://github.com/websoft9/ansible-wordpress), [产品文档](https://support.websoft9.com/docs/wordpress/zh/stack-installation.html)   
测试：必须两轮测试，第一轮测试：运行界面\服务启动\数据库可视化界面；第二轮测试：第一轮测试内容+随机密码测试

- [ ] 生产准备：查阅Github项目主页，确认软件和OS版本
- [ ] 安装应用：基于mcloud，安装出错，立即将出错任务从本 issue 中剔除，并新增 issue
- [ ] 第一轮测试：对安装结果进行测试，出错或不符合预期，提交issue，终止
- [ ] 打包镜像
- [ ] 填写组件

**质检**
- [ ] 第二轮测试：对开机结果进行测试，出错或不符合预期，提交issue，终止
- [ ] 完成生产


**上架**

重点关注：合规性、ID不可更改性、所属分类、亮点提炼、主数据核实

- [ ] 完成草稿
- [ ] 内部审核
- [ ] 平台审核
- [ ] 被拒
- [ ] 主动撤回
- [ ] 平台审核通过
- [ ] 镜像分发全球
- [ ] 购买测试（100次）
- [ ] 删除镜像和快照

# 制造

## 生产方针：

- 环境配备，方可生产
- 生产任务，明确清晰
- 生产环节，有迹可循
- 测试规范，严格遵守
- 准确第一，兼顾效率
- 任务流转，确认到人
- 快速上架，强化审核
- 当日产品，当日审核

## 上架流程

任务分配->生产->质检->服务器清理->商品录入->内审->平台审核->上架

## 变更点说明

### 责任人

调整模板能指定多个责任人，任务分配时按先后顺序指定生产者和质检者：第一个是生产者，第二个是消费者

### BUG

#### 分类

##### bug-产品故障
应用程序自身bug或者websoft9生产程序的bug

##### bug-生产过失
生产者过失，如镜像错误删除，服务未启动，初始画面无法进入。生产过失责任者需要两个，第一个是生产者，需要扣除；第二个是质检者，需要奖励

#### 变更点
##### Lable
由Bug调整为【bug-产品故障】，【 bug-生产过失】
##### bug提出方式
发现bug，责任人第一时间提出新issue，并标注Lable
##### 标签修改
由于bug导致的再次生产，不提交新的生产issue，原生产issue的Lable改成【第2次生产】，【第3次生产】。。。
##### 可重复性
1个生产任务【bug-产品故障】允许提交多次；【bug-生产过失】最多只能提交一次，最好生产者和质检者协调解决，保证没有【bug-生产过失】

### 财务结算

#### 时间点
由按周结算改为按月结算

#### 完成标准
由质检完成改为上架完成

#### 单价
生产计件单价：10元，BUG计件单价：10元

#### 计算方法与公式
1. 完成面板过滤责任者后
2. 工资公式  
责任者工资为=Lable为空issue数量x5 + Lable为【第2次生产】issue数量x5x2 + 。。。 + Lable为【bug-产品故障】issue数量x10 ± Lable为【bug-生产过失】issue数量x10
（奖惩请参照BUG分类原则）
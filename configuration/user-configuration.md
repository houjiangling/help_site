# 用户管理

## 1.简介

GrowingIO提供了高度自定义的权限方式，方便您管理您项目内部的所有数据，以及用户。保障高度的数据安全的同时，帮助您和您的组织实现更好的协作。

## 2.权限角色

GrowingIO的系统内部提供了多种的权限角色，帮助企业内部不同权限和分工的用户都能参与到数据驱动的过程中来。不同的权限角色，能够使用不同的功能，并且提供了差异化的功能权限、资源权限和数据权限。

### 默认角色

GrowingIO系统提供了默认的两个权限角色，分别是：

* 超级管理员:权限最高的管理员，项目的创建者和拥有者，能够管理所有的用户（包括管理员）和数据
* 普通用户:无法进行新建和编辑，只能查看被授权的数据

#### 超级管理员

超级管理员能够：

1. 新建&管理项目内的应用
2. 管理自定义上传数据
3. 邀请&禁用&删除用户
4. 管理用户权限&设置用户小组
5. 管理项目内的所有的单图
6. 管理所有的指标
7. 所有更低权限拥有的权限
8. 直接添加用户或批量添加用户

#### 普通用户

普通用户不具备创建和编辑能力，只能够查看被授权的内容，具体权限细节包括：

1. 查看被授权的内容
2. 不可使用圈选&热图
3. 不可进行内容创建

具备用户管理权限的人员可对普通用户角色的权限进行设置。

### 自定义角色

自定义权限角色，是提供给GrowingIO付费用户的高级权限管理功能。通过自定义权限角色，您可以对GrowingIO所有的功能做到精确的控制。根据不同的需求组合出不同的权限角色。帮助您的所有系统用户都能够加入到数据驱动的过程中。

可以设置的权限包括：

1. 功能权限：泛指产品内各个功能模块的操作权限，本次涉及的操作包括：查看、新建、编辑、分享、删除、邀请、下载、圈选
2. 资源权限：用户通过产品创造的内容统称为资源，包括看板、单图、留存、漏斗、分群、指标，对这些资源在分享传播时，可以分配权限进行访问控制
3. 数据权限：全局设置，可以对用户可以访问的数据范围进行控制

## 典型应用场景

1. **指定一名人员主要负责圈选，不做其他操作**

   通过创建一个圈选角色，只分配功能权限中的圈选和指标管理即可。

2. **在内部流程中，将数据的生产和消费划分的十分清晰**

   通过创建至少3个角色，分别为

   **圈选角色：**只分配功能权限中的圈选和指标管理，主要负责维护公司级别的指标体系，供生产者使用

   **生产角色：**分配功能权限中看板/单图/漏斗/留存/分群的查看/新建/分享权限，主要负责制作分析资源并进行传播

   **消费角色：**分配功能权限中概览/实时/业务模板/看板/单图/漏斗/留存/分群的查看权限，主要消费生产者制作的分析内容和系统默认的分析模板，必要时，可以开通功能权限中看板/单图/漏斗/留存/分群的分享权限，利于再传播

3. **指定一名管理员，负责系统的日常管理**

   通过创建一个管理员角色，只分配功能权限中的角色管理/用户管理/项目管理/应用管理的查看/编辑功能，负责日常创建新应用、创建新角色/用户并分配权限等操作。

4. **将某一指标视为核心数据，不需要全员公开**

   由该指标的创建人在分享指标时，选择部分用户可见，并指定操作仅为查看。如此，在分享名单之外的用户，即使访问使用了该指标的看板或单图时，也无法查看到指标数据。

5. **针对同一看板，需要区分不同人员的可访问数据范围**

   通过对用户设置数据权限来限定数据访问范围，例如：设置用户A只可访问地区=北京的数据，那么在任一看板中，相当于默认做了维度地区=北京的数据过滤。


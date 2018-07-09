# BPM
## BPM模式调整
### 串行会签
- 修改文件
properties-multiinstancemodel-controller.js 
$scope.items定义了审批模式数组
- 修改配置
stencilset.json

{
    "name" : "multiinstance_modelpackage",
    "properties" : [ {
      "id" : "multiinstance_model",
      "type" : "kisbpm-multiinstancemodel",
      "title" : "审批模式",
      "value" : "Grab",
      "description" : "审批模式",
      "group" : "参与人",
      "popular" : true,
      "refToView" : "multiinstancemodel"
    } ]
  }


## BPM扩展属性

### 角色限定 
### 用户组限定
### 扩展角色(动态限定)

### 指派
* 发起指派
* 环节指派
### 逾期
act_ru_task：due_date
### 抄送
bpm_re_message：copytousers
### 操作
* 可驳回
* 可被驳回
* 可加签
* 可改派
* 可指派


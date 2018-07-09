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
## 指派
* 发起指派
* 环节指派

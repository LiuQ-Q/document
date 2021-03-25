# v2.2.5
操作日志

学科管理员

开放辅导-问答中心-投诉列表-1

home.common.double.faq.all-question_home.common.double.faq.all-question_home.maintenance.usermanage.log

{
  "area": "home",
  "view": "maintenance",
  "subview": "usermanage",
  "lastview": "log"
}

-----------------------------------------
双师统计

区县管理员

第三个平台统计-14

home.maintenance.statistics.termteststats_home.maintenance.statistics.double

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "double",
  "region_type": "double"
}


-----------------------------------------

诊断报告页面--浏览试题详情

openExamQuestionsDetail

{
  exam_id:"string",            //考试ID
  paper_id:"string",           //试卷ID
  title: "string",             //标题
  course: "string",            //学科
  question_id: "string"        //题目id
}

应用场景：

群体总测/模拟/微测/日测报告--能力表现中查看相关题目详情

# v2.3.3
## 平台统计菜单改三级

### 平台统计-1（管理员、运营管理员、学科管理员）

#### 顺序

平台活跃、功能使用、报告查看、题库使用、测评使用、资源统计、批阅统计、双师辅导

#### 测评使用统计

测评使用统计

home.maintenance.statistics.platformretained_home.maintenance.statistics.termteststats

20

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "termteststats",
  "showSubRoute": true
}

1. 测评使用统计-总测使用统计

总测使用统计

home.maintenance.statistics.platformretained_home.maintenance.statistics.termteststats_home.maintenance.statistics.termteststats

0

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "termteststats"
}

2. 测评使用统计-微测使用统计

微测使用统计

home.maintenance.statistics.platformretained_home.maintenance.statistics.termteststats_home.maintenance.statistics.unitteststats

1

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "unitteststats"
}

3. 测评使用统计-日常测评统计

日常测评统计

home.maintenance.statistics.platformretained_home.maintenance.statistics.termteststats_home.maintenance.statistics.dailyteststats

2

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "dailyteststats"
}

4. 测评使用统计-模拟测试统计

模拟测试统计

home.maintenance.statistics.platformretained_home.maintenance.statistics.termteststats_home.maintenance.statistics.simulationteststats

3

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "simulationteststats"
}

5. 测评使用统计-素质测评统计

素质测评统计

home.maintenance.statistics.platformretained_home.maintenance.statistics.termteststats_home.maintenance.statistics.qomtest

4

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "qomtest"
}

6. 测评使用统计-健康知识统计

健康知识统计

home.maintenance.statistics.platformretained_home.maintenance.statistics.termteststats_home.maintenance.statistics.healthknowledge

5

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "healthknowledge"
}

#### 资源统计

资源统计

home.maintenance.statistics.platformretained_home.maintenance.statistics.resources

21

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "resources",
  "showSubRoute": true
}

1. 资源统计-资源使用统计

资源使用统计

home.maintenance.statistics.platformretained_home.maintenance.statistics.resources_home.maintenance.statistics.resources

0

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "resources"
}

2. 资源统计-资源上传统计

资源上传统计

home.maintenance.statistics.platformretained_home.maintenance.statistics.resources_home.maintenance.statistics.resource

1

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "resource"
}

#### 批阅统计

批阅统计

home.maintenance.statistics.platformretained_home.maintenance.statistics.automarking

22-

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "automarking",
  "showSubRoute": true
}

1. 自动批阅统计

自动批阅统计

home.maintenance.statistics.platformretained_home.maintenance.statistics.automarking_home.maintenance.statistics.automarking

0

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "automarking"
}

2. 第三方批阅统计

第三方批阅统计

home.maintenance.statistics.platformretained_home.maintenance.statistics.automarking_home.maintenance.statistics.thirdmark

1

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "thirdmark"
}

2. 1. 查看总测

查看总测

home.maintenance.statistics.platformretained_home.maintenance.statistics.automarking_home.maintenance.statistics.thirdmark_home.maintenance.statistics.termtest

0

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "termtest",
  "hidden": true
}

2. 2. 查看模拟

查看模拟

home.maintenance.statistics.platformretained_home.maintenance.statistics.automarking_home.maintenance.statistics.thirdmark_home.maintenance.statistics.simulationtest

1

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "simulationtest",
  "hidden": true
}

2. 3. 查看微测

查看微测

home.maintenance.statistics.platformretained_home.maintenance.statistics.automarking_home.maintenance.statistics.thirdmark_home.maintenance.statistics.unittest

2

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "unittest",
  "hidden": true
}

2. 4. 第三方批阅统计设置

第三方批阅统计设置

home.maintenance.statistics.platformretained_home.maintenance.statistics.automarking_home.maintenance.statistics.thirdmark_home.maintenance.statistics.thirdmarksetup

3

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "thirdmarksetup"
}

#### 双师辅导统计

双师辅导统计

home.maintenance.statistics.platformretained_report.common.index.double

7

{
  "area": "report",
  "view": "common",
  "subview": "index",
  "report_type": "double",
  "showSubRoute": true
}

1. 一对一辅导统计

一对一辅导统计

home.maintenance.statistics.platformretained_report.common.index.double_report.common.index.double

0

{
  "area": "report",
  "view": "common",
  "subview": "index",
  "report_type": "double"
}

2. 双师统计

双师统计

home.maintenance.statistics.platformretained_report.common.index.double_home.maintenance.statistics.double

1

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "double"
}

3. 互动课堂统计

互动课堂统计

home.maintenance.statistics.platformretained_report.common.index.double_home.maintenance.statistics.livelessonstats

2

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "livelessonstats"
}

4. 问答情况统计

问答情况统计

home.maintenance.statistics.platformretained_report.common.index.double_home.maintenance.statistics.faq

3

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "faq"
}

5. 问答知识点统计

问答知识点统计

home.maintenance.statistics.platformretained_report.common.index.double_report.common.index

4

{
  "area": "report",
  "view": "common",
  "subview": "index",
  "report_type": "faq"
}

## 新增素质测评菜单

1. 平台统计-3

市级管理员、区县管理员、学校管理员

素质测评统计

home.maintenance.statistics.termteststats_home.maintenance.statistics.qomtest

17

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "qomtest"
}

2. 平台统计-2

年级主任

素质测评统计

home.maintenance.statistics.dailyteststats_home.maintenance.statistics.qomtest

6

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "qomtest"
}

3. 平台统计-4

班主任

素质测评统计

report.common.index.platform_home.maintenance.statistics.qomtest

6

{
  "area": "home",
  "view": "maintenance",
  "subview": "statistics",
  "lastview": "qomtest"
}

4. 平台统计-6

2心理  勾选

home.maintenance.statistics.qomtest_home.maintenance.statistics.qomtest
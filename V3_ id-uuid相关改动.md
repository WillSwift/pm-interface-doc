### V3  id->uuid相关改动

#### 首页新闻

* 轮播图和新闻列表返回值

  project_id -> uuid

#### 搜索

##### 综合

* 返回参数

  personSearchResults

  ​	person_id -> uuid

  orgSearchResults

  ​	org_id -> uuid

  projectSearchResults

  ​	project_id ->uuid

#### 工商信息

##### 查询工商信息

* 请求参数

  company_id -> uuid（请求参数拼接方式由/改为?）

* 返回参数

  id -> uuid

#### 机构信息

##### 查询已投项目

* 请求参数

  org_id -> uuid（请求参数拼接方式由/改为?）

* 返回参数

  project_id -> uuid

##### 查询机构成员

* 请求参数

  org_id -> uuid（请求参数拼接方式由/改为?）

* 返回参数

  person_id -> person_uuid

##### 查询合投机构

- 请求参数

  org_id -> uuid（请求参数拼接方式由/改为?）

- 返回参数

  investor_id -> investor_uuid

#### 人物信息

##### 查询人物信息

* 请求参数

  person_id -> uuid（请求参数拼接方式由/改为?）

* 返回参数

  person

  ​	id -> uuid

##### 查询已投项目

* 请求参数

  person_id -> uuid（请求参数拼接方式由/改为?）

* 返回参数

  project_id -> uuid

#### 项目信息

##### 查询项目信息

* 请求参数

  project_id -> uuid（请求参数拼接方式由/改为?）

* 返回参数

  project

  	id -> uuid

  	company_id -> company_uuid

##### 查询竞品信息

* 请求参数

  project_id -> uuid（请求参数拼接方式由/改为?）

* 返回参数

  project_id -> uuid






---
title: Rancher API - projectTemplate
layout: rancher-api-v2-beta-default-v1.3
version: v1.3
lang: zh
apiVersion: v2-beta
---

## ProjectTemplate



### Resource Fields

#### Writeable Fields

Field | Type | Create | Update | Default | Notes
---|---|---|---|---|---
description | string | Optional | Yes | - | 
externalId | string | Optional | Yes | - | 
name | string | Optional | Yes | - | 
stacks | array[[catalogTemplate]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/{{page.apiVersion}}/api-resources/catalogTemplate/)] | Optional | Yes | - | 


#### Read Only Fields

Field | Type   | Notes
---|---|---
id | int  | The unique identifier for the projectTemplate


<br>

Please read more about the [common resource fields]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/{{page.apiVersion}}/common/). These fields are read only and applicable to almost every resource. We have segregated them from the list above.





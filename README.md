# **<div id="INDEX">INDEX</div>**
* [ACTIVITY](#ACTIVITY)
* [APP_NOTICE](#APP_NOTICE)

----------
# **<div id="ACTIVITY">ACTIVITY</div>**
> Here is the table description.

| Column            | Datatype      | NotNull | Default                                       | Comments                                                     |
| ----------------- | ------------- | ------- | --------------------------------------------- | ------------------------------------------------------------ |
| SN | int(11) AI PK | v | | |
| TITLE | varchar(512) | v | | |
| TYPE | int(1) | v | 1 | |
| TARGET_SN | int(11) | v | | |
| REQUEST_STAFF_SN | int(11) | v | | |
| REQUEST_TIME | timestamp | | NULL | ㅁㄴㅇㄹㅁㄴㅇㄹㅁㄴㅇㄹㅇㄴㅁㄹㅁㄴㅇㄹㅁㄴㅇㄹㅁㄹㅇㅁㄴㅇㄹㅁㄴㅇㄹㅁㄴㅇㄹ |
| CONFIRM_STAFF_SN | int(11) | | NULL | |
| CONFIRM_TIME | timestamp | | NULL | |
| STATUS | int(1) | v | 1 | |
| TARGET_CONTENT | mediumtext | v | | |
| TARGET_CONTENT_EN | mediumtext | v | | |
| LAST_UPDATE | timestamp | v | CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP | |

## Indexes
* **PRIMARY** - *Index description...*
    1. SN / ASC
* **IDX_ACTIVITY_FK0_idx** - *Index description...*
    1. REQUEST_STAFF_SN / ASC
* **IDX_ACTIVITY_FK1_idx** - *Index description...*
	1. CONFIRM_STAFF_SN / ASC
* **IDX_ACTIVITY_IDX0** - *Index description...*
	1. TYPE / ASC
	2. TARGET_SN / ASC
	3. STATUS / ASC

[Go to Index](#INDEX)

----------

# **<div id="APP_NOTICE">APP_NOTICE</div>**
> Here is the table description.

| Column            | Datatype      | NotNull | Default                                       | Comments                                                     |
| ----------------- | ------------- | ------- | --------------------------------------------- | ------------------------------------------------------------ |
| SN | int(11) AI PK | v | | |
| TITLE | varchar(512) | v | | |
| TYPE | int(1) | v | 1 | |
| TARGET_SN | int(11) | v | | |
| REQUEST_STAFF_SN | int(11) | v | | |
| REQUEST_TIME | timestamp | | NULL | ㅁㄴㅇㄹㅁㄴㅇㄹㅁㄴㅇㄹㅇㄴㅁㄹㅁㄴㅇㄹㅁㄴㅇㄹㅁㄹㅇㅁㄴㅇㄹㅁㄴㅇㄹㅁㄴㅇㄹ |
| CONFIRM_STAFF_SN | int(11) | | NULL | |
| CONFIRM_TIME | timestamp | | NULL | |
| STATUS | int(1) | v | 1 | |
| TARGET_CONTENT | mediumtext | v | | |
| TARGET_CONTENT_EN | mediumtext | v | | |
| LAST_UPDATE | timestamp | v | CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP | |

## Indexes
* **PRIMARY** - *Index description...*
    1. SN / ASC
* **IDX_ACTIVITY_FK0_idx** - *Index description...*
    1. REQUEST_STAFF_SN / ASC
* **IDX_ACTIVITY_FK1_idx** - *Index description...*
	1. CONFIRM_STAFF_SN / ASC
* **IDX_ACTIVITY_IDX0** - *Index description...*
	1. TYPE / ASC
	2. TARGET_SN / ASC
	3. STATUS / ASC

[Go to Index](#INDEX)



# RecSysArcht

## Summary

一个通用推荐系统实现，在线召回/特征抽取/排序 & 离线数据/模型batch更新。

离线（scala）能够复用部分在线抽取特征代码（java）。数据/模型通过s3/elasticsearch等存储中转。

## 在线服务

<img src="https://github.com/cyber4ron/notes/blob/master/images/rec_sys_online.jpg" width="737" height="630">

## 离线数据pipeline

<img src="https://github.com/cyber4ron/notes/blob/master/images/rec_sys_offline.jpg" width="775" height="626">

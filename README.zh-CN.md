# dolphindb_project
# 1. 分组查询 top N
查询指定1小时内CPU平均利用率最高的三台设备。假设CPU利用率为指标1。这里使用嵌套查询，先分组计算平均值，然后根据平均值排序，再对结果使用 top 子句（或 limit 子句）
# 2. 关联查询
DolphinDB支持如下7种关联查询:equal join (ej), left join (lj), cross join (cj), full join (fj), asof join (aj), window join (wj) 和 prefix join (pj)

详见 https://github.com/dolphindb/Tutorials_CN/blob/master/iot_examples.md
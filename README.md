# api-doc
数据驾驶舱接口文档


（名称，值，解释）

### 服务费用明细表

* 参数：  
procName: "PROC_SYS_SERVICE_CHARGE_LIST_LOAD"  
in_shopName: "杭州蚂葵电子商务有限公司"   -- 公司名称
in_gongsName: "toto旗舰店"               -- 店铺名  
in_starTime："1900-01-01"               -- 起始时间  
in_endTime："1900-01-01"                -- 结束时间  

* 返回值：  
gongsName（公司名称）b2cshop(店铺名称) cankNo(参考单号) b_org_otype_name(订单来源) pinpName (品牌)
shangpcode(商品编码) leibName(类别) service_parent(服务类型) service_count(服务数量) service_money(佣金(元))
order_status(单据状态) real_create_time(创建时间) finished_time(完工时间) yewOrgName(业务部门)

### 服务费用统计表
* 参数： 

* 返回值：  



### 服务费用统计表-服务类型
* 参数：  

* 返回值：  



### 所有公司
* 参数：  

* 返回值：  



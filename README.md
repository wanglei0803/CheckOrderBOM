	BOM比对系统方案V1.2
<br />	文档编写：王磊
<br />	1、项目内容：JIS生产中，客户发送的订单，每个订单的配置要求不一样。客户发送给供应商的订单又是一堆零件，这些零件是否可以组成对应的产品，如何分析？ BOM比对系统将解决这些问题，确切说：也可以称客户BOM校验系统。
<br />	2、系统基础信息：
<br />	(1)角色管理：名称、权限、状态。
<br />	(2)账号信息管理：姓名、部门、员工编号、登陆名、密码、最后登陆时间、是否域用户、域用户名。
<br />	(3)账号密码安全策略：密码长度、历史保存几次、密码有效时间、长期不使用天数锁定。
<br />	(4)职员信息管理：姓名、部门、员工编号、电话，第三方系统比对姓名、员工编号。
<br />	3、BOM管理
<br />	(1)项目管理：项目名称、负责人、项目开始时间、结束时间、状态、备注
<br />	(2)BOM版本管理：BOM版本名称、负责人、开始时间、结束时间
<br />	(3)BOM维护：所属项目、父零件号、零件号、零件描述、零件数量、变更记录时间、BOM状态（历史、当前、预计变更）
<br />	(4)BOM导入：支持CSV报表直接导入。
<br />	(5)BOM导出：导出CSV报表，可以用Excel打开。
<br />	(6)第三方BOM系统数据校验差异：根据使用环境搭建。
<br />	4、订单管理
<br />	(1)订单管理：订单号，子零件号、数量、添加时间、预计生产时间、属性编码、其他信息。
<br />	(2)订单校验：对一个或多个订单号的的子零件及数量域BOM匹配校验。对订单完成相同、历史相同、预计变更相同、存在差异进行颜色标识。
<br />	(3)订单差异分析：对一个或多个订单号的的子零件及数量域BOM匹配校验，进行相似程度排序，并列出最相似的5个配置明细,BOM的配置类似一个人工智能的小模型，客户的订单是需要校验的数据。
<br />	(4)第三防系统对接，根据实际环境进行开发、编写。
<br />	5、审计日志
<br />	(1)BOM变更记录。
<br />	(2)系统账号登陆记录。
<br />  注：对于年产值40亿左右的JIS模块生产，差异纠正起初每年预计5000万左右。


<br /> This is a Chinese project. 
<br /> email: wanglei0803@126.com  wecat: Kaixinsanshi  
<br /> Please link me in Chinese.  
<br /> thank you.  

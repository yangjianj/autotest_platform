# autotest_platform
自动化测试平台  
功能构想：    
1.UI页面实现任务导入\选择--调度    
2.UI页面实现任务执行实时查看    
3.UI页面执行结果查看，结果分析，统计，bug管理系统对接    
4.支持分布式执行,分布式各slave状态管理    

实现构想：    
1.lib测试库  
2.贴合业务的逻辑模块  
3.测试用例  
4.测试数据  
5.测试日志  
6.测试报告（测试结果收集：allcase,passed,failed,error，通过case名，失败case名..）  
收集方法：
robot framework--提取output.xml文件信息    
pytest--    
unittest--    
7.run.py执行文件  
8.测试条件筛选配置文件(执行那些类型的业务)*.py/*.ini      
9.配置文件（服务器，用户名等）*.py/*.ini    

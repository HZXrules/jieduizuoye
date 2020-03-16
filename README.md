**作业链接：** [结对第二次作业](https://www.cnblogs.com/021700613h/p/12490473.html)

**结对学号：** 021700613/041701407

**项目介绍：** 
![功能结构图](https://images.cnblogs.com/cnblogs_com/021700613h/1670594/o_200316112016%E7%96%AB%E6%83%85%E7%B3%BB%E7%BB%9F.png "功能结构图")



**如何构建：** 
1.前端源码：www目录下（VUE、ElementUI、ECharts、Maptalks、D3js）

	开发部署：
		
		cd www
		
		npm install
		
		npm run serve	
	
	在：http://localhost:8080/查看

2.后端源码：src目录下（PYTHON3、Flask、Mysql）

	配置文件：src/config.py	

3.数据库：（Mysql）
	
	文件：src/db/epidemic.sql
	
	新建数据库epidemic，将该文件导入MySQL即可。（命令行方式：use epidemic; source /root/epidemic.sql;）

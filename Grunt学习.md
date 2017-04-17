# 什么是前端集成解决方案以及能解决什么问题
- 开发团队风格不统一，如何强制开发规范
- 前端开发组建库如何维护和使用
- 如何模块化前端项目
- 服务器部署前必须的压缩，检查流程如何简化，流程如何完善
# nodejs npm 安装grunt -the javascript Task Runner（一头面目可憎的猪）
- 安装grunt 的命令<b>npm install -g -grunt-cli</b>
-  build tool:可以帮我们实现自动化，减少像压缩，编译，单元测试，代码校验，这种重复且无业务关联的工作
## nodeJs 提供了一个package.json的配置文件，当在cmd中输入npm install 后面没有任何参数时，npm则会去当前目录找package.json这个文件，安装这个文件的中的配置安装
	package.json中的dependencies 里面的内容就是当前项目所依赖 的包
		{
		    "dependencies":{
				"grunt":"^0.4.6",
				"grunt-contrib-concat":"^0.4.0"
				}
		} 
## npm安装yoman
- 安装命令 <b>npm install -g yo</b>
## npm安装Bower（一种鸟）
	 在传统的开发流程中，当项目需要jquery1.1 和jquery1.2 时，我们要到官网把2个版本都下载下来，这样很麻烦，当是有了bower，
	 我们就不用在去到官网下载
	 bower会自动帮我们下载我们项目中需要的版本
- 安装bower的命令<b>npm install -g bower</b>

# 我们为什么选择GRUNT ？
- 生态强大，插件齐全
- 生态急速增长 
	

# 什么是前端集成解决方案以及能解决什么问题
- 开发团队风格不统一，如何强制开发规范
- 前端开发组建库如何维护和使用
- 如何模块化前端项目
- 服务器部署前必须的压缩，检查流程如何简化，流程如何完善
# nodejs npm 安装grunt
- 安装grunt 的命令<b>npm install -g -grunt-cli</b>
## nodeJs 提供了一个package.json的配置文件，当在cmd中输入npm install 后面没有任何参数时，npm则会去当前目录找package.json这个文件，安装这个文件的
中的配置安装
- package.json中的dependencies 里面的内容就是当前项目所依赖 的包
	{
		"dependencies":{
			"grunt":"^0.4.6",
			"grunt-contrib-concat":"^0.4.0"
		}
	} 
  

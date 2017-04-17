# 什么是前端集成解决方案以及能解决什么问题
- 开发团队风格不统一，如何强制开发规范
- 前端开发组建库如何维护和使用
- 如何模块化前端项目
- 服务器部署前必须的压缩，检查流程如何简化，流程如何完善
# nodejs npm 安装grunt -the javascript Task Runner（一头面目可憎的猪）
- 安装grunt 的命令<b>npm install -g -grunt-cli</b>
	  cli是commandLine interface
-  build tool:可以帮我们实现自动化，减少像压缩，编译，单元测试，代码校验，这种重复且无业务关联的工作
		然后在cmd中执行grunt ，如果 看到一个unable to find local grunt.说明以及安装成功，
	 	<b>为什么会报错呢？</b>
		  因为grunt-cli 会执行当前目录中package.json中指定安装的grunt 版本来读取当前目录中grunt.file的配置文件。然后根据配置
		  来对我们的项目执行自动化

## nodeJs 提供了一个package.json的配置文件，当在cmd中输入npm install 后面没有任何参数时，npm则会去当前目录找package.json这个文件，安装这个文件的中的配置安装
	package.json中的dependencies 里面的内容就是当前项目所依赖 的包
		{
		    "dependencies":{
				"grunt":"^0.4.6",
				"grunt-contrib-concat":"^0.4.0"
				}
		} 
## npm安装YEOMAN（yeoman只是一团橡皮泥）
- yeoman 的作用：在web项目的立项阶段，使用yeoman来生成项目的文件，代码结构。yeoman自动将自动实践工具整合进来，大大加速和方便了我们后续的开发。
### yeoman 为什么会自动选择最佳的实践工具？
	 yeoman的开发者 很早就想到了这一点，所以他们维护了一套生成器的生态。yeoman为我们提供了一套最基本的功能流程
	 代码校验————测试———— 压缩，其余部分交给生成器自由发挥
- 安装命令 <b>npm install -g yo</b>
## npm安装Bower（一种鸟）a package manager for the web
	 一个web 站点有很多部分组成，框架，库，公共部分等。而bower则用来跟踪管理这些
	 在传统的开发流程中，当项目需要jquery1.1 和jquery1.2 时，我们要到官网把2个版本都下载下来，这样很麻烦，当是有了bower，
	 我们就不用在去到官网下载bower会自动帮我们下载我们项目中需要的版本.
- 安装bower的命令<b>npm install -g bower</b>

# 我们为什么选择GRUNT ？
- 生态强大，插件齐全
- 生态急速增长 
	

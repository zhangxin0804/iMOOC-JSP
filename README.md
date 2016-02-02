1. 课程网址 http://www.imooc.com/learn/166

2. 如何安装Tomcat 8 on OSX?  https://wolfpaulus.com/journal/mac/tomcat8/

3. MyEclipse是在Eclipse基础上加上自己的插件开发而成的功能强大的企业级应用程序集成开发环境，主要用于Java, JavaEE以及移动应用程序的开发。
MyEclipse的功能非常强大，支持广泛，尤其是对各种开源产品的支持也不错。

	MyEclipse: 		收费，集成了很多收费的插件，比如 SSH，安卓等。
	Eclipse: 		免费开源，不包含任何附加功能的插件。
	Eclipse J2EE: 	也可以用于Java WEB应用程序的开发。

4. 使用MyEclipse开发Java WEB程序   以及  使用Eclipse_J2EE开发Java WEB程序。 
http://www.imooc.com/video/2929
http://www.imooc.com/video/2931

5. 如何使用Eclipse For Java EE 来开发Java WEB应用程序。

	首先下载Eclipse J2EE版本，然后打开eclipse指定workspace. 新建一个dynamic web project工程，输入工程名称。然后Target Runtime表示
项目的运行环境，选择Apache Tomcat v8.0，然后指定到Tomcat的安装主目录 /usr/local/apache-tomcat-8.0.30    指定JRE运行环境，选择JDK1.8
	接下来创建一个默认的首页，在工程explore栏的WebContent下，创建一个index.jsp文件。然后输入测试例句。
	右键工程，run as on Server，选择Tomcat 8.然后会出现eclipse自带的浏览器显示效果。

6. 注意：当在Tomcat上部署发布了一个Web应用程序后，默认的路径是和我们在IDE中新建的工程名是相同的，但实际上可以不相同。换句话说，可以修改成其他的
Web项目虚拟路径。修改后，要重新部署，然后启动tomcat后，要换成新的虚拟路径才能正确访问！！！ ( 目前只针对MyEclipse IDE, 不知道Eclipse J2EE )

7. JSP页面的生命周期。http://www.imooc.com/video/2950


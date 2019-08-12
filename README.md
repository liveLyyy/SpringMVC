SpringMVC
=========
1、SpringMVC中重要组件<br>
>1.1、DispatcherServlet：前端控制器，接收所有请求（如果配置/不包含jsp)<br>
>1.2、HandlerMapping：判断请求格式,判断希望要执行那个具体的方法<br>
>1.3、HandlerAdapter：负责调用具体的方法<br>
>1.4、ViewResovler：视图解析器，解析结果，准备跳转到具体的物理视图<br>
>1.4[工作流程](src/main/img/流程.png)<br>


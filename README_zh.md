# 在这个项目里面添加GO2机器人的配置文件以及模型
具体添加内容如下：
* 在legged_gym包中添go2文件夹，包含两个配置文件，一个是宇树的基础配置，一个是AMP需要的配置
* 在legged_gym包的__init__.py中注册go2_amp任务
* 在resources/robot中添加go2的资源文件，包括dae文件以及urdf文件


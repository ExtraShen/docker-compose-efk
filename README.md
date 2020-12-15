# docker-compose 部署efk
docker-compose 一键部署elasticsearch、kibana、filebeat
            
启动步骤：
1、将.env.example文件改名为.env文件

2、将GLOBAL_APP_PATH的路径修改为本项目路径

3、docker-compose build    #构建容器

4、docker-compose start    #一键启动elasticsearch、filebeat、kibana容器

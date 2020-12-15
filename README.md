# docker-compose 部署efk
docker-compose 一键部署elasticsearch、kibana、filebeat

├── README.md
├── docker-compose.yml
├── elasticsearch
│   ├── Dockerfile
│   └── config
│       └── elasticsearch.yml
├── filebeat
│   ├── Dockerfile
│   └── config
│       └── filebeat.yml
├── kibana
│   ├── Dockerfile
│   └── config
│       └── kibana.yml
└── log
    └── crontab
        └── 20200823
            └── 22.log
            
启动步骤：
1、docker-compose build    #构建容器

2、docker-compose start    #一键启动elasticsearch、filebeat、kibana容器

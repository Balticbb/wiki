# 执行arthas脚本
        #!/bin/sh
        if [ ! -f "arthas-boot.jar" ];then
            curl -O https://arthas.aliyun.com/arthas-boot.jar
        sudo -u deploy -EH java -jar arthas-boot.jar
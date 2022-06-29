# Conda 技能点

速效救心丸

查看 conda 下的所有虚拟环境：
- ```conda info -e```

创建 conda 虚拟环境：
- ```conda create -n <new_env_name>```（创建时不指定 python 版本，不推荐）
- ```conda create -n <new_env_name> python=3.*```（创建时指定 python 版本）

删除 conda 虚拟环境：
- ```conda remove -n <env_name> --all```（删除整个环境）


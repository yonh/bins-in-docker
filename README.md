# bins-in-docker

[![Build Status](https://travis-ci.org/yonh/bins-in-docker.svg?branch=master)](https://travis-ci.org/yonh/bins-in-docker)

把所有bin跑在docker里面(可能的情况下)

# bins

* yonh/bin-hugo




### 初始化
拷贝alias脚本到指定位置,并添加source命令,以后更新只需要覆盖alias脚本即可
```
# 如果你使用bash,执行
cp bash_aliases ~/.aliases_file
echo "source ~/.aliases_file" >> ~/.bash_rc

# 如果你使用fish,执行
cp fish_aliases ~/.aliases_file
echo "source ~/.aliases_file" >> ~/.config/fish/config.fish
```


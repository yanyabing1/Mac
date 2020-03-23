# Mac环境配置

## Homebrew安装失败如何处理？

参考： [http://mintimate.cn/2019/06/26/Mac%E6%9D%82%E5%9D%9B/](http://mintimate.cn/2019/06/26/Mac杂坛/)

## Mac下nvm如何安装？

1. 通过brew安装nvm

   `$ brew install nvm`

2. 编辑 ~/.bash_profile文件

   ```
   export NVM_NODEJS_ORG_MIRROR=https://npm.taobao.org/mirrors/node
   source $(brew --prefix nvm)/nvm.sh
   ```

3. 查看当前电脑可安装node的版本

   `$ nvm ls-remote`

4. 安装node

   `$ nvm install v12.6.1`

5. 测试是否安装完成

   > 输入一下命令如果终端显示正常，那么久可以开心的使用node了

   `$ node -v `

   `$ npm -v`


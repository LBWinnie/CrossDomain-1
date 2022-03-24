# 使用方法

0. 安装 node-dev
    `yarn global add node-dev`
1. 进入 qq-com文件夹 运行 server.js
    `cd ../LBWinnie-com; node-dev server.js 8888`
2. 进入 LBWinnie-com文件夹 运行 server.js
    `cd ../LBWinnie-com; node-dev server.js 9999`
3. 设置 hosts (事前设置事后删除)       ————————————————————————
    以管理员身份运行记事本->文件(F)->打开(O)->C盘->Windows->System32->drivers->etc->选择 所有文件(\*.\*)->hosts->添加：
    ```
    127.0.0.1 qq.com
    127.0.0.1 LBWinnie.com
    ```

4. 打开两个页面 
   qq.com:8888/index.html 
   和
   LBWinnie.com:9999/index.html

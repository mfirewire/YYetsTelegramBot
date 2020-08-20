这是一个人人影视资源搜索机器人，效果自行看演示就好 [戳我](https://cdn.jsdelivr.net/gh/AlphaBrock/md_img/macos/20200815222225.mp4)  daemon: [戳我](https://t.me/fuckyoucfbot)

目前实现的功能:
1. 输入任意内容可自行去人人影视查询，并返回资源海报
2. 通过点击返回的内容获取资源下载链接
3. 没事干加一个捐赠接口，需要扶贫

使用方法
1. 代码克隆
    ```
    git clone https://github.com/AlphaBrock/YYetsTelegramBot.git
    ```
2. 安装依赖
    ```
    pip install -r requirements.txt
    ```
3. 修改config.py进行配置，TOKEN 为 Bot 的 API
    ```
    TOKEN = 'Your TOKEN'
    ```
4. 启动服务
    ```
   nohup /usr/bin/python3 /root/YYetsTelegramBot/src/main.py &
   ```

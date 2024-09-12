# 配置小红书通知s

## 飞书(免费通知)

1. 下载一个pc端的飞书
   [下载地址](https://www.feishu.cn/download)

2. 创建群聊，因为机器人的消息是发到群里的。
    1. [手机创建教程](https://jingyan.baidu.com/article/19020a0a52e9b7139c28420a.html)
    2. [电脑创建群聊教程](https://jingyan.baidu.com/article/3ea514899f860513e61bbaad.html)


3. 配置群的机器人，然后在群里添加机器人，然后获取机器人的webhook地址就行,下面的步骤不用操作。
   [配置教程](https://open.feishu.cn/document/client-docs/bot-v3/add-custom-bot#399d949c)


4. 获得到webhook的地址,把webhook的地址告诉我。我帮你配置飞书通知。webhook地址格式如下:

    ```angular2html
    https://open.feishu.cn/open-apis/bot/v2/hook/xxxxxxxxxxxxxxxxx
    ```
 ## 企业微信（免费通知）
1. 自己申请一个企业微信,[教程](https://blog.csdn.net/m0_64130892/article/details/128533639),看第一步的注册就行
2. 创建与添加机器人
   1. 创建与添加机器人
      打开企业微信手机客户端  ，进入全员群（只要你加入了企业，就会自动进入这个群），点击右上角进入详情，选择“群机器人”
      ![](http://cdn.weixin1234.top/vitepress/202409121439477.png)
   2. 然后进入，点击右上角“添加”，然后进入后再点右上角“新建”，然后输入机器人名字，即可新建一个机器人。建立成功后，会给你一个Webhook地址，保管好不要泄露 ，然后添加到群
      ![](http://cdn.weixin1234.top/vitepress/202409121440981.png)
   3. 再把这个webhook地址发给我,我帮你配置企业微信通知。
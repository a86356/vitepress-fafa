# 配置通知代码

## 飞书

1. 下载一个pc端的飞书
下载地址
https://www.feishu.cn/download

2. 创建群聊，因为机器人的消息是发到群里的。
   1. 手机创建教程 https://jingyan.baidu.com/article/19020a0a52e9b7139c28420a.html
   2. 电脑创建群聊教程：https://jingyan.baidu.com/article/3ea514899f860513e61bbaad.html


3. 配置群的机器人，，然后在群里添加机器人，然后获取机器人的webhook地址，然后填入到配置文件中。
https://open.feishu.cn/document/client-docs/bot-v3/add-custom-bot#399d949c


4. 看上面的链接,获得到webhook的地址,把webhook的地址告诉我。我帮你配置飞书通知。地址格式如下:
    
    ```angular2html
    https://open.feishu.cn/open-apis/bot/v2/hook/xxxxxxxxxxxxxxxxx
    ```

5. 配置代码
   ```angular2html
   https://open.feishu.cn/open-apis/bot/v2/hook/28f4bd17-a158-4167-8847-c93510faad35
   ```
6. php的调用
   https://open.feishu.cn/document/client-docs/bot-v3/add-custom-bot#4996824a

# 企业微信
1. 自己申请一个企业微信,[教程](https://blog.csdn.net/m0_64130892/article/details/128533639),看第一步的注册就行
2. 调用使用markdown格式调用
3. 
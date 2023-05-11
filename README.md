# GPT-account GPT账号 GPT账号批发


全网最便宜的账号货源 120刀只需8r！

交流群：637658452

成品号：2.5r一个(价格可能变化以网页下单为准)

下单：https://fk.gpt0.icu/ 

另外有注册机项目！

## 目录

- [安装](#安装)
- [使用](#使用)
- [许可证](#许可证)

## 安装

```
pip install -r requirements.txt
```

## 使用

1. > AutoRegOutlook.py

   注册微软账号，注册成功账号将放在outlook.csv中。

   每个IP只能注册3个邮箱，没有实现代理IP池，所以需要手动更换IP。

   验证码需手动进行验证。
2. > HelloChatGPT.py

   新注册的微软账号，登录chatgpt无法正常重定向，需要预处理ChatGPT账号，成功后将账号放在ok.csv中。

   可能产生cf盾验证，需手动点击验证。
3. > ChatGPTSmsVerify.py

   先更改 sa = SMSActivateAPI('') 中的API key，实现自动对ChatGPT账号进行短信验证，将短信验证码放在chatgpt.csv中。

   可能产生cf盾验证，需手动点击验证。
4. > GetApiKey.py

   获取ChatGPT账号的API key，将API key放在api.csv中。

   可能产生cf盾验证，需手动点击验证。

## 许可证

该 Python 脚本小程序的许可证信息。本项目采用 [MIT 许可证](LICENSE)。

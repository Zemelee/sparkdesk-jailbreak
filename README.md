# sparkdesk-jailbreak

## 如何运行?
```
npm install
npm run serve
```

## 简介
一个偶然发现的 sparkdesk-jailbreak bug

## 原理
大模型返回消息后不会主动保留消息记录，消息历史又开发者主动调用
在调用前用于通过界面自定义消息记录，实现篡改消息记录
一定程度上可以实现诱导大模型回答敏感问题，但不建议

## 使用
在根目录下的.env文件中填写应用id、应用密钥等，应用可在 [讯飞开放平台](https://console.xfyun.cn/app/myapp) 申请


```env
VUE_APP_SPARKAI_APPID=""
VUE_APP_SPARKAI_KEY=""
VUE_APP_SPARKAI_SECRET=""
```

填写完成后即可生效

![界面](./asset/sparkdesk.png "界面")
# Azure-line-bot-exmaple

This is simple echo bot on Line messenger.  

## Before you begin
- Line developer account
- [A channel for Line Messaging API](https://developers.line.me/en/docs/messaging-api/getting-started/)

## Get started

### install dependencies

```
$ npm install 
```

### insert your Line bot Access Token & Secret 
```
const config = {
  channelAccessToken: "CHANNEL_ACCESS_TOKEN",
  channelSecret: "CHANNEL_SECRET",
};

```

### deploy
```
serverless deploy
```

## More details  
- [Building a bot](https://developers.line.me/en/docs/messaging-api/building-bot/)
- [line-bot-sdk-nodejs](https://github.com/line/line-bot-sdk-nodejs)
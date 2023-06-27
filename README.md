


#### 🌈 介绍

基于websocket中保持连接状态，实现的一个简单的聊天室，支持多人在线聊天，支持发送图片，支持发送表情，支持发送文件，支持发送语音，支持发送视频，支持发送链接，支持发送代码，支持发送位置，支持发送名片，支持发送红包，支持发送小程序，支持发送音乐，支持发送视频，支持发送商品，

#### 🚧 使用
  
  ```javascript
  import WebsocketHB from './index.js';

  const opts = {
    url: 'ws://ws.100.64.0.2.nip.io',
    pingTimeout: 15000, // 发送心跳包间隔，默认 8000 毫秒
    reconnectLimit: 10, // 最大重连次数
    pingMsg: 'ping' // 心跳包的消息内容
  };

  ws.current = new WebsocketHB(opts);
  
  ws.current.onopen = function () {
    console.log('连接成功');
  };
  ```



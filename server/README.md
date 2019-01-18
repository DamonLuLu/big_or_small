# Big or Small

> 猜大小（服务）
> 版本：v0.1.0

<p align="left">
  <a href="https://github.com/spring-projects/spring-framework">
    <img src="https://img.shields.io/badge/springMvc-4.3.4.RELEASE-brightgreen.svg" alt="springMvc">
  </a>
  <a href="http://rocksdb.org/">
    <img src="https://img.shields.io/badge/rocksdb-5.17.2-green.svg" alt="rocksdb">
  </a>
 
</p>

## 开发及构建

- 主要引用包
  - 机器人SDK，用于IMCHAT发红包和发消息
       <dependency>
            <groupId>bot_sdk</groupId>
            <artifactId>bot_sdk</artifactId>
            <version>1.0-SNAPSHOT</version>
        </dependency>
  - 支付SDK, 用于IMCHAT支付功能
        <dependency>
            <groupId>pay_sdk</groupId>
            <artifactId>pay_sdk</artifactId>
            <version>1.0-SNAPSHOT</version>
        </dependency>

- tomcat7.0以上 运行环境


## 配置文件
appId=imcd18e42dbc747453eac4db9abcca7e485      //AppID  
appSecret=e31ba945f9d641249a6939d011007352     //App密钥
mchId=d3b4f433cda84d9faf93b928108f3abd         //商户appID
mchSecret=022c4bfc8d034dfbb248f223b08aad07     //商户密钥
siteUrl=http://open.dev.iweipeng.com/ChatGuess //站点域名,用于授权
imchatUrl=http://open.dev.iweipeng.com         //imchat开放平台域名
botId=bf474caffdde4f688acc1095fb927fc4         //机器人appID
botSecret=imcf1a06be1238a48018f9aa0c66b8e7be2  //机器人密钥
groupId=56bb921b1f584bf88ecd5ccd581cae0f       //群ID
gameIntervalTime=5                             //游戏投注时长
gameBlockSize=3                                //游戏结束后的第一个块到中奖块的间隔块数
roundIntervalTime=1                            //游戏中奖结果公布后到下一轮游戏间隔时间
domain=https://f.dev.iweipeng.com              //猜一猜前端域名，用于跨域


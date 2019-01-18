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
<table>
<tr>
<td>名称</td><td>值</td><td>说明</td>
</tr>
<tr>
<td>appId</td><td>imcd18e42dbc747453eac4db9abcca7e485</td><td>AppID</td>
</tr>
<tr>
<td>appSecret</td><td>e31ba945f9d641249a6939d011007352</td><td>App密钥</td>
</tr>
<tr>
<td>mchId</td><td>d3b4f433cda84d9faf93b928108f3abd</td><td>商户appID</td>
</tr>
<tr>
<td>mchSecret</td><td>022c4bfc8d034dfbb248f223b08aad07</td><td>商户密钥</td>
</tr>
<tr>
<td>siteUrl</td><td>http://open.dev.iweipeng.com/ChatGuess</td><td>站点域名,用于授权</td>
</tr>
<tr>
<td>imchatUrl</td><td>http://open.dev.iweipeng.com</td><td>imchat开放平台域名</td>
</tr>
<tr>
<td>botId</td><td>bf474caffdde4f688acc1095fb927fc4</td><td>机器人botID</td>
</tr>
<tr>
<td>botSecret</td><td>imcf1a06be1238a48018f9aa0c66b8e7be2</td><td>机器人密钥</td>
</tr>
<tr>
<td>gameIntervalTime</td><td>5</td><td>游戏投注时长</td>
<td>gameBlockSize</td><td>3</td><td>游戏结束后的第一个块到中奖块的间隔块数 </td>
<td>roundIntervalTime</td><td>1</td><td>游戏中奖结果公布后到下一轮游戏间隔时间</td>
<td>domain</td><td>https://f.dev.iweipeng.com</td><td>猜一猜前端域名，用于跨域</td>
</tr>

</table>

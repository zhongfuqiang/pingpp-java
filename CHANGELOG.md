## 2.1.9
* 修改：  
添加 RateLimitException  
兼容 http 地址，仅为方便测试

## 2.1.8
* 新增：  
Identification 身份证银行卡接口

## 2.1.7
* 修正：  
RedEnvelope、Transfer 添加字段

## 2.1.6
* 修正：  
签名内容编码问题

## 2.1.5
* 修改：  
补充 RedEnvelope、Transfer 缺少字段

## 2.1.4
* 修改：  
更改 content-type 为 application/json

## 2.1.3
* 兼容两种微信公众号接入方式

## 2.1.2
* 补全确实字段  
* 修正 Event 解析  
* 修正部分字符 JSON 序列化问题  
* 添加请求签名

## 2.1.1
* 修正 extra 类型  
* 兼容 jdk 1.6

## 2.1.0
* 添加应用内快捷支付对应接口

## 2.0.10
* 增加 Refund 对象 status 字段

## 2.0.8
* 增加 ChannelException

## 2.0.6
* 增加企业转账、修改红包接口

## 2.0.5
* 增加 event sdk

## 2.0.4
* 更改 sdk 目录格式，修复wx_pub渠道timeStamp 类型问题。

## 2.0.3
* 增加 apple pay ，重写 getcredential 方法。

## 2.0.2
* 增加微信红包

## 2.0.1
* 更改：  
修改 wx credential 里的 timeStamp 类型为字符串，防止变成科学计数法

## 2.0.0
* 更改：  
添加新渠道支持：百付宝、百付宝WAP、微信公众平台

## 1.0.4
* 更改：  
添加 `Expanding` 机制

# 本地获取token需要的步骤2_ClientAuth

- 接口描述：`本地获取token需要的步骤2_ClientAuth`
- 接口名称：`lazy.opweb.pjx.client_auth`
- 报文版本：1.0
- 接口说明：本地获取token需要的步骤2_ClientAuth

##### 请求报文：

```json
{
	"nsrsbh": "纳税人识别号",
	"clientauthcode": "",
    "serverRandom": "",
    "publickey": "",
	"ts": ""
}
```

#####  请求参数说明：

| 索引 |       ID       |                      名称                       | 长度 | 必须 | 说明     |
| :--: | :------------: | :---------------------------------------------: | :--: | :--: | :------- |
|  1   |     nsrsbh     |                  纳税人识别号                   |  20  |  是  | 企业税号 |
|  2   | clientauthcode |         本地ClientAuth返回值 strresult          | 100  |  是  |          |
|  3   |  serverRandom  | lazy.opwen.pjx.client_hello返回值：serverRandom |      |      |          |
|  4   |   publickey    |  lazy.opwen.pjx.client_hello返回值：publickey   |      |      |          |
|  5   |       ts       |      lazy.opwen.pjx.client_hello返回值：ts      |      |      |          |


##### 返回报文：

```json
暂无
```

#####  返回参数说明：
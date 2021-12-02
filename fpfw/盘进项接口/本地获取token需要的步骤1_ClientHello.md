# 本地获取token需要的步骤1_ClientHello

- 接口描述：`本地获取token需要的步骤1_ClientHello`
- 接口名称：`lazy.opweb.pjx.client_hello`
- 报文版本：1.0
- 接口说明：本地获取token需要的步骤1_ClientHello

##### 请求报文：
```json
{
	"nsrsbh": "纳税人识别号",
	"strresult": ""

}
```
#####  请求参数说明：

| 索引 |    ID    |     名称     | 长度 | 必须 | 说明                                    |
| :--: | :------: | :----------: | :--: | :--: | :-------------------------------------- |
|  1   |  nsrsbh   |  纳税人识别号  | 20  |  是  | 企业税号                                |
|  2   |  strresult  | 本地ClientHello返回值 strresult |  100  |  是  |                 |


##### 返回报文：

```json
暂无
```

#####  返回参数说明：


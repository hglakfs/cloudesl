# ActivateApService {#doc_api_cloudesl_ActivateApService .reference}

调用ActivateApService接口激活AP。

## 调试 {#apiExplorer .section}

前往【[API Explorer](https://api.aliyun.com/#product=cloudesl&api=ActivateApService)】在线调试，API Explorer 提供在线调用 API、动态生成 SDK Example 代码和快速检索接口等能力，能显著降低使用云 API 的难度，强烈推荐使用。

## 请求参数 {#parameters .section}

|名称|类型|是否必选|示例值|描述|
|--|--|----|---|--|
|Action|String|是|ActivateApService|系统规定参数。取值：**ActivateApService**。

 |
|ApMac|String|是|23sdsf343\*\*\*\*|AP的mac地址。

 |
|StoreId|String|是|s-sds1233\*\*\*\*|门店ID。

 |

## 返回数据 {#resultMapping .section}

|名称|类型|示例值|描述|
|--|--|---|--|
|ErrorCode|String|ERROR|错误码。

 |
|Message|String|success|消息。

 |
|RequestId|String|123-1212-sdfsf2|请求ID。

 |
|Success|Boolean|true|请求状态标识。

 |

## 示例 {#demo .section}

请求示例

``` {#request_demo}

http(s)://cloudesl.cn-hangzhou.aliyuncs.com/?Action=ActivateApService
&ApMac=23sdsf343****
&StoreId=s-sds1233****
&<公共请求参数>

```

正常返回示例

`XML` 格式

``` {#xml_return_success_demo}
<ActivateApServiceResponse>
  <Message>success</Message>
  <RequestId>A7E52C64-959B-4452-8479-DEE18346A9B8</RequestId>
  <Success>true</Success>
  <ErrorCode/>
</ActivateApServiceResponse>

```

`JSON` 格式

``` {#json_return_success_demo}
{
	"Message":"success",
	"RequestId":"A7E52C64-959B-4452-8479-DEE18346A9B8",
	"ErrorCode":"",
	"Success":true
}
```

## 错误码 { .section}

访问[错误中心](https://error-center.aliyun.com/status/product/cloudesl)查看更多错误码。


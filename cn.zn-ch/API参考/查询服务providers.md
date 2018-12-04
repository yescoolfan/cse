# 查询服务providers<a name="ZH-CN_TOPIC_0115698131"></a>

## 功能介绍<a name="zh-cn_topic_0060210594_section4304192761912"></a>

根据consumerId获取该服务的所有providers。

## URI<a name="zh-cn_topic_0060210594_section134557291090"></a>

GET /v4/\{project\_id\}/registry/microservices/\{serviceId\}/providers

参数说明请参见[表1](#zh-cn_topic_0060210594_table51620847114953)。

**表 1**  参数说明

<a name="zh-cn_topic_0060210594_table51620847114953"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060210594_row43559169114953"><th class="cellrowborder" valign="top" width="15.841584158415841%" id="mcps1.2.6.1.1"><p id="zh-cn_topic_0060210594_p3155843511508"><a name="zh-cn_topic_0060210594_p3155843511508"></a><a name="zh-cn_topic_0060210594_p3155843511508"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="10.891089108910892%" id="mcps1.2.6.1.2"><p id="zh-cn_topic_0060210594_p441319561091"><a name="zh-cn_topic_0060210594_p441319561091"></a><a name="zh-cn_topic_0060210594_p441319561091"></a>位于</p>
</th>
<th class="cellrowborder" valign="top" width="11.881188118811881%" id="mcps1.2.6.1.3"><p id="zh-cn_topic_0060210594_p609644911508"><a name="zh-cn_topic_0060210594_p609644911508"></a><a name="zh-cn_topic_0060210594_p609644911508"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="8.91089108910891%" id="mcps1.2.6.1.4"><p id="zh-cn_topic_0060210594_p2405040011508"><a name="zh-cn_topic_0060210594_p2405040011508"></a><a name="zh-cn_topic_0060210594_p2405040011508"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="52.475247524752476%" id="mcps1.2.6.1.5"><p id="zh-cn_topic_0060210594_p192541611508"><a name="zh-cn_topic_0060210594_p192541611508"></a><a name="zh-cn_topic_0060210594_p192541611508"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060210594_row1499024717274"><td class="cellrowborder" valign="top" width="15.841584158415841%" headers="mcps1.2.6.1.1 "><p id="zh-cn_topic_0060210594_p895821704912"><a name="zh-cn_topic_0060210594_p895821704912"></a><a name="zh-cn_topic_0060210594_p895821704912"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="10.891089108910892%" headers="mcps1.2.6.1.2 "><p id="zh-cn_topic_0060210594_p395813172491"><a name="zh-cn_topic_0060210594_p395813172491"></a><a name="zh-cn_topic_0060210594_p395813172491"></a>path</p>
</td>
<td class="cellrowborder" valign="top" width="11.881188118811881%" headers="mcps1.2.6.1.3 "><p id="zh-cn_topic_0060210594_p550511331492"><a name="zh-cn_topic_0060210594_p550511331492"></a><a name="zh-cn_topic_0060210594_p550511331492"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="8.91089108910891%" headers="mcps1.2.6.1.4 "><p id="zh-cn_topic_0060210594_p4521173314920"><a name="zh-cn_topic_0060210594_p4521173314920"></a><a name="zh-cn_topic_0060210594_p4521173314920"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="52.475247524752476%" headers="mcps1.2.6.1.5 "><p id="zh-cn_topic_0060210594_p13958181774915"><a name="zh-cn_topic_0060210594_p13958181774915"></a><a name="zh-cn_topic_0060210594_p13958181774915"></a>租户子项目的唯一标识。字符长度为1~64。</p>
</td>
</tr>
<tr id="zh-cn_topic_0060210594_row35538952114953"><td class="cellrowborder" valign="top" width="15.841584158415841%" headers="mcps1.2.6.1.1 "><p id="zh-cn_topic_0060210594_p60082860114953"><a name="zh-cn_topic_0060210594_p60082860114953"></a><a name="zh-cn_topic_0060210594_p60082860114953"></a>serviceId</p>
</td>
<td class="cellrowborder" valign="top" width="10.891089108910892%" headers="mcps1.2.6.1.2 "><p id="zh-cn_topic_0060210594_p2414356891"><a name="zh-cn_topic_0060210594_p2414356891"></a><a name="zh-cn_topic_0060210594_p2414356891"></a>path</p>
</td>
<td class="cellrowborder" valign="top" width="11.881188118811881%" headers="mcps1.2.6.1.3 "><p id="zh-cn_topic_0060210594_p34873521114953"><a name="zh-cn_topic_0060210594_p34873521114953"></a><a name="zh-cn_topic_0060210594_p34873521114953"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="8.91089108910891%" headers="mcps1.2.6.1.4 "><p id="zh-cn_topic_0060210594_p6182975114953"><a name="zh-cn_topic_0060210594_p6182975114953"></a><a name="zh-cn_topic_0060210594_p6182975114953"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="52.475247524752476%" headers="mcps1.2.6.1.5 "><p id="zh-cn_topic_0060210594_p31058941114953"><a name="zh-cn_topic_0060210594_p31058941114953"></a><a name="zh-cn_topic_0060210594_p31058941114953"></a>消费者服务id。</p>
</td>
</tr>
</tbody>
</table>

## 请求消息<a name="zh-cn_topic_0060210594_section6638077392226"></a>

**表 2**  参数说明

<a name="zh-cn_topic_0060210594_table1679716288401"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060210594_row67977289401"><th class="cellrowborder" valign="top" width="19.191919191919194%" id="mcps1.2.6.1.1"><p id="zh-cn_topic_0060210594_p113502429403"><a name="zh-cn_topic_0060210594_p113502429403"></a><a name="zh-cn_topic_0060210594_p113502429403"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="11.111111111111112%" id="mcps1.2.6.1.2"><p id="zh-cn_topic_0060210594_p19357742184016"><a name="zh-cn_topic_0060210594_p19357742184016"></a><a name="zh-cn_topic_0060210594_p19357742184016"></a>位于</p>
</th>
<th class="cellrowborder" valign="top" width="9.090909090909092%" id="mcps1.2.6.1.3"><p id="zh-cn_topic_0060210594_p1335734264019"><a name="zh-cn_topic_0060210594_p1335734264019"></a><a name="zh-cn_topic_0060210594_p1335734264019"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="9.090909090909092%" id="mcps1.2.6.1.4"><p id="zh-cn_topic_0060210594_p133571142184010"><a name="zh-cn_topic_0060210594_p133571142184010"></a><a name="zh-cn_topic_0060210594_p133571142184010"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="51.515151515151516%" id="mcps1.2.6.1.5"><p id="zh-cn_topic_0060210594_p16357342124011"><a name="zh-cn_topic_0060210594_p16357342124011"></a><a name="zh-cn_topic_0060210594_p16357342124011"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060210594_row19368112035210"><td class="cellrowborder" valign="top" width="19.191919191919194%" headers="mcps1.2.6.1.1 "><p id="zh-cn_topic_0060210594_p126698307474"><a name="zh-cn_topic_0060210594_p126698307474"></a><a name="zh-cn_topic_0060210594_p126698307474"></a>x-domain-name</p>
</td>
<td class="cellrowborder" valign="top" width="11.111111111111112%" headers="mcps1.2.6.1.2 "><p id="zh-cn_topic_0060210594_p1767743014711"><a name="zh-cn_topic_0060210594_p1767743014711"></a><a name="zh-cn_topic_0060210594_p1767743014711"></a>header</p>
</td>
<td class="cellrowborder" valign="top" width="9.090909090909092%" headers="mcps1.2.6.1.3 "><p id="zh-cn_topic_0060210594_p1667763015471"><a name="zh-cn_topic_0060210594_p1667763015471"></a><a name="zh-cn_topic_0060210594_p1667763015471"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="9.090909090909092%" headers="mcps1.2.6.1.4 "><p id="zh-cn_topic_0060210594_p1767733010474"><a name="zh-cn_topic_0060210594_p1767733010474"></a><a name="zh-cn_topic_0060210594_p1767733010474"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.515151515151516%" headers="mcps1.2.6.1.5 "><p id="zh-cn_topic_0060210594_p7684430114719"><a name="zh-cn_topic_0060210594_p7684430114719"></a><a name="zh-cn_topic_0060210594_p7684430114719"></a>租户账号名称。</p>
</td>
</tr>
</tbody>
</table>

**请求示例**

```
GET /v4/d9f4da085f2c11e8959a00ff2d7c69b7/registry/microservices/com.huawei.test.TestService/providers
```

## 响应消息<a name="zh-cn_topic_0060210594_section5419268816116"></a>

**响应参数**

参数说明请参见[表3](#zh-cn_topic_0060210594_table8618102815341)。

**表 3**  参数说明

<a name="zh-cn_topic_0060210594_table8618102815341"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060210594_row136181128113410"><th class="cellrowborder" valign="top" width="16%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0060210594_p0618182883412"><a name="zh-cn_topic_0060210594_p0618182883412"></a><a name="zh-cn_topic_0060210594_p0618182883412"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="33%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0060210594_p2618132819347"><a name="zh-cn_topic_0060210594_p2618132819347"></a><a name="zh-cn_topic_0060210594_p2618132819347"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="51%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0060210594_p6618152818345"><a name="zh-cn_topic_0060210594_p6618152818345"></a><a name="zh-cn_topic_0060210594_p6618152818345"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060210594_row0618128193419"><td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0060210594_p1961812819342"><a name="zh-cn_topic_0060210594_p1961812819342"></a><a name="zh-cn_topic_0060210594_p1961812819342"></a>dependency</p>
</td>
<td class="cellrowborder" valign="top" width="33%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0060210594_p66614789103624"><a name="zh-cn_topic_0060210594_p66614789103624"></a><a name="zh-cn_topic_0060210594_p66614789103624"></a>GetConDependenciesResponse</p>
</td>
<td class="cellrowborder" valign="top" width="51%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0060210594_p261817280342"><a name="zh-cn_topic_0060210594_p261817280342"></a><a name="zh-cn_topic_0060210594_p261817280342"></a>成功获取消费者微服务内容的响应结构体。</p>
</td>
</tr>
</tbody>
</table>

**表 4**  GetConDependenciesResponse参数说明

<a name="zh-cn_topic_0060210594_table2814715310134"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060210594_row6055643110134"><th class="cellrowborder" valign="top" width="17%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0060210594_p612388210134"><a name="zh-cn_topic_0060210594_p612388210134"></a><a name="zh-cn_topic_0060210594_p612388210134"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="33%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0060210594_p2627240910134"><a name="zh-cn_topic_0060210594_p2627240910134"></a><a name="zh-cn_topic_0060210594_p2627240910134"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="10%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0060210594_p4769037310134"><a name="zh-cn_topic_0060210594_p4769037310134"></a><a name="zh-cn_topic_0060210594_p4769037310134"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="40%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0060210594_p3771496510134"><a name="zh-cn_topic_0060210594_p3771496510134"></a><a name="zh-cn_topic_0060210594_p3771496510134"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060210594_row3501329710134"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060210594_p1750483410134"><a name="zh-cn_topic_0060210594_p1750483410134"></a><a name="zh-cn_topic_0060210594_p1750483410134"></a>dependency</p>
</td>
<td class="cellrowborder" valign="top" width="33%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060210594_p860548810134"><a name="zh-cn_topic_0060210594_p860548810134"></a><a name="zh-cn_topic_0060210594_p860548810134"></a>array</p>
<p id="zh-cn_topic_0060210594_p1034053310134"><a name="zh-cn_topic_0060210594_p1034053310134"></a><a name="zh-cn_topic_0060210594_p1034053310134"></a>每一项为ConDependency。</p>
</td>
<td class="cellrowborder" valign="top" width="10%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060210594_p2205625710134"><a name="zh-cn_topic_0060210594_p2205625710134"></a><a name="zh-cn_topic_0060210594_p2205625710134"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060210594_p4172638810134"><a name="zh-cn_topic_0060210594_p4172638810134"></a><a name="zh-cn_topic_0060210594_p4172638810134"></a>消费者微服务的集合。</p>
</td>
</tr>
</tbody>
</table>

**表 5**  ConDependency参数说明

<a name="zh-cn_topic_0060210594_table1451808210210"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060210594_row6134872010210"><th class="cellrowborder" valign="top" width="17%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0060210594_p319040610210"><a name="zh-cn_topic_0060210594_p319040610210"></a><a name="zh-cn_topic_0060210594_p319040610210"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="33%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0060210594_p5709637010210"><a name="zh-cn_topic_0060210594_p5709637010210"></a><a name="zh-cn_topic_0060210594_p5709637010210"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="11%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0060210594_p6140322510210"><a name="zh-cn_topic_0060210594_p6140322510210"></a><a name="zh-cn_topic_0060210594_p6140322510210"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="39%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0060210594_p760534910210"><a name="zh-cn_topic_0060210594_p760534910210"></a><a name="zh-cn_topic_0060210594_p760534910210"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060210594_row1205356610210"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060210594_p3681479510210"><a name="zh-cn_topic_0060210594_p3681479510210"></a><a name="zh-cn_topic_0060210594_p3681479510210"></a>Providers</p>
</td>
<td class="cellrowborder" valign="top" width="33%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060210594_p2920843710210"><a name="zh-cn_topic_0060210594_p2920843710210"></a><a name="zh-cn_topic_0060210594_p2920843710210"></a><a href="MicroService.md">MicroService</a></p>
</td>
<td class="cellrowborder" valign="top" width="11%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060210594_p1944095910210"><a name="zh-cn_topic_0060210594_p1944095910210"></a><a name="zh-cn_topic_0060210594_p1944095910210"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="39%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060210594_p3121387110210"><a name="zh-cn_topic_0060210594_p3121387110210"></a><a name="zh-cn_topic_0060210594_p3121387110210"></a>微服务结构体。</p>
</td>
</tr>
</tbody>
</table>

**响应示例**

```
{
  "dependency": [
    {
      "Providers": {
        "serviceId": "string",
        "environment": "string",
        "appId": "string",
        "serviceName": "string",
        "version": "string",
        "description": "string",
        "level": "string",
        "registerBy": "string",
        "schemas": [
          "string"
        ],
        "status": "UP",
        "timestamp": "string",
        "modTimestamp": "string",
        "framework": {
          "name": "string",
          "version": "string"
        },
        "paths": [
          {
            "Path": "string",
            "Property": {
              "additionalProp1": "string",
              "additionalProp2": "string",
              "additionalProp3": "string"
            }
          }
        ]
      }
    }
  ]
}
```

## 状态码<a name="zh-cn_topic_0060210594_section4458192915911"></a>

-   正常

    状态码如[表6](#zh-cn_topic_0060210594_zh-cn_topic_0079393967_zh-cn_topic_0075248102_table287518019404)所示。


**表 6**  状态码

<a name="zh-cn_topic_0060210594_zh-cn_topic_0079393967_zh-cn_topic_0075248102_table287518019404"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060210594_zh-cn_topic_0079393967_zh-cn_topic_0075248102_row29079739404"><th class="cellrowborder" valign="top" width="16.470000000000002%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0060210594_p668134843614"><a name="zh-cn_topic_0060210594_p668134843614"></a><a name="zh-cn_topic_0060210594_p668134843614"></a>HTTP状态码</p>
</th>
<th class="cellrowborder" valign="top" width="43.53%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0060210594_p1761448123611"><a name="zh-cn_topic_0060210594_p1761448123611"></a><a name="zh-cn_topic_0060210594_p1761448123611"></a>返回消息体</p>
</th>
<th class="cellrowborder" valign="top" width="40%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0060210594_p137604819368"><a name="zh-cn_topic_0060210594_p137604819368"></a><a name="zh-cn_topic_0060210594_p137604819368"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060210594_zh-cn_topic_0079393967_zh-cn_topic_0075248102_row333343189404"><td class="cellrowborder" valign="top" width="16.470000000000002%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0060210594_p37870402151037"><a name="zh-cn_topic_0060210594_p37870402151037"></a><a name="zh-cn_topic_0060210594_p37870402151037"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="43.53%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0060210594_p3600163234710"><a name="zh-cn_topic_0060210594_p3600163234710"></a><a name="zh-cn_topic_0060210594_p3600163234710"></a>{</p>
<p id="zh-cn_topic_0060210594_p7600103214470"><a name="zh-cn_topic_0060210594_p7600103214470"></a><a name="zh-cn_topic_0060210594_p7600103214470"></a>"service": {</p>
<p id="zh-cn_topic_0060210594_p12600143220474"><a name="zh-cn_topic_0060210594_p12600143220474"></a><a name="zh-cn_topic_0060210594_p12600143220474"></a>"appId": "default",</p>
<p id="zh-cn_topic_0060210594_p116007328478"><a name="zh-cn_topic_0060210594_p116007328478"></a><a name="zh-cn_topic_0060210594_p116007328478"></a>"serviceName": "TestMicroService",</p>
<p id="zh-cn_topic_0060210594_p4600153214718"><a name="zh-cn_topic_0060210594_p4600153214718"></a><a name="zh-cn_topic_0060210594_p4600153214718"></a>"version": "v1",</p>
<p id="zh-cn_topic_0060210594_p1160012324479"><a name="zh-cn_topic_0060210594_p1160012324479"></a><a name="zh-cn_topic_0060210594_p1160012324479"></a>"description": "Micros service for test",</p>
<p id="zh-cn_topic_0060210594_p960013274717"><a name="zh-cn_topic_0060210594_p960013274717"></a><a name="zh-cn_topic_0060210594_p960013274717"></a>"level": "FRONT",</p>
<p id="zh-cn_topic_0060210594_p17600932194719"><a name="zh-cn_topic_0060210594_p17600932194719"></a><a name="zh-cn_topic_0060210594_p17600932194719"></a>"schemas": [</p>
<p id="zh-cn_topic_0060210594_p56001132134716"><a name="zh-cn_topic_0060210594_p56001132134716"></a><a name="zh-cn_topic_0060210594_p56001132134716"></a>"com.huawei.bes.om.OrderManagementService",</p>
<p id="zh-cn_topic_0060210594_p8600732194717"><a name="zh-cn_topic_0060210594_p8600732194717"></a><a name="zh-cn_topic_0060210594_p8600732194717"></a>"com.huawei.bes.om.OrderItemService",</p>
<p id="zh-cn_topic_0060210594_p126007327476"><a name="zh-cn_topic_0060210594_p126007327476"></a><a name="zh-cn_topic_0060210594_p126007327476"></a>"com.huawei.bes.om.OrderCheckoutService"</p>
<p id="zh-cn_topic_0060210594_p166001832174720"><a name="zh-cn_topic_0060210594_p166001832174720"></a><a name="zh-cn_topic_0060210594_p166001832174720"></a>],</p>
<p id="zh-cn_topic_0060210594_p4600153234713"><a name="zh-cn_topic_0060210594_p4600153234713"></a><a name="zh-cn_topic_0060210594_p4600153234713"></a>"status": "UP",</p>
<p id="zh-cn_topic_0060210594_p166001932124717"><a name="zh-cn_topic_0060210594_p166001932124717"></a><a name="zh-cn_topic_0060210594_p166001932124717"></a>"properties": {}</p>
<p id="zh-cn_topic_0060210594_p46004325473"><a name="zh-cn_topic_0060210594_p46004325473"></a><a name="zh-cn_topic_0060210594_p46004325473"></a>}</p>
<p id="zh-cn_topic_0060210594_p126006328472"><a name="zh-cn_topic_0060210594_p126006328472"></a><a name="zh-cn_topic_0060210594_p126006328472"></a>}</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0060210594_p19285181416360"><a name="zh-cn_topic_0060210594_p19285181416360"></a><a name="zh-cn_topic_0060210594_p19285181416360"></a>查询成功，如果存在，则返回 ServiceId 或者 SchemaId。 否则返回 400 资源不存在。</p>
</td>
</tr>
</tbody>
</table>

-   异常

    状态码如[表7](#zh-cn_topic_0060210594_zh-cn_topic_0079393967_zh-cn_topic_0075248102_table217266469404)所示。


**表 7**  状态码

<a name="zh-cn_topic_0060210594_zh-cn_topic_0079393967_zh-cn_topic_0075248102_table217266469404"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060210594_zh-cn_topic_0079393967_zh-cn_topic_0075248102_row149156199404"><th class="cellrowborder" valign="top" width="13%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0060210594_p77551172194"><a name="zh-cn_topic_0060210594_p77551172194"></a><a name="zh-cn_topic_0060210594_p77551172194"></a>HTTP状态码</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0060210594_p10143552175014"><a name="zh-cn_topic_0060210594_p10143552175014"></a><a name="zh-cn_topic_0060210594_p10143552175014"></a>业务错误码</p>
</th>
<th class="cellrowborder" valign="top" width="38%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0060210594_p537034565010"><a name="zh-cn_topic_0060210594_p537034565010"></a><a name="zh-cn_topic_0060210594_p537034565010"></a>返回消息体</p>
</th>
<th class="cellrowborder" valign="top" width="33%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0060210594_p1776216718193"><a name="zh-cn_topic_0060210594_p1776216718193"></a><a name="zh-cn_topic_0060210594_p1776216718193"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060210594_zh-cn_topic_0079393967_zh-cn_topic_0075248102_row66966729404"><td class="cellrowborder" valign="top" width="13%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060210594_zh-cn_topic_0079393967_zh-cn_topic_0075248102_p55595609404"><a name="zh-cn_topic_0060210594_zh-cn_topic_0079393967_zh-cn_topic_0075248102_p55595609404"></a><a name="zh-cn_topic_0060210594_zh-cn_topic_0079393967_zh-cn_topic_0075248102_p55595609404"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060210594_p954813200351"><a name="zh-cn_topic_0060210594_p954813200351"></a><a name="zh-cn_topic_0060210594_p954813200351"></a>001</p>
</td>
<td class="cellrowborder" valign="top" width="38%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060210594_p115481620193511"><a name="zh-cn_topic_0060210594_p115481620193511"></a><a name="zh-cn_topic_0060210594_p115481620193511"></a>{errCode:"400001", errMsg:"Invalid parameter(s)", detail:""}</p>
</td>
<td class="cellrowborder" valign="top" width="33%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060210594_p18548152011354"><a name="zh-cn_topic_0060210594_p18548152011354"></a><a name="zh-cn_topic_0060210594_p18548152011354"></a>请求参数错误</p>
</td>
</tr>
</tbody>
</table>

更多状态码请参考[错误码列表](错误码列表.md)。


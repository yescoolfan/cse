# 查询微服务实例（根据service\_id）<a name="ZH-CN_TOPIC_0115698134"></a>

## 功能介绍<a name="zh-cn_topic_0060210606_section199452216265"></a>

实例注册后可以根据service\_id发现该微服务的所有实例。

## URI<a name="zh-cn_topic_0060210606_section134557291090"></a>

GET /v4/\{project\_id\}/registry/microservices/\{serviceId\}/instances

参数说明请参见[表1](#zh-cn_topic_0060210606_table51620847114953)。

**表 1**  参数说明

<a name="zh-cn_topic_0060210606_table51620847114953"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060210606_row43559169114953"><th class="cellrowborder" valign="top" width="16.666666666666668%" id="mcps1.2.6.1.1"><p id="zh-cn_topic_0060210606_p3155843511508"><a name="zh-cn_topic_0060210606_p3155843511508"></a><a name="zh-cn_topic_0060210606_p3155843511508"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="10.784313725490197%" id="mcps1.2.6.1.2"><p id="zh-cn_topic_0060210606_p9735557111318"><a name="zh-cn_topic_0060210606_p9735557111318"></a><a name="zh-cn_topic_0060210606_p9735557111318"></a>位于</p>
</th>
<th class="cellrowborder" valign="top" width="11.76470588235294%" id="mcps1.2.6.1.3"><p id="zh-cn_topic_0060210606_p609644911508"><a name="zh-cn_topic_0060210606_p609644911508"></a><a name="zh-cn_topic_0060210606_p609644911508"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="9.803921568627452%" id="mcps1.2.6.1.4"><p id="zh-cn_topic_0060210606_p2405040011508"><a name="zh-cn_topic_0060210606_p2405040011508"></a><a name="zh-cn_topic_0060210606_p2405040011508"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="50.98039215686274%" id="mcps1.2.6.1.5"><p id="zh-cn_topic_0060210606_p192541611508"><a name="zh-cn_topic_0060210606_p192541611508"></a><a name="zh-cn_topic_0060210606_p192541611508"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060210606_row12196183412308"><td class="cellrowborder" valign="top" width="16.666666666666668%" headers="mcps1.2.6.1.1 "><p id="zh-cn_topic_0060210606_p895821704912"><a name="zh-cn_topic_0060210606_p895821704912"></a><a name="zh-cn_topic_0060210606_p895821704912"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="10.784313725490197%" headers="mcps1.2.6.1.2 "><p id="zh-cn_topic_0060210606_p395813172491"><a name="zh-cn_topic_0060210606_p395813172491"></a><a name="zh-cn_topic_0060210606_p395813172491"></a>path</p>
</td>
<td class="cellrowborder" valign="top" width="11.76470588235294%" headers="mcps1.2.6.1.3 "><p id="zh-cn_topic_0060210606_p550511331492"><a name="zh-cn_topic_0060210606_p550511331492"></a><a name="zh-cn_topic_0060210606_p550511331492"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="9.803921568627452%" headers="mcps1.2.6.1.4 "><p id="zh-cn_topic_0060210606_p4521173314920"><a name="zh-cn_topic_0060210606_p4521173314920"></a><a name="zh-cn_topic_0060210606_p4521173314920"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="50.98039215686274%" headers="mcps1.2.6.1.5 "><p id="zh-cn_topic_0060210621_p13958181774915"><a name="zh-cn_topic_0060210621_p13958181774915"></a><a name="zh-cn_topic_0060210621_p13958181774915"></a>租户子项目的唯一标识。字符长度为1~64。</p>
</td>
</tr>
<tr id="zh-cn_topic_0060210606_row35538952114953"><td class="cellrowborder" valign="top" width="16.666666666666668%" headers="mcps1.2.6.1.1 "><p id="zh-cn_topic_0060210606_p60082860114953"><a name="zh-cn_topic_0060210606_p60082860114953"></a><a name="zh-cn_topic_0060210606_p60082860114953"></a>serviceId</p>
</td>
<td class="cellrowborder" valign="top" width="10.784313725490197%" headers="mcps1.2.6.1.2 "><p id="zh-cn_topic_0060210606_p1736155711313"><a name="zh-cn_topic_0060210606_p1736155711313"></a><a name="zh-cn_topic_0060210606_p1736155711313"></a>path</p>
</td>
<td class="cellrowborder" valign="top" width="11.76470588235294%" headers="mcps1.2.6.1.3 "><p id="zh-cn_topic_0060210606_p34873521114953"><a name="zh-cn_topic_0060210606_p34873521114953"></a><a name="zh-cn_topic_0060210606_p34873521114953"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="9.803921568627452%" headers="mcps1.2.6.1.4 "><p id="zh-cn_topic_0060210606_p6182975114953"><a name="zh-cn_topic_0060210606_p6182975114953"></a><a name="zh-cn_topic_0060210606_p6182975114953"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="50.98039215686274%" headers="mcps1.2.6.1.5 "><p id="zh-cn_topic_0060210606_p31058941114953"><a name="zh-cn_topic_0060210606_p31058941114953"></a><a name="zh-cn_topic_0060210606_p31058941114953"></a>微服务唯一标识。</p>
<p id="zh-cn_topic_0060210606_p621853614160"><a name="zh-cn_topic_0060210606_p621853614160"></a><a name="zh-cn_topic_0060210606_p621853614160"></a>字符长度为1~64。</p>
<p id="zh-cn_topic_0060210606_p119757471167"><a name="zh-cn_topic_0060210606_p119757471167"></a><a name="zh-cn_topic_0060210606_p119757471167"></a>正则表达式为^.*$</p>
</td>
</tr>
</tbody>
</table>

## 请求消息<a name="zh-cn_topic_0060210606_section6638077392226"></a>

**请求参数**

参数说明请参见[表2](#zh-cn_topic_0060210606_table2377430892226)。

**表 2**  参数说明

<a name="zh-cn_topic_0060210606_table2377430892226"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060210606_row1383670292226"><th class="cellrowborder" valign="top" width="17.82178217821782%" id="mcps1.2.6.1.1"><p id="zh-cn_topic_0060210606_p4703105592226"><a name="zh-cn_topic_0060210606_p4703105592226"></a><a name="zh-cn_topic_0060210606_p4703105592226"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="10.891089108910892%" id="mcps1.2.6.1.2"><p id="zh-cn_topic_0060210606_p8622121181120"><a name="zh-cn_topic_0060210606_p8622121181120"></a><a name="zh-cn_topic_0060210606_p8622121181120"></a>位于</p>
</th>
<th class="cellrowborder" valign="top" width="10.891089108910892%" id="mcps1.2.6.1.3"><p id="zh-cn_topic_0060210606_p5141914292226"><a name="zh-cn_topic_0060210606_p5141914292226"></a><a name="zh-cn_topic_0060210606_p5141914292226"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="8.91089108910891%" id="mcps1.2.6.1.4"><p id="zh-cn_topic_0060210606_p420093692226"><a name="zh-cn_topic_0060210606_p420093692226"></a><a name="zh-cn_topic_0060210606_p420093692226"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="51.48514851485149%" id="mcps1.2.6.1.5"><p id="zh-cn_topic_0060210606_p473155192226"><a name="zh-cn_topic_0060210606_p473155192226"></a><a name="zh-cn_topic_0060210606_p473155192226"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060210606_row11913576101538"><td class="cellrowborder" valign="top" width="17.82178217821782%" headers="mcps1.2.6.1.1 "><p id="zh-cn_topic_0060210606_p6839151744312"><a name="zh-cn_topic_0060210606_p6839151744312"></a><a name="zh-cn_topic_0060210606_p6839151744312"></a>X-ConsumerId</p>
</td>
<td class="cellrowborder" valign="top" width="10.891089108910892%" headers="mcps1.2.6.1.2 "><p id="zh-cn_topic_0060210606_p37351557131320"><a name="zh-cn_topic_0060210606_p37351557131320"></a><a name="zh-cn_topic_0060210606_p37351557131320"></a>header</p>
</td>
<td class="cellrowborder" valign="top" width="10.891089108910892%" headers="mcps1.2.6.1.3 "><p id="zh-cn_topic_0060210606_p11839151724311"><a name="zh-cn_topic_0060210606_p11839151724311"></a><a name="zh-cn_topic_0060210606_p11839151724311"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="8.91089108910891%" headers="mcps1.2.6.1.4 "><p id="zh-cn_topic_0060210606_p108391517174315"><a name="zh-cn_topic_0060210606_p108391517174315"></a><a name="zh-cn_topic_0060210606_p108391517174315"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.48514851485149%" headers="mcps1.2.6.1.5 "><p id="zh-cn_topic_0060210606_p15839317154318"><a name="zh-cn_topic_0060210606_p15839317154318"></a><a name="zh-cn_topic_0060210606_p15839317154318"></a>微服务消费者的微服务唯一标识。</p>
</td>
</tr>
<tr id="zh-cn_topic_0060210606_row45133614439"><td class="cellrowborder" valign="top" width="17.82178217821782%" headers="mcps1.2.6.1.1 "><p id="zh-cn_topic_0060210606_p126698307474"><a name="zh-cn_topic_0060210606_p126698307474"></a><a name="zh-cn_topic_0060210606_p126698307474"></a>x-domain-name</p>
</td>
<td class="cellrowborder" valign="top" width="10.891089108910892%" headers="mcps1.2.6.1.2 "><p id="zh-cn_topic_0060210606_p1767743014711"><a name="zh-cn_topic_0060210606_p1767743014711"></a><a name="zh-cn_topic_0060210606_p1767743014711"></a>header</p>
</td>
<td class="cellrowborder" valign="top" width="10.891089108910892%" headers="mcps1.2.6.1.3 "><p id="zh-cn_topic_0060210606_p1667763015471"><a name="zh-cn_topic_0060210606_p1667763015471"></a><a name="zh-cn_topic_0060210606_p1667763015471"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="8.91089108910891%" headers="mcps1.2.6.1.4 "><p id="zh-cn_topic_0060210606_p1767733010474"><a name="zh-cn_topic_0060210606_p1767733010474"></a><a name="zh-cn_topic_0060210606_p1767733010474"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.48514851485149%" headers="mcps1.2.6.1.5 "><p id="zh-cn_topic_0060210606_p7684430114719"><a name="zh-cn_topic_0060210606_p7684430114719"></a><a name="zh-cn_topic_0060210606_p7684430114719"></a>租户账号名称。</p>
</td>
</tr>
<tr id="zh-cn_topic_0060210606_row6472989143041"><td class="cellrowborder" valign="top" width="17.82178217821782%" headers="mcps1.2.6.1.1 "><p id="zh-cn_topic_0060210606_p18612152334314"><a name="zh-cn_topic_0060210606_p18612152334314"></a><a name="zh-cn_topic_0060210606_p18612152334314"></a>tags</p>
</td>
<td class="cellrowborder" valign="top" width="10.891089108910892%" headers="mcps1.2.6.1.2 "><p id="zh-cn_topic_0060210606_p11736155716134"><a name="zh-cn_topic_0060210606_p11736155716134"></a><a name="zh-cn_topic_0060210606_p11736155716134"></a>query</p>
</td>
<td class="cellrowborder" valign="top" width="10.891089108910892%" headers="mcps1.2.6.1.3 "><p id="zh-cn_topic_0060210606_p361252317437"><a name="zh-cn_topic_0060210606_p361252317437"></a><a name="zh-cn_topic_0060210606_p361252317437"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="8.91089108910891%" headers="mcps1.2.6.1.4 "><p id="zh-cn_topic_0060210606_p8612172320437"><a name="zh-cn_topic_0060210606_p8612172320437"></a><a name="zh-cn_topic_0060210606_p8612172320437"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="51.48514851485149%" headers="mcps1.2.6.1.5 "><p id="zh-cn_topic_0060210606_p156126231437"><a name="zh-cn_topic_0060210606_p156126231437"></a><a name="zh-cn_topic_0060210606_p156126231437"></a>Tag标签过滤，多个时逗号分隔。</p>
<p id="zh-cn_topic_0060210606_p8101487175"><a name="zh-cn_topic_0060210606_p8101487175"></a><a name="zh-cn_topic_0060210606_p8101487175"></a>正则表达式为^[a-zA-Z][a-zA-Z0-9_\-\.]{0,63}$</p>
</td>
</tr>
</tbody>
</table>

**请求示例**

```
GET /v4/d9f4da085f2c11e8959a00ff2d7c69b7/registry/microservices/e0f0da073f2c91e8979a89ff2d7c69t6/instances
```

## 响应消息<a name="zh-cn_topic_0060210606_section1006390163649"></a>

**响应参数**

参数说明请参见[表3](#zh-cn_topic_0060210606_table8618102815341)。

**表 3**  参数说明

<a name="zh-cn_topic_0060210606_table8618102815341"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060210606_row136181128113410"><th class="cellrowborder" valign="top" width="14.85148514851485%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0060210606_p0618182883412"><a name="zh-cn_topic_0060210606_p0618182883412"></a><a name="zh-cn_topic_0060210606_p0618182883412"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="33.663366336633665%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0060210606_p2618132819347"><a name="zh-cn_topic_0060210606_p2618132819347"></a><a name="zh-cn_topic_0060210606_p2618132819347"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="51.48514851485149%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0060210606_p6618152818345"><a name="zh-cn_topic_0060210606_p6618152818345"></a><a name="zh-cn_topic_0060210606_p6618152818345"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060210606_row0618128193419"><td class="cellrowborder" valign="top" width="14.85148514851485%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0060210606_p1961812819342"><a name="zh-cn_topic_0060210606_p1961812819342"></a><a name="zh-cn_topic_0060210606_p1961812819342"></a>instances</p>
</td>
<td class="cellrowborder" valign="top" width="33.663366336633665%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0060210606_p1219686215649"><a name="zh-cn_topic_0060210606_p1219686215649"></a><a name="zh-cn_topic_0060210606_p1219686215649"></a>GetInstancesResponse</p>
</td>
<td class="cellrowborder" valign="top" width="51.48514851485149%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0060210606_p261817280342"><a name="zh-cn_topic_0060210606_p261817280342"></a><a name="zh-cn_topic_0060210606_p261817280342"></a>成功获取微服务实例的响应结构体。</p>
</td>
</tr>
</tbody>
</table>

**表 4**  GetInstancesResponse参数说明

<a name="zh-cn_topic_0060210606_table4743276101211"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060210606_row5901317101211"><th class="cellrowborder" valign="top" width="13.861386138613863%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0060210606_p8244687101211"><a name="zh-cn_topic_0060210606_p8244687101211"></a><a name="zh-cn_topic_0060210606_p8244687101211"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="35.64356435643564%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0060210606_p63839901101211"><a name="zh-cn_topic_0060210606_p63839901101211"></a><a name="zh-cn_topic_0060210606_p63839901101211"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="9.900990099009901%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0060210606_p3649496101211"><a name="zh-cn_topic_0060210606_p3649496101211"></a><a name="zh-cn_topic_0060210606_p3649496101211"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="40.59405940594059%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0060210606_p27173735101211"><a name="zh-cn_topic_0060210606_p27173735101211"></a><a name="zh-cn_topic_0060210606_p27173735101211"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060210606_row53588915101211"><td class="cellrowborder" valign="top" width="13.861386138613863%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060210606_p45734819101211"><a name="zh-cn_topic_0060210606_p45734819101211"></a><a name="zh-cn_topic_0060210606_p45734819101211"></a>instances</p>
</td>
<td class="cellrowborder" valign="top" width="35.64356435643564%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060210606_p13532831101211"><a name="zh-cn_topic_0060210606_p13532831101211"></a><a name="zh-cn_topic_0060210606_p13532831101211"></a>array</p>
<p id="zh-cn_topic_0060210606_p54686622101211"><a name="zh-cn_topic_0060210606_p54686622101211"></a><a name="zh-cn_topic_0060210606_p54686622101211"></a>每一项为<a href="MicroServiceInstance.md">MicroServiceInstance</a>。</p>
</td>
<td class="cellrowborder" valign="top" width="9.900990099009901%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060210606_p3882462101211"><a name="zh-cn_topic_0060210606_p3882462101211"></a><a name="zh-cn_topic_0060210606_p3882462101211"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.59405940594059%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060210606_p46044016101211"><a name="zh-cn_topic_0060210606_p46044016101211"></a><a name="zh-cn_topic_0060210606_p46044016101211"></a>微服务实例的集合。</p>
</td>
</tr>
</tbody>
</table>

**响应示例**

```
{
  "instances": [
    {
      "instanceId": "string",
      "serviceId": "string",
      "version": "string",
      "hostName": "string",
      "endpoints": [
        "string"
      ],
      "status": "string",
      "healthCheck": {
        "mode": "string",
        "port": 0,
        "interval": 0,
        "times": 0
      },
      "dataCenterInfo": {
        "name": "string",
        "region": "string",
        "availableZone": "string"
      },
      "timestamp": "string",
      "modTimestamp": "string"
    }
  ]
}
```

## 状态码<a name="zh-cn_topic_0060210606_section4458192915911"></a>

-   正常

    状态码如[表5](#zh-cn_topic_0060210606_zh-cn_topic_0079393967_zh-cn_topic_0075248102_table287518019404)所示。


**表 5**  状态码

<a name="zh-cn_topic_0060210606_zh-cn_topic_0079393967_zh-cn_topic_0075248102_table287518019404"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060210606_zh-cn_topic_0079393967_zh-cn_topic_0075248102_row29079739404"><th class="cellrowborder" valign="top" width="11.110000000000001%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0060210606_p15140191517311"><a name="zh-cn_topic_0060210606_p15140191517311"></a><a name="zh-cn_topic_0060210606_p15140191517311"></a>HTTP状态码</p>
</th>
<th class="cellrowborder" valign="top" width="40.739999999999995%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0060210606_p537034565010"><a name="zh-cn_topic_0060210606_p537034565010"></a><a name="zh-cn_topic_0060210606_p537034565010"></a>返回消息体</p>
</th>
<th class="cellrowborder" valign="top" width="48.15%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0060210606_p71561815534"><a name="zh-cn_topic_0060210606_p71561815534"></a><a name="zh-cn_topic_0060210606_p71561815534"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060210606_zh-cn_topic_0079393967_zh-cn_topic_0075248102_row333343189404"><td class="cellrowborder" valign="top" width="11.110000000000001%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0060210606_p37870402151037"><a name="zh-cn_topic_0060210606_p37870402151037"></a><a name="zh-cn_topic_0060210606_p37870402151037"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="40.739999999999995%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0060210606_p568815266717"><a name="zh-cn_topic_0060210606_p568815266717"></a><a name="zh-cn_topic_0060210606_p568815266717"></a>{</p>
<p id="zh-cn_topic_0060210606_p2689142613716"><a name="zh-cn_topic_0060210606_p2689142613716"></a><a name="zh-cn_topic_0060210606_p2689142613716"></a>"instances": [</p>
<p id="zh-cn_topic_0060210606_p1068914263720"><a name="zh-cn_topic_0060210606_p1068914263720"></a><a name="zh-cn_topic_0060210606_p1068914263720"></a>{</p>
<p id="zh-cn_topic_0060210606_p868911266719"><a name="zh-cn_topic_0060210606_p868911266719"></a><a name="zh-cn_topic_0060210606_p868911266719"></a>"instanceId": "18",</p>
<p id="zh-cn_topic_0060210606_p16689172613719"><a name="zh-cn_topic_0060210606_p16689172613719"></a><a name="zh-cn_topic_0060210606_p16689172613719"></a>"serviceId": "3",</p>
<p id="zh-cn_topic_0060210606_p76891026875"><a name="zh-cn_topic_0060210606_p76891026875"></a><a name="zh-cn_topic_0060210606_p76891026875"></a>"endpoints": [</p>
<p id="zh-cn_topic_0060210606_p1068982611711"><a name="zh-cn_topic_0060210606_p1068982611711"></a><a name="zh-cn_topic_0060210606_p1068982611711"></a>"grpc:10.74.190.78:8080"</p>
<p id="zh-cn_topic_0060210606_p1568922617719"><a name="zh-cn_topic_0060210606_p1568922617719"></a><a name="zh-cn_topic_0060210606_p1568922617719"></a>],</p>
<p id="zh-cn_topic_0060210606_p176890265712"><a name="zh-cn_topic_0060210606_p176890265712"></a><a name="zh-cn_topic_0060210606_p176890265712"></a>"hostName": "szxy8c003701231",</p>
<p id="zh-cn_topic_0060210606_p1968915261778"><a name="zh-cn_topic_0060210606_p1968915261778"></a><a name="zh-cn_topic_0060210606_p1968915261778"></a>"status": "UP"</p>
<p id="zh-cn_topic_0060210606_p36891926773"><a name="zh-cn_topic_0060210606_p36891926773"></a><a name="zh-cn_topic_0060210606_p36891926773"></a>}</p>
<p id="zh-cn_topic_0060210606_p56896261675"><a name="zh-cn_topic_0060210606_p56896261675"></a><a name="zh-cn_topic_0060210606_p56896261675"></a>]</p>
<p id="zh-cn_topic_0060210606_p868914265715"><a name="zh-cn_topic_0060210606_p868914265715"></a><a name="zh-cn_topic_0060210606_p868914265715"></a>}</p>
<p id="zh-cn_topic_0060210606_p168952616719"><a name="zh-cn_topic_0060210606_p168952616719"></a><a name="zh-cn_topic_0060210606_p168952616719"></a></p>
</td>
<td class="cellrowborder" valign="top" width="48.15%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0060210606_p47603723151037"><a name="zh-cn_topic_0060210606_p47603723151037"></a><a name="zh-cn_topic_0060210606_p47603723151037"></a>查询成功</p>
</td>
</tr>
</tbody>
</table>

-   异常

    状态码如[表6](#zh-cn_topic_0060210606_zh-cn_topic_0079393967_zh-cn_topic_0075248102_table217266469404)所示。


**表 6**  状态码

<a name="zh-cn_topic_0060210606_zh-cn_topic_0079393967_zh-cn_topic_0075248102_table217266469404"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060210606_zh-cn_topic_0079393967_zh-cn_topic_0075248102_row149156199404"><th class="cellrowborder" valign="top" width="13.13131313131313%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0060210606_p152371515315"><a name="zh-cn_topic_0060210606_p152371515315"></a><a name="zh-cn_topic_0060210606_p152371515315"></a>HTTP状态码</p>
</th>
<th class="cellrowborder" valign="top" width="14.14141414141414%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0060210606_p523717517320"><a name="zh-cn_topic_0060210606_p523717517320"></a><a name="zh-cn_topic_0060210606_p523717517320"></a>业务错误码</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0060210606_p823719511737"><a name="zh-cn_topic_0060210606_p823719511737"></a><a name="zh-cn_topic_0060210606_p823719511737"></a>返回消息体</p>
</th>
<th class="cellrowborder" valign="top" width="39.39393939393939%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0060210606_p14237125115316"><a name="zh-cn_topic_0060210606_p14237125115316"></a><a name="zh-cn_topic_0060210606_p14237125115316"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060210606_zh-cn_topic_0079393967_zh-cn_topic_0075248102_row66966729404"><td class="cellrowborder" valign="top" width="13.13131313131313%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060210606_zh-cn_topic_0079393967_zh-cn_topic_0075248102_p55595609404"><a name="zh-cn_topic_0060210606_zh-cn_topic_0079393967_zh-cn_topic_0075248102_p55595609404"></a><a name="zh-cn_topic_0060210606_zh-cn_topic_0079393967_zh-cn_topic_0075248102_p55595609404"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="14.14141414141414%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060210606_p12137841789"><a name="zh-cn_topic_0060210606_p12137841789"></a><a name="zh-cn_topic_0060210606_p12137841789"></a>001</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060210606_p111371141983"><a name="zh-cn_topic_0060210606_p111371141983"></a><a name="zh-cn_topic_0060210606_p111371141983"></a>{errCode:"400001", errMsg:"Invalid parameter(s)", detail:""}</p>
</td>
<td class="cellrowborder" valign="top" width="39.39393939393939%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060210606_p313774111816"><a name="zh-cn_topic_0060210606_p313774111816"></a><a name="zh-cn_topic_0060210606_p313774111816"></a>请求参数错误</p>
</td>
</tr>
</tbody>
</table>

更多状态码请参考[错误码列表](错误码列表.md)。


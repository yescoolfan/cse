# Rule<a name="ZH-CN_TOPIC_0115714407"></a>

**表 1**  参数说明

<a name="zh-cn_topic_0060506830_table51620847114953"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060506830_row43559169114953"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0060506830_p3155843511508"><a name="zh-cn_topic_0060506830_p3155843511508"></a><a name="zh-cn_topic_0060506830_p3155843511508"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="13.350000000000001%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0060506830_p609644911508"><a name="zh-cn_topic_0060506830_p609644911508"></a><a name="zh-cn_topic_0060506830_p609644911508"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="8.64%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0060506830_p2405040011508"><a name="zh-cn_topic_0060506830_p2405040011508"></a><a name="zh-cn_topic_0060506830_p2405040011508"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="53.010000000000005%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0060506830_p192541611508"><a name="zh-cn_topic_0060506830_p192541611508"></a><a name="zh-cn_topic_0060506830_p192541611508"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060506830_row25019244112726"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506830_p13292893112726"><a name="zh-cn_topic_0060506830_p13292893112726"></a><a name="zh-cn_topic_0060506830_p13292893112726"></a>ruleId</p>
</td>
<td class="cellrowborder" valign="top" width="13.350000000000001%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506830_p46572646115339"><a name="zh-cn_topic_0060506830_p46572646115339"></a><a name="zh-cn_topic_0060506830_p46572646115339"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="8.64%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506830_p40260032112726"><a name="zh-cn_topic_0060506830_p40260032112726"></a><a name="zh-cn_topic_0060506830_p40260032112726"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="53.010000000000005%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506830_p39837187112726"><a name="zh-cn_topic_0060506830_p39837187112726"></a><a name="zh-cn_topic_0060506830_p39837187112726"></a>黑白名单ID</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506830_row52390368115548"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506830_p15761454115548"><a name="zh-cn_topic_0060506830_p15761454115548"></a><a name="zh-cn_topic_0060506830_p15761454115548"></a>ruleType</p>
</td>
<td class="cellrowborder" valign="top" width="13.350000000000001%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506830_p1609408115548"><a name="zh-cn_topic_0060506830_p1609408115548"></a><a name="zh-cn_topic_0060506830_p1609408115548"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="8.64%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506830_p63253247115548"><a name="zh-cn_topic_0060506830_p63253247115548"></a><a name="zh-cn_topic_0060506830_p63253247115548"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="53.010000000000005%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506830_p4956673311570"><a name="zh-cn_topic_0060506830_p4956673311570"></a><a name="zh-cn_topic_0060506830_p4956673311570"></a>类型，WHITE表示白名单、BLACK表示黑名单</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506830_row30742068115557"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506830_p7079605115557"><a name="zh-cn_topic_0060506830_p7079605115557"></a><a name="zh-cn_topic_0060506830_p7079605115557"></a>attribute</p>
</td>
<td class="cellrowborder" valign="top" width="13.350000000000001%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506830_p36577171115557"><a name="zh-cn_topic_0060506830_p36577171115557"></a><a name="zh-cn_topic_0060506830_p36577171115557"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="8.64%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506830_p9960885115557"><a name="zh-cn_topic_0060506830_p9960885115557"></a><a name="zh-cn_topic_0060506830_p9960885115557"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="53.010000000000005%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506830_p1525380115557"><a name="zh-cn_topic_0060506830_p1525380115557"></a><a name="zh-cn_topic_0060506830_p1525380115557"></a>如果是tag_xxx开头，则按Tag过滤attribute属性。否则，则按ServiceId、AppId、ServiceName、Version、Description、Level、Status过滤。</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506830_row66326485115558"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506830_p3736211115558"><a name="zh-cn_topic_0060506830_p3736211115558"></a><a name="zh-cn_topic_0060506830_p3736211115558"></a>pattern</p>
</td>
<td class="cellrowborder" valign="top" width="13.350000000000001%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506830_p34197714115558"><a name="zh-cn_topic_0060506830_p34197714115558"></a><a name="zh-cn_topic_0060506830_p34197714115558"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="8.64%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506830_p18551482115558"><a name="zh-cn_topic_0060506830_p18551482115558"></a><a name="zh-cn_topic_0060506830_p18551482115558"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="53.010000000000005%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506830_p26275058115558"><a name="zh-cn_topic_0060506830_p26275058115558"></a><a name="zh-cn_topic_0060506830_p26275058115558"></a>匹配规则，正则表达式，长度1到64个字符。</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506830_row15148785115559"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506830_p19092076115559"><a name="zh-cn_topic_0060506830_p19092076115559"></a><a name="zh-cn_topic_0060506830_p19092076115559"></a>timestamp</p>
</td>
<td class="cellrowborder" valign="top" width="13.350000000000001%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506830_p2954299115559"><a name="zh-cn_topic_0060506830_p2954299115559"></a><a name="zh-cn_topic_0060506830_p2954299115559"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="8.64%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506830_p37971655115559"><a name="zh-cn_topic_0060506830_p37971655115559"></a><a name="zh-cn_topic_0060506830_p37971655115559"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="53.010000000000005%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506830_p55805175115559"><a name="zh-cn_topic_0060506830_p55805175115559"></a><a name="zh-cn_topic_0060506830_p55805175115559"></a>创建rule的时间，只有获取rule时返回使用。</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506830_row4444020911560"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506830_p4288715111560"><a name="zh-cn_topic_0060506830_p4288715111560"></a><a name="zh-cn_topic_0060506830_p4288715111560"></a>description</p>
</td>
<td class="cellrowborder" valign="top" width="13.350000000000001%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506830_p5130717311560"><a name="zh-cn_topic_0060506830_p5130717311560"></a><a name="zh-cn_topic_0060506830_p5130717311560"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="8.64%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506830_p6224034811560"><a name="zh-cn_topic_0060506830_p6224034811560"></a><a name="zh-cn_topic_0060506830_p6224034811560"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="53.010000000000005%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506830_p830341911560"><a name="zh-cn_topic_0060506830_p830341911560"></a><a name="zh-cn_topic_0060506830_p830341911560"></a>Rule的描述信息，字符长度不超过256。</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506830_row374314125521"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506830_p942919522521"><a name="zh-cn_topic_0060506830_p942919522521"></a><a name="zh-cn_topic_0060506830_p942919522521"></a>modTimestamp</p>
</td>
<td class="cellrowborder" valign="top" width="13.350000000000001%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506830_p6743121255213"><a name="zh-cn_topic_0060506830_p6743121255213"></a><a name="zh-cn_topic_0060506830_p6743121255213"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="8.64%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506830_p13743512185218"><a name="zh-cn_topic_0060506830_p13743512185218"></a><a name="zh-cn_topic_0060506830_p13743512185218"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="53.010000000000005%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506830_p107432120524"><a name="zh-cn_topic_0060506830_p107432120524"></a><a name="zh-cn_topic_0060506830_p107432120524"></a>最后修改UTC时间</p>
</td>
</tr>
</tbody>
</table>


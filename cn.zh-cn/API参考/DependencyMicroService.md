# DependencyMicroService<a name="ZH-CN_TOPIC_0115714406"></a>

**表 1**  参数说明

<a name="zh-cn_topic_0060506827_table51620847114953"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060506827_row43559169114953"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0060506827_p3155843511508"><a name="zh-cn_topic_0060506827_p3155843511508"></a><a name="zh-cn_topic_0060506827_p3155843511508"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.29%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0060506827_p609644911508"><a name="zh-cn_topic_0060506827_p609644911508"></a><a name="zh-cn_topic_0060506827_p609644911508"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="13.15%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0060506827_p2405040011508"><a name="zh-cn_topic_0060506827_p2405040011508"></a><a name="zh-cn_topic_0060506827_p2405040011508"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="47.56%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0060506827_p192541611508"><a name="zh-cn_topic_0060506827_p192541611508"></a><a name="zh-cn_topic_0060506827_p192541611508"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060506827_row35538952114953"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506827_p60082860114953"><a name="zh-cn_topic_0060506827_p60082860114953"></a><a name="zh-cn_topic_0060506827_p60082860114953"></a>appId</p>
</td>
<td class="cellrowborder" valign="top" width="14.29%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506827_p34873521114953"><a name="zh-cn_topic_0060506827_p34873521114953"></a><a name="zh-cn_topic_0060506827_p34873521114953"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="13.15%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506827_p6182975114953"><a name="zh-cn_topic_0060506827_p6182975114953"></a><a name="zh-cn_topic_0060506827_p6182975114953"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="47.56%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506827_p31058941114953"><a name="zh-cn_topic_0060506827_p31058941114953"></a><a name="zh-cn_topic_0060506827_p31058941114953"></a>应用app唯一标识。</p>
<p id="zh-cn_topic_0060506827_p20849115233114"><a name="zh-cn_topic_0060506827_p20849115233114"></a><a name="zh-cn_topic_0060506827_p20849115233114"></a>字符长度为1~160。</p>
<p id="zh-cn_topic_0060506827_p66707282328"><a name="zh-cn_topic_0060506827_p66707282328"></a><a name="zh-cn_topic_0060506827_p66707282328"></a>正则表达式为^[a-zA-Z0-9]*$|^[a-zA-Z0-9][a-zA-Z0-9_\-.]*[a-zA-Z0-9]$</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506827_row16010111113439"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506827_p21750639113439"><a name="zh-cn_topic_0060506827_p21750639113439"></a><a name="zh-cn_topic_0060506827_p21750639113439"></a>serviceName</p>
</td>
<td class="cellrowborder" valign="top" width="14.29%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506827_p16971352113439"><a name="zh-cn_topic_0060506827_p16971352113439"></a><a name="zh-cn_topic_0060506827_p16971352113439"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="13.15%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506827_p32502241113439"><a name="zh-cn_topic_0060506827_p32502241113439"></a><a name="zh-cn_topic_0060506827_p32502241113439"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="47.56%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506827_p284425711359"><a name="zh-cn_topic_0060506827_p284425711359"></a><a name="zh-cn_topic_0060506827_p284425711359"></a>微服务名称。</p>
<p id="zh-cn_topic_0060506827_p45600599113542"><a name="zh-cn_topic_0060506827_p45600599113542"></a><a name="zh-cn_topic_0060506827_p45600599113542"></a>作为provider支持为*，表示依赖同一租户下的所有服务。当服务名称为*时，appId和version可以省略。</p>
<p id="zh-cn_topic_0060506827_p15435826113439"><a name="zh-cn_topic_0060506827_p15435826113439"></a><a name="zh-cn_topic_0060506827_p15435826113439"></a>consumer不支持*。</p>
<p id="zh-cn_topic_0060506827_p171921783310"><a name="zh-cn_topic_0060506827_p171921783310"></a><a name="zh-cn_topic_0060506827_p171921783310"></a>字符长度为1~128。</p>
<p id="zh-cn_topic_0060506827_p2309416342"><a name="zh-cn_topic_0060506827_p2309416342"></a><a name="zh-cn_topic_0060506827_p2309416342"></a>正则表达式为^[a-zA-Z0-9]*$|^[a-zA-Z0-9][a-zA-Z0-9_\-.]*[a-zA-Z0-9]$</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506827_row1031530311365"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506827_p3023321311365"><a name="zh-cn_topic_0060506827_p3023321311365"></a><a name="zh-cn_topic_0060506827_p3023321311365"></a>version</p>
</td>
<td class="cellrowborder" valign="top" width="14.29%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506827_p3297115911365"><a name="zh-cn_topic_0060506827_p3297115911365"></a><a name="zh-cn_topic_0060506827_p3297115911365"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="13.15%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506827_p5341820511365"><a name="zh-cn_topic_0060506827_p5341820511365"></a><a name="zh-cn_topic_0060506827_p5341820511365"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="47.56%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506827_p46930165113628"><a name="zh-cn_topic_0060506827_p46930165113628"></a><a name="zh-cn_topic_0060506827_p46930165113628"></a>微服务版本。</p>
<p id="zh-cn_topic_0060506827_p3237089411381"><a name="zh-cn_topic_0060506827_p3237089411381"></a><a name="zh-cn_topic_0060506827_p3237089411381"></a>作为provider支持+、固定版本和latest（当前最新版本），如1.0.1+，表示1.0.1以上的版本，包括1.0.1。</p>
<p id="zh-cn_topic_0060506827_p3190738511365"><a name="zh-cn_topic_0060506827_p3190738511365"></a><a name="zh-cn_topic_0060506827_p3190738511365"></a>作为consumer只能为固定版本。</p>
<p id="zh-cn_topic_0060506827_p522932943413"><a name="zh-cn_topic_0060506827_p522932943413"></a><a name="zh-cn_topic_0060506827_p522932943413"></a>字符长度为1~64。</p>
<p id="zh-cn_topic_0060506827_p148195119340"><a name="zh-cn_topic_0060506827_p148195119340"></a><a name="zh-cn_topic_0060506827_p148195119340"></a>正则表达式为^[0-9]*$|^[0-9]+(\.[0-9]+)*$</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506827_row1447293511387"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506827_p3145709111387"><a name="zh-cn_topic_0060506827_p3145709111387"></a><a name="zh-cn_topic_0060506827_p3145709111387"></a>environment</p>
</td>
<td class="cellrowborder" valign="top" width="14.29%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506827_p6499643911387"><a name="zh-cn_topic_0060506827_p6499643911387"></a><a name="zh-cn_topic_0060506827_p6499643911387"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="13.15%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506827_p3022023611387"><a name="zh-cn_topic_0060506827_p3022023611387"></a><a name="zh-cn_topic_0060506827_p3022023611387"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="47.56%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506827_p946320692219"><a name="zh-cn_topic_0060506827_p946320692219"></a><a name="zh-cn_topic_0060506827_p946320692219"></a>微服务的环境信息。包括：</p>
<a name="zh-cn_topic_0060506827_ul13435826122211"></a><a name="zh-cn_topic_0060506827_ul13435826122211"></a><ul id="zh-cn_topic_0060506827_ul13435826122211"><li>development</li><li>testing</li><li>acceptance</li><li>production</li></ul>
</td>
</tr>
</tbody>
</table>


# TxInfoCollection<a name="ZH-CN_TOPIC_0115714433"></a>

**表 1**  参数说明

<a name="zh-cn_topic_0074793171_table46511657115712"></a>
<table><thead align="left"><tr id="zh-cn_topic_0074793171_row1565211570579"><th class="cellrowborder" valign="top" width="21%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0074793171_p8652657175713"><a name="zh-cn_topic_0074793171_p8652657175713"></a><a name="zh-cn_topic_0074793171_p8652657175713"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="19%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0074793171_p166537577572"><a name="zh-cn_topic_0074793171_p166537577572"></a><a name="zh-cn_topic_0074793171_p166537577572"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0074793171_p865355719570"><a name="zh-cn_topic_0074793171_p865355719570"></a><a name="zh-cn_topic_0074793171_p865355719570"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="44%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0074793171_p5653145715715"><a name="zh-cn_topic_0074793171_p5653145715715"></a><a name="zh-cn_topic_0074793171_p5653145715715"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0074793171_row1065318574576"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0074793171_p46539578576"><a name="zh-cn_topic_0074793171_p46539578576"></a><a name="zh-cn_topic_0074793171_p46539578576"></a>uploadHead</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0074793171_p565315577578"><a name="zh-cn_topic_0074793171_p565315577578"></a><a name="zh-cn_topic_0074793171_p565315577578"></a>string</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0074793171_p4653105725720"><a name="zh-cn_topic_0074793171_p4653105725720"></a><a name="zh-cn_topic_0074793171_p4653105725720"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="44%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0074793171_p1565395716572"><a name="zh-cn_topic_0074793171_p1565395716572"></a><a name="zh-cn_topic_0074793171_p1565395716572"></a>汇总唯一标志。</p>
</td>
</tr>
<tr id="zh-cn_topic_0074793171_row265315718570"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0074793171_p665316576576"><a name="zh-cn_topic_0074793171_p665316576576"></a><a name="zh-cn_topic_0074793171_p665316576576"></a>committed</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0074793171_p365414572579"><a name="zh-cn_topic_0074793171_p365414572579"></a><a name="zh-cn_topic_0074793171_p365414572579"></a>integer</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0074793171_p20654175785715"><a name="zh-cn_topic_0074793171_p20654175785715"></a><a name="zh-cn_topic_0074793171_p20654175785715"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="44%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0074793171_p136541557205712"><a name="zh-cn_topic_0074793171_p136541557205712"></a><a name="zh-cn_topic_0074793171_p136541557205712"></a>成功事务数量。</p>
</td>
</tr>
<tr id="zh-cn_topic_0074793171_row196541757175714"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0074793171_p365475725714"><a name="zh-cn_topic_0074793171_p365475725714"></a><a name="zh-cn_topic_0074793171_p365475725714"></a>rollbacked</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0074793171_p15654185715577"><a name="zh-cn_topic_0074793171_p15654185715577"></a><a name="zh-cn_topic_0074793171_p15654185715577"></a>integer</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0074793171_p965425765710"><a name="zh-cn_topic_0074793171_p965425765710"></a><a name="zh-cn_topic_0074793171_p965425765710"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="44%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0074793171_p106541557195712"><a name="zh-cn_topic_0074793171_p106541557195712"></a><a name="zh-cn_topic_0074793171_p106541557195712"></a>回滚事务数量。</p>
</td>
</tr>
<tr id="zh-cn_topic_0074793171_row166541257145719"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0074793171_p176541571570"><a name="zh-cn_topic_0074793171_p176541571570"></a><a name="zh-cn_topic_0074793171_p176541571570"></a>prepared</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0074793171_p565445717577"><a name="zh-cn_topic_0074793171_p565445717577"></a><a name="zh-cn_topic_0074793171_p565445717577"></a>integer</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0074793171_p1865495714579"><a name="zh-cn_topic_0074793171_p1865495714579"></a><a name="zh-cn_topic_0074793171_p1865495714579"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="44%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0074793171_p186541257175720"><a name="zh-cn_topic_0074793171_p186541257175720"></a><a name="zh-cn_topic_0074793171_p186541257175720"></a>准备事务数量。</p>
</td>
</tr>
<tr id="zh-cn_topic_0074793171_row1155618181613"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0074793171_p115581218812"><a name="zh-cn_topic_0074793171_p115581218812"></a><a name="zh-cn_topic_0074793171_p115581218812"></a>type</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0074793171_p6558618513"><a name="zh-cn_topic_0074793171_p6558618513"></a><a name="zh-cn_topic_0074793171_p6558618513"></a>string</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0074793171_p1555814185111"><a name="zh-cn_topic_0074793171_p1555814185111"></a><a name="zh-cn_topic_0074793171_p1555814185111"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="44%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0074793171_p1155818181716"><a name="zh-cn_topic_0074793171_p1155818181716"></a><a name="zh-cn_topic_0074793171_p1155818181716"></a>事务类型。</p>
</td>
</tr>
<tr id="zh-cn_topic_0074793171_row46558811"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0074793171_p16145814116"><a name="zh-cn_topic_0074793171_p16145814116"></a><a name="zh-cn_topic_0074793171_p16145814116"></a>subTxCount</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0074793171_p468581212"><a name="zh-cn_topic_0074793171_p468581212"></a><a name="zh-cn_topic_0074793171_p468581212"></a>integer</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0074793171_p869583110"><a name="zh-cn_topic_0074793171_p869583110"></a><a name="zh-cn_topic_0074793171_p869583110"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="44%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0074793171_p1664587110"><a name="zh-cn_topic_0074793171_p1664587110"></a><a name="zh-cn_topic_0074793171_p1664587110"></a>子事务数量。</p>
</td>
</tr>
<tr id="zh-cn_topic_0074793171_row36243220217"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0074793171_p12626321727"><a name="zh-cn_topic_0074793171_p12626321727"></a><a name="zh-cn_topic_0074793171_p12626321727"></a>txTimeout</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0074793171_p662113218211"><a name="zh-cn_topic_0074793171_p662113218211"></a><a name="zh-cn_topic_0074793171_p662113218211"></a>integer</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0074793171_p662173214216"><a name="zh-cn_topic_0074793171_p662173214216"></a><a name="zh-cn_topic_0074793171_p662173214216"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="44%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0074793171_p163932726"><a name="zh-cn_topic_0074793171_p163932726"></a><a name="zh-cn_topic_0074793171_p163932726"></a>事务超时时间。</p>
</td>
</tr>
<tr id="zh-cn_topic_0074793171_row685471417317"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0074793171_p88541814138"><a name="zh-cn_topic_0074793171_p88541814138"></a><a name="zh-cn_topic_0074793171_p88541814138"></a>txInfos</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0074793171_p138543141639"><a name="zh-cn_topic_0074793171_p138543141639"></a><a name="zh-cn_topic_0074793171_p138543141639"></a><a href="ActiveTxInfo.md">ActiveTxInfo</a></p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0074793171_p148541514133"><a name="zh-cn_topic_0074793171_p148541514133"></a><a name="zh-cn_topic_0074793171_p148541514133"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="44%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0074793171_p98544149315"><a name="zh-cn_topic_0074793171_p98544149315"></a><a name="zh-cn_topic_0074793171_p98544149315"></a>事务明细信息。</p>
</td>
</tr>
</tbody>
</table>


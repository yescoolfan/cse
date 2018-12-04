# MicroService<a name="ZH-CN_TOPIC_0115714404"></a>

**表 1**  参数说明

<a name="zh-cn_topic_0060506824_table5582460911196"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060506824_row4963271911196"><th class="cellrowborder" valign="top" width="20.3%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0060506824_p6082728511196"><a name="zh-cn_topic_0060506824_p6082728511196"></a><a name="zh-cn_topic_0060506824_p6082728511196"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="18.61%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0060506824_p2806308911196"><a name="zh-cn_topic_0060506824_p2806308911196"></a><a name="zh-cn_topic_0060506824_p2806308911196"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="9.21%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0060506824_p5851770411196"><a name="zh-cn_topic_0060506824_p5851770411196"></a><a name="zh-cn_topic_0060506824_p5851770411196"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="51.88%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0060506824_p4231360411196"><a name="zh-cn_topic_0060506824_p4231360411196"></a><a name="zh-cn_topic_0060506824_p4231360411196"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060506824_row484993311196"><td class="cellrowborder" valign="top" width="20.3%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p5730029811196"><a name="zh-cn_topic_0060506824_p5730029811196"></a><a name="zh-cn_topic_0060506824_p5730029811196"></a>serviceId</p>
</td>
<td class="cellrowborder" valign="top" width="18.61%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p1081258011196"><a name="zh-cn_topic_0060506824_p1081258011196"></a><a name="zh-cn_topic_0060506824_p1081258011196"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="9.21%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p340377811196"><a name="zh-cn_topic_0060506824_p340377811196"></a><a name="zh-cn_topic_0060506824_p340377811196"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="51.88%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506824_p727060511196"><a name="zh-cn_topic_0060506824_p727060511196"></a><a name="zh-cn_topic_0060506824_p727060511196"></a>微服务唯一标识。</p>
<p id="zh-cn_topic_0060506824_p1156113572534"><a name="zh-cn_topic_0060506824_p1156113572534"></a><a name="zh-cn_topic_0060506824_p1156113572534"></a>字符长度为1~64。</p>
<p id="zh-cn_topic_0060506824_p1172946185415"><a name="zh-cn_topic_0060506824_p1172946185415"></a><a name="zh-cn_topic_0060506824_p1172946185415"></a>正则表达式为^.*$</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506824_row50458592163344"><td class="cellrowborder" valign="top" width="20.3%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p60614140163344"><a name="zh-cn_topic_0060506824_p60614140163344"></a><a name="zh-cn_topic_0060506824_p60614140163344"></a>environment</p>
</td>
<td class="cellrowborder" valign="top" width="18.61%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p10798268163344"><a name="zh-cn_topic_0060506824_p10798268163344"></a><a name="zh-cn_topic_0060506824_p10798268163344"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="9.21%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p2244488163344"><a name="zh-cn_topic_0060506824_p2244488163344"></a><a name="zh-cn_topic_0060506824_p2244488163344"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="51.88%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506824_p5736096017839"><a name="zh-cn_topic_0060506824_p5736096017839"></a><a name="zh-cn_topic_0060506824_p5736096017839"></a>用于区分服务阶段，取值为development|testing|acceptance|production。</p>
<p id="zh-cn_topic_0060506824_p58761106163439"><a name="zh-cn_topic_0060506824_p58761106163439"></a><a name="zh-cn_topic_0060506824_p58761106163439"></a>当配置为development、testing或acceptance时，可以通过批量上传schemas接口新增或者修改已存在的Schema；当配置为production时，则不可以新增或者修改Schema。</p>
<p id="zh-cn_topic_0060506824_p45289460164812"><a name="zh-cn_topic_0060506824_p45289460164812"></a><a name="zh-cn_topic_0060506824_p45289460164812"></a>默认值：development</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506824_row6543544611196"><td class="cellrowborder" valign="top" width="20.3%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p6577979111196"><a name="zh-cn_topic_0060506824_p6577979111196"></a><a name="zh-cn_topic_0060506824_p6577979111196"></a>appId</p>
</td>
<td class="cellrowborder" valign="top" width="18.61%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p2656282411196"><a name="zh-cn_topic_0060506824_p2656282411196"></a><a name="zh-cn_topic_0060506824_p2656282411196"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="9.21%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p410509711196"><a name="zh-cn_topic_0060506824_p410509711196"></a><a name="zh-cn_topic_0060506824_p410509711196"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.88%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506824_p6407743511196"><a name="zh-cn_topic_0060506824_p6407743511196"></a><a name="zh-cn_topic_0060506824_p6407743511196"></a>应用App唯一标识。</p>
<p id="zh-cn_topic_0060506824_p1845416518469"><a name="zh-cn_topic_0060506824_p1845416518469"></a><a name="zh-cn_topic_0060506824_p1845416518469"></a>字符长度为1~160。</p>
<p id="zh-cn_topic_0060506824_p19716313164815"><a name="zh-cn_topic_0060506824_p19716313164815"></a><a name="zh-cn_topic_0060506824_p19716313164815"></a>正则表达式为^[a-zA-Z0-9]*$|^[a-zA-Z0-9][a-zA-Z0-9_\-.]*[a-zA-Z0-9]$</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506824_row3982600511196"><td class="cellrowborder" valign="top" width="20.3%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p468101111196"><a name="zh-cn_topic_0060506824_p468101111196"></a><a name="zh-cn_topic_0060506824_p468101111196"></a>serviceName</p>
</td>
<td class="cellrowborder" valign="top" width="18.61%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p4361762111196"><a name="zh-cn_topic_0060506824_p4361762111196"></a><a name="zh-cn_topic_0060506824_p4361762111196"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="9.21%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p4336643611196"><a name="zh-cn_topic_0060506824_p4336643611196"></a><a name="zh-cn_topic_0060506824_p4336643611196"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.88%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506824_p2302042311196"><a name="zh-cn_topic_0060506824_p2302042311196"></a><a name="zh-cn_topic_0060506824_p2302042311196"></a>微服务名称，同一个App要保证唯一。</p>
<p id="zh-cn_topic_0060506824_p244451471915"><a name="zh-cn_topic_0060506824_p244451471915"></a><a name="zh-cn_topic_0060506824_p244451471915"></a>字符长度为1~128。</p>
<p id="zh-cn_topic_0060506824_p56411721194914"><a name="zh-cn_topic_0060506824_p56411721194914"></a><a name="zh-cn_topic_0060506824_p56411721194914"></a>正则表达式为^[a-zA-Z0-9]*$|^[a-zA-Z0-9][a-zA-Z0-9_\-.]*[a-zA-Z0-9]$</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506824_row585722011196"><td class="cellrowborder" valign="top" width="20.3%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p467280111196"><a name="zh-cn_topic_0060506824_p467280111196"></a><a name="zh-cn_topic_0060506824_p467280111196"></a>version</p>
</td>
<td class="cellrowborder" valign="top" width="18.61%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p4295258211196"><a name="zh-cn_topic_0060506824_p4295258211196"></a><a name="zh-cn_topic_0060506824_p4295258211196"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="9.21%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p5660713211196"><a name="zh-cn_topic_0060506824_p5660713211196"></a><a name="zh-cn_topic_0060506824_p5660713211196"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.88%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506824_p2177498611196"><a name="zh-cn_topic_0060506824_p2177498611196"></a><a name="zh-cn_topic_0060506824_p2177498611196"></a>微服务版本号。</p>
<p id="zh-cn_topic_0060506824_p87317371608"><a name="zh-cn_topic_0060506824_p87317371608"></a><a name="zh-cn_topic_0060506824_p87317371608"></a>字符长度为1~64。</p>
<p id="zh-cn_topic_0060506824_p12335941312"><a name="zh-cn_topic_0060506824_p12335941312"></a><a name="zh-cn_topic_0060506824_p12335941312"></a>正则表达式为^[0-9]*$|^[0-9]+(\.[0-9]+)*$</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506824_row6175715411196"><td class="cellrowborder" valign="top" width="20.3%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p3627360911196"><a name="zh-cn_topic_0060506824_p3627360911196"></a><a name="zh-cn_topic_0060506824_p3627360911196"></a>description</p>
</td>
<td class="cellrowborder" valign="top" width="18.61%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p5248117911196"><a name="zh-cn_topic_0060506824_p5248117911196"></a><a name="zh-cn_topic_0060506824_p5248117911196"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="9.21%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p2311712211196"><a name="zh-cn_topic_0060506824_p2311712211196"></a><a name="zh-cn_topic_0060506824_p2311712211196"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="51.88%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506824_p6054762211196"><a name="zh-cn_topic_0060506824_p6054762211196"></a><a name="zh-cn_topic_0060506824_p6054762211196"></a>微服务描述信息。</p>
<p id="zh-cn_topic_0060506824_p14417631232"><a name="zh-cn_topic_0060506824_p14417631232"></a><a name="zh-cn_topic_0060506824_p14417631232"></a>字符长度不超过256。</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506824_row805769011196"><td class="cellrowborder" valign="top" width="20.3%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p4869315511196"><a name="zh-cn_topic_0060506824_p4869315511196"></a><a name="zh-cn_topic_0060506824_p4869315511196"></a>level</p>
</td>
<td class="cellrowborder" valign="top" width="18.61%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p5183151711196"><a name="zh-cn_topic_0060506824_p5183151711196"></a><a name="zh-cn_topic_0060506824_p5183151711196"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="9.21%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p3760337611196"><a name="zh-cn_topic_0060506824_p3760337611196"></a><a name="zh-cn_topic_0060506824_p3760337611196"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="51.88%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506824_p176450214424"><a name="zh-cn_topic_0060506824_p176450214424"></a><a name="zh-cn_topic_0060506824_p176450214424"></a>微服务层级。包括：</p>
<a name="zh-cn_topic_0060506824_ul514914409424"></a><a name="zh-cn_topic_0060506824_ul514914409424"></a><ul id="zh-cn_topic_0060506824_ul514914409424"><li>FRONT</li><li>MIDDLE</li><li>BACK</li></ul>
</td>
</tr>
<tr id="zh-cn_topic_0060506824_row3244476411196"><td class="cellrowborder" valign="top" width="20.3%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p1078021011196"><a name="zh-cn_topic_0060506824_p1078021011196"></a><a name="zh-cn_topic_0060506824_p1078021011196"></a>timestamp</p>
</td>
<td class="cellrowborder" valign="top" width="18.61%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p78185411196"><a name="zh-cn_topic_0060506824_p78185411196"></a><a name="zh-cn_topic_0060506824_p78185411196"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="9.21%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p6333018111196"><a name="zh-cn_topic_0060506824_p6333018111196"></a><a name="zh-cn_topic_0060506824_p6333018111196"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="51.88%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506824_p2947105711196"><a name="zh-cn_topic_0060506824_p2947105711196"></a><a name="zh-cn_topic_0060506824_p2947105711196"></a>post或者put。</p>
<p id="zh-cn_topic_0060506824_p6391292911196"><a name="zh-cn_topic_0060506824_p6391292911196"></a><a name="zh-cn_topic_0060506824_p6391292911196"></a>不带该参数，timestamp是内部生成的，只get接口才返回该值。</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506824_row3834545011196"><td class="cellrowborder" valign="top" width="20.3%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p1897375111196"><a name="zh-cn_topic_0060506824_p1897375111196"></a><a name="zh-cn_topic_0060506824_p1897375111196"></a>schemas</p>
</td>
<td class="cellrowborder" valign="top" width="18.61%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p6047888111196"><a name="zh-cn_topic_0060506824_p6047888111196"></a><a name="zh-cn_topic_0060506824_p6047888111196"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="9.21%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p6695118311196"><a name="zh-cn_topic_0060506824_p6695118311196"></a><a name="zh-cn_topic_0060506824_p6695118311196"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="51.88%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506824_p5433674611196"><a name="zh-cn_topic_0060506824_p5433674611196"></a><a name="zh-cn_topic_0060506824_p5433674611196"></a>微服务访问契约内容的外键ID。支持数字、字母，支持使用括号内字符做连接符(_-.)，长度1-160字节，数组长度最大100</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506824_row1926866711196"><td class="cellrowborder" valign="top" width="20.3%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p1725821211196"><a name="zh-cn_topic_0060506824_p1725821211196"></a><a name="zh-cn_topic_0060506824_p1725821211196"></a>status</p>
</td>
<td class="cellrowborder" valign="top" width="18.61%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p5573790111196"><a name="zh-cn_topic_0060506824_p5573790111196"></a><a name="zh-cn_topic_0060506824_p5573790111196"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="9.21%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p1847609411196"><a name="zh-cn_topic_0060506824_p1847609411196"></a><a name="zh-cn_topic_0060506824_p1847609411196"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="51.88%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506824_p2016864011196"><a name="zh-cn_topic_0060506824_p2016864011196"></a><a name="zh-cn_topic_0060506824_p2016864011196"></a>微服务状态，UP表示上线，DOWN表示下线。默认值UP</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506824_row4730003411196"><td class="cellrowborder" valign="top" width="20.3%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p609758411196"><a name="zh-cn_topic_0060506824_p609758411196"></a><a name="zh-cn_topic_0060506824_p609758411196"></a>paths</p>
</td>
<td class="cellrowborder" valign="top" width="18.61%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p2414230611196"><a name="zh-cn_topic_0060506824_p2414230611196"></a><a name="zh-cn_topic_0060506824_p2414230611196"></a>ServicePath</p>
</td>
<td class="cellrowborder" valign="top" width="9.21%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p936979311196"><a name="zh-cn_topic_0060506824_p936979311196"></a><a name="zh-cn_topic_0060506824_p936979311196"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="51.88%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506824_p2075576411196"><a name="zh-cn_topic_0060506824_p2075576411196"></a><a name="zh-cn_topic_0060506824_p2075576411196"></a>服务路由信息。</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506824_row5258415311196"><td class="cellrowborder" valign="top" width="20.3%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p3145799011196"><a name="zh-cn_topic_0060506824_p3145799011196"></a><a name="zh-cn_topic_0060506824_p3145799011196"></a>framework</p>
</td>
<td class="cellrowborder" valign="top" width="18.61%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p13986185911211"><a name="zh-cn_topic_0060506824_p13986185911211"></a><a name="zh-cn_topic_0060506824_p13986185911211"></a>Framework</p>
</td>
<td class="cellrowborder" valign="top" width="9.21%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p1985101712411"><a name="zh-cn_topic_0060506824_p1985101712411"></a><a name="zh-cn_topic_0060506824_p1985101712411"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="51.88%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506824_p3982383911196"><a name="zh-cn_topic_0060506824_p3982383911196"></a><a name="zh-cn_topic_0060506824_p3982383911196"></a>微服务开发框架。支持数字、字母，支持使用括号内字符做连接符(_-.)，长度1-64字节</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506824_row123113302034"><td class="cellrowborder" valign="top" width="20.3%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p17132342635"><a name="zh-cn_topic_0060506824_p17132342635"></a><a name="zh-cn_topic_0060506824_p17132342635"></a>registerBy</p>
</td>
<td class="cellrowborder" valign="top" width="18.61%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p61351742336"><a name="zh-cn_topic_0060506824_p61351742336"></a><a name="zh-cn_topic_0060506824_p61351742336"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="9.21%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p799451720414"><a name="zh-cn_topic_0060506824_p799451720414"></a><a name="zh-cn_topic_0060506824_p799451720414"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="51.88%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506824_p195471457103"><a name="zh-cn_topic_0060506824_p195471457103"></a><a name="zh-cn_topic_0060506824_p195471457103"></a>微服务注册方式。包括：</p>
<a name="zh-cn_topic_0060506824_ul47897141102"></a><a name="zh-cn_topic_0060506824_ul47897141102"></a><ul id="zh-cn_topic_0060506824_ul47897141102"><li>SDK</li><li>PLATFORM</li><li>SIDECAR</li><li>UNKNOWN</li></ul>
</td>
</tr>
<tr id="zh-cn_topic_0060506824_row94717346315"><td class="cellrowborder" valign="top" width="20.3%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p2026012015214"><a name="zh-cn_topic_0060506824_p2026012015214"></a><a name="zh-cn_topic_0060506824_p2026012015214"></a>modTimestamp</p>
</td>
<td class="cellrowborder" valign="top" width="18.61%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p1126062075211"><a name="zh-cn_topic_0060506824_p1126062075211"></a><a name="zh-cn_topic_0060506824_p1126062075211"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="9.21%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p1899410175419"><a name="zh-cn_topic_0060506824_p1899410175419"></a><a name="zh-cn_topic_0060506824_p1899410175419"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="51.88%" headers="mcps1.2.5.1.4 "><p id="p166603339505"><a name="p166603339505"></a><a name="p166603339505"></a>最后修改UTC时间</p>
</td>
</tr>
</tbody>
</table>

**表 2**  ServicePath参数说明

<a name="zh-cn_topic_0060506824_table51620847114953"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060506824_row43559169114953"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0060506824_p3155843511508"><a name="zh-cn_topic_0060506824_p3155843511508"></a><a name="zh-cn_topic_0060506824_p3155843511508"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0060506824_p609644911508"><a name="zh-cn_topic_0060506824_p609644911508"></a><a name="zh-cn_topic_0060506824_p609644911508"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="13%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0060506824_p2405040011508"><a name="zh-cn_topic_0060506824_p2405040011508"></a><a name="zh-cn_topic_0060506824_p2405040011508"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="37%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0060506824_p192541611508"><a name="zh-cn_topic_0060506824_p192541611508"></a><a name="zh-cn_topic_0060506824_p192541611508"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060506824_row35538952114953"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p60082860114953"><a name="zh-cn_topic_0060506824_p60082860114953"></a><a name="zh-cn_topic_0060506824_p60082860114953"></a>Path</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p34873521114953"><a name="zh-cn_topic_0060506824_p34873521114953"></a><a name="zh-cn_topic_0060506824_p34873521114953"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p6182975114953"><a name="zh-cn_topic_0060506824_p6182975114953"></a><a name="zh-cn_topic_0060506824_p6182975114953"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="37%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506824_p31058941114953"><a name="zh-cn_topic_0060506824_p31058941114953"></a><a name="zh-cn_topic_0060506824_p31058941114953"></a>路由地址。支持数字、字母和括号内字符(.,?'\/+&amp;%$#=~_-@{})，长度1-160字节</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506824_row25019244112726"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p13292893112726"><a name="zh-cn_topic_0060506824_p13292893112726"></a><a name="zh-cn_topic_0060506824_p13292893112726"></a>Property</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p2982550112726"><a name="zh-cn_topic_0060506824_p2982550112726"></a><a name="zh-cn_topic_0060506824_p2982550112726"></a><a href="Properties.md">Properties</a></p>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p40260032112726"><a name="zh-cn_topic_0060506824_p40260032112726"></a><a name="zh-cn_topic_0060506824_p40260032112726"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="37%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506824_p39837187112726"><a name="zh-cn_topic_0060506824_p39837187112726"></a><a name="zh-cn_topic_0060506824_p39837187112726"></a>扩展属性。</p>
</td>
</tr>
</tbody>
</table>

**表 3**  Framework参数说明

<a name="zh-cn_topic_0060506824_table15652132919416"></a>
<table><thead align="left"><tr id="zh-cn_topic_0060506824_row1865715290413"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0060506824_p1665802919420"><a name="zh-cn_topic_0060506824_p1665802919420"></a><a name="zh-cn_topic_0060506824_p1665802919420"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0060506824_p465917295415"><a name="zh-cn_topic_0060506824_p465917295415"></a><a name="zh-cn_topic_0060506824_p465917295415"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="13.34%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0060506824_p36601329449"><a name="zh-cn_topic_0060506824_p36601329449"></a><a name="zh-cn_topic_0060506824_p36601329449"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="36.66%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0060506824_p66611229545"><a name="zh-cn_topic_0060506824_p66611229545"></a><a name="zh-cn_topic_0060506824_p66611229545"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0060506824_row106612029141"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p4664529142"><a name="zh-cn_topic_0060506824_p4664529142"></a><a name="zh-cn_topic_0060506824_p4664529142"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p0665629540"><a name="zh-cn_topic_0060506824_p0665629540"></a><a name="zh-cn_topic_0060506824_p0665629540"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="13.34%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p109313819618"><a name="zh-cn_topic_0060506824_p109313819618"></a><a name="zh-cn_topic_0060506824_p109313819618"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="36.66%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506824_p96673296416"><a name="zh-cn_topic_0060506824_p96673296416"></a><a name="zh-cn_topic_0060506824_p96673296416"></a>微服务开发框架，默认值为UNKNOWN</p>
</td>
</tr>
<tr id="zh-cn_topic_0060506824_row186683298410"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0060506824_p01271546510"><a name="zh-cn_topic_0060506824_p01271546510"></a><a name="zh-cn_topic_0060506824_p01271546510"></a>version</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0060506824_p9670162910416"><a name="zh-cn_topic_0060506824_p9670162910416"></a><a name="zh-cn_topic_0060506824_p9670162910416"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="13.34%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0060506824_p0929889615"><a name="zh-cn_topic_0060506824_p0929889615"></a><a name="zh-cn_topic_0060506824_p0929889615"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="36.66%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0060506824_p66771529743"><a name="zh-cn_topic_0060506824_p66771529743"></a><a name="zh-cn_topic_0060506824_p66771529743"></a>微服务开发框架版本号，支持任意字符，长度1-64字节</p>
</td>
</tr>
</tbody>
</table>


# 逃离北上广

>[项目主页](https://jiangwei1995910.github.io/getAwayBSG/)

## What!

如果你是一个正准备逃离北上广等一线城市却又找不到去处的IT人士，或许这个项目能给你点建议。

## Desc

或许你跟我一样困惑，为此我通过爬虫抓取了智联招聘跟链家这2个平台的全部数据。最终拿到了18W+全国各个城市的招聘数据与81W+全国各地的房屋成交记录数据。

其中，招聘数据我抓取了工作年限，公司名称，公司规模，公司类型，工作类型，创建时间，工作名称，结束时间，教育情况，薪资字段，

对应房屋成交记录，我抓取了成交时间，成交价格，每平米均价，地址字段。

## 分析

首先，我计算了各个城市的平均薪资和方差情况，平均薪资前20如下：

| 序号  | 城市|  薪资| 方差| 样本总数|
| ---------- | -----------| -----------| -----------| -----------|
|1|"14834.7557"|"9331.410903951468"|"北京"|"5976"|
|2|"13708.5211"|"7736.06007380049"|"上海"|"4882"|
|3|"13075.8115"|"8557.670772674064"|"深圳"|"4775"|
|4|"11813.3489"|"7852.895751793788"|"杭州"|"4270"|
|5|"10953.3319"|"7363.7315469494415"|"广州"|"4607"|
|6|"10019.6305"|"12561.266313982946"|"其他"|"433"|
|7|"10012.0618"|"6464.859054939942"|"南京"|"3109"|
|8|"9946.0683"|"6041.077819712191"|"厦门"|"2429"|
|9|"9405.9081"|"9070.530112221546"|"拉萨"|"457"|
|10|"9367.4017"|"6232.818905479873"|"苏州"|"3356"|
|11|"9213.1109"|"5631.923650627519"|"武汉"|"4256"|
|12|"9149.5177"|"6370.5666291862535"|"长沙"|"3421"|
|13|"9025.9162"|"6573.61524233348"|"西安"|"3820"|
|14|"8999.3025"|"6172.310646614675"|"成都"|"4301"|
|15|"8935.7143"|"6416.9126508046475"|"天津"|"3220"|
|16|"8847.9281"|"6644.477328976252"|"珠海"|"1279"|
|17|"8699.5828"|"6901.177717061463"|"重庆"|"2157"|
|18|"8687.1069"|"6269.778049286164"|"太仓市"|"318"|
|19|"8632.3810"|"8789.338728450888"|"嘉兴"|"525"|
|20|"8626.6781"|"4768.90683931002"|"福州"|"2905"|




## 未完成 TODO

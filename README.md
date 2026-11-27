# 热搜爬虫

抓取**微博、抖音、小红书**热榜，输出统一结构的 JSON 快照。仓库自带两条发布链路：

- **实时**：用仓库内置的 Cloudflare Worker 每 10 分钟触发一次 GitHub Actions，把最新榜单发布到 GitHub Pages。
- **归档**：每小时把快照、日报和 README 提交回仓库，仓库本身就是一份可检索的热搜历史。

[![crawl](https://github.com/solarhell/hot-search-crawler/actions/workflows/crawl.yml/badge.svg)](https://github.com/solarhell/hot-search-crawler/actions/workflows/crawl.yml)
[![live](https://github.com/solarhell/hot-search-crawler/actions/workflows/live.yml/badge.svg)](https://github.com/solarhell/hot-search-crawler/actions/workflows/live.yml)

**实时 JSON**：<https://solarhell.github.io/hot-search-crawler/latest.json>

<!-- BEGIN HOTSEARCH -->
> 数据更新于 **2026-11-27 11:35**（Asia/Shanghai），展示今日榜单前 50。

### 微博

1. [中国十大最宜居城市](https://s.weibo.com/weibo?q=%E4%B8%AD%E5%9B%BD%E5%8D%81%E5%A4%A7%E6%9C%80%E5%AE%9C%E5%B1%85%E5%9F%8E%E5%B8%82) — 181.8万 · 热
2. [女子因超40岁被酒店拒办入住](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%9B%A0%E8%B6%8540%E5%B2%81%E8%A2%AB%E9%85%92%E5%BA%97%E6%8B%92%E5%8A%9E%E5%85%A5%E4%BD%8F%23) — 116.5万 · 新
3. [政府机关带头过紧日子](https://s.weibo.com/weibo?q=%E6%94%BF%E5%BA%9C%E6%9C%BA%E5%85%B3%E5%B8%A6%E5%A4%B4%E8%BF%87%E7%B4%A7%E6%97%A5%E5%AD%90) — 115.4万
4. [警方回应50余人摘蜜桔仅留下10元](https://s.weibo.com/weibo?q=%23%E8%AD%A6%E6%96%B9%E5%9B%9E%E5%BA%9450%E4%BD%99%E4%BA%BA%E6%91%98%E8%9C%9C%E6%A1%94%E4%BB%85%E7%95%99%E4%B8%8B10%E5%85%83%23) — 90.6万
5. [服务贸易发展十五五规划来了](https://s.weibo.com/weibo?q=%23%E6%9C%8D%E5%8A%A1%E8%B4%B8%E6%98%93%E5%8F%91%E5%B1%95%E5%8D%81%E4%BA%94%E4%BA%94%E8%A7%84%E5%88%92%E6%9D%A5%E4%BA%86%23) — 84.5万 · 新
6. [赖冠霖一下就get到了赵昭仪的愤怒](https://s.weibo.com/weibo?q=%23%E8%B5%96%E5%86%A0%E9%9C%96%E4%B8%80%E4%B8%8B%E5%B0%B1get%E5%88%B0%E4%BA%86%E8%B5%B5%E6%98%AD%E4%BB%AA%E7%9A%84%E6%84%A4%E6%80%92%23) — 83.5万 · 新
7. [高交会尽显中国科技创新活力](https://s.weibo.com/weibo?q=%23%E9%AB%98%E4%BA%A4%E4%BC%9A%E5%B0%BD%E6%98%BE%E4%B8%AD%E5%9B%BD%E7%A7%91%E6%8A%80%E5%88%9B%E6%96%B0%E6%B4%BB%E5%8A%9B%23) — 73.2万 · 新
8. [黄金重大变化](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E9%87%8D%E5%A4%A7%E5%8F%98%E5%8C%96%23) — 69.2万
9. [许飞这段反应可以进北影教材了](https://s.weibo.com/weibo?q=%23%E8%AE%B8%E9%A3%9E%E8%BF%99%E6%AE%B5%E5%8F%8D%E5%BA%94%E5%8F%AF%E4%BB%A5%E8%BF%9B%E5%8C%97%E5%BD%B1%E6%95%99%E6%9D%90%E4%BA%86%23) — 67.9万 · 新
10. [失去了文王才知道文王的重要性](https://s.weibo.com/weibo?q=%23%E5%A4%B1%E5%8E%BB%E4%BA%86%E6%96%87%E7%8E%8B%E6%89%8D%E7%9F%A5%E9%81%93%E6%96%87%E7%8E%8B%E7%9A%84%E9%87%8D%E8%A6%81%E6%80%A7%23) — 59.4万 · 热
11. [患者用豆包质疑医生诊断](https://s.weibo.com/weibo?q=%E6%82%A3%E8%80%85%E7%94%A8%E8%B1%86%E5%8C%85%E8%B4%A8%E7%96%91%E5%8C%BB%E7%94%9F%E8%AF%8A%E6%96%AD) — 56.7万 · 新
12. [厉娜身上有非常重的重建痕迹](https://s.weibo.com/weibo?q=%23%E5%8E%89%E5%A8%9C%E8%BA%AB%E4%B8%8A%E6%9C%89%E9%9D%9E%E5%B8%B8%E9%87%8D%E7%9A%84%E9%87%8D%E5%BB%BA%E7%97%95%E8%BF%B9%23) — 55.1万 · 新
13. [老鼠钻女老师裤子涉事账号已设为私密](https://s.weibo.com/weibo?q=%23%E8%80%81%E9%BC%A0%E9%92%BB%E5%A5%B3%E8%80%81%E5%B8%88%E8%A3%A4%E5%AD%90%E6%B6%89%E4%BA%8B%E8%B4%A6%E5%8F%B7%E5%B7%B2%E8%AE%BE%E4%B8%BA%E7%A7%81%E5%AF%86%23) — 48.7万 · 新
14. [Viper跟观众告别](https://s.weibo.com/weibo?q=%23Viper%E8%B7%9F%E8%A7%82%E4%BC%97%E5%91%8A%E5%88%AB%23) — 46.3万 · 新
15. [曾经80万的车现在卖5万](https://s.weibo.com/weibo?q=%E6%9B%BE%E7%BB%8F80%E4%B8%87%E7%9A%84%E8%BD%A6%E7%8E%B0%E5%9C%A8%E5%8D%965%E4%B8%87) — 33.8万 · 新
16. [三只松鼠致歉声明](https://s.weibo.com/weibo?q=%23%E4%B8%89%E5%8F%AA%E6%9D%BE%E9%BC%A0%E8%87%B4%E6%AD%89%E5%A3%B0%E6%98%8E%23) — 32万 · 热
17. [赵昭仪曝被导演开黄腔](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E6%98%AD%E4%BB%AA%E6%9B%9D%E8%A2%AB%E5%AF%BC%E6%BC%94%E5%BC%80%E9%BB%84%E8%85%94%23) — 32万 · 新
18. [怀孕本质是你一个人的事](https://s.weibo.com/weibo?q=%E6%80%80%E5%AD%95%E6%9C%AC%E8%B4%A8%E6%98%AF%E4%BD%A0%E4%B8%80%E4%B8%AA%E4%BA%BA%E7%9A%84%E4%BA%8B) — 31.9万 · 热
19. [三只松鼠员工必须用鼠取名](https://s.weibo.com/weibo?q=%E4%B8%89%E5%8F%AA%E6%9D%BE%E9%BC%A0%E5%91%98%E5%B7%A5%E5%BF%85%E9%A1%BB%E7%94%A8%E9%BC%A0%E5%8F%96%E5%90%8D) — 31.7万 · 热
20. [许飞 那你们今天岂不是心碎了](https://s.weibo.com/weibo?q=%E8%AE%B8%E9%A3%9E+%E9%82%A3%E4%BD%A0%E4%BB%AC%E4%BB%8A%E5%A4%A9%E5%B2%82%E4%B8%8D%E6%98%AF%E5%BF%83%E7%A2%8E%E4%BA%86) — 31.6万 · 新
21. [青稚两连FMVP](https://s.weibo.com/weibo?q=%23%E9%9D%92%E7%A8%9A%E4%B8%A4%E8%BF%9EFMVP%23) — 31.3万
22. [50余人摘走数百斤橘子仅留下10元](https://s.weibo.com/weibo?q=%2350%E4%BD%99%E4%BA%BA%E6%91%98%E8%B5%B0%E6%95%B0%E7%99%BE%E6%96%A4%E6%A9%98%E5%AD%90%E4%BB%85%E7%95%99%E4%B8%8B10%E5%85%83%23) — 31.3万 · 新
23. [厉娜明显不高兴了](https://s.weibo.com/weibo?q=%23%E5%8E%89%E5%A8%9C%E6%98%8E%E6%98%BE%E4%B8%8D%E9%AB%98%E5%85%B4%E4%BA%86%23) — 30.7万 · 综艺
24. [圣枪哥再一次和Viper告别](https://s.weibo.com/weibo?q=%23%E5%9C%A3%E6%9E%AA%E5%93%A5%E5%86%8D%E4%B8%80%E6%AC%A1%E5%92%8CViper%E5%91%8A%E5%88%AB%23) — 30.2万 · 新
25. [郭士强说下场对黎巴嫩很重要](https://s.weibo.com/weibo?q=%23%E9%83%AD%E5%A3%AB%E5%BC%BA%E8%AF%B4%E4%B8%8B%E5%9C%BA%E5%AF%B9%E9%BB%8E%E5%B7%B4%E5%AB%A9%E5%BE%88%E9%87%8D%E8%A6%81%23) — 29.8万 · 新
26. [中国男篮曾98比10胜沙特](https://s.weibo.com/weibo?q=%E4%B8%AD%E5%9B%BD%E7%94%B7%E7%AF%AE%E6%9B%BE98%E6%AF%9410%E8%83%9C%E6%B2%99%E7%89%B9) — 29.3万
27. [女生投诉全季早餐有异物被找到导员](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%94%9F%E6%8A%95%E8%AF%89%E5%85%A8%E5%AD%A3%E6%97%A9%E9%A4%90%E6%9C%89%E5%BC%82%E7%89%A9%E8%A2%AB%E6%89%BE%E5%88%B0%E5%AF%BC%E5%91%98%23) — 28.2万 · 新
28. [特朗普钟爱无糖健怡可乐](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E9%92%9F%E7%88%B1%E6%97%A0%E7%B3%96%E5%81%A5%E6%80%A1%E5%8F%AF%E4%B9%90%23) — 27.8万 · 新
29. [王子璇文吉儿在节目中的作用](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AD%90%E7%92%87%E6%96%87%E5%90%89%E5%84%BF%E5%9C%A8%E8%8A%82%E7%9B%AE%E4%B8%AD%E7%9A%84%E4%BD%9C%E7%94%A8%23) — 27.5万
30. [杨蓉遗传病暂无根治手段](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E8%93%89%E9%81%97%E4%BC%A0%E7%97%85%E6%9A%82%E6%97%A0%E6%A0%B9%E6%B2%BB%E6%89%8B%E6%AE%B5%23) — 27.3万 · 新
31. [外媒称赞国足出了中国伊布](https://s.weibo.com/weibo?q=%23%E5%A4%96%E5%AA%92%E7%A7%B0%E8%B5%9E%E5%9B%BD%E8%B6%B3%E5%87%BA%E4%BA%86%E4%B8%AD%E5%9B%BD%E4%BC%8A%E5%B8%83%23) — 27.1万 · 新
32. [许飞这是人能承受的痛苦吗](https://s.weibo.com/weibo?q=%23%E8%AE%B8%E9%A3%9E%E8%BF%99%E6%98%AF%E4%BA%BA%E8%83%BD%E6%89%BF%E5%8F%97%E7%9A%84%E7%97%9B%E8%8B%A6%E5%90%97%23) — 26.9万 · 新
33. [今起电视开机广告没了](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E8%B5%B7%E7%94%B5%E8%A7%86%E5%BC%80%E6%9C%BA%E5%B9%BF%E5%91%8A%E6%B2%A1%E4%BA%86%23) — 26.5万 · 新
34. [A股明年或迎春天](https://s.weibo.com/weibo?q=%23A%E8%82%A1%E6%98%8E%E5%B9%B4%E6%88%96%E8%BF%8E%E6%98%A5%E5%A4%A9%23) — 26.3万
35. [海康威视取消大小周遭员工抵制](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E5%BA%B7%E5%A8%81%E8%A7%86%E5%8F%96%E6%B6%88%E5%A4%A7%E5%B0%8F%E5%91%A8%E9%81%AD%E5%91%98%E5%B7%A5%E6%8A%B5%E5%88%B6%23) — 23.1万 · 新
36. [别把豆包当医生](https://s.weibo.com/weibo?q=%23%E5%88%AB%E6%8A%8A%E8%B1%86%E5%8C%85%E5%BD%93%E5%8C%BB%E7%94%9F%23) — 22.6万 · 新
37. [徐璐身材](https://s.weibo.com/weibo?q=%E5%BE%90%E7%92%90%E8%BA%AB%E6%9D%90) — 22.2万
38. [长期炎症是至少8种癌症的帮凶](https://s.weibo.com/weibo?q=%23%E9%95%BF%E6%9C%9F%E7%82%8E%E7%97%87%E6%98%AF%E8%87%B3%E5%B0%918%E7%A7%8D%E7%99%8C%E7%97%87%E7%9A%84%E5%B8%AE%E5%87%B6%23) — 21.5万
39. [王楚然全世界最尊重冬天穿搭之人](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E5%85%A8%E4%B8%96%E7%95%8C%E6%9C%80%E5%B0%8A%E9%87%8D%E5%86%AC%E5%A4%A9%E7%A9%BF%E6%90%AD%E4%B9%8B%E4%BA%BA%23) — 21.5万 · 新
40. [爱情公寓众人月薪](https://s.weibo.com/weibo?q=%23%E7%88%B1%E6%83%85%E5%85%AC%E5%AF%93%E4%BC%97%E4%BA%BA%E6%9C%88%E8%96%AA%23) — 21.1万 · 剧集
41. [ON也舍不得Viper](https://s.weibo.com/weibo?q=%23ON%E4%B9%9F%E8%88%8D%E4%B8%8D%E5%BE%97Viper%23) — 19.5万
42. [明日方舟](https://s.weibo.com/weibo?q=%E6%98%8E%E6%97%A5%E6%96%B9%E8%88%9F) — 19.2万 · 新
43. [中纪委一天连打三虎](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E7%BA%AA%E5%A7%94%E4%B8%80%E5%A4%A9%E8%BF%9E%E6%89%93%E4%B8%89%E8%99%8E%23) — 18.8万
44. [从5到24看载人航天之路](https://s.weibo.com/weibo?q=%23%E4%BB%8E5%E5%88%B024%E7%9C%8B%E8%BD%BD%E4%BA%BA%E8%88%AA%E5%A4%A9%E4%B9%8B%E8%B7%AF%23) — 18.4万
45. [厉娜远远没有麦琳承受的多](https://s.weibo.com/weibo?q=%23%E5%8E%89%E5%A8%9C%E8%BF%9C%E8%BF%9C%E6%B2%A1%E6%9C%89%E9%BA%A6%E7%90%B3%E6%89%BF%E5%8F%97%E7%9A%84%E5%A4%9A%23) — 18.4万 · 热
46. [许飞口碑](https://s.weibo.com/weibo?q=%E8%AE%B8%E9%A3%9E%E5%8F%A3%E7%A2%91) — 18.3万
47. [乙肝药功能性治愈终点获批](https://s.weibo.com/weibo?q=%E4%B9%99%E8%82%9D%E8%8D%AF%E5%8A%9F%E8%83%BD%E6%80%A7%E6%B2%BB%E6%84%88%E7%BB%88%E7%82%B9%E8%8E%B7%E6%89%B9) — 18万 · 新
48. [文吉儿不止邀请过王子璇](https://s.weibo.com/weibo?q=%23%E6%96%87%E5%90%89%E5%84%BF%E4%B8%8D%E6%AD%A2%E9%82%80%E8%AF%B7%E8%BF%87%E7%8E%8B%E5%AD%90%E7%92%87%23) — 17.8万 · 新
49. [胡明轩 中国男篮](https://s.weibo.com/weibo?q=%E8%83%A1%E6%98%8E%E8%BD%A9+%E4%B8%AD%E5%9B%BD%E7%94%B7%E7%AF%AE) — 16.8万 · 新
50. [U17国足8比0斐济](https://s.weibo.com/weibo?q=U17%E5%9B%BD%E8%B6%B38%E6%AF%940%E6%96%90%E6%B5%8E) — 16.6万 · 新

### 抖音

1. [U17国足迎战斐济争出线](https://www.douyin.com/search/U17%E5%9B%BD%E8%B6%B3%E8%BF%8E%E6%88%98%E6%96%90%E6%B5%8E%E4%BA%89%E5%87%BA%E7%BA%BF) — 1202万
2. [中国男篮80:82不敌沙特男篮](https://www.douyin.com/search/%E4%B8%AD%E5%9B%BD%E7%94%B7%E7%AF%AE80:82%E4%B8%8D%E6%95%8C%E6%B2%99%E7%89%B9%E7%94%B7%E7%AF%AE) — 1141.5万
3. [2026世界市长对话乌鲁木齐](https://www.douyin.com/search/2026%E4%B8%96%E7%95%8C%E5%B8%82%E9%95%BF%E5%AF%B9%E8%AF%9D%E4%B9%8C%E9%B2%81%E6%9C%A8%E9%BD%90) — 1140.4万
4. [U17国足8:0斐济](https://www.douyin.com/search/U17%E5%9B%BD%E8%B6%B38:0%E6%96%90%E6%B5%8E) — 1135.3万
5. [我国将加快培育服务贸易发展新动能](https://www.douyin.com/search/%E6%88%91%E5%9B%BD%E5%B0%86%E5%8A%A0%E5%BF%AB%E5%9F%B9%E8%82%B2%E6%9C%8D%E5%8A%A1%E8%B4%B8%E6%98%93%E5%8F%91%E5%B1%95%E6%96%B0%E5%8A%A8%E8%83%BD) — 1105.4万
6. [评论区摄影作品点评大赛开启](https://www.douyin.com/search/%E8%AF%84%E8%AE%BA%E5%8C%BA%E6%91%84%E5%BD%B1%E4%BD%9C%E5%93%81%E7%82%B9%E8%AF%84%E5%A4%A7%E8%B5%9B%E5%BC%80%E5%90%AF) — 1097.7万
7. [巴航天员进驻天宫进入工作状态](https://www.douyin.com/search/%E5%B7%B4%E8%88%AA%E5%A4%A9%E5%91%98%E8%BF%9B%E9%A9%BB%E5%A4%A9%E5%AE%AB%E8%BF%9B%E5%85%A5%E5%B7%A5%E4%BD%9C%E7%8A%B6%E6%80%81) — 1093.7万
8. [中方回应美国称对华加征关税](https://www.douyin.com/search/%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E7%BE%8E%E5%9B%BD%E7%A7%B0%E5%AF%B9%E5%8D%8E%E5%8A%A0%E5%BE%81%E5%85%B3%E7%A8%8E) — 1036.8万
9. [普通人冬日彩色穿搭公式](https://www.douyin.com/search/%E6%99%AE%E9%80%9A%E4%BA%BA%E5%86%AC%E6%97%A5%E5%BD%A9%E8%89%B2%E7%A9%BF%E6%90%AD%E5%85%AC%E5%BC%8F) — 1033万
10. [张堃鹏张泰艺台球大奖赛晋级](https://www.douyin.com/search/%E5%BC%A0%E5%A0%83%E9%B9%8F%E5%BC%A0%E6%B3%B0%E8%89%BA%E5%8F%B0%E7%90%83%E5%A4%A7%E5%A5%96%E8%B5%9B%E6%99%8B%E7%BA%A7) — 1031.2万
11. [中方：日方应还中国人民以净土](https://www.douyin.com/search/%E4%B8%AD%E6%96%B9%EF%BC%9A%E6%97%A5%E6%96%B9%E5%BA%94%E8%BF%98%E4%B8%AD%E5%9B%BD%E4%BA%BA%E6%B0%91%E4%BB%A5%E5%87%80%E5%9C%9F) — 1016.2万
12. [清迈的天灯节也太美了吧](https://www.douyin.com/search/%E6%B8%85%E8%BF%88%E7%9A%84%E5%A4%A9%E7%81%AF%E8%8A%82%E4%B9%9F%E5%A4%AA%E7%BE%8E%E4%BA%86%E5%90%A7) — 1010.7万
13. [冬日冷感忧郁穿搭](https://www.douyin.com/search/%E5%86%AC%E6%97%A5%E5%86%B7%E6%84%9F%E5%BF%A7%E9%83%81%E7%A9%BF%E6%90%AD) — 906.9万
14. [特朗普念念不忘帽子菜可能是它](https://www.douyin.com/search/%E7%89%B9%E6%9C%97%E6%99%AE%E5%BF%B5%E5%BF%B5%E4%B8%8D%E5%BF%98%E5%B8%BD%E5%AD%90%E8%8F%9C%E5%8F%AF%E8%83%BD%E6%98%AF%E5%AE%83) — 902.9万
15. [武大通报教师曾某某被举报事件](https://www.douyin.com/search/%E6%AD%A6%E5%A4%A7%E9%80%9A%E6%8A%A5%E6%95%99%E5%B8%88%E6%9B%BE%E6%9F%90%E6%9F%90%E8%A2%AB%E4%B8%BE%E6%8A%A5%E4%BA%8B%E4%BB%B6) — 888.8万
16. [羊年贵金属纪念币今日发行](https://www.douyin.com/search/%E7%BE%8A%E5%B9%B4%E8%B4%B5%E9%87%91%E5%B1%9E%E7%BA%AA%E5%BF%B5%E5%B8%81%E4%BB%8A%E6%97%A5%E5%8F%91%E8%A1%8C) — 882.5万
17. [已被这届烟火榜美食选中](https://www.douyin.com/search/%E5%B7%B2%E8%A2%AB%E8%BF%99%E5%B1%8A%E7%83%9F%E7%81%AB%E6%A6%9C%E7%BE%8E%E9%A3%9F%E9%80%89%E4%B8%AD) — 878.7万
18. [弦乐版传奇是我的年终进行曲](https://www.douyin.com/search/%E5%BC%A6%E4%B9%90%E7%89%88%E4%BC%A0%E5%A5%87%E6%98%AF%E6%88%91%E7%9A%84%E5%B9%B4%E7%BB%88%E8%BF%9B%E8%A1%8C%E6%9B%B2) — 871.6万
19. [国防部回应“重塑台海安全态势”](https://www.douyin.com/search/%E5%9B%BD%E9%98%B2%E9%83%A8%E5%9B%9E%E5%BA%94%E2%80%9C%E9%87%8D%E5%A1%91%E5%8F%B0%E6%B5%B7%E5%AE%89%E5%85%A8%E6%80%81%E5%8A%BF%E2%80%9D) — 862.1万
20. [2026广州车展新车抢先看](https://www.douyin.com/search/2026%E5%B9%BF%E5%B7%9E%E8%BD%A6%E5%B1%95%E6%96%B0%E8%BD%A6%E6%8A%A2%E5%85%88%E7%9C%8B) — 853.9万
21. [提前预习圣诞穿搭](https://www.douyin.com/search/%E6%8F%90%E5%89%8D%E9%A2%84%E4%B9%A0%E5%9C%A3%E8%AF%9E%E7%A9%BF%E6%90%AD) — 850.3万
22. [求职季这些风险要避开](https://www.douyin.com/search/%E6%B1%82%E8%81%8C%E5%AD%A3%E8%BF%99%E4%BA%9B%E9%A3%8E%E9%99%A9%E8%A6%81%E9%81%BF%E5%BC%80) — 843.5万
23. [欧联奥林匹亚科斯不敌AC米兰](https://www.douyin.com/search/%E6%AC%A7%E8%81%94%E5%A5%A5%E6%9E%97%E5%8C%B9%E4%BA%9A%E7%A7%91%E6%96%AF%E4%B8%8D%E6%95%8CAC%E7%B1%B3%E5%85%B0) — 838.1万
24. [韩国央行加息25个基点](https://www.douyin.com/search/%E9%9F%A9%E5%9B%BD%E5%A4%AE%E8%A1%8C%E5%8A%A0%E6%81%AF25%E4%B8%AA%E5%9F%BA%E7%82%B9) — 804.9万
25. [换我画地为牢了](https://www.douyin.com/search/%E6%8D%A2%E6%88%91%E7%94%BB%E5%9C%B0%E4%B8%BA%E7%89%A2%E4%BA%86) — 786万
26. [第一次拥抱你 那时你也才二十几](https://www.douyin.com/search/%E7%AC%AC%E4%B8%80%E6%AC%A1%E6%8B%A5%E6%8A%B1%E4%BD%A0%20%E9%82%A3%E6%97%B6%E4%BD%A0%E4%B9%9F%E6%89%8D%E4%BA%8C%E5%8D%81%E5%87%A0) — 785.3万
27. [两京十五日轮到我登场](https://www.douyin.com/search/%E4%B8%A4%E4%BA%AC%E5%8D%81%E4%BA%94%E6%97%A5%E8%BD%AE%E5%88%B0%E6%88%91%E7%99%BB%E5%9C%BA) — 782.9万
28. [同频朋友是最好的生日礼物](https://www.douyin.com/search/%E5%90%8C%E9%A2%91%E6%9C%8B%E5%8F%8B%E6%98%AF%E6%9C%80%E5%A5%BD%E7%9A%84%E7%94%9F%E6%97%A5%E7%A4%BC%E7%89%A9) — 777.8万
29. [用这首松花晒出家乡](https://www.douyin.com/search/%E7%94%A8%E8%BF%99%E9%A6%96%E6%9D%BE%E8%8A%B1%E6%99%92%E5%87%BA%E5%AE%B6%E4%B9%A1) — 777.2万
30. [淡人一周穿搭合集](https://www.douyin.com/search/%E6%B7%A1%E4%BA%BA%E4%B8%80%E5%91%A8%E7%A9%BF%E6%90%AD%E5%90%88%E9%9B%86) — 777.1万
31. [电视剧风生水起开播](https://www.douyin.com/search/%E7%94%B5%E8%A7%86%E5%89%A7%E9%A3%8E%E7%94%9F%E6%B0%B4%E8%B5%B7%E5%BC%80%E6%92%AD) — 777万
32. [蔡磊回应病情进入终末期](https://www.douyin.com/search/%E8%94%A1%E7%A3%8A%E5%9B%9E%E5%BA%94%E7%97%85%E6%83%85%E8%BF%9B%E5%85%A5%E7%BB%88%E6%9C%AB%E6%9C%9F) — 777万
33. [解锁冬日cleanfit穿搭](https://www.douyin.com/search/%E8%A7%A3%E9%94%81%E5%86%AC%E6%97%A5cleanfit%E7%A9%BF%E6%90%AD) — 774.1万
34. [欧联奥林匹亚科斯vsAC米兰](https://www.douyin.com/search/%E6%AC%A7%E8%81%94%E5%A5%A5%E6%9E%97%E5%8C%B9%E4%BA%9A%E7%A7%91%E6%96%AFvsAC%E7%B1%B3%E5%85%B0) — 772.9万
35. [魔方新游狩线下试玩体验](https://www.douyin.com/search/%E9%AD%94%E6%96%B9%E6%96%B0%E6%B8%B8%E7%8B%A9%E7%BA%BF%E4%B8%8B%E8%AF%95%E7%8E%A9%E4%BD%93%E9%AA%8C) — 772.9万
36. [律师解读马天宇想把遗产分给朋友](https://www.douyin.com/search/%E5%BE%8B%E5%B8%88%E8%A7%A3%E8%AF%BB%E9%A9%AC%E5%A4%A9%E5%AE%87%E6%83%B3%E6%8A%8A%E9%81%97%E4%BA%A7%E5%88%86%E7%BB%99%E6%9C%8B%E5%8F%8B) — 772.6万
37. [一条视频看懂后会友期第七期](https://www.douyin.com/search/%E4%B8%80%E6%9D%A1%E8%A7%86%E9%A2%91%E7%9C%8B%E6%87%82%E5%90%8E%E4%BC%9A%E5%8F%8B%E6%9C%9F%E7%AC%AC%E4%B8%83%E6%9C%9F) — 772.1万
38. [央视网评金价大跌下的购金热](https://www.douyin.com/search/%E5%A4%AE%E8%A7%86%E7%BD%91%E8%AF%84%E9%87%91%E4%BB%B7%E5%A4%A7%E8%B7%8C%E4%B8%8B%E7%9A%84%E8%B4%AD%E9%87%91%E7%83%AD) — 772万
39. [快过年了我先跳个恭喜发财舞](https://www.douyin.com/search/%E5%BF%AB%E8%BF%87%E5%B9%B4%E4%BA%86%E6%88%91%E5%85%88%E8%B7%B3%E4%B8%AA%E6%81%AD%E5%96%9C%E5%8F%91%E8%B4%A2%E8%88%9E) — 771.6万
40. [冰封玫瑰是哈尔滨冬日独有的浪漫](https://www.douyin.com/search/%E5%86%B0%E5%B0%81%E7%8E%AB%E7%91%B0%E6%98%AF%E5%93%88%E5%B0%94%E6%BB%A8%E5%86%AC%E6%97%A5%E7%8B%AC%E6%9C%89%E7%9A%84%E6%B5%AA%E6%BC%AB) — 770.6万
41. [这只修狗有点吵](https://www.douyin.com/search/%E8%BF%99%E5%8F%AA%E4%BF%AE%E7%8B%97%E6%9C%89%E7%82%B9%E5%90%B5) — 770.6万
42. [北京也有网红咒语糖葫芦](https://www.douyin.com/search/%E5%8C%97%E4%BA%AC%E4%B9%9F%E6%9C%89%E7%BD%91%E7%BA%A2%E5%92%92%E8%AF%AD%E7%B3%96%E8%91%AB%E8%8A%A6) — 770.2万
43. [两京十五日1516集封神](https://www.douyin.com/search/%E4%B8%A4%E4%BA%AC%E5%8D%81%E4%BA%94%E6%97%A51516%E9%9B%86%E5%B0%81%E7%A5%9E) — 769.7万
44. [不为人知的故事首播观后感](https://www.douyin.com/search/%E4%B8%8D%E4%B8%BA%E4%BA%BA%E7%9F%A5%E7%9A%84%E6%95%85%E4%BA%8B%E9%A6%96%E6%92%AD%E8%A7%82%E5%90%8E%E6%84%9F) — 769.6万
45. [一碗面召唤许凯挑战](https://www.douyin.com/search/%E4%B8%80%E7%A2%97%E9%9D%A2%E5%8F%AC%E5%94%A4%E8%AE%B8%E5%87%AF%E6%8C%91%E6%88%98) — 769.6万
46. [我找到了厉娜许飞的留言本](https://www.douyin.com/search/%E6%88%91%E6%89%BE%E5%88%B0%E4%BA%86%E5%8E%89%E5%A8%9C%E8%AE%B8%E9%A3%9E%E7%9A%84%E7%95%99%E8%A8%80%E6%9C%AC) — 769.4万
47. [2026贺岁档超50部影片定档](https://www.douyin.com/search/2026%E8%B4%BA%E5%B2%81%E6%A1%A3%E8%B6%8550%E9%83%A8%E5%BD%B1%E7%89%87%E5%AE%9A%E6%A1%A3) — 768.7万
48. [中宣部原副部长蔡赴朝被开除党籍](https://www.douyin.com/search/%E4%B8%AD%E5%AE%A3%E9%83%A8%E5%8E%9F%E5%89%AF%E9%83%A8%E9%95%BF%E8%94%A1%E8%B5%B4%E6%9C%9D%E8%A2%AB%E5%BC%80%E9%99%A4%E5%85%9A%E7%B1%8D) — 768.3万
49. [天南地北我在各地赏雪](https://www.douyin.com/search/%E5%A4%A9%E5%8D%97%E5%9C%B0%E5%8C%97%E6%88%91%E5%9C%A8%E5%90%84%E5%9C%B0%E8%B5%8F%E9%9B%AA) — 768万
50. [国际油价拉升](https://www.douyin.com/search/%E5%9B%BD%E9%99%85%E6%B2%B9%E4%BB%B7%E6%8B%89%E5%8D%87) — 767.7万

### 小红书

1. [用万能旅行拍照姿势美美出片](https://www.xiaohongshu.com/search_result?keyword=%E7%94%A8%E4%B8%87%E8%83%BD%E6%97%85%E8%A1%8C%E6%8B%8D%E7%85%A7%E5%A7%BF%E5%8A%BF%E7%BE%8E%E7%BE%8E%E5%87%BA%E7%89%87) — 947.5万 · 热
2. [耗时三年拍下古诗词里的中国](https://www.xiaohongshu.com/search_result?keyword=%E8%80%97%E6%97%B6%E4%B8%89%E5%B9%B4%E6%8B%8D%E4%B8%8B%E5%8F%A4%E8%AF%97%E8%AF%8D%E9%87%8C%E7%9A%84%E4%B8%AD%E5%9B%BD) — 934.8万 · 热
3. [我拍到了海鸥雨](https://www.xiaohongshu.com/search_result?keyword=%E6%88%91%E6%8B%8D%E5%88%B0%E4%BA%86%E6%B5%B7%E9%B8%A5%E9%9B%A8) — 903.2万
4. [超日常美食教程速来get](https://www.xiaohongshu.com/search_result?keyword=%E8%B6%85%E6%97%A5%E5%B8%B8%E7%BE%8E%E9%A3%9F%E6%95%99%E7%A8%8B%E9%80%9F%E6%9D%A5get) — 886万
5. [定格这一刻的日照金山](https://www.xiaohongshu.com/search_result?keyword=%E5%AE%9A%E6%A0%BC%E8%BF%99%E4%B8%80%E5%88%BB%E7%9A%84%E6%97%A5%E7%85%A7%E9%87%91%E5%B1%B1) — 871.1万
6. [你可以永远相信赛里木湖的美景](https://www.xiaohongshu.com/search_result?keyword=%E4%BD%A0%E5%8F%AF%E4%BB%A5%E6%B0%B8%E8%BF%9C%E7%9B%B8%E4%BF%A1%E8%B5%9B%E9%87%8C%E6%9C%A8%E6%B9%96%E7%9A%84%E7%BE%8E%E6%99%AF) — 783.1万 · 热
7. [拼豆上也可以作画了](https://www.xiaohongshu.com/search_result?keyword=%E6%8B%BC%E8%B1%86%E4%B8%8A%E4%B9%9F%E5%8F%AF%E4%BB%A5%E4%BD%9C%E7%94%BB%E4%BA%86) — 749.8万 · 热
8. [我的家庭旅行更像是打副本](https://www.xiaohongshu.com/search_result?keyword=%E6%88%91%E7%9A%84%E5%AE%B6%E5%BA%AD%E6%97%85%E8%A1%8C%E6%9B%B4%E5%83%8F%E6%98%AF%E6%89%93%E5%89%AF%E6%9C%AC) — 737.1万
9. [原来古诗词里的河南真的存在](https://www.xiaohongshu.com/search_result?keyword=%E5%8E%9F%E6%9D%A5%E5%8F%A4%E8%AF%97%E8%AF%8D%E9%87%8C%E7%9A%84%E6%B2%B3%E5%8D%97%E7%9C%9F%E7%9A%84%E5%AD%98%E5%9C%A8) — 727.8万 · 热
10. [蒸出了奶香爆米花馒头](https://www.xiaohongshu.com/search_result?keyword=%E8%92%B8%E5%87%BA%E4%BA%86%E5%A5%B6%E9%A6%99%E7%88%86%E7%B1%B3%E8%8A%B1%E9%A6%92%E5%A4%B4) — 716.2万 · 热
11. [这可能是江西最被低估的一座山](https://www.xiaohongshu.com/search_result?keyword=%E8%BF%99%E5%8F%AF%E8%83%BD%E6%98%AF%E6%B1%9F%E8%A5%BF%E6%9C%80%E8%A2%AB%E4%BD%8E%E4%BC%B0%E7%9A%84%E4%B8%80%E5%BA%A7%E5%B1%B1) — 703万
12. [海边日落赴一场温柔约会](https://www.xiaohongshu.com/search_result?keyword=%E6%B5%B7%E8%BE%B9%E6%97%A5%E8%90%BD%E8%B5%B4%E4%B8%80%E5%9C%BA%E6%B8%A9%E6%9F%94%E7%BA%A6%E4%BC%9A) — 689.4万 · 热
13. [拼豆也能当火漆印章玩](https://www.xiaohongshu.com/search_result?keyword=%E6%8B%BC%E8%B1%86%E4%B9%9F%E8%83%BD%E5%BD%93%E7%81%AB%E6%BC%86%E5%8D%B0%E7%AB%A0%E7%8E%A9) — 241.7万
14. [我创造了新型遛狗法](https://www.xiaohongshu.com/search_result?keyword=%E6%88%91%E5%88%9B%E9%80%A0%E4%BA%86%E6%96%B0%E5%9E%8B%E9%81%9B%E7%8B%97%E6%B3%95) — 231.8万 · 热
15. [用镜头捕捉四季如画](https://www.xiaohongshu.com/search_result?keyword=%E7%94%A8%E9%95%9C%E5%A4%B4%E6%8D%95%E6%8D%89%E5%9B%9B%E5%AD%A3%E5%A6%82%E7%94%BB) — 222.8万 · 热
16. [笔墨重现课本诗意](https://www.xiaohongshu.com/search_result?keyword=%E7%AC%94%E5%A2%A8%E9%87%8D%E7%8E%B0%E8%AF%BE%E6%9C%AC%E8%AF%97%E6%84%8F) — 213.5万
17. [拍到了洱海的丁达尔效应](https://www.xiaohongshu.com/search_result?keyword=%E6%8B%8D%E5%88%B0%E4%BA%86%E6%B4%B1%E6%B5%B7%E7%9A%84%E4%B8%81%E8%BE%BE%E5%B0%94%E6%95%88%E5%BA%94) — 203.3万 · 热
18. [珠圆玉润妆完全是淡颜天菜](https://www.xiaohongshu.com/search_result?keyword=%E7%8F%A0%E5%9C%86%E7%8E%89%E6%B6%A6%E5%A6%86%E5%AE%8C%E5%85%A8%E6%98%AF%E6%B7%A1%E9%A2%9C%E5%A4%A9%E8%8F%9C) — 193.8万 · 热
19. [碎钻美甲指尖藏着细碎星光](https://www.xiaohongshu.com/search_result?keyword=%E7%A2%8E%E9%92%BB%E7%BE%8E%E7%94%B2%E6%8C%87%E5%B0%96%E8%97%8F%E7%9D%80%E7%BB%86%E7%A2%8E%E6%98%9F%E5%85%89) — 184.5万
20. [我来当旅行中的颜色猎手](https://www.xiaohongshu.com/search_result?keyword=%E6%88%91%E6%9D%A5%E5%BD%93%E6%97%85%E8%A1%8C%E4%B8%AD%E7%9A%84%E9%A2%9C%E8%89%B2%E7%8C%8E%E6%89%8B) — 175.7万 · 热

[完整快照](data/latest-hourly.json) · [今日归档](archives/2026-11-27.md)
<!-- END HOTSEARCH -->

## 特性

- **三个平台，一种结构**：微博、抖音、小红书统一为 `rank / title / url / hot / tag`，平台特有字段放进 `extra`。
- **实时与归档分离**：高频运行只发布 Pages 的 `latest.json`，不写 git；每小时才落一份归档（最新归档快照为 `data/latest-hourly.json`），避免仓库历史膨胀。
- **过滤广告**：微博接口里混在 `realtime` 中的推广位（`is_ad=1`）会被剔除，不占榜单名次。
- **限流友好**：识别小红书 `300013` 限流码，不连续重试；普通失败按 2s → 4s → 8s 指数退避。
- **零数据库依赖**：默认写文件，可直接用 GitHub Pages、对象存储或任意静态服务消费。
- **可持续归档**：小时快照 + 按天重建的 `summary.json` + 每日 Markdown 归档，重复运行或补抓都不会污染统计。
- **常驻模式**：`daemon` 子命令按间隔运行，连续失败时自动退避到 15 分钟。

## 快速开始

需要 Go 1.27+。

```bash
git clone https://github.com/solarhell/hot-search-crawler.git
cd hot-search-crawler

# 抓取一次，并更新 README 里的今日热榜
go run ./cmd/hot-search-crawler crawl --update-readme

# 只看看当前数据，不落盘
go run ./cmd/hot-search-crawler crawl --dry-run

# 只生成实时 JSON（用于 Pages 发布，不写小时快照/日报）
go run ./cmd/hot-search-crawler crawl --live --data dist
```

也可以直接安装：

```bash
go install github.com/solarhell/hot-search-crawler/cmd/hot-search-crawler@latest
```

构建二进制：

```bash
go build -o bin/hot-search-crawler ./cmd/hot-search-crawler
./bin/hot-search-crawler crawl
```

## 输出结构

```text
data/
  2026-10-30/
    09.json          # 每小时一次完整抓取（含各平台成功/失败状态）
    10.json
    summary.json     # 当天聚合：最高热度、最好名次、在榜次数、首次/最后出现
  latest-hourly.json # 最近一次小时归档快照；实时数据见 GitHub Pages
archives/
  2026-10-30.md      # 当天热榜 Markdown 归档
README.md            # 标记区间内的今日热榜
```

小时快照：

```json
{
  "schema_version": 1,
  "generated_at": "2026-10-30T09:32:05+08:00",
  "timezone": "Asia/Shanghai",
  "boards": [
    {
      "platform": "weibo",
      "name": "微博",
      "ok": true,
      "fetched_at": "2026-10-30T09:32:05+08:00",
      "elapsed_ms": 126,
      "items": [
        {
          "rank": 1,
          "title": "TES战胜BLG",
          "url": "https://s.weibo.com/weibo?q=TES%E6%88%98%E8%83%9CBLG",
          "hot": 1748429,
          "tag": "新"
        }
      ]
    }
  ]
}
```

抓取失败的平台也会保留在快照里，`ok` 为 `false`，`error` 写原因，`items` 为空数组。单个平台失败不会影响其他平台。

小红书等平台的热度是 `"947.5w"` 这样的文本，`hot` 会归一化成 `9475000`，同时用 `hot_text` 保留原始值。

## 平台说明

| 平台 | 接口 | 热度字段 | 备注 |
| --- | --- | --- | --- |
| 微博 | `weibo.com/ajax/side/hotSearch` | `num` | 使用 Chrome TLS 指纹；过滤 `is_ad=1` |
| 抖音 | `aweme.snssdk.com/aweme/v1/hot/search/list/` | `hot_value` | 只取 `word_list`，不混入“实时上升热点” |
| 小红书 | `edith.xiaohongshu.com/api/sns/v1/search/hot_list` | `score`（`947.5w`） | 复用固定 iOS 设备指纹，可能被限流 |

小红书没有公开热榜接口，`internal/source/xiaohongshu.go` 中的请求头来自客户端抓包。同一设备指纹被间歇性拒绝（`300013`）是常态，程序会按限流处理并保留其他平台的数据。指纹可能随客户端升级失效，届时需要重新抓包，或用 `--sources weibo,douyin` 暂时关闭小红书。

## 命令行

```text
hot-search-crawler crawl [flags]     抓取一次
hot-search-crawler daemon [flags]    常驻定时抓取
hot-search-crawler sources           列出内置平台
hot-search-crawler version           显示版本
```

常用参数：

| 参数 | 默认值 | 说明 |
| --- | --- | --- |
| `--sources` | `weibo,douyin,xiaohongshu` | 启用的平台，逗号分隔 |
| `--top` | `20` | 每个平台保留的条数 |
| `--data` | `data` | 小时快照目录 |
| `--archives` | `archives` | 每日 Markdown 归档目录 |
| `--readme` | `README.md` | README 路径 |
| `--update-readme` | `false` | 把今日热榜写入 README |
| `--live` | `false` | 只写实时 `latest.json`，不生成小时快照/日报/README |
| `--dry-run` | `false` | 只输出快照 JSON，不写文件 |
| `--timeout` | `25s` | 单次请求超时 |
| `--retries` | `2` | 普通失败的重试次数（限流不重试） |
| `--interval` | `30m` | 仅 `daemon`：抓取间隔 |
| `--debug` | `false` | 输出调试日志 |

`crawl` 在至少一个平台成功时返回 0；全部失败返回 1，但失败快照仍会写入，便于排查。`daemon` 不会因单轮失败退出。

## 更新频率与调度

| 数据 | 频率 | 发布位置 | 触发方式 |
| --- | --- | --- | --- |
| 实时快照 | 每 10 分钟 | GitHub Pages `latest.json` | Cloudflare Worker → `live.yml`；GitHub `schedule` `:13/:43` 兜底 |
| 小时归档 | 每小时 | `data/`、`archives/`、README | Cloudflare Worker `:23` + GitHub `schedule` `:47` 兜底 |

GitHub Actions 自带的 `schedule` 是 best-effort：2026 年实测常见延迟 1.5–4.5 小时，低活跃仓库的每小时任务实际每天只跑 4–8 次，丢跑不会留下记录。因此实时链路改为 Cloudflare Worker 调用 `workflow_dispatch`，部署步骤见 **[Cloudflare Worker 文档](deploy/cloudflare-worker/README.md)**；cron-job.org 和 systemd timer 的替代方案见 [外部定时器文档](docs/external-scheduler.md)。

高频运行只发布 Pages，不写 git，原因是单次快照约 24KB，10 分钟一次会让仓库一年增长数百 MB；归档仍保持每小时一份，兼顾历史价值和仓库体积。

## GitHub Actions

仓库内置三个工作流：

- [`live.yml`](.github/workflows/live.yml)：由 Cloudflare Worker 每 10 分钟触发，抓取后只把 `latest.json` 部署到 GitHub Pages，不产生 git 提交；GitHub `schedule` 在 `:13/:43` 做低频兜底。
- [`crawl.yml`](.github/workflows/crawl.yml)：每小时归档，写入小时快照、日报和 README。Cloudflare Worker 在 `:23` 触发，GitHub 自带 `schedule` 在 `:47` 兜底；如果当前小时已有快照则自动跳过，避免重复提交。
- [`test.yml`](.github/workflows/test.yml)：只在代码变更时运行 `go vet` 和 `go test -race`，数据提交不会触发。

第一次使用需要：

1. 在 **Settings → Actions → General** 确认 Workflow permissions 为 **Read and write permissions**。
2. 在 **Settings → Pages** 把 Source 设为 **GitHub Actions**（或运行一次 `live.yml`，按提示授权）。
3. 按 [Cloudflare Worker 部署文档](deploy/cloudflare-worker/README.md) 创建 fine-grained PAT 并部署 Worker；也支持 cron-job.org 或自己的 systemd timer，见 [外部定时器文档](docs/external-scheduler.md)。

### 部署 Cloudflare Worker

```bash
cd deploy/cloudflare-worker
npm install
npx wrangler login
npx wrangler secret put GITHUB_TOKEN
npm run deploy
```

Worker 的两个 cron 会分别触发 `live.yml`（每 10 分钟）和 `crawl.yml`（每小时 :23）。完整说明和失败告警配置见 [deploy/cloudflare-worker/README.md](deploy/cloudflare-worker/README.md)。

如果 GitHub Runner 访问国内接口不稳定，可以在 workflow 中给抓取步骤设置 `HTTPS_PROXY`，surf 会读取标准代理环境变量：

```yaml
- name: Crawl
  env:
    HTTPS_PROXY: ${{ secrets.HTTPS_PROXY }}
  run: go run ./cmd/hot-search-crawler crawl --update-readme
```

## 新增平台

实现 `internal/source.Source`：

```go
type Source interface {
    ID() string
    Name() string
    Fetch(ctx context.Context, limit int) ([]Item, error)
}
```

然后在 `internal/source/registry.go` 的 `All()` 里注册。解析逻辑建议拆成纯函数并用 `testdata/` 中的真实报文做单元测试，HTTP 请求、超时、重试和落盘由框架统一处理。

## 设计取舍

- **每次从小时文件重建日报**：`summary.json` 不是增量合并，而是读取当天所有 `HH.json` 重新聚合。这样重复运行、手动补抓、删除异常快照都不会让统计漂移。
- **广告与空标题在计数前过滤**：`--top` 限制的是有效条目数，不会被推广位占掉名额。
- **限流不重试**：小红书 `300013` 的 `RetryAfter` 是 10 分钟，连续敲门只会延长封禁；普通网络错误才走指数退避。
- **固定北京时间**：文件名和日报统一用 UTC+8，避免服务器时区不同导致目录漂移。

## 免责声明

本项目仅用于学习和技术研究。热搜数据归各平台所有，请遵守目标网站的 robots.txt、服务条款和当地法律法规；不要高频请求、绕过付费能力或用于商业用途。因使用本项目产生的任何后果由使用者自行承担。

## License

[MIT](LICENSE)

# echarts-china-cities-js

It collects all geo-jsons in javascript of all 363 provincial cities
in 27 and acts as a static asset to jupyter-echarts or your
echarts collection.

## Installation

```
npm i echarts-china-cities-js
```

## echarts usage

```
<html>
  <head>
    <meta charset="utf-8" />
	<style>
	  .citymap{
	  width: 100%;
	  height: 100%;
	  }
	</style>
  	<script src="https://chfw.github.io/echarts-china-cities-js/echarts.min.js"></script>
	<script src="https://chfw.github.io/echarts-china-cities-js/dist/jiang1_xi1/nan2_chang1.js"></script>
  </head>
  <body>
	<div id='nan2_chang1' class='citymap'></div>
	<script src='https://chfw.github.io/echarts-china-cities-js/demo.js'></script>
	<script>
	  make_city('南昌', 'nan2_chang1');
	</script>
  </body>
</html>
```

![Usage with echarts](https://chfw.github.io/echarts-china-cities-js/nanchang.png)

## pyecharts usage

This library is included in pyecharts 2.0.2. No action is required from you.

![Usage with pyecharts](https://user-images.githubusercontent.com/4280312/29755070-9bc9ae70-8b89-11e7-9bf2-bec09cb5f1a1.png)

## Featuring Cities(or for Single Download)

Cities:
1. **贵州**:
[六盘水]("https://chfw.github.io/echarts-china-cities-js/dist/gui4_zhou1/liu4_pan2_shui3.js"), [安顺]("https://chfw.github.io/echarts-china-cities-js/dist/gui4_zhou1/an1_shun4.js"), [毕节]("https://chfw.github.io/echarts-china-cities-js/dist/gui4_zhou1/bi4_jie2.js"), [贵阳]("https://chfw.github.io/echarts-china-cities-js/dist/gui4_zhou1/gui4_yang2.js"), [遵义]("https://chfw.github.io/echarts-china-cities-js/dist/gui4_zhou1/zun1_yi4.js"), [铜仁]("https://chfw.github.io/echarts-china-cities-js/dist/gui4_zhou1/tong2_ren2.js"), [黔东南苗族侗族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/gui4_zhou1/qian2_dong1_nan2_miao2_zu2_tong1_zu2_zi4_zhi4_zhou1.js"), [黔南布依族苗族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/gui4_zhou1/qian2_nan2_bu4_yi1_zu2_miao2_zu2_zi4_zhi4_zhou1.js"), [黔西南布依族苗族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/gui4_zhou1/qian2_xi1_nan2_bu4_yi1_zu2_miao2_zu2_zi4_zhi4_zhou1.js")
2. **河南**:
[三门峡]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/san1_men2_xia2.js"), [信阳]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/xin4_yang2.js"), [南阳]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/nan2_yang2.js"), [周口]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/zhou1_kou3.js"), [商丘]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/shang1_qiu1.js"), [安阳]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/an1_yang2.js"), [平顶山]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/ping2_ding3_shan1.js"), [开封]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/kai1_feng1.js"), [新乡]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/xin1_xiang1.js"), [洛阳]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/luo4_yang2.js"), [济源]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/ji4_yuan2.js"), [漯河]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/ta4_he2.js"), [濮阳]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/pu2_yang2.js"), [焦作]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/jiao1_zuo4.js"), [许昌]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/xu3_chang1.js"), [郑州]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/zheng4_zhou1.js"), [驻马店]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/zhu4_ma3_dian4.js"), [鹤壁]("https://chfw.github.io/echarts-china-cities-js/dist/he2_nan2/he4_bi4.js")
3. **山东**:
[东营]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_dong1/dong1_ying2.js"), [临沂]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_dong1/lin2_yi2.js"), [威海]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_dong1/wei1_hai3.js"), [德州]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_dong1/de2_zhou1.js"), [日照]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_dong1/ri4_zhao4.js"), [枣庄]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_dong1/zao3_zhuang1.js"), [泰安]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_dong1/tai4_an1.js"), [济南]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_dong1/ji4_nan2.js"), [济宁]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_dong1/ji4_ning2.js"), [淄博]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_dong1/zi1_bo2.js"), [滨州]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_dong1/bin1_zhou1.js"), [潍坊]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_dong1/wei2_fang1.js"), [烟台]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_dong1/yan1_tai2.js"), [聊城]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_dong1/liao2_cheng2.js"), [莱芜]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_dong1/lai2_wu2.js"), [菏泽]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_dong1/he2_ze2.js"), [青岛]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_dong1/qing1_dao3.js")
4. **四川**:
[乐山]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/le4_shan1.js"), [内江]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/nei4_jiang1.js"), [凉山彝族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/liang2_shan1_yi2_zu2_zi4_zhi4_zhou1.js"), [南充]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/nan2_chong1.js"), [宜宾]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/yi2_bin1.js"), [巴中]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/ba1_zhong1.js"), [广元]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/guang3_yuan2.js"), [广安]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/guang3_an1.js"), [德阳]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/de2_yang2.js"), [成都]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/cheng2_du1.js"), [攀枝花]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/pan1_zhi1_hua1.js"), [泸州]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/lu2_zhou1.js"), [甘孜藏族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/gan1_zi1_cang2_zu2_zi4_zhi4_zhou1.js"), [眉山]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/mei2_shan1.js"), [绵阳]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/mian2_yang2.js"), [自贡]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/zi4_gong4.js"), [资阳]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/zi1_yang2.js"), [达州]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/da2_zhou1.js"), [遂宁]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/sui4_ning2.js"), [阿坝藏族羌族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/a1_ba4_cang2_zu2_qiang1_zu2_zi4_zhi4_zhou1.js"), [雅安]("https://chfw.github.io/echarts-china-cities-js/dist/si4_chuan1/ya3_an1.js")
5. **江苏**:
[南京]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_su1/nan2_jing1.js"), [南通]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_su1/nan2_tong1.js"), [宿迁]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_su1/su4_qian1.js"), [常州]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_su1/chang2_zhou1.js"), [徐州]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_su1/xu2_zhou1.js"), [扬州]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_su1/yang2_zhou1.js"), [无锡]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_su1/wu2_xi2.js"), [泰州]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_su1/tai4_zhou1.js"), [淮安]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_su1/huai2_an1.js"), [盐城]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_su1/yan2_cheng2.js"), [苏州]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_su1/su1_zhou1.js"), [连云港]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_su1/lian2_yun2_gang3.js"), [镇江]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_su1/zhen4_jiang1.js")
6. **青海**:
[果洛藏族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/qing1_hai3/guo3_luo4_cang2_zu2_zi4_zhi4_zhou1.js"), [海东]("https://chfw.github.io/echarts-china-cities-js/dist/qing1_hai3/hai3_dong1.js"), [海北藏族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/qing1_hai3/hai3_bei3_cang2_zu2_zi4_zhi4_zhou1.js"), [海南藏族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/qing1_hai3/hai3_nan2_cang2_zu2_zi4_zhi4_zhou1.js"), [海西蒙古族藏族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/qing1_hai3/hai3_xi1_meng2_gu3_zu2_cang2_zu2_zi4_zhi4_zhou1.js"), [玉树藏族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/qing1_hai3/yu4_shu4_cang2_zu2_zi4_zhi4_zhou1.js"), [西宁]("https://chfw.github.io/echarts-china-cities-js/dist/qing1_hai3/xi1_ning2.js"), [黄南藏族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/qing1_hai3/huang2_nan2_cang2_zu2_zi4_zhi4_zhou1.js")
7. **新疆**:
[乌鲁木齐]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/wu1_lu3_mu4_qi2.js"), [五家渠]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/wu3_jia1_qu2.js"), [伊犁哈萨克自治州]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/yi1_li2_ha1_sa4_ke4_zi4_zhi4_zhou1.js"), [克孜勒苏柯尔克孜自治州]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/ke4_zi1_le4_su1_ke1_er3_ke4_zi1_zi4_zhi4_zhou1.js"), [克拉玛依]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/ke4_la1_ma3_yi1.js"), [北屯]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/bei3_tun2.js"), [博尔塔拉蒙古自治州]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/bo2_er3_ta3_la1_meng2_gu3_zi4_zhi4_zhou1.js"), [双河]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/shuang1_he2.js"), [可克达拉]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/ke3_ke4_da2_la1.js"), [吐鲁番]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/tu3_lu3_fan1.js"), [和田地区]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/he2_tian2_di4_qu1.js"), [哈密]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/ha1_mi4.js"), [喀什地区]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/ka1_shi2_di4_qu1.js"), [图木舒克]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/tu2_mu4_shu1_ke4.js"), [塔城地区]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/ta3_cheng2_di4_qu1.js"), [巴音郭楞蒙古自治州]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/ba1_yin1_guo1_leng2_meng2_gu3_zi4_zhi4_zhou1.js"), [昆玉]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/kun1_yu4.js"), [昌吉回族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/chang1_ji2_hui2_zu2_zi4_zhi4_zhou1.js"), [石河子]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/shi2_he2_zi3.js"), [铁门关]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/tie3_men2_guan1.js"), [阿克苏地区]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/a1_ke4_su1_di4_qu1.js"), [阿勒泰地区]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/a1_le4_tai4_di4_qu1.js"), [阿拉尔]("https://chfw.github.io/echarts-china-cities-js/dist/xin1_jiang1/a1_la1_er3.js")
8. **福建**:
[三明]("https://chfw.github.io/echarts-china-cities-js/dist/fu2_jian4/san1_ming2.js"), [南平]("https://chfw.github.io/echarts-china-cities-js/dist/fu2_jian4/nan2_ping2.js"), [厦门]("https://chfw.github.io/echarts-china-cities-js/dist/fu2_jian4/sha4_men2.js"), [宁德]("https://chfw.github.io/echarts-china-cities-js/dist/fu2_jian4/ning2_de2.js"), [泉州]("https://chfw.github.io/echarts-china-cities-js/dist/fu2_jian4/quan2_zhou1.js"), [漳州]("https://chfw.github.io/echarts-china-cities-js/dist/fu2_jian4/zhang1_zhou1.js"), [福州]("https://chfw.github.io/echarts-china-cities-js/dist/fu2_jian4/fu2_zhou1.js"), [莆田]("https://chfw.github.io/echarts-china-cities-js/dist/fu2_jian4/fu3_tian2.js"), [龙岩]("https://chfw.github.io/echarts-china-cities-js/dist/fu2_jian4/long2_yan2.js")
9. **浙江**:
[丽水]("https://chfw.github.io/echarts-china-cities-js/dist/zhe4_jiang1/li4_shui3.js"), [台州]("https://chfw.github.io/echarts-china-cities-js/dist/zhe4_jiang1/tai2_zhou1.js"), [嘉兴]("https://chfw.github.io/echarts-china-cities-js/dist/zhe4_jiang1/jia1_xing1.js"), [宁波]("https://chfw.github.io/echarts-china-cities-js/dist/zhe4_jiang1/ning2_bo1.js"), [杭州]("https://chfw.github.io/echarts-china-cities-js/dist/zhe4_jiang1/hang2_zhou1.js"), [温州]("https://chfw.github.io/echarts-china-cities-js/dist/zhe4_jiang1/wen1_zhou1.js"), [湖州]("https://chfw.github.io/echarts-china-cities-js/dist/zhe4_jiang1/hu2_zhou1.js"), [绍兴]("https://chfw.github.io/echarts-china-cities-js/dist/zhe4_jiang1/shao4_xing1.js"), [舟山]("https://chfw.github.io/echarts-china-cities-js/dist/zhe4_jiang1/zhou1_shan1.js"), [衢州]("https://chfw.github.io/echarts-china-cities-js/dist/zhe4_jiang1/qu2_zhou1.js"), [金华]("https://chfw.github.io/echarts-china-cities-js/dist/zhe4_jiang1/jin1_hua2.js")
10. **湖北**:
[仙桃]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_bei3/xian1_tao2.js"), [十堰]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_bei3/shi2_yan4.js"), [咸宁]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_bei3/xian2_ning2.js"), [天门]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_bei3/tian1_men2.js"), [孝感]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_bei3/xiao4_gan3.js"), [宜昌]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_bei3/yi2_chang1.js"), [恩施土家族苗族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_bei3/en1_shi1_tu3_jia1_zu2_miao2_zu2_zi4_zhi4_zhou1.js"), [武汉]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_bei3/wu3_han4.js"), [潜江]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_bei3/qian2_jiang1.js"), [神农架林区]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_bei3/shen2_nong2_jia4_lin2_qu1.js"), [荆州]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_bei3/jing1_zhou1.js"), [荆门]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_bei3/jing1_men2.js"), [襄阳]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_bei3/xiang1_yang2.js"), [鄂州]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_bei3/e4_zhou1.js"), [随州]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_bei3/sui2_zhou1.js"), [黄冈]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_bei3/huang2_gang1.js"), [黄石]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_bei3/huang2_shi2.js")
11. **江西**:
[上饶]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_xi1/shang4_rao2.js"), [九江]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_xi1/jiu3_jiang1.js"), [南昌]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_xi1/nan2_chang1.js"), [吉安]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_xi1/ji2_an1.js"), [宜春]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_xi1/yi2_chun1.js"), [抚州]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_xi1/fu3_zhou1.js"), [新余]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_xi1/xin1_yu2.js"), [景德镇]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_xi1/jing3_de2_zhen4.js"), [萍乡]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_xi1/ping2_xiang1.js"), [赣州]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_xi1/gan4_zhou1.js"), [鹰潭]("https://chfw.github.io/echarts-china-cities-js/dist/jiang1_xi1/ying1_tan2.js")
12. **西藏**:
[山南]("https://chfw.github.io/echarts-china-cities-js/dist/xi1_cang2/shan1_nan2.js"), [拉萨]("https://chfw.github.io/echarts-china-cities-js/dist/xi1_cang2/la1_sa4.js"), [日喀则]("https://chfw.github.io/echarts-china-cities-js/dist/xi1_cang2/ri4_ka1_ze2.js"), [昌都]("https://chfw.github.io/echarts-china-cities-js/dist/xi1_cang2/chang1_du1.js"), [林芝]("https://chfw.github.io/echarts-china-cities-js/dist/xi1_cang2/lin2_zhi1.js"), [那曲地区]("https://chfw.github.io/echarts-china-cities-js/dist/xi1_cang2/na4_qu1_di4_qu1.js"), [阿里地区]("https://chfw.github.io/echarts-china-cities-js/dist/xi1_cang2/a1_li3_di4_qu1.js")
13. **黑龙江**:
[七台河]("https://chfw.github.io/echarts-china-cities-js/dist/hei1_long2_jiang1/qi1_tai2_he2.js"), [伊春]("https://chfw.github.io/echarts-china-cities-js/dist/hei1_long2_jiang1/yi1_chun1.js"), [佳木斯]("https://chfw.github.io/echarts-china-cities-js/dist/hei1_long2_jiang1/jia1_mu4_si1.js"), [双鸭山]("https://chfw.github.io/echarts-china-cities-js/dist/hei1_long2_jiang1/shuang1_ya1_shan1.js"), [哈尔滨]("https://chfw.github.io/echarts-china-cities-js/dist/hei1_long2_jiang1/ha1_er3_bin1.js"), [大兴安岭地区]("https://chfw.github.io/echarts-china-cities-js/dist/hei1_long2_jiang1/da4_xing1_an1_ling2_di4_qu1.js"), [大庆]("https://chfw.github.io/echarts-china-cities-js/dist/hei1_long2_jiang1/da4_qing4.js"), [牡丹江]("https://chfw.github.io/echarts-china-cities-js/dist/hei1_long2_jiang1/mu3_dan1_jiang1.js"), [绥化]("https://chfw.github.io/echarts-china-cities-js/dist/hei1_long2_jiang1/sui1_hua4.js"), [鸡西]("https://chfw.github.io/echarts-china-cities-js/dist/hei1_long2_jiang1/ji1_xi1.js"), [鹤岗]("https://chfw.github.io/echarts-china-cities-js/dist/hei1_long2_jiang1/he4_gang3.js"), [黑河]("https://chfw.github.io/echarts-china-cities-js/dist/hei1_long2_jiang1/hei1_he2.js"), [齐齐哈尔]("https://chfw.github.io/echarts-china-cities-js/dist/hei1_long2_jiang1/qi2_qi2_ha1_er3.js")
14. **广东**:
[东沙群岛]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/dong1_sha1_qun2_dao3.js"), [东莞]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/dong1_guan1.js"), [中山]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/zhong1_shan1.js"), [云浮]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/yun2_fu2.js"), [佛山]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/fo2_shan1.js"), [广州]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/guang3_zhou1.js"), [惠州]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/hui4_zhou1.js"), [揭阳]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/jie1_yang2.js"), [梅州]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/mei2_zhou1.js"), [汕头]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/shan4_tou2.js"), [汕尾]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/shan4_wei3.js"), [江门]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/jiang1_men2.js"), [河源]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/he2_yuan2.js"), [深圳]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/shen1_zhen4.js"), [清远]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/qing1_yuan3.js"), [湛江]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/zhan4_jiang1.js"), [潮州]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/chao2_zhou1.js"), [珠海]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/zhu1_hai3.js"), [肇庆]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/zhao4_qing4.js"), [茂名]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/mao4_ming2.js"), [阳江]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/yang2_jiang1.js"), [韶关]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_dong1/shao2_guan1.js")
15. **云南**:
[临沧]("https://chfw.github.io/echarts-china-cities-js/dist/yun2_nan2/lin2_cang1.js"), [丽江]("https://chfw.github.io/echarts-china-cities-js/dist/yun2_nan2/li4_jiang1.js"), [保山]("https://chfw.github.io/echarts-china-cities-js/dist/yun2_nan2/bao3_shan1.js"), [大理白族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/yun2_nan2/da4_li3_bai2_zu2_zi4_zhi4_zhou1.js"), [德宏傣族景颇族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/yun2_nan2/de2_hong2_dai3_zu2_jing3_po3_zu2_zi4_zhi4_zhou1.js"), [怒江傈僳族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/yun2_nan2/nu4_jiang1_li4_su4_zu2_zi4_zhi4_zhou1.js"), [文山壮族苗族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/yun2_nan2/wen2_shan1_zhuang4_zu2_miao2_zu2_zi4_zhi4_zhou1.js"), [昆明]("https://chfw.github.io/echarts-china-cities-js/dist/yun2_nan2/kun1_ming2.js"), [昭通]("https://chfw.github.io/echarts-china-cities-js/dist/yun2_nan2/zhao1_tong1.js"), [普洱]("https://chfw.github.io/echarts-china-cities-js/dist/yun2_nan2/pu3_er3.js"), [曲靖]("https://chfw.github.io/echarts-china-cities-js/dist/yun2_nan2/qu1_jing4.js"), [楚雄彝族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/yun2_nan2/chu3_xiong2_yi2_zu2_zi4_zhi4_zhou1.js"), [玉溪]("https://chfw.github.io/echarts-china-cities-js/dist/yun2_nan2/yu4_xi1.js"), [红河哈尼族彝族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/yun2_nan2/hong2_he2_ha1_ni2_zu2_yi2_zu2_zi4_zhi4_zhou1.js"), [西双版纳傣族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/yun2_nan2/xi1_shuang1_ban3_na4_dai3_zu2_zi4_zhi4_zhou1.js"), [迪庆藏族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/yun2_nan2/di2_qing4_cang2_zu2_zi4_zhi4_zhou1.js")
16. **广西**:
[北海]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_xi1/bei3_hai3.js"), [南宁]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_xi1/nan2_ning2.js"), [崇左]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_xi1/chong2_zuo3.js"), [来宾]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_xi1/lai2_bin1.js"), [柳州]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_xi1/liu3_zhou1.js"), [桂林]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_xi1/gui4_lin2.js"), [梧州]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_xi1/wu2_zhou1.js"), [河池]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_xi1/he2_chi2.js"), [玉林]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_xi1/yu4_lin2.js"), [百色]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_xi1/bai3_se4.js"), [贵港]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_xi1/gui4_gang3.js"), [贺州]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_xi1/he4_zhou1.js"), [钦州]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_xi1/qin1_zhou1.js"), [防城港]("https://chfw.github.io/echarts-china-cities-js/dist/guang3_xi1/fang2_cheng2_gang3.js")
17. **陕西**:
[咸阳]("https://chfw.github.io/echarts-china-cities-js/dist/shan3_xi1/xian2_yang2.js"), [商洛]("https://chfw.github.io/echarts-china-cities-js/dist/shan3_xi1/shang1_luo4.js"), [安康]("https://chfw.github.io/echarts-china-cities-js/dist/shan3_xi1/an1_kang1.js"), [宝鸡]("https://chfw.github.io/echarts-china-cities-js/dist/shan3_xi1/bao3_ji1.js"), [延安]("https://chfw.github.io/echarts-china-cities-js/dist/shan3_xi1/yan2_an1.js"), [榆林]("https://chfw.github.io/echarts-china-cities-js/dist/shan3_xi1/yu2_lin2.js"), [汉中]("https://chfw.github.io/echarts-china-cities-js/dist/shan3_xi1/han4_zhong1.js"), [渭南]("https://chfw.github.io/echarts-china-cities-js/dist/shan3_xi1/wei4_nan2.js"), [西安]("https://chfw.github.io/echarts-china-cities-js/dist/shan3_xi1/xi1_an1.js"), [铜川]("https://chfw.github.io/echarts-china-cities-js/dist/shan3_xi1/tong2_chuan1.js")
18. **甘肃**:
[临夏回族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/gan1_su4/lin2_xia4_hui2_zu2_zi4_zhi4_zhou1.js"), [兰州]("https://chfw.github.io/echarts-china-cities-js/dist/gan1_su4/lan2_zhou1.js"), [嘉峪关]("https://chfw.github.io/echarts-china-cities-js/dist/gan1_su4/jia1_yu4_guan1.js"), [天水]("https://chfw.github.io/echarts-china-cities-js/dist/gan1_su4/tian1_shui3.js"), [定西]("https://chfw.github.io/echarts-china-cities-js/dist/gan1_su4/ding4_xi1.js"), [平凉]("https://chfw.github.io/echarts-china-cities-js/dist/gan1_su4/ping2_liang2.js"), [庆阳]("https://chfw.github.io/echarts-china-cities-js/dist/gan1_su4/qing4_yang2.js"), [张掖]("https://chfw.github.io/echarts-china-cities-js/dist/gan1_su4/zhang1_ye4.js"), [武威]("https://chfw.github.io/echarts-china-cities-js/dist/gan1_su4/wu3_wei1.js"), [甘南藏族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/gan1_su4/gan1_nan2_cang2_zu2_zi4_zhi4_zhou1.js"), [白银]("https://chfw.github.io/echarts-china-cities-js/dist/gan1_su4/bai2_yin2.js"), [酒泉]("https://chfw.github.io/echarts-china-cities-js/dist/gan1_su4/jiu3_quan2.js"), [金昌]("https://chfw.github.io/echarts-china-cities-js/dist/gan1_su4/jin1_chang1.js"), [陇南]("https://chfw.github.io/echarts-china-cities-js/dist/gan1_su4/long3_nan2.js")
19. **河北**:
[保定]("https://chfw.github.io/echarts-china-cities-js/dist/he2_bei3/bao3_ding4.js"), [唐山]("https://chfw.github.io/echarts-china-cities-js/dist/he2_bei3/tang2_shan1.js"), [廊坊]("https://chfw.github.io/echarts-china-cities-js/dist/he2_bei3/lang2_fang1.js"), [张家口]("https://chfw.github.io/echarts-china-cities-js/dist/he2_bei3/zhang1_jia1_kou3.js"), [承德]("https://chfw.github.io/echarts-china-cities-js/dist/he2_bei3/cheng2_de2.js"), [石家庄]("https://chfw.github.io/echarts-china-cities-js/dist/he2_bei3/shi2_jia1_zhuang1.js"), [秦皇岛]("https://chfw.github.io/echarts-china-cities-js/dist/he2_bei3/qin2_huang2_dao3.js"), [衡水]("https://chfw.github.io/echarts-china-cities-js/dist/he2_bei3/heng2_shui3.js"), [邢台]("https://chfw.github.io/echarts-china-cities-js/dist/he2_bei3/xing2_tai2.js"), [邯郸]("https://chfw.github.io/echarts-china-cities-js/dist/he2_bei3/han2_dan1.js")
20. **宁夏**:
[中卫]("https://chfw.github.io/echarts-china-cities-js/dist/ning2_xia4/zhong1_wei4.js"), [吴忠]("https://chfw.github.io/echarts-china-cities-js/dist/ning2_xia4/wu2_zhong1.js"), [固原]("https://chfw.github.io/echarts-china-cities-js/dist/ning2_xia4/gu4_yuan2.js"), [石嘴山]("https://chfw.github.io/echarts-china-cities-js/dist/ning2_xia4/shi2_zui3_shan1.js"), [银川]("https://chfw.github.io/echarts-china-cities-js/dist/ning2_xia4/yin2_chuan1.js")
21. **吉林**:
[吉林]("https://chfw.github.io/echarts-china-cities-js/dist/ji2_lin2/ji2_lin2.js"), [四平]("https://chfw.github.io/echarts-china-cities-js/dist/ji2_lin2/si4_ping2.js"), [延边朝鲜族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/ji2_lin2/yan2_bian1_zhao1_xian1_zu2_zi4_zhi4_zhou1.js"), [松原]("https://chfw.github.io/echarts-china-cities-js/dist/ji2_lin2/song1_yuan2.js"), [白城]("https://chfw.github.io/echarts-china-cities-js/dist/ji2_lin2/bai2_cheng2.js"), [白山]("https://chfw.github.io/echarts-china-cities-js/dist/ji2_lin2/bai2_shan1.js"), [辽源]("https://chfw.github.io/echarts-china-cities-js/dist/ji2_lin2/liao2_yuan2.js"), [通化]("https://chfw.github.io/echarts-china-cities-js/dist/ji2_lin2/tong1_hua4.js"), [长春]("https://chfw.github.io/echarts-china-cities-js/dist/ji2_lin2/chang2_chun1.js")
22. **湖南**:
[娄底]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_nan2/lou2_di3.js"), [岳阳]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_nan2/yue4_yang2.js"), [常德]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_nan2/chang2_de2.js"), [张家界]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_nan2/zhang1_jia1_jie4.js"), [怀化]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_nan2/huai2_hua4.js"), [株洲]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_nan2/zhu1_zhou1.js"), [永州]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_nan2/yong3_zhou1.js"), [湘潭]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_nan2/xiang1_tan2.js"), [湘西土家族苗族自治州]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_nan2/xiang1_xi1_tu3_jia1_zu2_miao2_zu2_zi4_zhi4_zhou1.js"), [益阳]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_nan2/yi4_yang2.js"), [衡阳]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_nan2/heng2_yang2.js"), [邵阳]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_nan2/shao4_yang2.js"), [郴州]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_nan2/chen1_zhou1.js"), [长沙]("https://chfw.github.io/echarts-china-cities-js/dist/hu2_nan2/chang2_sha1.js")
23. **安徽**:
[亳州]("https://chfw.github.io/echarts-china-cities-js/dist/an1_hui1/bo2_zhou1.js"), [六安]("https://chfw.github.io/echarts-china-cities-js/dist/an1_hui1/liu4_an1.js"), [合肥]("https://chfw.github.io/echarts-china-cities-js/dist/an1_hui1/he2_fei2.js"), [安庆]("https://chfw.github.io/echarts-china-cities-js/dist/an1_hui1/an1_qing4.js"), [宣城]("https://chfw.github.io/echarts-china-cities-js/dist/an1_hui1/xuan1_cheng2.js"), [宿州]("https://chfw.github.io/echarts-china-cities-js/dist/an1_hui1/su4_zhou1.js"), [池州]("https://chfw.github.io/echarts-china-cities-js/dist/an1_hui1/chi2_zhou1.js"), [淮北]("https://chfw.github.io/echarts-china-cities-js/dist/an1_hui1/huai2_bei3.js"), [淮南]("https://chfw.github.io/echarts-china-cities-js/dist/an1_hui1/huai2_nan2.js"), [滁州]("https://chfw.github.io/echarts-china-cities-js/dist/an1_hui1/chu2_zhou1.js"), [芜湖]("https://chfw.github.io/echarts-china-cities-js/dist/an1_hui1/wu2_hu2.js"), [蚌埠]("https://chfw.github.io/echarts-china-cities-js/dist/an1_hui1/bang4_bu4.js"), [铜陵]("https://chfw.github.io/echarts-china-cities-js/dist/an1_hui1/tong2_ling2.js"), [阜阳]("https://chfw.github.io/echarts-china-cities-js/dist/an1_hui1/fu4_yang2.js"), [马鞍山]("https://chfw.github.io/echarts-china-cities-js/dist/an1_hui1/ma3_an1_shan1.js"), [黄山]("https://chfw.github.io/echarts-china-cities-js/dist/an1_hui1/huang2_shan1.js")
24. **内蒙古**:
[乌兰察布]("https://chfw.github.io/echarts-china-cities-js/dist/nei4_meng2_gu3/wu1_lan2_cha2_bu4.js"), [乌海]("https://chfw.github.io/echarts-china-cities-js/dist/nei4_meng2_gu3/wu1_hai3.js"), [兴安盟]("https://chfw.github.io/echarts-china-cities-js/dist/nei4_meng2_gu3/xing1_an1_meng2.js"), [包头]("https://chfw.github.io/echarts-china-cities-js/dist/nei4_meng2_gu3/bao1_tou2.js"), [呼伦贝尔]("https://chfw.github.io/echarts-china-cities-js/dist/nei4_meng2_gu3/hu1_lun2_bei4_er3.js"), [呼和浩特]("https://chfw.github.io/echarts-china-cities-js/dist/nei4_meng2_gu3/hu1_he2_hao4_te4.js"), [巴彦淖尔]("https://chfw.github.io/echarts-china-cities-js/dist/nei4_meng2_gu3/ba1_yan4_nao4_er3.js"), [赤峰]("https://chfw.github.io/echarts-china-cities-js/dist/nei4_meng2_gu3/chi4_feng1.js"), [通辽]("https://chfw.github.io/echarts-china-cities-js/dist/nei4_meng2_gu3/tong1_liao2.js"), [鄂尔多斯]("https://chfw.github.io/echarts-china-cities-js/dist/nei4_meng2_gu3/e4_er3_duo1_si1.js"), [锡林郭勒盟]("https://chfw.github.io/echarts-china-cities-js/dist/nei4_meng2_gu3/xi2_lin2_guo1_le4_meng2.js"), [阿拉善盟]("https://chfw.github.io/echarts-china-cities-js/dist/nei4_meng2_gu3/a1_la1_shan4_meng2.js")
25. **山西**:
[临汾]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_xi1/lin2_fen2.js"), [吕梁]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_xi1/lv3_liang2.js"), [大同]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_xi1/da4_tong2.js"), [太原]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_xi1/tai4_yuan2.js"), [忻州]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_xi1/xin1_zhou1.js"), [晋中]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_xi1/jin4_zhong1.js"), [晋城]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_xi1/jin4_cheng2.js"), [朔州]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_xi1/shuo4_zhou1.js"), [运城]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_xi1/yun4_cheng2.js"), [长治]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_xi1/chang2_zhi4.js"), [阳泉]("https://chfw.github.io/echarts-china-cities-js/dist/shan1_xi1/yang2_quan2.js")
26. **海南**:
[万宁]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/wan4_ning2.js"), [三亚]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/san1_ya4.js"), [三沙]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/san1_sha1.js"), [东方]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/dong1_fang1.js"), [临高县]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/lin2_gao1_xian4.js"), [乐东黎族自治县]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/le4_dong1_li2_zu2_zi4_zhi4_xian4.js"), [五指山]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/wu3_zhi3_shan1.js"), [保亭黎族苗族自治县]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/bao3_ting2_li2_zu2_miao2_zu2_zi4_zhi4_xian4.js"), [儋州]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/dan1_zhou1.js"), [定安县]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/ding4_an1_xian4.js"), [屯昌县]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/tun2_chang1_xian4.js"), [文昌]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/wen2_chang1.js"), [昌江黎族自治县]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/chang1_jiang1_li2_zu2_zi4_zhi4_xian4.js"), [海口]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/hai3_kou3.js"), [澄迈县]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/cheng2_mai4_xian4.js"), [琼中黎族苗族自治县]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/qiong2_zhong1_li2_zu2_miao2_zu2_zi4_zhi4_xian4.js"), [琼海]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/qiong2_hai3.js"), [白沙黎族自治县]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/bai2_sha1_li2_zu2_zi4_zhi4_xian4.js"), [陵水黎族自治县]("https://chfw.github.io/echarts-china-cities-js/dist/hai3_nan2/ling2_shui3_li2_zu2_zi4_zhi4_xian4.js")
27. **辽宁**:
[丹东]("https://chfw.github.io/echarts-china-cities-js/dist/liao2_ning2/dan1_dong1.js"), [大连]("https://chfw.github.io/echarts-china-cities-js/dist/liao2_ning2/da4_lian2.js"), [抚顺]("https://chfw.github.io/echarts-china-cities-js/dist/liao2_ning2/fu3_shun4.js"), [朝阳]("https://chfw.github.io/echarts-china-cities-js/dist/liao2_ning2/zhao1_yang2.js"), [本溪]("https://chfw.github.io/echarts-china-cities-js/dist/liao2_ning2/ben3_xi1.js"), [沈阳]("https://chfw.github.io/echarts-china-cities-js/dist/liao2_ning2/shen3_yang2.js"), [盘锦]("https://chfw.github.io/echarts-china-cities-js/dist/liao2_ning2/pan2_jin3.js"), [营口]("https://chfw.github.io/echarts-china-cities-js/dist/liao2_ning2/ying2_kou3.js"), [葫芦岛]("https://chfw.github.io/echarts-china-cities-js/dist/liao2_ning2/hu2_lu2_dao3.js"), [辽阳]("https://chfw.github.io/echarts-china-cities-js/dist/liao2_ning2/liao2_yang2.js"), [铁岭]("https://chfw.github.io/echarts-china-cities-js/dist/liao2_ning2/tie3_ling2.js"), [锦州]("https://chfw.github.io/echarts-china-cities-js/dist/liao2_ning2/jin3_zhou1.js"), [阜新]("https://chfw.github.io/echarts-china-cities-js/dist/liao2_ning2/fu4_xin1.js"), [鞍山]("https://chfw.github.io/echarts-china-cities-js/dist/liao2_ning2/an1_shan1.js")


## Development

Please use python

```shell
$ python makedemo.py
```

## Test

```shell
$ pip install test/requirements.txt
$ npm test
```

## License

The geojson files are downloaded from AMap.com(高德地图) via [echarts-map-tool](http://ecomfe.github.io/echarts-map-tool/),
hence are subjected to AMap's [service and content license](https://lbs.amap.com/home/terms/).

**No content right** have been transferred to you and you shall **engage AMap.com** before
making commercial applications using the files in this package. No liability/Guarantee were
given for any error or flaws in the downloaded files.

### Free usage instructions

Similiar to google's map data, it is free as long as the public's access to your files
are free. 

This bundling code(makedemo.py) is MIT license.
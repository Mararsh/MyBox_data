# [ReadMe in English](https://github.com/Mararsh/MyBox_data/tree/master/en)  ![ReadMe](https://mararsh.github.io/MyBox_data/iconOK.png)   

# MyBox的数据

## 适用范围   

除了“MyBox内部格式”，其它格式均是自洽的：数据都是显值，可以被第三方应用直接使用。    

所有文件均是UTF-8编码。除了xlsx，其它格式均可用任意文本编辑器来查看和修改。   

“MyBox内部格式”和“MyBox外部格式”可用MyBox v6.3及以后的版本来导入/导出。   
-  MyBox内部格式：外键引用数据标识。好处是快速导入/导出，坏处是数据相互依赖。   
-  MyBox外部格式：数据都是值。好处是不依赖其它数据，坏处是导入/导出慢。

## 地理代码

### 数据源
| 引用内容 | 链接 |    
| --- | --- |   
| 国家的坐标/描述 | https://github.com/wizardcode/world-area |       
| 国家的代码/人口/面积 | https://www.geonames.org/countries/ |       
| 中国行政地名 | http://www.stats.gov.cn/tjsj/tjbz/tjyqhdmhcxhfdm/ |     
| 中国地址坐标 | https://lbs.amap.com/api/webservice/guide/api/georegeo   |     
 

### 下载

最后更新时间：2020-5-15 修正国家“布基纳法索”的名字错误
  

| 内容 | 格式 | 大小 | 链接 |    
| --- | --- | --- |  --- |   
| 全球地理编码-中文 | zip | 318kb | [Global_zh.zip](https://github.com/Mararsh/MyBox_data/releases/download/v1.2/Global_zh.zip) |       
| 中国地理编码-中文 | zip | 103mb | [China_zh.zip](https://github.com/Mararsh/MyBox_data/releases/download/v1.2/China_zh.zip) |       
| 全球地理编码-英文 | zip | 319kb | [Global_en.zip](https://github.com/Mararsh/MyBox_data/releases/download/v1.2/Global_en.zip) |       
| 中国地理编码-英文 | zip | 2915kb | [China_en.zip](https://github.com/Mararsh/MyBox_data/releases/download/v1.2/China_en.zip) |       

### 程序引用

以下均是直接链接，可以被代码访问到。   

| 内容 | html | json | xlsx | xml | MyBox外部格式 | MyBox内部格式 |
| --- | --- | --- | --- | --- | --- | --- |
| 洲 | [5kb](http://mararsh.github.io/MyBox_data/地理代码/全球/洲.htm) | [2kb](http://mararsh.github.io/MyBox_data/地理代码/全球/洲.json) | [5kb](http://mararsh.github.io/MyBox_data/地理代码/全球/洲.xlsx) | [2kb](http://mararsh.github.io/MyBox_data/地理代码/洲.xml) | [1kb](http://mararsh.github.io/MyBox_data/地理代码/全球/洲_external.csv)  | [1kb](http://mararsh.github.io/MyBox_data/地理代码/全球/洲_internal.csv)  |     
| 国家 | [165kb](http://mararsh.github.io/MyBox_data/地理代码/全球/国家.htm) | [152kb](http://mararsh.github.io/MyBox_data/地理代码/全球/国家.json) | [72kb](http://mararsh.github.io/MyBox_data/地理代码/全球/国家.xlsx) | [150kb](http://mararsh.github.io/MyBox_data/地理代码/国家.xml) | [107kb](http://mararsh.github.io/MyBox_data/地理代码/全球/国家_external.csv)  | [103kb](http://mararsh.github.io/MyBox_data/地理代码/全球/国家_internal.csv)  |     
| 中国省份 | [14kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国省份/中国省份.htm) | [9kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国省份/中国省份.json) | [8kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国省份/中国省份.xlsx) | [9kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国省份/中国省份.xml) | [4kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国省份/中国省份_external.csv)  | [4kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国省份/中国省份_internal.csv)  |    
| 中国城市 | [118kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国城市/中国城市.htm) | [84kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国城市/中国城市.json) | [42kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国城市/中国城市.xlsx) | [83kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国城市/中国城市.xml) | [39kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国城市/中国城市_external.csv)  | [35kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国城市/中国城市_internal.csv)  |    
| 中国区县 | [1041kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国区县/中国区县.htm) | [783kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国区县/中国区县.json) | [325kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国区县/中国区县.xlsx) | [769kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国区县/中国区县.xml) | [359kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国区县/中国区县_external.csv)  | [310kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国区县/中国区县_internal.csv)  |    
| 中国乡镇 | [15186kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国乡镇/中国乡镇.htm) | [11483kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国乡镇/中国乡镇.json) | [4215kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国乡镇/中国乡镇.xlsx) | [11105kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国乡镇/中国乡镇.xml) | [5394kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国乡镇/中国乡镇_external.csv)  | [4495kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国乡镇/中国乡镇_internal.csv)  |    
| 中国村庄-安徽 | [6859kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/安徽_villages.htm) | [5717kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/安徽_villages.json) | [1641kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/安徽_villages.xlsx) | [5485kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/安徽_villages.xml) | [2706kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/安徽_villages_external.csv)  | [2192kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/安徽_villages_internal.csv)  |    
| 中国村庄-北京 | [2782kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/北京_villages.htm) | [2333kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/北京_villages.json) | [673kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/北京_villages.xlsx) | [2242kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/北京_villages.xml) | [1150kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/北京_villages_external.csv)  | [884kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/北京_villages_internal.csv)  |        
| 中国村庄-福建 | [6430kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/福建_villages.htm) | [5350kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/福建_villages.json) | [1545kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/福建_villages.xlsx) | [5131kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/福建_villages.xml) | [2503kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/福建_villages_external.csv)  | [2053kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/福建_villages_internal.csv)  |        
| 中国村庄-甘肃 | [6652kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/甘肃_villages.htm) | [5549kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/甘肃_villages.json) | [1578kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/甘肃_villages.xlsx) | [5325kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/甘肃_villages.xml) | [2640kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/甘肃_villages_external.csv)  | [2131kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/甘肃_villages_internal.csv)  |      
| 中国村庄-广东 | [9674kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/广东_villages.htm) | [8065kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/广东_villages.json) | [2370kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/广东_villages.xlsx) | [7739kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/广东_villages.xml) | [3822kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/广东_villages_external.csv)  | [3096kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/广东_villages_internal.csv)  |          
| 中国村庄-广西 | [6173kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/广西_villages.htm) | [5140kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/广西_villages.json) | [1482kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/广西_villages.xlsx) | [4931kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/广西_villages.xml) | [2418kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/广西_villages_external.csv)  | [1964kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/广西_villages_internal.csv)  |        
| 中国村庄-贵州 | [6765kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/贵州_villages.htm) | [5695kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/贵州_villages.json) | [1586kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/贵州_villages.xlsx) | [5434kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/贵州_villages.xml) | [2742kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/贵州_villages_external.csv)  | [2135kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/贵州_villages_internal.csv)  |        
| 中国村庄-海南 | [1173kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/海南_villages.htm) | [956kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/海南_villages.json) | [272kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/海南_villages.xlsx) | [923kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/海南_villages.xml) | [491kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/海南_villages_external.csv)  | [350kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/海南_villages_internal.csv)  |        
| 中国村庄-河北 | [20326kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/河北_villages.htm) | [16974kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/河北_villages.json) | [4735kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/河北_villages.xlsx) | [16293kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/河北_villages.xml) | [8126kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/河北_villages_external.csv)  | [6485kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/河北_villages_internal.csv)  |             
| 中国村庄-河南 | [20009kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/河南_villages.htm) | [8448kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/河南_villages.json) | [4578kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/河南_villages.xlsx) | [9288kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/河南_villages.xml) | [4712kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/河南_villages_external.csv)  | [6545kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/河南_villages_internal.csv)  |        
| 中国村庄-黑龙江 | [5417kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/黑龙江_villages.htm) | [4538kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/黑龙江_villages.json) | [1264kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/黑龙江_villages.xlsx) | [4360kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/黑龙江_villages.xml) | [2222kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/黑龙江_villages_external.csv)  | [1713kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/黑龙江_villages_internal.csv)  |        
| 中国村庄-湖北 | [10880kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/湖北_villages.htm) | [9075kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/湖北_villages.json) | [2562kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/湖北_villages.xlsx) | [8717kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/湖北_villages.xml) | [4390kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/湖北_villages_external.csv)  | [3466kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/湖北_villages_internal.csv)  |        
| 中国村庄-湖南 | [10877kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/湖南_villages.htm) | [9037kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/湖南_villages.json) | [2751kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/湖南_villages.xlsx) | [8663kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/湖南_villages.xml) | [4182kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/湖南_villages_external.csv)  | [3427kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/湖南_villages_internal.csv)  |        
| 中国村庄-吉林 | [4352kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/吉林_villages.htm) | [3620kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/吉林_villages.json) | [1079kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/吉林_villages.xlsx) | [3472kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/吉林_villages.xml) | [1692kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/吉林_villages_external.csv)  | [1368kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/吉林_villages_internal.csv)  |        
| 中国村庄-江苏 | [8335kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/江苏_villages.htm) | [6953kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/江苏_villages.json) | [2029kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/江苏_villages.xlsx) | [6673kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/江苏_villages.xml) | [3309kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/江苏_villages_external.csv)  | [2658kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/江苏_villages_internal.csv)  |        
| 中国村庄-江西 | [8128kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/江西_villages.htm) | [6777kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/江西_villages.json) | [1932kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/江西_villages.xlsx) | [6503kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/江西_villages.xml) | [3213kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/江西_villages_external.csv)  | [2605kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/江西_villages_internal.csv)  |        
| 中国村庄-辽宁 | [6290kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/辽宁_villages.htm) | [5262kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/辽宁_villages.json) | [1508kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/辽宁_villages.xlsx) | [5054kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/辽宁_villages.xml) | [2553kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/辽宁_villages_external.csv)  | [2002kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/辽宁_villages_internal.csv)  |        
| 中国村庄-内蒙古 | [5712kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内蒙古_villages.htm) | [4805kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内蒙古_villages.json) | [1319kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内蒙古_villages.xlsx) | [4621kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内蒙古_villages.xml) | [2416kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内蒙古_villages_external.csv)  | [1776kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内蒙古_villages_internal.csv)  |        
| 中国村庄-宁夏 | [1068kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/宁夏_villages.htm) | [889kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/宁夏_villages.json) | [255kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/宁夏_villages.xlsx) | [853kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/宁夏_villages.xml) | [420kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/宁夏_villages_external.csv)  | [339kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/宁夏_villages_internal.csv)  |        
| 中国村庄-青海 | [1806kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/青海_villages.htm) | [1510kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/青海_villages.json) | [416kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/青海_villages.xlsx) | [1450kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/青海_villages.xml) | [732kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/青海_villages_external.csv)  | [570kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/青海_villages_internal.csv)  |        
| 中国村庄-山东 | [29342kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/山东_villages.htm) | [24511kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/山东_villages.json) | [6756kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/山东_villages.xlsx) | [23531kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/山东_villages.xml) | [11772kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/山东_villages_external.csv)  | [9413kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/山东_villages_internal.csv)  |        
| 中国村庄-山西 | [10496kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/山西_villages.htm) | [8748kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/山西_villages.json) | [2444kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/山西_villages.xlsx) | [8393kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/山西_villages.xml) | [4135kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/山西_villages_external.csv)  | [3361kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/山西_villages_internal.csv)  |         
| 中国村庄-陕西 | [7501kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/陕西_villages.htm) | [6250kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/陕西_villages.json) | [1781kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/陕西_villages.xlsx) | [5997kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/陕西_villages.xml) | [2952kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/陕西_villages_external.csv)  | [2394kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/陕西_villages_internal.csv)  |        
| 中国村庄-上海 | [2335kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/上海_villages.htm) | [1954kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/上海_villages.json) | [563kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/上海_villages.xlsx) | [1877kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/上海_villages.xml) | [952kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/上海_villages_external.csv)  | [739kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/上海_villages_internal.csv)  |        
| 中国村庄-四川 | [17491kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/四川_villages.htm) | [10376kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/四川_villages.json) | [4049kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/四川_villages.xlsx) | [10768kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/四川_villages.xml) | [5520kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/四川_villages_external.csv)  | [5673kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/四川_villages_internal.csv)  |        
| 中国村庄-天津 | [2120kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/天津_villages.htm) | [1175kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/天津_villages.json) | [493kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/天津_villages.xlsx) | [1706kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/天津_villages.xml) | [869kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/天津_villages_external.csv)  | [672kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/天津_villages_internal.csv)  |        
| 中国村庄-西藏 | [2013kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/西藏_villages.htm) | [1668kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/西藏_villages.json) | [512kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/西藏_villages.xlsx) | [1599kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/西藏_villages.xml) | [763kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/西藏_villages_external.csv)  | [631kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/西藏_villages_internal.csv)  |        
| 中国村庄-新疆 | [5816kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/新疆_villages.htm) | [4872kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/新疆_villages.json) | [1360kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/新疆_villages.xlsx) | [4683kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/新疆_villages.xml) | [2406kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/新疆_villages_external.csv)  | [1818kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/新疆_villages_internal.csv)  |        
| 中国村庄-云南 | [5555kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/云南_villages.htm) | [4644kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/云南_villages.json) | [1336kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/云南_villages.xlsx) | [4459kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/云南_villages.xml) | [2242kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/云南_villages_external.csv)  | [1763kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/云南_villages_internal.csv)  |        
| 中国村庄-浙江 | [9578kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/浙江_villages.htm) | [7977kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/浙江_villages.json) | [2320kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/浙江_villages.xlsx) | [7652kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/浙江_villages.xml) | [3751kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/浙江_villages_external.csv)  | [3054kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/浙江_villages_internal.csv)  |        
| 中国村庄-重庆 | [4374kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/重庆_villages.htm) | [3674kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/重庆_villages.json) | [990kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/重庆_villages.xlsx) | [3533kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/重庆_villages.xml) | [1831kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/重庆_villages_external.csv)  | [1409kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/重庆_villages_internal.csv)  |        


### 数据定义
```
        Create_Table_Statement
                = " CREATE TABLE Geography_Code ( "
                + "  gcid BIGINT NOT NULL GENERATED BY DEFAULT AS IDENTITY (START WITH 1, INCREMENT BY 1), "
                + "  predefined SMALLINT NOT NULL, " // 1: yes
                + "  level SMALLINT NOT NULL, " // global/continent/country/province(state)/city/county(region/district)/town/village/building
                + "  longitude DOUBLE NOT NULL, "
                + "  latitude DOUBLE NOT NULL, "
                + "  chinese_name VARCHAR(1028), "
                + "  english_name VARCHAR(1028), "
                + "  code1 VARCHAR(16), "
                + "  code2 VARCHAR(16), "
                + "  code3 VARCHAR(16), "
                + "  code4 VARCHAR(16), "
                + "  code5 VARCHAR(16), "
                + "  alias1 VARCHAR(1028), "
                + "  alias2 VARCHAR(1028), "
                + "  alias3 VARCHAR(1028), "
                + "  alias4 VARCHAR(1028), "
                + "  alias5 VARCHAR(1028), "
                + "  area BIGINT, " // km2
                + "  population BIGINT, "
                // below are references to build relationships among codes
                + "  continent BIGINT, "
                + "  country BIGINT, "
                + "  province BIGINT, " // or state
                + "  city BIGINT, "
                + "  county BIGINT, " // or region/district
                + "  town BIGINT, " // or street
                + "  village BIGINT, " //  or neighborhood
                + "  building BIGINT, "
                + "  comments VARCHAR(32672), "
                + "  PRIMARY KEY (gcid)"
                + " )";
```
           
```
        switch (level) {
            case 1:
                chineseName = "全球";
                englishName = "Global";
                break;
            case 2:
                chineseName = "洲";
                englishName = "Continent";
                break;
            case 3:
                chineseName = "国家";
                englishName = "Country";
                break;
            case 4:
                chineseName = "省";
                englishName = "Province";
                break;
            case 5:
                chineseName = "市";
                englishName = "City";
                break;
            case 6:
                chineseName = "县";
                englishName = "County";
                break;
            case 7:
                chineseName = "镇";
                englishName = "Town";
                break;
            case 8:
                chineseName = "村";
                englishName = "Village";
                break;
            case 9:
                chineseName = "建筑";
                englishName = "Building";
                break;
            case 10:
                chineseName = "兴趣点";
                englishName = "Point Of Interest";
                break;
        }
``` 

```
    public static final String Create_Index_levelIndex
            = " CREATE INDEX  Geography_Code_level_index on Geography_Code ( "
            + "  level, continent, country ,province ,city ,county ,town , village , building "
            + " )";

    public static final String Create_Index_gcidIndex
            = " CREATE INDEX  Geography_Code_gcid_index on Geography_Code ( "
            + "  gcid DESC, level, continent, country ,province ,city ,county ,town , village , building "
            + " )";

```

### 数据约束
地理代码应当：
1. 从属于一个已存在的地理代码。
2. 级别应当低于它的祖先。
3. 有中文名或者英文名。	

地理代码不必逐级从属，即可以跨级定义，例如：一个村庄直接属于南极洲；又如：城市直接属于国家，而没有省/州一级。   


### 数据匹配
以下方式之一可以确定一个地址：
1. 匹配数据标识（由MyBox自动赋值）。这是精确匹配。
2. 匹配“级别 + 祖先 + 中文名或英文名或任一别名”。这是精确匹配。
3. 匹配“级别 + 中文名或英文名或任一别名”。这是模糊匹配，可能有同级重名导致匹配错误的情况。   

匹配名字或者别名时，不区分大小写。     

有时候“代码”（code1/2/3/4/5）也可以辅助查找。    


```
    public static final String NameEqual
            = "( chinese_name IS NOT NULL AND LCASE(chinese_name)=? ) OR "
            + " ( english_name IS NOT NULL AND LCASE(english_name)=? ) OR "
            + " ( alias1 IS NOT NULL AND LCASE(alias1)=? ) OR "
            + " ( alias2 IS NOT NULL AND LCASE(alias2)=? ) OR "
            + " ( alias3 IS NOT NULL AND LCASE(alias3)=? ) OR "
            + " ( alias4 IS NOT NULL AND LCASE(alias4)=? ) OR "
            + " ( alias5 IS NOT NULL AND LCASE(alias5)=? )";


    public static String codeEqual(GeographyCode code) {
        if (code.getGcid() > 0) {
            return "gcid=" + code.getGcid();
        }
        int level = code.getLevel();
        String s = "level=" + level;
        switch (level) {
            case 3:
                s += " AND continent=" + code.getContinent();
                break;
            case 4:
                s += " AND continent=" + code.getContinent()
                        + " AND country=" + code.getCountry();
                break;
            case 5:
                s += " AND continent=" + code.getContinent()
                        + " AND country=" + code.getCountry()
                        + " AND province=" + code.getProvince();
                break;
            case 6:
                s += " AND continent=" + code.getContinent()
                        + " AND country=" + code.getCountry()
                        + " AND province=" + code.getProvince()
                        + " AND city=" + code.getCity();
                break;
            case 7:
                s += " AND country=" + code.getCountry()
                        + " AND province=" + code.getProvince()
                        + " AND city=" + code.getCity()
                        + " AND county=" + code.getCounty();
                break;
            case 8:
                s += " AND continent=" + code.getContinent()
                        + " AND country=" + code.getCountry()
                        + " AND province=" + code.getProvince()
                        + " AND city=" + code.getCity()
                        + " AND county=" + code.getCounty()
                        + " AND town=" + code.getTown();
                break;
            case 9:
            case 10:
                s += " AND continent=" + code.getContinent()
                        + " AND country=" + code.getCountry()
                        + " AND province=" + code.getProvince()
                        + " AND city=" + code.getCity()
                        + " AND county=" + code.getCounty()
                        + " AND town=" + code.getTown()
                        + " AND village=" + code.getVillage();
                break;
        }

        if (code.getChineseName() != null) {
            String name = stringValue(code.getChineseName()).toLowerCase();
            s += " AND  ( ( chinese_name IS NOT NULL AND LCASE(chinese_name)='" + name + "' ) OR "
                    + " ( alias1 IS NOT NULL AND LCASE(alias1)='" + name + "' ) OR "
                    + " ( alias2 IS NOT NULL AND LCASE(alias2)='" + name + "' ) OR "
                    + " ( alias3 IS NOT NULL AND LCASE(alias3)='" + name + "' ) OR "
                    + " ( alias4 IS NOT NULL AND LCASE(alias4)='" + name + "' ) OR "
                    + " ( alias5 IS NOT NULL AND LCASE(alias5)='" + name + "' ) ) ";

        } else if (code.getEnglishName() != null) {
            String name = stringValue(code.getEnglishName()).toLowerCase();
            s += " AND ( ( english_name IS NOT NULL AND LCASE(english_name)='" + name + "' ) OR "
                    + " ( alias1 IS NOT NULL AND LCASE(alias1)='" + name + "' ) OR "
                    + " ( alias2 IS NOT NULL AND LCASE(alias2)='" + name + "' ) OR "
                    + " ( alias3 IS NOT NULL AND LCASE(alias3)='" + name + "' ) OR "
                    + " ( alias4 IS NOT NULL AND LCASE(alias4)='" + name + "' ) OR "
                    + " ( alias5 IS NOT NULL AND LCASE(alias5)='" + name + "' ) ) ";
        }
        return s;
    }


    public static String codeEqual(String value) {
        String v = stringValue(value).toLowerCase();
        return " ( ( code1 IS NOT NULL AND LCASE(code1)='" + v + "' ) OR "
                + " ( code2 IS NOT NULL AND LCASE(code2)='" + v + "' ) OR "
                + " ( code3 IS NOT NULL AND LCASE(code3)='" + v + "' ) OR "
                + " ( code4 IS NOT NULL AND LCASE(code4)='" + v + "' ) OR "
                + " ( code5 IS NOT NULL AND LCASE(code5)='" + v + "' ) )  ";
    }
	
```



# [ReadMe in English](https://github.com/Mararsh/MyBox_data/tree/master/en)  ![ReadMe](https://mararsh.github.io/MyBox_data/iconOK.png)   

# MyBox的数据

## 适用范围
除了“MyBox内部格式”，其它格式均是自洽的：数据都是显值，可以被第三方应用直接使用。

“MyBox内部格式”和“MyBox外部格式”可用MyBox v6.3及以后的版本来导入/导出。   
-  MyBox内部格式：外键引用数据标识。好处是快速导入/导出，坏处是数据相互依赖。   
-  MyBox外部格式：数据都是显值。好处是自洽、可用于其它软件，坏处是导入/导出慢。

## 地理代码

### 数据源
| 引用内容 | 链接 |    
| --- | --- |   
| 国家的坐标/描述 | https://github.com/wizardcode/world-area |       
| 国家的代码/人口/面积 | https://www.geonames.org/countries/ |       
| 中国行政地名 | http://www.stats.gov.cn/tjsj/tjbz/tjyqhdmhcxhfdm/ |     
| 中国地址坐标 | https://lbs.amap.com/api/webservice/guide/api/georegeo   |     
 

### 下载

所有文件均是UTF-8编码。除了xlsx，其它格式均可用任意文本编辑器来查看和修改。  

最后更新时间：2020-4-25  

| 内容 | 格式 | 大小 | 链接 |    
| --- | --- | --- |  --- |   
| 全球、中国省份/城市/区县/乡镇/村庄-中文 | zip | 26mb | [Geography_Codes_Chinese.zip](https://github.com/Mararsh/MyBox_data/releases/download/v1.0/Geography_Codes_Chinese.zip) |       
| 全球、中国省份/城市/区县/乡镇-英文 | zip | 3046kb | [Geography_Codes_English.zip](https://github.com/Mararsh/MyBox_data/releases/download/v1.0/Geography_Codes_English.zip) |       

### 程序引用

以下均是直接链接，可以被程序访问到。  

| 内容 | html | json | xlsx | xml | MyBox外部格式 | MyBox内部格式 |
| --- | --- | --- | --- | --- | --- | --- |
| 洲 | [5kb](http://mararsh.github.io/MyBox_data/地理代码/全球/洲.htm) | [2kb](http://mararsh.github.io/MyBox_data/地理代码/全球/洲.json) | [5kb](http://mararsh.github.io/MyBox_data/地理代码/全球/洲.xlsx) | [2kb](http://mararsh.github.io/MyBox_data/地理代码/洲.xml) | [1kb](http://mararsh.github.io/MyBox_data/地理代码/全球/洲_external.csv)  | [1kb](http://mararsh.github.io/MyBox_data/地理代码/全球/洲_internal.csv)  |     
| 国家 | [165kb](http://mararsh.github.io/MyBox_data/地理代码/全球/国家.htm) | [152kb](http://mararsh.github.io/MyBox_data/地理代码/全球/国家.json) | [72kb](http://mararsh.github.io/MyBox_data/地理代码/全球/国家.xlsx) | [150kb](http://mararsh.github.io/MyBox_data/地理代码/国家.xml) | [107kb](http://mararsh.github.io/MyBox_data/地理代码/全球/国家_external.csv)  | [103kb](http://mararsh.github.io/MyBox_data/地理代码/全球/国家_internal.csv)  |     
| 中国省份 | [14kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国省份/中国省份.htm) | [9kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国省份/中国省份.json) | [8kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国省份/中国省份.xlsx) | [9kb](http://mararsh.github.io/MyBox_data/地理代码/洲.xml) | [4kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国省份/中国省份_external.csv)  | [4kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国省份/中国省份_internal.csv)  |    
| 中国城市 | [118kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国城市/中国城市.htm) | [84kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国城市/中国城市.json) | [42kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国城市/中国城市.xlsx) | [83kb](http://mararsh.github.io/MyBox_data/地理代码/洲.xml) | [39kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国城市/中国城市_external.csv)  | [35kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国城市/中国城市_internal.csv)  |    
| 中国区县 | [1041kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国区县/中国区县.htm) | [783kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国区县/中国区县.json) | [325kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国区县/中国区县.xlsx) | [769kb](http://mararsh.github.io/MyBox_data/地理代码/洲.xml) | [359kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国区县/中国区县_external.csv)  | [310kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国区县/中国区县_internal.csv)  |    
| 中国乡镇 |   |   |   |   | [5394kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国乡镇/中国乡镇_external.csv)  | [4495kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国乡镇/中国乡镇_internal.csv)  |     
| 中国村庄-安徽 |   |   |   |   | [2085kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/安徽_villages_internal.csv)  | [2706kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/安徽_villages_external.csv)  |      
| 中国村庄-北京 |   |   |   |   | [842kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/北京_villages_internal.csv)  | [1150kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/北京_villages_external.csv)  |      
| 中国村庄-福建 |   |   |   |   | [2503kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/福建_villages_internal.csv)  | [1150kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/福建_villages_external.csv)  |  
| 中国村庄-甘肃 |   |   |   |   | [2640kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/甘肃_villages_internal.csv)  | [2027kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/甘肃_villages_external.csv)  | 
| 中国村庄-广东 |   |   |   |   | [2946kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/广东_villages_internal.csv)  | [3822kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/广东_villages_external.csv)  |      
| 中国村庄-广西 |   |   |   |   | [1867kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/广西_villages_internal.csv)  | [2418kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/广西_villages_external.csv)  |    
| 中国村庄-贵州 |   |   |   |   | [2032kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/贵州_villages_internal.csv)  | [2742kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/贵州_villages_external.csv)  |  
| 中国村庄-海南 |   |   |   |   | [332kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/海南_villages_internal.csv)  | [491kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/海南_villages_external.csv)  |      
| 中国村庄-河北 |   |   |   |   | [6170kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/河北_villages_internal.csv)  | [8126kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/河北_villages_external.csv)  |     
| 中国村庄-河南 |   |   |   |   | [6145kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/河南_villages_internal.csv)  | [8155kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/河南_villages_external.csv)  | 
| 中国村庄-黑龙江 |   |   |   |   | [1630kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/黑龙江_villages_internal.csv)  | [2222kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/黑龙江_villages_external.csv)  |      
| 中国村庄-湖北 |   |   |   |   | [3299kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/湖北_villages_internal.csv)  | [4390kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/湖北_villages_external.csv)  |      
| 中国村庄-湖南 |   |   |   |   | [3255kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/湖南_villages_internal.csv)  | [4182kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/湖南_villages_external.csv)  |    
| 中国村庄-吉林 |   |   |   |   | [3255kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/吉林_villages_internal.csv)  | [1299kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/吉林_villages_external.csv)  |      
| 中国村庄-江苏 |   |   |   |   | [2529kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/江苏_villages_internal.csv)  | [3309kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/江苏_villages_external.csv)  |    
| 中国村庄-江西 |   |   |   |   | [2478kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/江西_villages_internal.csv)  | [3213kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/江西_villages_external.csv)  |      
| 中国村庄-辽宁 |   |   |   |   | [1906kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/辽宁_villages_internal.csv)  | [2553kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/辽宁_villages_external.csv)  |      
| 中国村庄-内蒙古 |   |   |   |   | [1691kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/内蒙古_villages_internal.csv)  | [2416kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/内蒙古_villages_external.csv)  |      
| 中国村庄-宁夏 |   |   |   |   | [323kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/宁夏_villages_internal.csv)  | [420kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/宁夏_villages_external.csv)  |      
| 中国村庄-青海 |   |   |   |   | [542kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/青海_villages_internal.csv)  | [732kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/青海_villages_external.csv)  |    
| 中国村庄-山东 |   |   |   |   | [8961kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/山东_villages_internal.csv)  | [11772kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/山东_villages_external.csv)  |      
| 中国村庄-山西 |   |   |   |   | [3197kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/山西_villages_internal.csv)  | [4135kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/山西_villages_external.csv)  |      
| 中国村庄-陕西 |   |   |   |   | [2277kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/陕西_villages_internal.csv)  | [2954kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/陕西_villages_external.csv)  |     
| 中国村庄-上海 |   |   |   |   | [703kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/上海_villages_internal.csv)  | [952kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/上海_villages_external.csv)  |      
| 中国村庄-四川 |   |   |   |   | [5406kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/四川_villages_internal.csv)  | [7118kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/四川_villages_external.csv)  |      
| 中国村庄-天津 |   |   |   |   | [640kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/天津_villages_internal.csv)  | [869kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/天津_villages_external.csv)  |      
| 中国村庄-西藏 |   |   |   |   | [599kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/西藏_villages_internal.csv)  | [763kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/西藏_villages_external.csv)  |      
| 中国村庄-新疆 |   |   |   |   | [1730kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/新疆_villages_internal.csv)  | [2406kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/新疆_villages_external.csv)  |      
| 中国村庄-云南 |   |   |   |   | [1678kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/云南_villages_internal.csv)  | [2242kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/云南_villages_external.csv)  |    
| 中国村庄-浙江 |   |   |   |   | [2904kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/浙江_villages_internal.csv)  | [3751kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/浙江_villages_external.csv)  |      
| 中国村庄-重庆 |   |   |   |   | [1344kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/内部格式/重庆_villages_internal.csv)  | [1831kb](http://mararsh.github.io/MyBox_data/地理代码/中国/中国村庄/外部格式/重庆_villages_external.csv)  |      


### 数据定义
```
        Create_Table_Statement
                = " CREATE TABLE Geography_Code ( "
                + "  dataid BIGINT NOT NULL GENERATED BY DEFAULT AS IDENTITY (START WITH 1, INCREMENT BY 1), "
                + "  predefined SMALLINT NOT NULL, " // 1: yes
                + "  level SMALLINT NOT NULL, " // global/continent/country/area/province(state)/city/county(region/district)/town/village/building
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
                + "  PRIMARY KEY (dataid)"
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

		





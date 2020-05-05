# [中文ReadMe](https://github.com/Mararsh/MyBox_data)  ![ReadMe](https://mararsh.github.io/MyBox_data/iconOK.png)  

# Data of MyBox
Here are data for MyBox.

## Application
Except for "MyBox internal format", other formats are self-consistent, that is data are written as values and can be used directly by other applications.    

All files are in UTF-8 encoding. Except for xlsx, all formats can be viewed and updated by any text editor.   

“MyBox internal format” and “MyBox external format” can be imported into MyBox v6.3 and later versions.    
-  MyBox internal format refers to data ids for foreign keys. Its advantage is quicker importing/exporting, while its disadvantage is that data are dependant on others.   
-  MyBox external format holds all of data values. Its advantage is self-consistent, while its disadvantage is slow importing/exporting.    

## Geography Code

### Data Sources

| Reference | Link |    
| --- | --- |   
| Coordinates and description of countries | https://github.com/wizardcode/world-area |       
| Area, populations, and codes of countries | https://www.geonames.org/countries/ |       
| Addresses of China | http://www.stats.gov.cn/tjsj/tjbz/tjyqhdmhcxhfdm/ |       
| Coordinates of Chinese addresses | https://lbs.amap.com/api/webservice/guide/api/georegeo   |     
 

### Download

Last Updated: 2020-4-25  

| Contents | Format | Size | Link |    
| --- | --- | --- |  --- |   
| Global, China's provinces/cities/counties/towns/villages-Chinese | zip | 26mb | [Geography_Codes_Chinese.zip](https://github.com/Mararsh/MyBox_data/releases/download/v1.0/Geography_Codes_Chinese.zip) |       
| Global, China's provinces/cities/counties-English | zip | 3046kb | [Geography_Codes_English.zip](https://github.com/Mararsh/MyBox_data/releases/download/v1.0/Geography_Codes_English.zip) |       

### Referred by Programs 

Following are direct links which can be visited by codes.     

| Contents | html | json | xlsx | xml | MyBox external format | MyBox internal format |
| --- | --- | --- | --- | --- | --- | --- |
| Continents | [5kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Continents.htm) | [2kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Continents.json) | [5kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Continents.xlsx) | [2kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Continents.xml) | [1kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Continents_external.csv)  | [1kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Continents_internal.csv)  |     
| Countries | [98kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Countries.htm) | [82kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Countries.json) | [40kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Countries.xlsx) | [81kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Countries.xml) | [40kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Countries_external.csv)  | [34kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Countries_internal.csv)  |     
| ChinaProvinces | [14kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaProvinces/ChinaProvinces.htm) | [9kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaProvinces/ChinaProvinces.json) | [8kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaProvinces/ChinaProvinces.xlsx) | [9kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Continents.xml) | [5kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaProvinces/ChinaProvinces_external.csv)  | [4kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaProvinces/ChinaProvinces_internal.csv)  |    
| ChinaCities | [125kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCities/ChinaCities.htm) | [90kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCities/ChinaCities.json) | [42kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCities/ChinaCities.xlsx) | [89kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Continents.xml) | [45kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCities/ChinaCities_external.csv)  | [35kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCities/ChinaCities_internal.csv)  |    
| ChinaCounties | [1104kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCounties/ChinaCounties.htm) | [846kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCounties/ChinaCounties.json) | [326kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCounties/ChinaCounties.xlsx) | [833kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Continents.xml) | [422kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCounties/ChinaCounties_external.csv)  | [310kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCounties/ChinaCounties_internal.csv)  |    
| ChinaTowns |   |   |   |   | [5394kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaTowns/ChinaTowns_external.csv)  | [4495kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaTowns/ChinaTowns_internal.csv)  |      

### Data Defination
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

		



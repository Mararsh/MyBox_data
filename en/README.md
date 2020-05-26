# [中文ReadMe](https://github.com/Mararsh/MyBox_data)  ![ReadMe](https://mararsh.github.io/MyBox_data/iconTips.png)  

# Data of MyBox  

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

Last Updated: 2020-5-15  Fix error about country "Burkina Faso".

| Contents | Format | Size | Link |    
| --- | --- | --- |  --- |   
| Global Geography Codes in Chinese | zip | 318kb | [Global_zh.zip](https://github.com/Mararsh/MyBox_data/releases/download/v1.2/Global_zh.zip) |       
| Chinese Geography Codes in Chinese | zip | 103mb | [China_zh.zip](https://github.com/Mararsh/MyBox_data/releases/download/v1.2/China_zh.zip) |       
| Global Geography Codes in English | zip | 319kb | [Global_en.zip](https://github.com/Mararsh/MyBox_data/releases/download/v1.2/Global_en.zip) |       
| Chinese Geography Codes in English | zip | 2915kb | [China_en.zip](https://github.com/Mararsh/MyBox_data/releases/download/v1.2/China_en.zip) |       


### Referred by Programs 

Following are direct links which can be visited by codes.     

| Contents | html | json | xlsx | xml | MyBox external format | MyBox internal format |
| --- | --- | --- | --- | --- | --- | --- |
| Continents | [5kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Continents.htm) | [2kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Continents.json) | [5kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Continents.xlsx) | [2kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Continents.xml) | [1kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Continents_external.csv)  | [1kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Continents_internal.csv)  |     
| Countries | [98kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Countries.htm) | [82kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Countries.json) | [40kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Countries.xlsx) | [81kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Countries.xml) | [40kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Countries_external.csv)  | [34kb](http://mararsh.github.io/MyBox_data/Geography_Codes/Global/Countries_internal.csv)  |     
| ChinaProvinces | [14kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaProvinces/ChinaProvinces.htm) | [9kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaProvinces/ChinaProvinces.json) | [8kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaProvinces/ChinaProvinces.xlsx) | [9kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaProvinces/ChinaProvinces.xml) | [5kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaProvinces/ChinaProvinces_external.csv)  | [4kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaProvinces/ChinaProvinces_internal.csv)  |    
| ChinaCities | [125kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCities/ChinaCities.htm) | [90kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCities/ChinaCities.json) | [42kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCities/ChinaCities.xlsx) | [89kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCities/ChinaCities.xml) | [45kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCities/ChinaCities_external.csv)  | [35kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCities/ChinaCities_internal.csv)  |    
| ChinaCounties | [1104kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCounties/ChinaCounties.htm) | [846kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCounties/ChinaCounties.json) | [326kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCounties/ChinaCounties.xlsx) | [833kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCounties/ChinaCounties.xml) | [422kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCounties/ChinaCounties_external.csv)  | [310kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaCounties/ChinaCounties_internal.csv)  |    
| ChinaTowns |   |   |   |   | [5394kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaTowns/ChinaTowns_external.csv)  | [4495kb](http://mararsh.github.io/MyBox_data/Geography_Codes/China/ChinaTowns/ChinaTowns_internal.csv)  |      

### Data Defination
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

### Data Constrains
Geography code should:
1. Be subordinate to an existed geography code.
2. Its level should be lower than its ancestors'.
3. Has either Chinese name or English name.
	
Geography code is not necessary to belong to parent level by level. That is, it can cross levels. Example, a village can be subordinate to Antarctica directly. And a city can be child of a country without province/state level.    
 

### Data Matching
One of following can determine an address:
1. Match “dataid"(assigned by MyBox automatically). This is accurate matching.
2. Match "level + ancestors + chinese_name/english_name/alias". This is accurate matching.
3. Match "level + chinese_name/english_name/alias". This is fuzzy matching. Duplicated names in same level can cause false matching.    
       
Matching of name or alias is case-insensitive.    

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




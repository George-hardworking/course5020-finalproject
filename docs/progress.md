1. 原始数据解读
/raw
    /countries_shapefile
        cn_primary_countries.cpg        记录属性表使用的字符编码
        cn_primary_countries.dbf        国家边界属性表（国家名、代码等）
        cn_primary_countries.prj        投影坐标系定义文件
        cn_primary_countries.shp        国家边界矢量几何主体
        cn_primary_countries.shx        几何索引文件，加速 shapefile 访问
    /trade_data
        baci_hs12_y2016_v202001.csv    BACI HS12 2016 年双边贸易额（出口额/数量）
        baci_hs12_y2017_v202001.csv    BACI HS12 2017 年双边贸易额（出口额/数量）
        baci_hs12_y2018_v202001.csv    BACI HS12 2018 年双边贸易额（出口额/数量）
        country_codes_v202001.csv      BACI 使用的国家代码与 ISO 对照表
        product_codes_hs12_v202001.csv HS12 商品代码与产品描述映射
    api_ny_gdp_mktp_cd_ds2.csv          世界银行 GDP（现价美元）按国家年度数据

2. 
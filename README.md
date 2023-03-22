# README

选择的数据集有两个，分别为：

- [Alzheimer Disease and Healthy Aging Data in US](https://www.kaggle.com/datasets/ananthu19/alzheimer-disease-and-healthy-aging-data-in-us)

- [Movies Dataset from Pirated Sites](https://www.kaggle.com/datasets/arsalanrehman/movies-dataset-from-piracy-website)





## 1 美国阿尔茨海默病与健康老龄化数据

### 1.1 数据说明

数据集地址为：[Alzheimer Disease and Healthy Aging Data In US | Kaggle](https://www.kaggle.com/datasets/ananthu19/alzheimer-disease-and-healthy-aging-data-in-us)

说明：

> 数据集中的阿尔茨海默病和健康老龄化数据是关于美国老年人健康和福祉的全面数据收集。该数据集包括有关各种变量的信息，例如人口统计特征、健康状况、医疗保健利用率和健康行为。
>
> 该数据集由疾病控制和预防中心（CDC）编制，包括来自几项国家调查的数据，包括行为风险因素监测系统（BRFSS），国家健康和营养检查调查（NHANES）和全国健康访谈调查（NHIS）。
>
> 该数据集的主要重点是阿尔茨海默病和相关痴呆症，包括患病率、发病率、风险因素和结果。这些数据可用于确定这些疾病的患病率和发病率的趋势和模式，以及探索可能有助于预防或减轻其影响的潜在风险因素和干预措施。

数据字段

|           label           | describe                                                     |               说明               |
| :-----------------------: | ------------------------------------------------------------ | :------------------------------: |
|         YearStart         | The year the data collection began                           |        数据收集开始的年份        |
|          YearEnd          | The year the data collection ended                           |        数据收集结束的年份        |
|       LocationAbbr        | The abbreviation for the location where the data was collected |        数据收集位置的缩写        |
|       LocationDesc        | The full name of the location where the data was collected.  |       收集数据的位置的全名       |
|        Datasource         | The source of the data                                       |              数据源              |
|           Class           | The class of the data                                        |             数据分类             |
|           Topic           | The topic of the data                                        |            数据的主题            |
|         Question          | The question related to the data.                            |         与数据相关的问题         |
|      Data_Value_Unit      | The unit of measurement for the data value                   |           数据测量单位           |
|      DataValueTypeID      | The ID for the type of data value                            |           数据值类型ID           |
|      Data_Value_Type      | The type of data value (e.g. mean, percentage)               |           数据值的类型           |
|        Data_Value         | The actual data value                                        |              数据值              |
|      Data_Value_Alt       | An alternative data value, if applicable                     |   一个替代数据值，如果适用的话   |
|   Low_Confidence_Limit    | The lower limit of the confidence interval for the data value |       数据值置信区间的下限       |
|   High_Confidence_Limit   | The upper limit of the confidence interval for the data value |       数据值置信区间的上限       |
|        Sample_Size        | The size of the sample used to collect the data              |     用于收集数据的样本的大小     |
|  StratificationCategory1  | The first category used for stratification (e.g. age group)  | 用于分层的第一个类别（例如年龄） |
|      Stratification1      | The specific stratification used (e.g. 18-24 years old)      |  使用的特定分类（例如18-24岁）   |
|  StratificationCategory2  | The second category used for stratification, if applicable   |     如果可以，用于第二级分类     |
|      Stratification2      | The specific stratification used for the second category, if applicable |  如果适用，用于第二类的具体分层  |
|        Geolocation        | The latitude and longitude of the location where the data was collected |    收集数据的位置的纬度和经度    |
|          ClassID          | The ID for the class of the data                             |         数据所属类型的ID         |
|          TopicID          | The ID for the topic of the data                             |            数据主题ID            |
|        QuestionID         | The ID for the question related to the data                  |       与数据相关的问题的ID       |
|        LocationID         | The ID for the location where the data was collected         |         收集数据地区的ID         |
| StratificationCategoryID1 | The ID for the first category used for stratification        |         用于一级分类的ID         |
|     StratificationID1     | The ID for the specific stratification used for the first category |       一级分类具体内容的ID       |
| StratificationCategoryID2 | The ID for the second category used for stratification, if applicable |           二级分类的ID           |
|     StratificationID2     | The ID for the specific stratification used for the second category, if applicable |         二级分类内容的ID         |



### 1.2 代码使用说明

代码文件为：healthy.ipynb

代码中需要安装的包有：numpy 、pandas、  matplotlib、  seaborn

数据集 的CSV文件，需要和代码文件放在同一目录下

代码在ipynb文件当中，只需要在jupyter中运行即可





## 2、 盗版网站的电影数据

### 2.1 数据说明

数据集地址为：🎥 Movies Dataset from Pirated Sites | Kaggle](https://www.kaggle.com/datasets/arsalanrehman/movies-dataset-from-piracy-website)

说明：

> 该数据集是从盗版网站收集的，该网站的用户群每月约有2万访问者。该数据包含来自好莱坞，宝莱坞，动漫等所有行业的20000 +电影。

数据字段

|      label      |                 describe                 |
| :-------------: | :--------------------------------------: |
|       id        |            movie's unique id             |
|      title      |               movie's name               |
|    storyline    |     a short description of the movie     |
|      views      |         no. of clicks per movie          |
|    downloads    |        no. of downloads per movie        |
|   IMDb-rating   |                  rating                  |
| appropriate_for |           R-rated, PG-13, etc            |
|    language     |   this can be multiple languages also    |
|    industry     |        Hollywood, Bollywood, etc         |
|   posted_date   | when the movie is posted on the platform |
|  release_date   |   when the movie is released worldwide   |
|     runtime     |                in minutes                |
|    director     |             director's name              |
|     writer      |         list of all the writers          |



### 2.2 代码使用说明

代码文件为movies.ipynb

代码中需要安装的包有：numpy 、pandas、  matplotlib、  seaborn

数据集 的CSV文件，需要和代码文件放在同一目录下

代码在ipynb文件当中，只需要在jupyter中运行即可
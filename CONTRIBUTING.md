# 一、目录结构

- dictionary
  - A.csv
  - B.csv
  - N.csv
  - M.csv
  - ……
- index_A_M.csv
- index_N_Z.csv



dictionary里面存放具体翻译，以首字母分子文件

index视具体条目多少适当分割，用于快速索引



# 二、字典结构



|  ID  |   词/词组    |  翻译  |                       详解                       |        示例         |  分类  |
| :--: | :----------: | :----: | :----------------------------------------------: | :-----------------: | :----: |
|  1   | block shield | 方块墙 | 采矿机里常见的，前面推个11 12m厚度来排水的方块墙 | 视频BV...，几分几秒 | 采矿机 |



# 三、index结构

index其实就是记一下有没有这个词，不用一个个去翻

|     单词     |  分类  | 条目 |
| :----------: | :----: | :--: |
| block shield | 采矿机 |  B   |


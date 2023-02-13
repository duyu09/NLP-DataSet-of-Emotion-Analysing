# NLP Data Set of Emotion Analysing

## 说明

Emotion analyse data sets for natural language processing.

这是套用于自然语言处理文本情感分析的数据集。

## 更新日志

## Update on February 13th, 2023

上传了EmotionNLP(Simplified-Chinese).zip，里面压缩了一个简体中文的通用文本情感分析数据集(CSV格式)。

数据集结构说明：该数据集有两个字段，第一列为文本数据，第二列为标签，其中0表示消极情绪(或贬义语义)，1表示积极情绪(或褒义语义)。

数据量：该数据集的数据量为287936行。

数据来源与内容：文本主要来自于某些大型数据集的合并：1.微博网友对各类博文与帖子的评论。2.旅客在某些酒店的官方网站上，对这些酒店的评价。3.消费者在国内各大电商网购各类商品后，对商品的售后评价。4.某些视频网站上，网友对多部电影的评价。5.一些比较经典的，能够反映人积极或消极情绪的书面语。

数据集效果：随机挑选积极与消极文本各6000条，投喂到百度的EasyDL里进行高精度模式下的训练，测得模型的综合准确度为94.01%。若使用完整的数据集，预计准确度可达到98%~99%左右。

数据处理情况：进行了简单的数据清洗工作 (对原始数据进行了合并和去除空项，删除了一些明显不合适的项，最后对剩下的数据随机排序)，如需用于商业，建议对数据作进一步处理。

## 访客统计

<div>Number of Total Visits: &nbsp; <img src="https://visitor-badge.glitch.me/badge?page_id=Duyu09_NLP_DataSet_of_Emotion_Analysing" /></div>


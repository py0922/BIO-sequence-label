# BIO-sequence-label
BIO模式的-命名实体识别等任务的序列标注工具

笔者研究方向为NLP知识抽取，做实体识别实验过程中需要对训练数据进行标注。
我先使用jieba分词对原文本进行分词和pos词性标注，然后基于pos词性标注抽取出文本中的公司名、证券、基金名称（这部分也可以使用正则方法）等，保存到word_dict.txt中作为词典，然后基于该词典对原文本中进行的数据进行标注。
INT与BON文本对应的标签。
占位词 NONE，这一行必须要有，作为词典的停止关键词
word_dict.txt如下：


# kesic-text_classification
kesic的文本分类练习赛，网址是：https://www.kesci.com/home/competition/5c77ab9c1ce0af002b55af86，参考了这位同学的开源：https://github.com/willinseu/kesci-urdu-sentiment-analysis
其中lstm模型是使用深度学习来完成文本识别的，我使用了lstm和gru的平均连接。
sgd模型使用了sklearn中的SGDClassifier，这是一个经常用于文本问题的分类器。
lgb模型是将tf-idf后的模型直接送入到lgb分类器，在这里使用了贝叶斯优化进行调参的技术。

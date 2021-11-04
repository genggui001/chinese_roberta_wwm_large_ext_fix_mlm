chinese_roberta_wwm_large_ext_fix_mlm
===========================

锁定其余参数，只训练缺失mlm部分参数

语料：[nlp_chinese_corpus](https://github.com/brightmart/nlp_chinese_corpus)

训练平台：Colab [白嫖Colab训练语言模型教程](https://github.com/genggui001/everyone_can_pretrain_language_model)

基础框架：苏神的[bert4keras](https://github.com/bojone/bert4keras)

----------------------------

模型参数下载地址：

百度网盘：[链接](https://pan.baidu.com/s/1hK8hgyXinKzlMn9lZHA-SA) 提取码：a7p9

----------------------------

训练参数：

```
sequence_length = 512
batch_size = 512
learning_rate = 5e-4
weight_decay_rate = 0.01
num_warmup_steps = 0
num_train_steps = 250000
```

训练效果

```
mlm_loss = 1.987841
mlm_acc = 0.601258
```
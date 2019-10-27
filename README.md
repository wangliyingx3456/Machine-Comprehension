# Machine-Comprehension
测试机器阅读理解的模型及数据集。

## 模型

### BiDAF 模型

BiDAF 模型。

## 数据集

### SQuAD 数据集

使用 [transformers](https://github.com/huggingface/transformers) 封装的 BERT fine-tunning on SQuAD，参考 [Fine-tuning on SQuAD](https://huggingface.co/transformers/examples.html#fine-tuning-on-squad)。使用 BertForQuestionAnswering 模型测试 SQuAD 数据集。

###  CMRC2018

 使用 BertForQuestionAnswering 模型测试 CMRC2018 数据集。dev 测试结果：F1: 82.192, EM: 61.572。

### RACE 数据集

使用 [transformers]( https://github.com/huggingface/transformers) 提供的 [run_multiple_choice.py](https://github.com/huggingface/transformers/blob/master/examples/run_multiple_choice.py) 样例，使用 RobertaForMultipleChoice 模型测试 RACE 数据集。

### SWAG 数据集

使用 RobertaForMultipleChoice 模型测试 SWAG数据集。dev 测试结果为：eval_acc = 0.8213。








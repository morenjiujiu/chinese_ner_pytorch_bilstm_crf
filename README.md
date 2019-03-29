# chinese_ner_pytorch_bilstm_crf
中文命名体识别，采用pytorch官方提供的BiLSTM+CRF

## 运行环境
- python3
- pytorch1.0.1

## 数据说明
- 摘取自网络上人民日报的数据，标签有O，B-ORG，I-ORG，B-PER，I-PER，B-LOC，I-LOC几种，识别组织机构、人名、地名


## 程序说明
- pytorch 官方给出的方案[https://pytorch.org/tutorials/beginner/nlp/advanced_tutorial.html#sphx-glr-beginner-nlp-advanced-tutorial-py](https://pytorch.org/tutorials/beginner/nlp/advanced_tutorial.html#sphx-glr-beginner-nlp-advanced-tutorial-py)
- 官方给出的例子中没有实现batch化，都是batch=1操作的，运行速度慢
- 本文利用官方的demo进行了中文命名体识别的验证，batch化操作还希望有大家指路^_^



![gpt2-ml](./.github/logo.png)
# GPT2 for Multiple Languages

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/imcaspar/gpt2-ml/blob/master/pretrained_model_demo.ipynb)
![GitHub](https://img.shields.io/github/license/imcaspar/gpt2-ml)
![GitHub All Releases](https://img.shields.io/github/downloads/imcaspar/gpt2-ml/total)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/imcaspar/gpt2-ml/issues)
![GitHub stars](https://img.shields.io/github/stars/imcaspar/gpt2-ml?style=social)
![Twitter Follow](https://img.shields.io/twitter/follow/imcaspar?style=social)

[**中文说明**](./README.md) | [**English**](./README_EN.md)

- [x] 简化整理 GPT2 训练代码（based on grover）
- [x] 移植 bert tokenizer，添加多语言支持
- [x] 15亿参数 GPT2 中文预训练模型


## 预训练模型
15亿参数中文预训练模型 [Google Drive 下载](https://drive.google.com/open?id=1_6Py_UEGSAMt2RCq_dxsGNfpF4jMhm-5)

训练语料来自 [THUCNews](http://thuctc.thunlp.org/#%E4%B8%AD%E6%96%87%E6%96%87%E6%9C%AC%E5%88%86%E7%B1%BB%E6%95%B0%E6%8D%AE%E9%9B%86THUCNews) 以及 [nlp_chinese_corpus](https://github.com/brightmart/nlp_chinese_corpus)，清洗后总文本量约 15G 

使用 [Cloud TPU Pod v3-256](https://cloud.google.com/tpu/docs/types-zones#types) 训练 10w 步

![loss](./.github/loss.png)


## Google Colab


## 训练


## Reference
https://github.com/google-research/bert

https://github.com/rowanz/grover

Research supported with Cloud TPUs from Google's TensorFlow Research Cloud (TFRC)
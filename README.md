# Chinese-Clinical-Terminology-Standardization-Task

基于LLM实现CHIP2021-Task3中文临床术语标准化任务，准确率约70%。

原题：[http://cips-chip.org.cn/2021/eval3](http://cips-chip.org.cn/2021/eval3).

中文医疗信息处理数据集CBLUE：[https://tianchi.aliyun.com/dataset/dataDetail?dataId=95414](https://tianchi.aliyun.com/dataset/dataDetail?dataId=95414).

底座生成模型使用的是类型为llama的[shibing624/ziya-llama-13b-medical-merged](https://huggingface.co/shibing624/ziya-llama-13b-medical-merged)模型。

本作业参考代码仓库[shibing624/MedicalGPT](https://github.com/shibing624/MedicalGPT/tree/main)，感谢该项目作者:rose:。

更具体内容可查看[复现教程.ipynb](复现教程.ipynb)。

训练完的LORA模型下载地址[百度网盘](https://pan.baidu.com/s/1Y4xCbVls0ZC_J9qTHw6fUg)，提取码：fsiy。

这个项目是西北工业大学计算机学院《自然语言处理》课程大作业，作者已用该作业取得该课程满绩，现已结课，分享给大家参考，希望能帮助更多人学习，如果对你产生了启发希望能给个小星星:star2:，感谢~

本项目不作盈利目的，仅供学习交流用。如果本项目侵犯了您的合法权益请及时联系我，我会及时删除相关侵权内容。

本项目仅可应用于研究目的，项目开发者不承担任何因使用本项目（包含但不限于数据、模型、代码等）导致的危害或损失。详细请参考[免责声明](DISCLAIMER)。

项目代码的授权协议为[The Apache License 2.0](LICENSE)，代码可免费用做商业用途，模型权重和数据只能用于研究目的。请在产品说明中附加MedicalGPT的链接和授权协议。

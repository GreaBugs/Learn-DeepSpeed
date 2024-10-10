### 注意事项
* 工程运行前，注意检查子模块版本是否正确

### 环境准备
``` bash
pip install deepspeed==0.9.0

git clone git@github.com:GreaBugs/Learn-DeepSpeedExamples.git
cd DeepSpeedExamples/applications/DeepSpeed-Chat
pip install -r requirements.txt

## 一键训练
cd DeepSpeedExamples/applications/DeepSpeed-Chat
python e2e_rlhf.py --actor-model facebook/opt-13b --reward-model facebook/opt-350m --deployment-type single_node
```

### 官方提供预训练权重
[预训练模型](https://huggingface.co/facebook/opt-1.3b)

### Debug步骤
1. 模型训练

2. 模型评测

3. 
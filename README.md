# llm-learn
## 更新2025.3
### RL(GRPO)Qwen2.5-0.5B-Instruct
由于本人的女朋友数学成绩很差，所以想尝试使用强化学习训练开源大模型，增强大模型的数学解题能力，外加产生解题COT的能力。所以模仿deepseek-r1-zero训练方法，训练具有推理能力的大模型。
作为一次小小的尝试，数据集选择：https://huggingface.co/datasets/swulling/gsm8k_chinese ,模型选择：Qwen2.5-0.5B-Instruct，框架使用的是:trl。模型上传至: https://huggingface.co/huihui1234/qwen2.5-05b-gsmrl

效果真的很一般，模型太小了，这是checkpoint-300和checkpoint-500的结果：
![图片](https://github.com/user-attachments/assets/0697d63c-ac59-4068-964d-c633e611f459)
![图片](https://github.com/user-attachments/assets/23169dca-4420-465f-aedf-6c756d0d2960)

# 隧道地质LVLM评估数据集

* [英文](./readme.md)

<image src="./images/Geo-LVLM.png" width="200" height="200" />

## 评估数据集
* **常见场景**：来源于[CogVLM-SFT-311K](https://github.com/THUDM/CogVLM/blob/main/dataset.md)数据集，提供了与隧道施工相关的多样化视觉场景。
* **复杂推理**：需要对开挖面进行多维度分析的任务，整合地质、结构和操作数据。
* **单一特征判断**：专注于隧道施工过程中某个特定、独立的方面，例如识别岩石类型或评估结构完整性。
* **支持参数问答**：与隧道施工中支持参数相关的问题-答案对，帮助理解关键工程决策。
* **隧道知识问答**：基于隧道相关知识的问题-答案对，促进对施工方法和安全协议的深入理解。

### 1. 数据集组成
- **图像**：数据集包含281张从隧道施工现场拍摄的高分辨率图像。
- **知识**：包含197条精心整理的隧道相关知识，涵盖技术规范、安全指南、施工方法及其他相关信息。

### 2. 视觉判别分类
- **单一特征判断**：此类任务专注于隧道施工中开挖面暴露的某个单一、特定的方面。例如，识别岩石类型或评估某个结构部件的状况。
- **复杂推理**：此类任务需要进行更复杂的分析，要求整合多个数据点。例如，识别潜在风险并对围岩条件进行全面评估。

### 3. 领域知识
知识库来源于**隧道设计与施工规范**，确保所有信息符合行业标准和最佳实践。

### 4.说明
部分数据使用chatGPT生成，可能存在错误，请勿直接用于实际生产中。
## 引用
```bibtex
@misc{sungatetop,
      title={LVLM Evaluation Dataset for Tunnel Geology}, 
      author={Baolin Chen and Jiawei Xie},
      howpublished={\url{https://github.com/sungatetop/geology-vllm.git}},
      year={2024},
}
```

该数据集旨在为隧道地质领域的VLLM评估和研究提供支持。

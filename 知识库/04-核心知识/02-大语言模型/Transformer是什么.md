# Transformer是什么

## 1. 一句话说明

Transformer是一类组织神经网络内部计算的模型架构，注意力机制是其关键组成部分之一。

## 2. 生活类比

工厂布局描述车间怎样组织；工人怎样学习、处理什么材料、执行什么任务，是另外几个问题。这个类比只帮助区分观察层次。

## 3. 正式概念

Transformer属于模型架构层。深度神经网络是较宽泛的结构类别，Transformer是更具体的架构家族。不能只凭它判断模型采用何种学习方式、处理什么模态或执行什么任务；这些维度有区别，也需要在实际设计中配合。注意力机制的细节仍留待第20天，不在本卡认定已掌握。

## 4. 可视化原理

结构类别：深度神经网络
↓ 其中的一类架构
Transformer
↓ 内部关键组成之一
注意力机制

## 5. 现实例子

第19天案例：采用Transformer、通过监督学习训练、输入产品照片、判断有无缺陷。分别对应架构、学习方式、图像模态和分类任务。

## 6. 常见误解

- Transformer就是监督学习：前者是架构，后者是学习方式。
- Transformer只能处理文字：可用于图像等任务，取决于具体设计和训练。
- 注意力就是人的意识：这里只是计算机制名称。
- 不同分类维度完全互不影响：实际设计仍需配合。

## 7. 与其他知识的联系

[[04-核心知识/01-AI基础/什么是大语言模型|大语言模型]]常采用Transformer。[[模型训练|训练]]与[[模型推理|推理]]描述形成能力和使用能力；架构说明计算模块如何组织。细分层级的独立表达见[[08-学习记录/问题清单|待复检项]]。

## 8. 三道理解检查题

1. Transformer、监督学习、图像和分类分别回答什么问题？
2. 能仅凭架构判断输入模态吗？
3. Transformer与注意力机制是什么关系？

## 9. 来源和复核日期

- [Google Transformer课程](https://developers.google.com/machine-learning/crash-course/llm/transformers)。
- [Google机器学习术语表](https://developers.google.com/machine-learning/glossary)。


### 主张映射

- 主张：Transformer是语言模型常用的一类神经网络架构；类型：解释；来源：[Google Transformer课程](https://developers.google.com/machine-learning/crash-course/llm/transformers)
- 主张：注意力机制是Transformer的重要内部组成；类型：解释；来源：[Google Transformer课程](https://developers.google.com/machine-learning/crash-course/llm/transformers)

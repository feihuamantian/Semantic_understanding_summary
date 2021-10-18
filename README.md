# Semantic_understanding_summary
语义理解模型信息汇总
#### 百度语义理解模型
url：https://github.com/PaddlePaddle/PaddleNLP/tree/develop/examples/text_matching/question_matching
介绍：（1）采用ernie-gram预训练模型进行初始化处理，ernie-gram模型融入实体预训练的方式，提升了实体的表达能力
     （2）将R-Drop机制引入到语义理解当中，保证dropout后结果的一致性
#### query对语义一致性分类
url：https://github.com/fuxuelinwudi/2021-qianyan-question-matching
介绍：（1）采用华为的 NA-ZHA预训练模型初始化
      （2）直接取模型的输出进行二分类

# pm_tb_classification
肺炎肺结核分类
问题：肺炎肺结核假阳性 数据不均衡（2:6:1）
病灶征象类型有重叠 对病灶进行分类时 学要结合额外的医生知识进行判断

Backbone: DenseNet121, SwinT

Input:original胸片，lung region， lession region Concatnate

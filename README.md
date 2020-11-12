# 使用Amazon Sagemaker 与 BERT PyTorch实现文本多分类
 

实验内容
 
 - 使用 [huggingface](https://huggingface.co/transformers/pretrained_models.html) 在 [Amazon Sagemaker](https://docs.aws.amazon.com/sagemaker/latest/dg/pytorch.html) 训练 [BERT](https://www.aclweb.org/anthology/N19-1423/)。 通过使用 [Spot instances](https://docs.aws.amazon.com/sagemaker/latest/dg/model-managed-spot-training.html). 来降低训练成本。

  
使用Jupyternote book [BertTextClassification.ipynb](BertTextClassification.ipynb)开始实验。
 
 ## 数据集
 使用[Dbpedia ontology dataset](https://wiki.dbpedia.org/services-resources/dbpedia-data-set-2014#2)数据集, 关于数据集的更多信息，请查看 https://wiki.dbpedia.org/services-resources/dbpedia-data-set-2014#2
 
 ### Customise for your dataset
 In order to customise this sample, for your own dataset, perform the following steps

            

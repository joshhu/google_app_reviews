# 使用Bert進行多分類問題

## 說明

使用Google Play上面的app星評分析，原來5顆星變成三類，壞、中、好(0,1,2)，然後使用huggingface的transformers中的model = BertForSequenceClassification.from_pretrained('bert-base-cased', num_labels=3)。

## 重點

載入模型時的類別數設定`num_labels=3`。

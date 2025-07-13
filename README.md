# “Misinformation Detection and Generation Using Large Language Models” - Fine-tuning 


في هذا المشروع قمت بتجربة عدة إعدادات، منها معدلات تعلم مختلفة (Learning Rates) بهدف تحسين أداء النموذج ودقّة التنبؤ.

⸻

This script performs the following steps:
	•	✅ Loads and preprocesses synthetic news datasets (LLMFake).
 
	•	✅ Splits the data into training, validation, and test sets.
 
	•	✅ Loads a pre-trained BERT model (bert-base-uncased) and adapts it for binary classification (True / Misinformation).
 
	•	✅ Trains the model with early stopping to prevent overfitting.
 
	•	✅ Calculates evaluation metrics (accuracy, precision, recall, F1-score).
	•	✅ Runs inference on example texts and prints predictions.
	•	✅ Reports final evaluation results on the test set.

⸻

هذا التطبيق يعكس جانبًا من استكشافي لاستراتيجيات Fine-tuning لنماذج اللغة الكبيرة بهدف الكشف التلقائي عن الأخبار المضللة في البيانات الحقيقية والمولدة.

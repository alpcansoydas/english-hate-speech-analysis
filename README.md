# english-hate-speech-analysis

In this work, hate speech recognition system is implemented in English.

This model is a fine-tuned version of YSKartal/bert-base-turkish-cased-turkish_offensive_trained_model and dbmdz/bert-base-turkish-cased.

Used dataset is from https://huggingface.co/datasets/badmatr11x/hate-offensive-speech

Evaluation results for the limited number of data:

<img width="488" alt="Screenshot 2023-05-05 at 10 00 48" src="https://user-images.githubusercontent.com/48163702/236395237-0f23628c-1f98-4460-8b02-3a4867a0a352.png">


*Evaluation code is seperated because of memory limitations.

You can download the english_offensive_language.pt file to use the model from: https://drive.google.com/file/d/1QKaPAqKm8jNv_kkiAxXBvrX1iT-EJ6gZ/view?usp=share_link

You can use the model directly with model_usage code and english_offensive_language.pt file.

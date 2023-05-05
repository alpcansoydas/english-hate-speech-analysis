# english-hate-speech-analysis

In this work, hate speech recognition system is implemented in English. Texts that consist hate speech or offensive language are labeled as offensive and others are labeled as non-offensive.

This model is a fine-tuned version of https://huggingface.co/cardiffnlp/twitter-roberta-base-offensive

Used dataset is from https://huggingface.co/datasets/badmatr11x/hate-offensive-speech

Evaluation results for the limited number of data:

<img width="477" alt="Screenshot 2023-05-05 at 10 11 43" src="https://user-images.githubusercontent.com/48163702/236397000-e605d261-a7c4-498b-999b-c12ed0ed4c3a.png">

*Evaluation code is seperated because of memory limitations.

You can download the english_offensive_language.pt file to use the model from: https://drive.google.com/file/d/1QKaPAqKm8jNv_kkiAxXBvrX1iT-EJ6gZ/view?usp=share_link

You can use the model directly with model_usage code and english_offensive_language.pt file.

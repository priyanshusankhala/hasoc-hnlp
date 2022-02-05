# hasoc-hnlp
Hate Speech and Offensive Content Identification in Indo-Aryan Languages.
HASOC (2021).



This repo contains the code for our solutions at the Forum for Information Retrieval Evaluation (FIRE-2021). Our team called HNLP participated in both tasks (Subtasks A & B) for English and Hindi languages. In all languages task know as "Subtask A" refers to a classification problem of twittersamples on the basis of hate and offensive content. The second task, know as "Subtask B" refers to a classification of twitter samples on the basis of Profane Words, Hate speech, offensive Content, and Non-hate content.


We fine-tune the large language modelsto help in our task. The data is also quite unbalanced; so we used a modified cross-entropy loss to tacklethe issue. We observed that using a model which is fine-tuned in hindi corpora performs better

In all languages task know as "Subtask A" refers to a classification problem of twittersamples on the basis of hate and offensive content. The second task, know as "Subtask B" refers to a classification of twitter samples on the basis of Profane Words, Hate speech, offensive Content, and Non-hate content.

We achieved rank fourth, sixth with the macro F1-scores of 0.808, 0.639 in English Subtask A and English Subtask B respectively. For Hindi Subtask A, Hindi Subtask B our team achieved rank 22, 16 with the macro F1-scores of 0.737, 0.443 respectively in HASOC 2021.


Please cite this paper if you use this method or codes:
```sh
@article{,
  title={Multilingual Hate Speech and Offensive ContentDetection using Modified Cross-entropy Loss},
  author={Mitra, Arka and Sankhala, Priyanshu},
  journal={arXiv preprint arXiv:},
  year={2021}
}

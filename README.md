# hasoc-hnlp
Hate Speech and Offensive Content Identification in Indo-Aryan Languages.
HASOC (2021).



This repo contains the code for our solutions at the Forum for Information Retrieval Evaluation (FIRE-2021). Our team called HNLP participated in two tasks
on binary and fine-grained classification of English tweets that contain hate, offensive, and profane content (English Subtasks A & B) and one task on identification of problematic content in Marathi (Marathi Subtask A). For English subtasks, we investigate the impact of additional corpora for hate speech detection to fine-tune transformer models. We also apply a one-vs-rest approach based on Twitter-RoBERTa to discrimination between hate, profane and offensive posts. Our models ranked third in English Subtask A with the F1-score of 81.99% and ranked second in English Subtask B with the F1-score of 65.77%. For the Marathi tasks, we propose a system based on the Language-Agnostic BERT Sentence Embedding (LaBSE). This model achieved the second result in Marathi Subtask A obtaining an F1 of 88.08%.

Colab:
1) create a new notebook
2) do something
3) save
4) File->Save a copy to GitHub
5) append "src/" to the file name, e.g. "src/test.ipynb"


Please cite this paper if you use this method or codes:
```sh
@article{
  year={2021}
}

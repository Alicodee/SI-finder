# SI-finder

This is the git repository of "SI-Finder: Automated Detection of Security Issues From Commit Messages using Deep learning"



Files Information

1. Test_Data/test_redis.csv
 -> Redis Git Repository
 -> This file contains 200 git commits of Redis Git Repository which are divided equally into security-related and security-unrelated commit messages.
 -> We used this file as a of the test dataset to fine-tune BERT.
 
2. Test_Data/test_reis2021.csv
   -->>> Reis2021 [1] : A ground-truth dataset of real security patches
   -->>> We used this dataset as ground-truth dataset to evaluate the performance of our framework
 
3. Train_Data/train_labeled.csv
   -->>> This file contains manually labeled git commits of three git repositories Android, TensorFlow, and MongoDB.
   -->>> It has total of 5700 git commits including 4422, 844, 234 from Android, TensorFlow, and MongoDB respectively.
   -->>>This data is used as a training dataset for our framework of automatic identification of security issues.
 
4. resuls/BERT_[reis2021]_260_samples.csv 
   -->>> this file contains predictions given by our fine-tuned BERT model on 200 commit messages of Reis2021 [1] ground truth dataset.

5. results/BERT_redis_samples.csv 
   -->>> this file contains predictions given by our fine-tuned BERT model on 200 commit messages of Redis GitHub Repository.

References:
Reis, S., & Lisbon, I. S. T. U. (2021). A ground-truth dataset of real security patches. 15. https://arxiv.org/abs/2110.09635

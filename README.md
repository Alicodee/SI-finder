# SI-finder

This is the git repository of "SI-Finder: Automated Detection of Security Issues From Commit Messages using Deep learning"



Files Information

1. test_redis.csv
 -> Redis Git Repository
 -> This file contains 200 git commits of Redis Git Repository.
 -> We used this file as a of the test dataset.
 
2. test_reis2021.csv
 -> Reis2021: A ground-truth dataset of real security patches
 -> We used this as ground-truth dataset to evaluate the performance of our framework
 
3. test_labeled.csv
 -> This file contains manually labeled git commits of three git repositories Android, TensorFlow, and MongoDB.
 -> It has total of 5700 git commits including 4422, 844, 234 from Android, TensorFlow, and MongoDB respectively.
 -> This data is used as a training dataset for our framework of automatic identification of security issues.

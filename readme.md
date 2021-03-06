# Leveraging Adversarial Training in Self-Learning for Cross-Lingual Text Classification

This is Pytorch implemenation of our papers: A Robust Self-Learning Framework for Cross-Lingual Text Classification,
Leveraging Adversarial Training in Self-Learning for Cross-Lingual Text Classification, introduced by Xin Dong, Gerard de Melo.

## Requirements

```
python 3.7
pytorch 1.0
```

### Datasets

This sample code uses MLDoc dataset which is not public because of the privacy. 
You can request it on your own. Besides, you can create new data_processor for you own dataset in run_ld.py. 


### Training

Please run 

```
./run_ld.sh
```

To run adversarial training, Plese add

```
--adv_training 
```
in run_ld.sh

### Citation

If you found this code/work to be useful in your own research, please considering citing the following:

```
@inproceedings{dong2019robust,
  title={A robust self-learning framework for cross-lingual text classification},
  author={Dong, Xin and de Melo, Gerard},
  booktitle={Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP)},
  pages={6307--6311},
  year={2019}
}
```
```
@inproceedings{dong2020leveraging,
  title={Leveraging Adversarial Training in Self-Learning for Cross-Lingual Text Classification},
  author={Dong, Xin and Zhu, Yaxin and Zhang, Yupeng and Fu, Zuohui and Xu, Dongkuan and Yang, Sen and de Melo, Gerard},
  booktitle={Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval},
  pages={1541--1544},
  year={2020}
}
```

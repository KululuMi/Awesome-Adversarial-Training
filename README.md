# Awesome-Adversarial-Training
Here is a paper list about **Adversarial Training**
## Research Groups
[MIT madry Lab](http://madry-lab.ml/)    
[Bo Li](https://aisecure.github.io/)    
[Jun Zhu](https://ml.cs.tsinghua.edu.cn/~jun/index.shtml)    
[Quanshi Zhang](http://qszhang.com/)

## Survey
Recent Advances in Adversarial Training for Adversarial Robustness[[paper](https://www.ijcai.org/proceedings/2021/0591.pdf)](IJCAI2021)  

## Classic papers
    
(FGSM)Explaining and Harnessing Adversarial Examples[[paper](https://arxiv.org/abs/1412.6572)](ICLR2015)    
(PGD)Towards deep learning models resistant to adversarial attacks[[paper](https://arxiv.org/pdf/1706.06083.pdf)](ICLR2018)    
(TRADES)Theoretically Principled Trade-off between Robustness and Accuracy[[paper](https://arxiv.org/pdf/1901.08573.pdf)](ICML2019)    
(AutoAttack)Reliable evaluation of adversarial robustness with an ensemble of diverse parameter-free attacks[[paper](https://arxiv.org/abs/2003.01690)[code](https://github.com/fra31/auto-attack)](ICML2020)        
(C&W)Towards Evaluating the Robustness of Neural Networks[[paper](https://arxiv.org/pdf/1608.04644.pdf)]    
adversarial examples are not bugs they are features[[paper](https://arxiv.org/abs/1905.02175)](NIPS2019)    
Adversarially Robust Generalization Requires More Data[[paper](https://proceedings.neurips.cc/paper/2018/file/f708f064faaf32a43e4d3c784e6af9ea-Paper.pdf)](NIPS2019)    
On Adaptive Attacks to Adversarial Example Defenses[[paper](https://arxiv.org/pdf/2002.08347.pdf)](NIPS2020)    

## Data Augmentation
Overfitting in adversarially robust deep learning[[paper](https://arxiv.org/pdf/2002.11569.pdf)](ICML2020)    
ROBUST LOCAL FEATURES FOR IMPROVING THE GENERALIZATION OF ADVERSARIAL TRAINING[[paper](https://arxiv.org/pdf/1909.10147.pdf)](ICLR2020)
Fixing Data Augmentation to Improve Adversarial Robustness[[paper](https://arxiv.org/pdf/2103.01946.pdf)](NIPS2021)
## Unsupervised/Semi-supervised
Are labels required for improving adversarial robustness?(NIPS2019)    
Unlabeled data improves adversarial robustness(NIPS2019)    
Adversarially robust generalization just requires more unlabeled data(arXiv2019)    
Using self-supervised learning can improve model robustness and uncertainty(NIPS2019)
## Adaptive epsilon/Curriculum Learning
Attacks Which Do Not Kill Training Make Adversarial Learning Stronger(ICML2020)   
Curriculum adversarial training(IJCAI2018)   
On the convergence and robustness of adversarial training.(ICML2019)  
Instance adaptive adversarial training: Improved accuracy tradeoffs in neural nets(arXiv2019)    

## Efficient Adversarial Training
## Ensemble Adversarial Training
## Adversarial Regularization
## Transformer and other network architectures
Adversarial Robustness Comparison of Vision Transformer and MLP-Mixer to CNNs[[paper](https://arxiv.org/pdf/2110.02797.pdf)](arXiv2021)         
ON THE ADVERSARIAL ROBUSTNESS OF VISION TRANSFORMERS[[paper](https://arxiv.org/pdf/2103.15670.pdf)](arXiv2021)     
## Robust Architecture
## Others
ADVERSARIAL ROBUSTNESS THROUGH THE LENS OF CAUSALITY[[paper](https://openreview.net/pdf?id=cZAi1yWpiXQ)](ICLR2022)
## Except for Adversarial Training
Adversarial Robustness without Adversarial Training: A Teacher-Guided Curriculum Learning Approach[[paper](https://openreview.net/forum?id=MqCzSKCQ1QB)](NIPS2021)
## Robust Transfer Learning(forked from [jindongwang](https://github.com/jindongwang/transferlearning))
- ICSE-22 [ReMoS: Reducing Defect Inheritance in Transfer Learning via Relevant Model Slicing](https://link.zhihu.com/?target=https%3A//jd92.wang/assets/files/icse22-remos.pdf) | [Code](https://github.com/ziqi-zhang/ReMoS_artifact) | [Blog](https://zhuanlan.zhihu.com/p/446453487) | [Video](https://www.bilibili.com/video/BV1mi4y1C7bP)
  - Safe transfer learning by reducing defect inheritance
  - ?????????????????????????????????
- ICLR-22 [ON ROBUST PREFIX-TUNING FOR TEXT CLASSIFICATION](https://openreview.net/pdf?id=eBCmOocUejf) | [Code](https://github.com/minicheshire/Robust-Prefix-Tuning)
- CVPR workshop-21 [Renofeation: A Simple Transfer Learning Method for Improved Adversarial Robustness](https://openaccess.thecvf.com/content/CVPR2021W/TCV/html/Chin_Renofeation_A_Simple_Transfer_Learning_Method_for_Improved_Adversarial_Robustness_CVPRW_2021_paper.html)
  - Improve adversarial robustness of transfer learning models
  - ????????????????????????adversarial robustness????????????

- ICLR-20 [A Target-Agnostic Attack on Deep Models: Exploiting Security Vulnerabilities of Transfer Learning](https://openreview.net/forum?id=BylVcTNtDS)
  - Softmax layer is easy to get attacked
  - ????????????????????????????????????softmax layer

- RAID'18 [Fine-Pruning: Defending Against Backdooring Attacks on Deep Neural Networks](https://link.springer.com/chapter/10.1007/978-3-030-00470-5_13)
  - Finetune and prune the weights against backdoor attack
  - ???finetune????????????????????????????????????

- ACM CCS-18 [Model-Reuse Attacks on Deep Learning Systems](https://dl.acm.org/doi/10.1145/3243734.3243757)
  - Model-resuse attack on transfer learning models
  - ???????????????????????????????????????????????????

- USENIX Security-18 [With Great Training Comes Great Vulnerability: Practical Attacks against Transfer Learning](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-wang.pdf)
  - First work to design experiments to attack pretrained models
  - ??????????????????????????????????????????????????????

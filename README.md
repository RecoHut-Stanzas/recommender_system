<<<<<<< HEAD
### Andrew Ng 교수님의 Deep Learning Specialization 강의 정리

* 딥러닝 주제 관련 내용 및 논문 코드를 정리하였습니다.

### 1. 딥러닝 주제 관련

* Course 2: Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization
  * [Week 1 - 1 - Initialization](/02-Improving-Deep-Neural-Networks/Initialization.ipynb)
  * [Week 1 - 2 - Regularization](/02-Improving-Deep-Neural-Networks/Regularization.ipynb)
  * [Week 1 - 3 - Optimization Methods](/02-Improving-Deep-Neural-Networks/Optimization_methods.ipynb)
  * [Week 1 - 4 - Gradient Checking](/02-Improving-Deep-Neural-Networks/Gradient_Checking.ipynb)

* Course 4: Convolutional Neural Networks
  * [Week 2 - Residual Networks](/03-Convolutional-Neural-Networks/Residual_Networks.ipynb)

* Course 5: Sequence Models
  * [Week 1 - Building a Recurrent Neural Network - Step by Step](/04-Sequence-Models/Building_A_Recurrent_Neural_Network.ipynb)

### 2. 논문 

#### Image Recognition (이미지 인식)

* Image Style Transfer Using Convolutional Neural Networks (CVPR 2016)
  * [Original Paper Link](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf) / [Code Practice](/03-Convolutional-Neural_Networks/Style_Transfer.ipynb)

#### Natural Language Processing (자연어 처리)

* Attention is All You Need (NIPS 2017)
  * [Original Paper Link](https://arxiv.org/abs/1706.03762) / [Code Practice](/04-Sequence-Models/Attention_Is_All_You_Need.ipynb)
* Sequence to Sequence Learning with Neural Networks (NIPS 2014)
  * [Original Paper Link](https://arxiv.org/abs/1409.3215) / [Code Practice](/04-Sequence-Models/Sequence_to_Sequence_with_LSTM.ipynb)
=======
# Recommender System 관련 논문 정리

- Reccommender System 관련 논문의 코드, 데이터, paper 등을 정리해 올려두는 github repo 입니다. 

### Data
- 활용한 데이터셋은 다음과 같습니다. 아래 링크와 수업 내용을 참고해서 데이터를 직접 다운받아 사용할 수 있습니다.
    1. [MovieLens](https://grouplens.org/datasets/movielens/)
    2. [KMRD](https://github.com/lovit/kmrd)
    3. [Netflix](https://archive.org/details/nf_prize_dataset.tar)
    4. Amazon Product Review / Image
        - [Download Link]((https://nijianmo.github.io/amazon/index.html))에서 review와 image 데이터 모두 다운로드 할 수 있다. image데이터는 상품별 5-core 데이터를 다운로드한다.
    5. Music dataset
        - [Million Song Dataset](http://millionsongdataset.com/)과 [Last.fm](http://millionsongdataset.com/lastfm/#getting)

### Paper
- 정리한 논문 리스트는 다음과 같습니다.
    1. Part 2
        - BPR: Bayesian Personalized Ranking from Implicit Feedback
    2. Part 3
        - LARS: A Location-Aware Recommender System
    3. Part 4
        - Neural Collaborative Filtering
        - Factorization Machines
        - Wide & Deep Learning for Recommender Systems
        - DeepFM: A Factorization-Machine based Neural Network for CTR Prediction
        - AutoRec: Autoencoders Meet Collaborative Filtering
        - Training Deep AutoEncoders for Collaborative Filtering
        - Joint Training of Ratings and Reviews with Recurrent Recommender Networks
        - Image-based Recommendations on Styles and Substitutes
        - VBPR: Visual Bayesian Personalized Ranking from Implicit Feedback
        - Deep content-based music recommendation
        - Session-based Recommendations with Recurrent Neural Networks
        - Deep Neural Networks for YouTube Recommendations
        - Deep Learning Based Recommender System: A Survey and New Perspectives
>>>>>>> a8fe571029532a7139385d7b4a8ede036eae6bcd
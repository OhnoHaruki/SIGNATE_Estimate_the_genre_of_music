# SIGNATEの楽曲のジャンル推定チャレンジ！！にTPOTを用いて挑戦してみた

[SIGNATE Student Cup 2021春：楽曲のジャンル推定チャレンジ!!](https://signate.jp/competitions/565)に挑戦した時のものです。  
今回はAutoMLのライブラリの一つであるTPOTを用いて行いました。  

## TPOTとは
TPOTはAutoMLの一つで、scikit-learnの上に構築されます。詳しくは[こちら](http://epistasislab.github.io/tpot/)をご覧ください。  

## 使用したライブラリとインポート
import pandas as pd  
import sklearn  
from sklearn.model_selection import   train_test_split  
import tpot  
from tpot import TPOTClassifier  
from sklearn.metrics import confusion_matrix  
## 環境
MacBook Air(2018)  
mac0S Monterey  
Visual Studio Code ver:1.66.2  

## 使用したデータ
今回のコード中にあるtrainやtestなどのデータは[こちら](https://signate.jp/competitions/565/data)にあります。  

## 作者  
* はるき  
* 大学生
* Twitter: @haruki_data

## 最後に
ご覧いただきありがとうございます。  
初めてのgithubで慣れないところや至らないところがあるかもしれません。何かありましたら、TwitterのDMなどで、ご指摘いただけるとありがたいです。
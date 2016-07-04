# NN 的基本概念
關於 NN 的概念，請參考李宏毅老師的[課程](http://speech.ee.ntu.edu.tw/~tlkagk/courses_MLSD15_2.html)
 - Neural Network (Basic Ideas)
 - Backpropagation

剩下的都是進階題目，你可以不用那麼早開始看，例如
 - Theano 那章你也許可以先跳過，那是一個 toolkit
 - Tips for Training Deep Neural Network (這留在實作前再看吧)

選李宏毅的教學文，是因為他講的滿好的、而且比較精華；
看 paper 來學反而太慢了。


<!-- ======== -->
# NN 的實作
[Kaggle: Facial Keypoints Detection Competition]
(https://www.kaggle.com/c/facial-keypoints-detection)  
(請先註冊一個帳號)  
讀過 NN 的基本概念之後，再來玩這個實作。  
選這個競賽來當NN的入門，是因為它包含了  
  1. 一般的 Fully-connected, feed-forward NN 和  
  3. 進階的 Convolutional NN  

請參考 Daniel Nouri 的這篇[教學]
(http://danielnouri.org/notes/2014/12/17/using-convolutional-neural-nets-to-detect-facial-keypoints-tutorial/)
一步一步做。  
他會跟你解釋 CNN 是怎麼回事，
怎麼樣防止 NN 的頭號敵人──over-fitting，
還有告訴你有哪些方法可以改進你的系統。  

會推薦這篇，是因為 Kaggle 網頁上的那篇教學是用 R 語言實作的。  
我比較推薦 Python，因為 Python 是一個就算到業界都還會很常用的語言；  
相較之下，R 的社群雖然也很大，但業界似乎不太用。  
(比如說，業界在分析 system log 、或作一些文件處理的時候，都會編寫 Python script 來作分析)

# 其他
這只是個起始點。  
我一時半刻沒想到其他更適合的。  
你也可以找其他的理論或實作教學文  
有問題隨時問我們吧~

<br>
<br>
華山

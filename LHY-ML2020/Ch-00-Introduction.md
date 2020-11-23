# Introduction

[Slide](http://speech.ee.ntu.edu.tw/~tlkagk/courses/ML2020/introduction.pdf)

[Vedio](https://www.youtube.com/watch?v=c9TwBeWAj_U&feature=youtu.be)

## Algorithm

- Regression
  - 輸出為數值
- Classification
  - Binary Classification: 輸出為 [ Yes, No ]
    - RNN: 輸入為 [ sentence ], 輸出為 [ 正面, 負面 ]
  - Multi Classification: 輸出為 [ N 個 class ]
    - CNN: 輸入為 [ picture ], 輸出為 [ 哪種食物 ]
- Generation
  - Seg2Seg: 翻譯產生文句
  - GAN: 讓機器畫圖，產生二次元人物
  
### Function

#### function 產生方式

1. Supervised Learning
   1. 需要 Label，告訴機器要找的函式理想 output 該是什麼樣子
   2. 用 Loss 判別 function 好壞 (似錯誤率計算，但計算更為複雜)，由機器自動找出 Loss 最低的 function
   - Regression, Classification, RNN, CNN, Seg2Seg
2. Reinforcement Learning
   - 機器自己想辦法提高正確率，沒有 Base Data 教它
   - 如 Alphago: Reward 為機器輸贏
3. Unsupervised Learning
   - 給機器 Data，但沒有 Label，可以讓機器學到什麼？
   - GAN, Auto-encoder

#### 找 function 的步驟

1. 給定 function 尋找範圍 - 如：Regression、Classification......
2. function 尋找方法 ( Algorithm ) - Gradient Descent

# Regression

## 應用

1. Stock Market Forecast (股票預測系統)
   - Input: 過去十年各種股票起伏的資料
   - Output: 明天的道瓊工業指數的點數(Dow Taones Industrial Average)
2. Self-driving Car (無人車 / 自動車)
   - Input: 無人車的各種感應器
   - Output: 方向盤角度
3. Recommendation (推薦系統)
   - Input: 使用者A & 商品B
   - Output: 使用者 A 購買商品 B 的可能性

## 上課範例

目標：預測寶可夢的 CP(Combat Power，戰鬥力) 值
原因：為了計算是否有進化的價值

1. 找一個 function set(Model)
2. 定義 set 中某 function 評估好壞
3. 找最佳的 function

Input:

- $x$: 某一隻寶可夢
- $x_{cp}$: 進化前 CP
- $x_s$: 物種
- $x_{hp}$: 血量
- $x_w$: 重量
- $x_h$: 高度

Output:

- $y$: 進化後的 CP 值

## 開始

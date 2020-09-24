# Reinforcement-learning-note
 This note is learning from HiSKIO

## 何謂是強化學習
- 針對一種目標嘗試進行學習和嘗試的方法。
- 主要概念是透過有策略地與環境進行互動。
- 強化學習的方式，是利用獎勵的方法，使其想辦法找到最大回報的互動方式。

![image](https://github.com/ShowXD/Reinforcement-learning-note/blob/master/images/1.png)
![image](https://github.com/ShowXD/Reinforcement-learning-note/blob/master/images/2.png)

## 強化學習與其他學習的不同
- 相對於監督式學習，無需做標記資料，是透過與環境互動得到的資訊進行學習。
- 相對於非監督式學習，並非尋找資料之間隱藏的關聯性，而是透過獎勵的方式糾正學習的方向。
- 相對於深度學習，不須事先準備大量的資料，利用與環境的互動即時取得資料來學習。

## 強化學習的關鍵
1. **行動獎勵(Reward)**
    - 智能體的目標就是透過行動持續獲得信號。
2. **馬可夫決策過程(Markov decision process)**
    - 用來定義整個強化學習的範疇。
3. **評價函數(Value Functions)**
    - 用來評價這個決定的好壞。
4. **學習策略(Policy)**
    - 收集從環境獲得的資訊後，所採取的策略。

## 強化學習的困難點
1. 擬定好強化學習的範疇
2. 過程中探索新方向的權衡取捨
3. 需要不斷嘗試各種動作
4. 花費大量的時間進行運算和Debug

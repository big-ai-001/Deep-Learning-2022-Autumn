 # [Deep Residual Learning for Image Recognition](https://arxiv.org/pdf/1512.03385.pdf)

> ## 在你想報的部分標上你的名子 如:（roger 林榮顯）
> 參考資訊：  
> [論文速速讀 Deep Residual Learning for Image Recognition](https://meetonfriday.com/posts/7c0020de/)  
> [論文 Deep Residual Learning for Image Recognition](https://allen108108.github.io/blog/2019/10/29/[%E8%AB%96%E6%96%87]%20Deep%20Residual%20Learning%20for%20Image%20Recognition/#%E7%9B%B8%E9%97%9C%E5%B7%A5%E4%BD%9C-related-work)  
> [論文 Aggregating local descriptors into a compact image represenatation](http://mrulafi.blogspot.com/2016/03/aggregating-local-descriptors-into.html)  
> [為甚麼要Deep?](https://youtu.be/FN8jclCrqY0)
## Abstract + 1 Introduction 謝永盛

1. 深度的重要性
2. 增加深度時所遇到的困難
3. 提出的架構與優勢

## 2 Related Work

1. Residual（殘差）是什麼
2. VLAD, Fisher Vector, Multigrid, hierarchical basis preconditioning 證明優秀的目標分解or重構方法可以更簡易的優化模型
3. Shortcut Connections 做法以及目的

## 3 Network Architectures

1. 重構方法&為何以殘差為學習目標
2. Shortcut的技術細節
3. Plain&Residual 架構說明

## 4.1 ImageNet Classification ~ 4.1.Residual Networks

1. ImageNet Dataset
2. Plain&Residual Networks 效果比較&**歸因**

## 4.1.Identity vs. Projection Shortcuts ~ 4.1.Comparisons with State-of-the-art Methods

1. Shortcuts策略選擇&比較(消融測試)
2. Bottleneck用途
3. 深度提供的效益
4. 與SOTA比較

## 4.2 CIFAR-10 and Analysis ~ 4.3. Object Detection on PASCAL and MS COCO  許禾諭

1. CIFAR-10 Dataset, 實驗目的, 細節, 效果比較
2. 透過每層輸出分布的標準差證明Residual更好優化
3. 超DEEP model的探索
4. 泛化性(PASCAL, MS COCO)

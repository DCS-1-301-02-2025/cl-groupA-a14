# 海川の通学経路

[メンバー表に戻る](member.md#メンバー表)

```graphviz
digraph {
    edge [dir=both]

    八王子国際　キャンパス -> 高尾駅 [label=徒歩]
    高尾駅 -> 八王子駅[label=中央線]

    八王子駅 -> 東神奈川駅[label=横浜線]
    東神奈川駅 -> 関内駅[label=京浜東北線]
    関内駅 -> 海川自宅[label=徒歩] 
    
}
```

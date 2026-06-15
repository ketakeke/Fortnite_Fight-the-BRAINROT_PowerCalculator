# Fortnite Fight the BRAINROT Power Calculator

Fight the BRAINROT（ブレインロットファイト）のブレインロット戦闘力を計算・逆算するための静的Webアプリです。

## 計算式

```text
ceil(ベース戦闘力 × (凸倍率 + 属性倍率 - 1 + 変異0.1))
```

例：777 を ★5 Pirate にした場合

```text
ceil(777 × 1.7 + 777 × (2.8 - 1)) = 2720
```

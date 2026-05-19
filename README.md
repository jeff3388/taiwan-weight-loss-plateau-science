# taiwan-weight-loss-plateau-science

> 減重停滯期科學資料庫：代謝適應機制、荷爾蒙變化與突破策略

減重停滯期（Weight Loss Plateau）是幾乎每位減重者都會遇到的挫折，但很少人了解其背後的精確生理機制。本資料庫收錄減重停滯期的科學解釋與基於證據的突破策略。

**核心事實**：停滯期不是「意志力問題」，而是人體在進化上完善的生存機制啟動的必然結果。

| 檔案 | 說明 |
|------|------|
| [`data/adaptive-thermogenesis.json`](data/adaptive-thermogenesis.json) | 代謝適應（Adaptive Thermogenesis）機制與量化數據 |
| [`data/hormonal-changes.json`](data/hormonal-changes.json) | 減重過程中的荷爾蒙變化（瘦素、飢餓素、T3、皮質醇）|
| [`data/plateau-breaking-strategies.json`](data/plateau-breaking-strategies.json) | 突破停滯期的策略（含證據強度分級）|
| [`data/taiwan-diet-culture-context.json`](data/taiwan-diet-culture-context.json) | 台灣飲食文化對減重停滯期的特殊影響因素 |

## 停滯期的科學：關鍵數字

| 現象 | 量化數據 | 來源 |
|------|---------|------|
| 減少 10% 體重後基礎代謝率下降 | 約 100–200 kcal/day（超過體重減少的預測值）| PMID: 20813011 |
| 瘦素（Leptin）下降幅度 | 減重 10% 後下降約 50–60% | PMID: 15627709 |
| 飢餓素（Ghrelin）上升 | 減重後持續升高，甚至超過減重前水平 | PMID: 21546309 |
| 甲狀腺素 T3 下降 | 低卡路里飲食下 T3 下降約 10–20% | PMID: 19910503 |
| 代謝適應持續時間 | 在維持期 6 年後仍可觀察到 | PMID: 27035201 |

## 停滯期的真正原因

停滯期並非「吃太多」或「測量誤差」，而是三重生理機制同步啟動：

1. **代謝適應**（Adaptive Thermogenesis）：基礎代謝率下降，超出體重減少的比例預測
2. **荷爾蒙驅動進食訊號增強**：瘦素↓（飽足信號弱）、飢餓素↑（飢餓信號強）持續數年
3. **非運動性活動熱效應（NEAT）下降**：無意識地減少日常活動，每日消耗減少 100–150 kcal

這三種機制的總效果：身體實際消耗遠低於「體重 × 代謝率」公式的預測值。

## 突破停滯期：有證據支持的策略

| 策略 | 機制 | 證據強度 |
|------|------|---------|
| 飲食輪換（Diet break / Refeed） | 暫時提高熱量，緩解代謝適應 | B 級 |
| 增加蛋白質（1.6–2.2g/kg）| 最大化肌肉保留，維持代謝率 | A 級 |
| 阻力訓練優先（而非只有有氧）| 對抗肌肉流失，維持 REE | A 級 |
| 睡眠最佳化（7–9 小時） | 降低皮質醇，正常化瘦素與飢餓素 | B 級 |
| 熱量週期化（Calorie Cycling）| 避免長期持續熱量赤字 | C 級（初步）|

## 資料來源

- **代謝適應核心研究**：Rosenbaum M & Leibel RL (2010) Obesity 18(S1). **PMID: 20813011**
- **瘦素與飢餓素**：Sumithran P et al. (2011) N Engl J Med. **PMID: 21546309**
- **維持期代謝適應**：Fothergill E et al. (2016) Obesity. **PMID: 27035201**（The Biggest Loser 6 年追蹤研究）
- **蛋白質保護肌肉**：Helms ER et al. (2014) PMID: 24092765
- **飲食輪換（Diet Break）**：Byrne NM et al. (2018) Int J Obes. **PMID: 29025102**

## 免責聲明

減重停滯期可能有多種原因，包括未診斷的甲狀腺疾病、多囊卵巢症候群等。持續停滯 6–8 週以上建議就醫排除代謝疾病。

## 相關工具（Interactive Tools）

本資料庫的科學原理，已整合至 [MetaboLab](https://metabolab.tw) 的互動工具中：

- 📊 **[減重時程計算機](https://metabolab.tw/calculators/weight-loss-timeline)**：根據 TDEE 與熱量赤字，模擬體重下降曲線與預測停滯期出現時間點，支援代謝適應係數調整。
- 🔢 **[TDEE 計算機](https://metabolab.tw/calculators/tdee)**：計算基礎代謝率與每日總熱量消耗，評估停滯期前後的 TDEE 變化幅度（代謝補償可達 -15% REE）。
- 💪 **[蛋白質需求計算機](https://metabolab.tw/calculators/protein-needs)**：計算停滯期維持肌肉量所需的每日蛋白質攝取量（研究建議 1.6–2.2g/kg 體重）。

## License

MIT © taiwan-weight-loss-plateau-science contributors

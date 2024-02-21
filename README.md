# zksync
zkSync 的生態及發展
首先讓我簡單介紹一下 zkSync 的起源。 在2018 年，Alex Gluchowski 和 Alexandr Vlasov 共同創立了“Matter Labs”，並將公司總部設在德國柏林。 他們的宣言是「將以太坊擴展到數十億用戶，充分保留其最有價值的特性——無需許可、無需信任和彈性——以保護和增強全球經濟自由。 」 為了實現這一目標，Matter Labs 創建了第 2 層擴展解決方案 zkSync 1.0 並於 2020 年 6 月 15 日在以太坊主網上發布。

zkSync 在2022年宣布推出 zkSync 2.0（現在稱為 zkSync Era）時，它是 2022 年主網上第一個與 EVM 相容的 zkRollup。

ZkSync 是如何運作的？ 要了解 ZK-Rollups 和隨後的 ZkSync，我們首先需要了解什麼是零知識證明。 零知識證明是一種複雜的加密方法，可以隱藏交易的細節，同時仍然執行和確認交易。 使用這種方法，驗證者可以保證交易的有效性，而無需了解其基本組成部分，例如涉及的金額或實體。

零知識證明交易涉及兩方－證明者(Prover)和驗證者(Verifier)。 證明者想要驗證者證明一個陳述，但不透露該陳述是什麼，而驗證者需要驗證該陳述，同時又不透露該陳述的內容。 這就是零知識技術發揮作用並驗證交易的地方。
zkSync 的生態及發展
3KeN1
0x26eB
February 18th, 2024

zkSync 是什麼？
https://www.footprint.network/article/unleashing-the-power-of-zksync-era-a-new-era-of-layer-2-scaling-Cu4hPseW
https://www.footprint.network/article/unleashing-the-power-of-zksync-era-a-new-era-of-layer-2-scaling-Cu4hPseW

首先讓我簡單介紹一下 zkSync 的起源。 在2018 年，Alex Gluchowski 和 Alexandr Vlasov 共同創立了“Matter Labs”，並將公司總部設在德國柏林。 他們的宣言是「將以太坊擴展到數十億用戶，充分保留其最有價值的特性——無需許可、無需信任和彈性——以保護和增強全球經濟自由。 」 為了實現這一目標，Matter Labs 創建了第 2 層擴展解決方案 zkSync 1.0 並於 2020 年 6 月 15 日在以太坊主網上發布。

zkSync 在2022年宣布推出 zkSync 2.0（現在稱為 zkSync Era）時，它是 2022 年主網上第一個與 EVM 相容的 zkRollup。

ZkSync 是如何運作的？ 要了解 ZK-Rollups 和隨後的 ZkSync，我們首先需要了解什麼是零知識證明。 零知識證明是一種複雜的加密方法，可以隱藏交易的細節，同時仍然執行和確認交易。 使用這種方法，驗證者可以保證交易的有效性，而無需了解其基本組成部分，例如涉及的金額或實體。

零知識證明交易涉及兩方－證明者(Prover)和驗證者(Verifier)。 證明者想要驗證者證明一個陳述，但不透露該陳述是什麼，而驗證者需要驗證該陳述，同時又不透露該陳述的內容。 這就是零知識技術發揮作用並驗證交易的地方。如下圖：[1]

1.驗證者寫入一條秘密訊息並將其放入上鎖的保險箱中
https://www.circularise.com/blogs/zero-knowledge-proofs-explained-in-3-examples#example-proof-of-membership-2
https://www.circularise.com/blogs/zero-knowledge-proofs-explained-in-3-examples#example-proof-of-membership-2

2.滿足要求的證明者知道組合代碼並打開上鎖的保險箱
https://www.circularise.com/blogs/zero-knowledge-proofs-explained-in-3-examples#example-proof-of-membership-2
https://www.circularise.com/blogs/zero-knowledge-proofs-explained-in-3-examples#example-proof-of-membership-2

3.證明者將秘密訊息傳回驗證者
https://www.circularise.com/blogs/zero-knowledge-proofs-explained-in-3-examples#example-proof-of-membership-2
https://www.circularise.com/blogs/zero-knowledge-proofs-explained-in-3-examples#example-proof-of-membership-2

4.驗證者確信證明者確實知道組合代碼，因此可以信任
https://www.circularise.com/blogs/zero-knowledge-proofs-explained-in-3-examples#example-proof-of-membership-2
https://www.circularise.com/blogs/zero-knowledge-proofs-explained-in-3-examples#example-proof-of-membership-2


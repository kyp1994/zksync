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

接下來讓我們回到 zkSync 。 ZkSync Era 使用稱為 ZK-Rollups 的東西。 它們被稱為匯總，因為它們批量匯總數千個交易並在鏈下執行它們。 匯總透過索引而不是位址來表示帳戶，從而壓縮資訊以使用更少的運算能力。當 ZK-rollups 對鏈下交易進行批次處理時，它們也會產生有效性證明。 這種安全模型允許雙方確保鏈下完成的交易確實有效，而無需透露聲明本身。 ← 這就是我們的零知識範例出現的地方。

ZK-Rollups 本質上奠定了 zkSync 時代的基礎。 透過在鏈外執行批次並結合有效性證明，ZkSync Era 實現了高流通量並以低gas fees、安全性和可擴展性進行交易，同時建構在以太坊網路上。

於 zkSync 發展的好處

安全性

zkSync Era的安全模型繼承了以太坊的安全方面。 他們透過將加密證明、驗證和重建所有交易所需的資料直接發佈到 ETH L1 來做到這一點。 此外， Matter Labs 對安全性也非常重視。 在發布前一年多，他們投資了數百萬美元，以確保它對公眾來說足夠安全。 在主網啟動之前，進行了多次安全審計（內部審計和安全公司審計）、安全競賽和錯誤賞金計劃[2]。

可擴展性

對於使用者和開發人員來說，另一個重要的好處是 zkSync Era 的整體可擴展性，它利用 ZK 技術將交易成本降低到 ETH 交易價格的一小部分。 透過利用Rollup技術（捆綁交易並將最終狀態發佈到鏈上）及其專有技術-Rollup，zkSync 允許比以前更便宜、更快和更大的交易。

使用者體驗
對於 web3 而言，使用者體驗仍然是缺少的部分之一，特別是考慮到每天都有數百萬新用戶加入。

話雖如此，zkSync 在與 dApp 互動時為用戶提供了比競爭對手更友善的體驗。 支援本地的抽象帳戶[3]zkSync 使開發人員能夠建立以下 dApp：

1.不需要助記詞，可以支持生物辨識驗證和社交恢復。

2.允許用戶用任何 ERC-20 代幣支付 Gas 費。

3.允許用戶進行自動和定期轉帳以及定期付款訂閱。

4.允許一次性簽署，使用戶只需登入一次即可啟動簽署並進行任意次數的交互。

zkSync 生態的概況

最後會簡單介紹zksync下部分的生態項目

基礎設施

1.Pyth Network
Pyth Network 是一個去中心化的’預言機’網絡，它依賴時間敏感的現實世界數據，但不會存取它。

它是一個將金融市場數據分發到各個區塊鏈的預言機。 他們的資料庫包含來自 80 個不同的第一方發布商的市場數據，其中包括一些世界上最大的交易所和做市商。

Pyth 不像其他預言機那樣使用「推送」預言機，而是將這項工作委託給使用者。

Pyth Network 正在為 zkSync Era 的幾個專案提供資料預言機，包括 Derivio、OT Protocol 和 Nexon Finance。

他們的數據可在多個區塊鏈上使用，甚至可以在鏈下應用程式中使用。 他們每天提供約 2500 萬次更新，並擁有超過 250 個資料來源。[4]

ZNS Domain 是一個基於 zkSync 的命名系統。 ZNS 的職責是將人類可讀的地址（例如「3ken1.zkSync」）轉換為可由程式碼讀取的名稱，例如： 地址、內容雜湊和元數據。

遊戲
1.Tevaera
Tevaera 是一個遊戲生態系統，正在透過眾多工具集、dApp 及其專有的 EVM 相容鏈來改變 web3 遊戲產業。

同時，他們正在開發不同的鏈上遊戲以及多人遊戲框架、去中心化遊戲交易所和市場。

此外，他們正在建立 Teva Chain，它作為基於 zkSync 的超鏈，提供可擴展性、效能和安全性。

根據他們的網站[5]，他們在 zkSync Lite 和 zkSync Era 都有超過 90,000 名註冊用戶。 其中大部分來自他們最受歡迎的遊戲——Teva Run。

跨橋

1.Layerswap
Layerswap 是一個跨鏈橋，支援快速、簡化地跨錢包、區塊鏈和中心化交易所轉移資產。

LayerSwap目前支援超過16個交易所和19個區塊鏈之間的轉帳。 它們還整合在許多錢包、DEX 和 dApp 中，讓用戶輕鬆進行交易。

它們是第一個也是唯一一個允許從中央交易所直接轉移到區塊鏈的橋樑。

2.ZKSwap

ZKSwap是一套基於自動做市商模型的去中心化代幣Swap協議，可為以太坊用戶提供無需許可的交易服務。 ZKSwap透過zkRollup技術在Layer-2上實現了全套Swap的功能，同時可以提供無限可擴展性和隱私性。

ZKSwap為流動性提供者和交易者提供超高吞吐量的Swap基礎設施，且用戶無需支付Gas費用。

總結

總而言之，zkSync 已成為以太坊生態系統中頂級的可擴展性解決方案之一，解決了高費用、網路緩慢和安全問題等關鍵挑戰。 憑藉零知識證明和 ZK-rollups 的創新實施，zkSync 為所有尋求可擴展性和效率的基於以太坊的項目提供了一個引人注目的機會。

Wen Token呢？ zkSync 沒有其原生代幣。 Matter Labs 執行長 Alex Gluchowski 表示：

由於網路目前基本上是中心化的，因此不需要代幣。

不過，他提到，一旦網路完全去中心化，代幣就會到來。 這次空投尚未得到官方確認，但人們高度相信 zkSync 會獎勵其早期採用者。[6]

總而言之，在不到三年的時間裡，zkSync 成功獲得了超過59億美元的TVL，過去30 天內的交易量超過十億筆，這在web3 原生受眾和項目中帶來了巨大的增長和採用。[7]

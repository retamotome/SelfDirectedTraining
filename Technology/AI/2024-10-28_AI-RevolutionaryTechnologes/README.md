# 撐起AI的5個革命性「台柱」
## Introduction Video 介紹影片
| Video | Description |
|:--|:----------|
|<a href="https://www.youtube.com/watch?v=AMDn1RCcqGM" target="_blank"><image src="img/Thumbnail.png" width="200"></a>| <sub>:arrow_forward: <a href="https://www.youtube.com/watch?v=AMDn1RCcqGM" target="_blank">YouTube</a><br> 🟢 Chinese 🟢 English 🟢 Japaness</sub><br>晶片突破摩爾定律｜核廢料電池可發電2.8萬年！|

## News and Reference
### Network
2025-12-11 [史上第一次 AI 模型在外太空運行！NVIDIA 支持的新創 Starcloud 打破資料中心「地心引力」](https://techorange.com/2025/12/11/starcloud-trains-first-ai-model-in-space/)  

### Energy
TED Speaker: [Taylor Wilson](https://www.ted.com/speakers/taylor_wilson)  
+ 2012-03-22 [Yup, I built a nuclear fusion reactor](https://www.youtube.com/watch?v=9B0PaSznWJE)  
+ 2013-04-30 [My radical plan for small nuclear fission reactors](https://www.youtube.com/watch?v=5HL1BEC024g&t=0)  
2023-03-24 [核廢料變身鑽石電池　壽命28萬年充電寶可以扔了？](https://timenews.com.tw/%E3%80%90%E7%A7%91%E6%8A%80online%E3%80%91%E6%A0%B8%E5%BB%A2%E6%96%99%E8%AE%8A%E8%BA%AB%E9%91%BD%E7%9F%B3%E9%9B%BB%E6%B1%A0%E3%80%80%E5%A3%BD%E5%91%BD28%E5%B9%B4%E5%85%85%E9%9B%BB%E5%AF%B6%E5%8F%AF)  
2024-09 [A Nuclear Nano-Diamond Battery, that Lasts For 28,000 Years](https://www.electricaltechnology.org/2024/09/nuclear-nano-diamond-battery.html)  

### Storage 
2026-01-09 [「5D 記憶晶體」來了：一片玻璃塞進 360TB，壽命竟直逼 138 億年？](https://www.bnext.com.tw/article/89747/5d-memory-crystal-eternal-data-storage-tech)   

### Game Engine
2019-07-13 [【イメージムービー】Connect future ～5Gでつながる世界～（3分ver）](https://www.youtube.com/watch?v=XsGhldzNrjg)  

### AI Chip
2025-04-15 [解決 AI 資料傳輸瓶頸的關鍵一步，矽光子新創企業登場](https://eetimes.itmedia.co.jp/ee/articles/2504/15/news117.html)  

<details><summary>AI Translate</summary>
  
__為「光子超級晶片」打造的平台__  
Lightmatter 發表了其參考平台「Passage M1000」，專為該公司所稱的「光子超級晶片」設計。這款平台基於 Lightmatter 的 Passage 主動光互連技術，採用可程式化導波路網路進行固態光切換。據稱，它可實現總計 114Tbps 的光頻寬，並能為每個封裝提供最高 1.5kW 的電力供應。  
Harris 表示：「若使用其他 CPO 技術來實現這一點，所有光學模組都必須外置，導致封裝體積龐大。Passage M1000 是為了實現這樣的頻寬所能構建的最小尺寸封裝，已達到理論極限。」  
他補充說：「根據封裝附近或封裝上的光學元件的物理尺寸，可能會出現熱散問題。」  
Passage 可邊緣連接 256 條光纖，每條光纖的頻寬為 448Gbps。Lightmatter 的設計目標是讓單一封裝可搭載最多 4000mm² 的矽晶片，從而實現最大規模的多重光罩 ASIC。單一擴展域可擴展至最多 2000 顆 XPU。  
    
__Lightmatter 的「光子超級晶片」__  
與 L200 和 L200X 相同，該平台可消除大型多晶片系統中對 I/O 海灘前緣（beachfront）的依賴，使單一擴展域可擴展至 2000 顆 GPU。當設計中包含四個以上的運算晶粒時，I/O 海灘前緣會成為限制，因此晶粒需透過各自的晶片內網路（NoC）進行通訊。而「Passage M」系列則可將 SerDes 放置於晶片上的任意位置。  
Lightmatter 與封裝廠 ASE 和 Amkor 合作，為客戶在 Passage 互連基板上構建晶片。  
Passage M1000 預計將於 2025 年夏季上市。  
</details>
<details><summary>Appendix</summary>
  
+  目前多數 AI 晶片模組因晶片邊緣可用空間有限，導致資料輸入/輸出受限，難以支援更多高頻寬記憶體或運算單元。Lightmatter 推出的L200與L200X透過與 Alphawave Semi合作，將I/O晶片與XPU（處理器、GPU、AI加速器等）緊密配置於封裝內部，跳脫傳統邊緣佈線架構。 這些創新將打破多晶片架構受限於 I/O 傳輸頻寬與晶片邊緣佈線（即「海灘線」）的設計瓶頸，為AI晶片提供更高擴展性與整合彈性。  
+   L200 搭載了傳輸與接收速率32Tbps的光學引擎，而升級版 L200X則達64Tbps。每條光纖可傳輸 1.6Tbps（由 16 條波長組成，每條波長速率為 112Gbps），是目前主流光模組的兩倍。在 64Tbps 的版本中，每個封裝內包含4顆 I/O 晶片，即可在單一封裝內總頻寬可達 256Tbps，傳輸能力遠高於現有 NVIDIA 「NVLink」架構。  
+   Lightmatter開放授權的I/O IP策略，加上與供應鏈大廠協作的產業布局，展現打造開放式矽光子平台的戰略眼光。相較於目前以 NVIDIA主導的封閉型高速互連生態，Lightmatter 提供另一種開放且高效的可能性。   
</details>

### Graph RAG
2025-09-05 [從資料到洞察：Graph RAG 如何改變企業 AI 策略？](https://www.find.org.tw/tech_obser/browse/f7dbbc70530c92ccf55017de31e5f2e7)  
2024-11-13 [Graph RAG－RAG結合知識圖譜之技術解析及應用](https://www.moea.gov.tw/MNS/doit/industrytech/IndustryTech.aspx?menu_id=13545&it_id=563)  

### Vision 
[【イメージムービー】Connect future ～5Gでつながる世界～（3分ver）](https://www.youtube.com/watch?v=XsGhldzNrjg)  
+ [Chinese : 日本总务省发布5G时代概念宣传片：5G连接下的世界](https://www.youtube.com/watch?v=9BwAlU4WyZo&pp=ygUS5pel5pys57i95YuZ55yBIDVH)







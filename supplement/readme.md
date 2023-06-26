# 資通安全概論(三天課程)

## 第1單元 資通安全基本觀念
- 資安威脅趨勢
  - 國家級駭客[北韓駭客|ITHOME](https://www.ithome.com.tw/tags/%E5%8C%97%E9%9F%93%E9%A7%AD%E5%AE%A2)
    - 北韓政府的國家駭客組織 Lazarus(Hidden Cobra) | Kimsuky |
    - [遭到北韓駭客入侵的美國資安研究人員，以一己之力癱瘓北韓網路](https://www.ithome.com.tw/news/149189)
- [資通安全目標: CIA](CIA.md)
- NIST CSF 安全架構 [NIST CSF 安全架構](NIST_CSF.md)
## 第2單元 資通安全相關法規
- A.法規 [補充資料](./LAW.MD)
  - 行政院國家資通安全會報
  - 資通安全管理法與子法
    - [資通安全管理法(23條)](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=A0030297)
    - 六大子法
      - 1.[資通安全管理法施行細則(13條)](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=A0030303)
      - 2.[資通安全責任等級分級辦法(12條)](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=A0030304)
        - 第 2 條 公務機關及特定非公務機關（以下簡稱各機關）之資通安全責任等級，由高至低，分為 A 級、B 級、C 級、D 級及 E 級。
        - 附表1-8:應辦事項
        - 附表九 資通系統防護需求分級原則
        - 附表十 資通系統防護基準
      - 3.[資通安全事件通報及應變辦法(21條)](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=A0030305)
      - 4.[資通安全情資分享辦法(11條)](https://law.moj.gov.tw/lawclass/lawall.aspx?pcode=a0030307)
      - 5.[特定非公務機關資通安全維護計畫實施情形稽核辦法(10條)](https://law.moj.gov.tw/LawClass/LawAll.aspx?media=print&pcode=A0030306)
      - 6.[公務機關所屬人員資通安全事項獎懲辦法(7條)](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=A0030308)
    - [資安法常見問題](https://moda.gov.tw/ACS/laws/faq/28/646)
      - 納管對象及範圍
      - 資通安全責任等級分級
      - 資通安全責任等級分級之應辦事項-資安專職人力及證照
      - 資通安全責任等級分級應辦事項-其他
      - 資通安全維護計畫撰寫及實施情形填報
      - 辦理受託業務-受託者之選任及監督
    - [國家機密保護法(41條)](https://law.moj.gov.tw/LawClass/LawAll.aspx?PCode=I0060003)
    - [個人資料保護法(56條)]](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=I0050021)
- B.ISO 27001:2022資訊安全管理系統 Information security management systems [補充資料](./ISMS.MD)
  - 資訊安全管理系統 Information security management systems
  - ISO/IEC 27001：2022版本 
    - 4 大關鍵領域(2013版本:14 個)
      - 1.組織
      - 2.人員
      - 3.實體
      - 4.技術
    - 93項控制措施(2013版本:114 項) 部分控制措施被合併，另一些被刪除，引入了新的控制措施(11個)，還有一些做更新
    - 引入新的5大屬性
      - 1.控制類型
      - 2.資安特性
      - 3.網路安全概念
      - 4.執行能力
      - 5.安全領域 
  - ISMS建置流程
## 第3單元 資通安全風險管理與業務持續運作管理
- [風險管理](./risk.md)
- [業務持續運作管理](./BCM.md)
## 第4單元 作業安全
## 第5單元 資訊委外安全
## 第6單元 存取控制與加解密技術
- 存取控制
- 加解密技術
## 第7單元 網路安全與實體安全
## 第8單元 應用程式安全
- 不安全的程式
  - 緩衝區溢位(Buffer overflow)
  - 惡意程式(Malware)
  - 邏輯炸彈(logical bomb)
  - 隱藏通道(Covert Channel)
  - 輸入攻擊
- 軟體開發生命週期安全(Secure Software Development Life Cycle, SSDLC)
- 應用程式安全控制==> 強化程式安全的各種做法
  - 變更控制
  - 職責區隔
  - 程式庫維護
  - 應用程式安全檢測
    - 入侵防禦系統(Intrusion Prevention System, IPS)：具備部份防禦功能
    - 源碼檢測(Static Code Analysis)：使用自動化的源碼檢測工具找出有問題的程式碼
    - 網頁應用程式防火牆(Web Application Firewall, WAF)：針對應用層攻擊進行防禦
    - 滲透測試(Penetration Test, PT )：模擬攻擊者行為找出網站漏洞
    - 網站弱點評估(Web Vulnerability Assessment)：使用掃描工具檢測弱點
  - 行動應用程式安全
    - 政府行動化安全防護規劃報告V1.0」第61~62頁
    - 行動應用程式的開發過程，會衍生二大安全議題:
      - 1.行動應用程式碼的安全性議題 :
        - 因撰寫方式的錯誤，使用Apps存有安全弱點，導致系統遭入侵
        - 參考OWASP Mobile TOP 10
          - Top 10 Mobile Risks Beta 2 Draft 2023
        - 行動裝置資安防護參考指引
        - 解決方法建議遵守安全系統發展生命週期進行開發，藉助第三方或是自動化檢測進行白箱、黑箱靜態與動態之檢測。
        - [OWASP Mobile Application Security](https://owasp.org/www-project-mobile-app-security/)
        - [OWASP Mobile Application Security Verification Standard (MASVS)](https://owasp.org/www-project-mobile-app-security/)
        - [Mobile Application Security Checklist](https://owasp.org/www-project-mobile-app-security/)
      - 2.隱私侵犯的議題
        - 因程式開發時，索取過多行動裝置上的敏感資訊，例如：通訊錄、行事曆、座標位置、郵件、簡訊內容等
        - 建議遵守Privacy by Design之原則，將隱私保護之概念，融入於應用程式的設計 
- Web應用程式安全
  - [OWASP Top 10 2021](https://owasp.org/Top10/zh_TW/)
  - A1	權限控制失效(Broken Access Control)
  - A2	加密機制失效(Cryptographic Failures)
  - A3	注入式攻擊(Injection)
    - SQL Injection
    - XSS (JAVAscript Injection)
    - Command Injection
    - LDAP Injection
    - .....
  - A4	不安全設計(Insecure Design)
  - A5	安全設定缺陷(Security Misconfiguration)
  - A6	危險或過舊的元件(Vulnerable and Outdated Components)
  - A7	認證及驗證機制失效(Identification and Authentication Failures)
  - A8	軟體及資料完整性失效(Software and Data Integrity Failures)
  - A9	資安記錄及監控失效(Security Logging and Monitoring Failures)
  - A10	伺服端請求偽造(Server-Side Request Forgery)

## 第9單元 資通安全健診
- 資通安全健診:目的
- 資通安全健診:項目
  - 機關定期辦理資通安全健診(A級機關每年1次，B級機關每2年1次)，檢測項目包含：
    - 1.網路架構檢視
    - 2.網路惡意活動檢視
      - a.封包側錄
      - b.資安設備紀錄檔(log)分析
    - 3.使用者端電腦惡意活動檢視
    - 4.伺服器主機惡意活動檢視
    - 5.目錄伺服器(Directory Service)設定檢視 ==> Windows Server 2022 AD(active Directory)的安全設定
    - 6.防火牆連線設定檢視 ==>防火牆規則檢視
- 資通安全健診:流程
- 
## 第10單元 資通安全事件通報及應變
- incident vs event
- [資通安全事件通報及應變辦法(共21條)](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=A0030305)
  - 第一章 總則
    - 第 2 條 資通安全事件分為四級。
      - 資通安全事件分級由輕至重分「1」、「2」、「3」、「4」四個級別
      - 這四個級別怎麼定?
    - 第 3 條 資通安全事件之`通報內容`  ==> 參考3-63頁
  - 第二章 公務機關資通安全事件之通報及應變
    - 第 4 條 通報
    - 第 5 條 審核
    - 第 6 條 應變 ==>
    - 第 9 條 `通報`作業規範
    - 第 10 條 `應變`作業規範
 - 第三章 特定非公務機關資通安全事件之通報及應變
    - 第 11 條 通報
    - 第 12 條 審核
    - 第 13 條 應變 ==>
    - 第 15 條 `通報`作業規範
    - 第 15 條 `應變`作業規範
 - 第四章 附則
   - 第 18 條 公務機關 資通安全演練作業
   - 第 19 條  特定非公務機關  資通安全演練作業
- 資安事件處理(incidenet handling)
  - [NIST SP 800 61r2 Computer Security Incident Handling Guide ](https://nvlpubs.nist.gov/nistpubs/specialpublications/nist.sp.800-61r2.pdf)
  - 目的
  - 資安事件處理計畫
  - 資安事件處理程序|流程
    - 準備：資安事件處理時所需之專業人員、組織分工、處理與鑑識的訓練、計畫與程序的編撰及模擬演練
識別：當資安事件發生時，第一步驟是識別資安事件的嚴重性與影響範圍
封鎖：封鎖入侵來源，以避免災害擴大
根除：徹底清除被植入的惡意程式並修補被入侵的管道。
回復：被入侵的系統回復至正常運作的狀況
經驗學習：在事件中學習到相關的經驗，並反應在資安政策與防護措施上，以避免相同問題再度發生

 
  - NIST SP 800-53, Revision 5| IR: Incident Response   Controls [參考資料](https://csf.tools/reference/nist-sp-800-53/r5/ir/)
    - IR-1: Policy and Procedures
    - IR-2: Incident Response Training
    - IR-3: Incident Response Testing  ==> BASELINE(S):Moderate  High   Privacy
    - IR-4: Incident Handling
    - IR-6: Incident Reporting
    - IR-7: Incident Response Assistance
    - IR-8: Incident Response Plan
    - 電腦緊急應變小組（Computer Emergency Response Team，CERT）
    - 電腦資安事件應變小組（Computer Security Incident Response Team，CSIRT）
      - [CSIRT| ithome專刊](https://www.ithome.com.tw/taxonomy/term/13043/all)
    - 產品資安事件應變小組（Product Security Incident Response Team，PSIRT）

- [Incident Handling & Response Career Path(入侵處理與響應 資安職涯發展) | EC-Council](https://www.eccouncil.org/incident-handling-response-career-path/)
 
- 數位證據(Digital Evidence)


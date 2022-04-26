# 巨量資料分析技術與應用 Final Project：DDos Analysis
- [Course Information](https://timetable.nycu.edu.tw/?r=main/crsoutline&Acy=109&Sem=1&CrsNo=5283&lang=zh-tw)<br>
- [GitHub Repository](https://github.com/WCChang1997/2020-BD_final_project.git)<br>
- [Project Report](巨量資料PJ_report.pdf)<br>
- [Presentation Slide](巨量資料PJ_present.pdf)

## 計畫摘要
- 背景介紹
    DoS：一種嘗試對目標系統（如網站、應用程式等）進行惡意攻擊的行為，通常攻擊者會產生大量的封包或請求，最終使得目標系統無法負荷。
    DDoS：第一個 D 意指「分散式」，即攻擊者會使用多個盜用或受控的來源來產生 DoS 攻擊。
- 計畫目的
    防範 DDoS 的方法主要有兩種，一種是以流量限制，如此可能會影響流量較高的正常使用者；另一種則是過濾出有問題的 IP，直接將進行惡意攻擊的來源加入黑名單。
    本次計畫我們希望透過巨量資料分析的方式找出進行 DDoS 攻擊來源的特徵（上述方法之後者），藉此將 DDoS 造成的傷害降到最低。
- 參考文獻
    - M. S. Elsayed, N. -A. Le-Khac, S. Dev and A. D. Jurcut, "DDoSNet: A Deep-Learning Model for Detecting Network Attacks," 2020 IEEE 21st International Symposium on "A World of Wireless, Mobile and Multimedia Networks" (WoWMoM), Cork, Ireland, 2020, pp. 391-396, doi: 10.1109/WoWMoM49955.2020.00072
    - Lopez, Alma D., Asha P. Mohan, and Sukumaran Nair. "Network Traffic Behavioral Analytics for Detection of DDoS Attacks." SMU Data Science Review 2.1 (2019): 14. 

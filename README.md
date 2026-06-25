本專案「方案 A」以樹莓派 3 與 DHT11 為核心，透過 Python 定時採集數據並經由 HTTP POST 傳送至 GAS 雲端腳本。系統自動將資料寫入 Google 試算表，並透過 LINE API 發送即時推播。此輕量化架構精簡了硬體端代碼，實現高效的雲端行動整合，適用於快速佈署需求。

"Plan A" utilizes Raspberry Pi 3 and DHT11 sensors to collect data via Python. Data is sent to Google Apps Script (GAS) via HTTP POST for automatic logging to Google Sheets and real-time LINE notifications. This lightweight architecture simplifies client-side code and ensures efficient cloud-to-mobile integration for rapid IoT deployment.

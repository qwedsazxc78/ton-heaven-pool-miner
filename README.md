# TON Pool - Hive OS 設定流程

## 飛行儀表板設定步驟


![alt text](https://github.com/qwedsazxc78/ton-heaven-pool-miner/blob/main/image/%E9%A3%9B%E8%A1%8C%E5%84%80%E8%A1%A8%E6%9D%BF%E8%A8%AD%E5%AE%9A.png?raw=true)

1. COIN: ton
2. 錢包: 選擇你的對應貨幣錢包
3. 礦池: 選擇在礦機中設定
4. 客製化設定:
   - 安裝網址: 複製後貼上 hiveos 礦機設定
      ```sh
      https://github.com/qwedsazxc78/ton-heaven-pool-miner/releases/download/0.1.11/ton-heaven-pool-miner-0.1.11-hiveos.tar.gz
      ```
   - 礦機名稱: 輸入安裝網址後自動帶入
   - 演算法: 不輸入，留預設值
   - 錢包與模板: 輸入
      ```sh
      %WAL%.%WORKER_NAME%
      ```
   - 礦池網址: 請輸入
      ```sh
      https://ton.rich-thinking.com
      ```
   - 點選保存設定
5. 名稱：ton-heaven-pool

   ![alt text](https://github.com/qwedsazxc78/ton-heaven-pool-miner/blob/main/image/%E9%A3%9B%E8%A1%8C%E5%84%80%E8%A1%A8%E6%9D%BF%E8%A8%AD%E5%AE%9A-%E5%AE%A2%E8%A3%BD%E5%8C%96%E8%A8%AD%E5%AE%9A.png?raw=true)

## 注意事項

1. 特別確認礦機目前使用版本，最新版為0.1.11
2. 使用管理者的飛行儀表板，才能應用到大多數礦機
3. 安裝版本的版號**一定要一樣**，否則會安裝失敗，或是跑起來有問題
   **https://github.com/qwedsazxc78/ton-heaven-pool-miner/releases/download/0.1.11/ton-heaven-pool-miner-0.1.11-hiveos.tar.gz**
4. 網址尾碼不可以有 "/" ，否則跑起來會有問題。不可以最後多斜線
   https://ton.rich-thinking.com/
5. 最新礦機下載網址： https://github.com/qwedsazxc78/ton-heaven-pool-miner/releases?page=1
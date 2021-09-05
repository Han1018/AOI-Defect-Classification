# AOI-Defect-Classification
AIdea的AOI瑕疵分類計畫

## WebSite
https://aidea-web.tw/topic/285ef3be-44eb-43dd-85cc-f0388bf85ea4

## 簡介
自動光學檢查（Automated Optical Inspection，簡稱 AOI）[1]，為高速高精度光學影像檢測系統，運用機器視覺做為檢測標準技術，可改良傳統上以人力使用光學儀器進行檢測的缺點，應用層面包括從高科技產業之研發、製造品管，以至國防、民生、醫療、環保、電力…等領域。工研院電光所投入軟性電子顯示器之研發多年，在試量產過程中，希望藉由 AOI 技術提升生產品質。本次邀請各界資料科學家共襄盛舉，針對所提供的 AOI 影像資料，來判讀瑕疵的分類，藉以提升透過數據科學來加強 AOI 判讀之效能。

## 資料說明
本議題所提供之影像資料，包含 6 個類別（正常類別 + 5 種瑕疵類別）。
下載資料 aoi_data.zip 檔案包含：

train_images.zip：訓練所需的影像資料（PNG格式），共計 2,528 張。
train.csv：包含 2 個欄位，ID 和 Label。
ID：影像的檔名。
Label：瑕疵分類類別（0 表示 normal，1 表示 void，2 表示 horizontal defect，3 表示 vertical defect，4 表示 edge defect，5 表示 particle）。
test_images.zip：測試所需的影像資料（PNG格式），共計 10,142 張。
test.csv：包含 2 個欄位，ID 和 Label。
ID：影像的檔名。
Label：瑕疵分類類別（其值只能是下列其中之一：0、1、2、3、4、5）。



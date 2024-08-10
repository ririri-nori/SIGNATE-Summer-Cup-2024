# SIGNATE Cup 2024
## データ説明
### 配布データ
- 学習用データ: train.csv
- 評価用データ: test.csv
- 応募用サンプルファイル: sample_submit.csv
- discord招待用リンク: discord_url.txt
- チュートリアルコード: tutorial.ipynb
## 特徴量詳細
| ヘッダ名称  |  値例  |  データ型  |  説明  |
| ---- | ---- | ---- | ---- |
| id  |  0  |  int64  |  顧客ID  |
| Age  |  50歳  |  str  |  顧客の年齢  |
| TypeofContact  |  Self Enquiry  |  str  |  顧客への連絡・接触方法  |
| CityTier  |  2  |  int64  |  都市層(1>2>3)  |
| DurationOfPitch  |  900秒  |  str  |  営業担当者による顧客への商品のセールス時間  |
| Occupation  |  Large Business  | str  |  顧客の職業  |
| Gender | male | str | 顧客の性別 |
| NumberOfPersonVisiting | 1 | int64 | 予定している旅行の同行者の数 |
| NumberOfFollowups | 4.0 | float64 | セールス後に営業担当者が行ったフォローアップの回数 |
| ProductPitched | Basic | str | 営業担当者のセールスした商品の種類 |
| PreferredPropertyStar | 3.0 | float64 | 顧客の希望するホテルのランク |
| NumberOfTrips | 5 | str | 顧客の年間旅行数 |
| Passport | 1 | int64 | パスポートの所持(0: 不所持、1: 所持) |
| PitchSatisfactionScore | 4 | int64 | 営業担当者のセールストークに対する顧客の満足度 |
| Designation | Executive | str | 顧客の役職 |
| MonthlyIncome | 253905.0 | str | 顧客の月収 |
| customer_info | 未婚 車未所持 子供なし | str | 顧客の情報のメモ(婚姻状況や車の有無、旅行への子どもの同伴の有無) |
| ProdTaken(目的変数) | 1 | int64 | 商品の契約状態(0:不成約、1:成約) |

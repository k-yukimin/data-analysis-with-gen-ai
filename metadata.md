## データセット情報
このアーカイブには、2006年12月から2010年11月（47か月間）の間に、フランスのパリから7kmのSceauxにある住宅で収集された34589件の測定値が含まれています。  
注：（global_active_power*1000/60 - sub_metering_1 - sub_metering_2 - sub_metering_3）は、サブメータリング1、2、3で測定されていない電気機器によって家庭内で毎分消費される有効電力（ワット時単位）を表します。

## 変数テーブル
| 変数名                           | 型              |   単位 | 説明                                    |
| ------------------------------- | --------------- | -----: | ------------------------------------- |
| Datetime                        | datetime64\[ns] |      – | 時刻（各行の**時間の先頭**）。1時間間隔。    |
| Global\_active\_power\_min      | float64         |     kW | 有効電力の**最小値**。                |
| Global\_active\_power\_mean     | float64         |     kW | 有効電力の**平均値**。                 |
| Global\_active\_power\_max      | float64         |     kW | 有効電力の**最大値**。                  |
| Global\_reactive\_power\_min    | float64         |   kVAr | 無効電力の**最小値**。                          |
| Global\_reactive\_power\_mean   | float64         |   kVAr | 無効電力の**平均値**。         |
| Global\_reactive\_power\_max    | float64         |   kVAr | 無効電力の**最大値**。         |
| Voltage\_min                    | float64         |      V | 電圧の**最小値**。                     |
| Voltage\_mean                   | float64         |      V | 電圧の**平均値**。                         |
| Voltage\_max                    | float64         |      V | 電圧の**最大値**。                     |
| Global\_intensity\_min          | float64         |      A | 電流の**最小値**。                            |
| Global\_intensity\_mean         | float64         |      A | 電流の**平均値**。                         |
| Global\_intensity\_max          | float64         |      A | 電流の**最大値**。                            |
| Sub\_metering\_1                | float64         |     Wh | サブメータ1の**合計エネルギー**。主に食器洗い機、オーブン、電子レンジ（ホットプレートは電気ではなくガスで動作）を備えたキッチンに対応。 |
| Sub\_metering\_2                | float64         |     Wh | サブメータ2の**合計エネルギー**。洗濯機、タンブル乾燥機、冷蔵庫、照明を備えたランドリールームに対応。        |
| Sub\_metering\_3                | float64         |     Wh | サブメータ3の**合計エネルギー**。電気温水器とエアコンに対応。     |
| Sub\_metering\_other            | float64         |     Wh | サブメータ1-3以外の**合計エネルギー**。        |
| Sub\_metering\_total            | float64         |     Wh | サブメータ1-3とotherの和。     |

# Lily58 - χ
Lily58-χ(カイ)はLily58からforkされた[Lily58-glow](https://github.com/qtkb/Lily58-Glow)に以下の変更を加えたものです。

- RGBLEDのpad配置をSK6812mini-e用に変更(6つのunderglow用LEDは削除)
- BLE Micro Proのインジケータ用にLEDを追加
- ピンヘッダを追加してモジュールの開発を意識した設計に変更
- 縁を覆うようなケースを追加で設計

Lily58-χ(chi) is a forked version of [Lily58-glow](https://github.com/qtkb/Lily58-Glow) from Lily58 with the following changes.

- Change RGB LED pad from for SK6812mini-e. (I deleted 6 underglow LEDs)
- Add  LED for BLE Micro Pro's indicator.
- Add new Pinheader for additional modules.
- Add case that can cover edge.

このプロジェクトは開発中です。PCBの設計にミスがある可能性があります。
This project is still in progress. There may be some mistakes in PCB design.

![PCB view](https://i.imgur.com/vcMlJlq.png)

# Parts

| Part Name                                                    | Quantity | Shops I ordered from                                         |
| ------------------------------------------------------------ | -------- | ------------------------------------------------------------ |
| PCB                                                          | 2        | [Elecrow](https://www.elecrow.com/pcb-manufacturing.html?l=jp) |
| Top Case・Bottom Case<br />There's 2 option. Large one and Small one. | 2        | アクリル板をレーザー加工機で切り出し<br />Cutting out acrylic with a laser cutting machine by myself. |
| Pro Micro or BLE Micro Pro(=BMP)                             | 2        | 遊舎工房 [ProMicro](https://shop.yushakobo.jp/products/pro-micro?_pos=1&_sid=8720c1cd6&_ss=r) [BLEMicro](https://shop.yushakobo.jp/products/ble-micro-pro?_pos=4&_sid=8720c1cd6&_ss=r) |
| Blue LED SMLE13BC8TT86(option for BMP)                       | 1        | [秋月](https://akizukidenshi.com/catalog/g/gI-11881/)        |
| Constant current diode S-562T(option for BMP)                | 1        | [秋月](https://akizukidenshi.com/catalog/g/gI-06282/)        |
| Choc Key Switch                                              | 58       | [遊舎工房](https://shop.yushakobo.jp/products/pg1350?_pos=33&_sid=57b4f8c74&_ss=r) |
| Keycap(choc, transparent)                                    | 58       | [Aliexpress](https://ja.aliexpress.com/item/32979973961.html?spm=a2g0o.cart.0.0.4c8c3c00uyiPfq&mp=1) |
| SK6812-MINI-E                                                | 58       | [Aliexpress](https://ja.aliexpress.com/item/4000475685852.html?spm=a2g0o.productlist.0.0.7419755awSVy7F&algo_pvid=37805785-d316-40cc-8d8d-518c90b69743&algo_expid=37805785-d316-40cc-8d8d-518c90b69743-0&btsid=0ab6f8ad15936253073377411eecdc&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603) |
| OLED                                                         | 2        | [Aliexpress](https://ja.aliexpress.com/item/4001028384269.html?spm=a2g0o.cart.0.0.4c8c3c00uyiPfq&mp=1) |
| Diode 1N4148                                                 | 58       | [秋月](https://akizukidenshi.com/catalog/g/gI-07084/)        |
| Tact switch                                                  | 2        | [秋月](https://akizukidenshi.com/catalog/g/gP-08074/)        |
| TRRS jack (option for Pro Micro)                             | 2        | [秋月](https://akizukidenshi.com/catalog/g/gC-06070/)        |
| TRRS cable (opton for Pro Micro)                             | 1        | [遊舎工房](https://shop.yushakobo.jp/products/trrs_cable?_pos=1&_sid=0f41857b1&_ss=r) |
| M2 spacer 10mm                                               | 4        |                                                              |
| M2 spacer 4mm                                                | 10       |                                                              |
| M2 screw 10mm (option for large case)                        | 20       |                                                              |
| M2 screw 5mm                                                 | 8        |                                                              |
| M2 screw 3mm                                                 | 20       |                                                              |
| M2 Nut (option for large case)                               | 20       |                                                              |
| Urethane cushion                                             | 2        | [遊舎工房](https://shop.yushakobo.jp/collections/all-keyboard-parts/products/a0800ur-01-6) |
| Pin header(1×4 or 2×4)                                       | 2        |                                                              |

OLED部分に追加で取り付ける拡張モジュールの開発を予定しています。
The expansion modules that mount on the place of OLED will be coming soon.


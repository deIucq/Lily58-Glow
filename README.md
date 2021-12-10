# Lily58 - χ
ビルドガイドは[こちら](https://github.com/deIucq/Lily58-X/blob/master/buildguide.md)

BuildGuide is [here](https://github.com/deIucq/Lily58-X/blob/master/buildguide.md)



Lily58-χ(カイ)はLily58からforkされた[Lily58-glow](https://github.com/qtkb/Lily58-Glow)に以下の変更を加えたものです。

- RGBLEDのpad配置をSK6812mini-e用に変更(6つのunderglow用LEDは削除)
- BLE Micro Proのインジケータ用にLEDを追加
- トラックパッド用のピンヘッダ・ネジ穴を追加
- 縁を覆うようなケースを追加

Lily58-χ(chi) is a forked version of [Lily58-glow](https://github.com/qtkb/Lily58-Glow) from Lily58 with the following changes.

- Change RGB LED pad from for SK6812mini-e. (I deleted 6 underglow LEDs)
- Add  LED for BLE Micro Pro's indicator.
- Add new Pinheader for additional modules.
- Add case that can cover edge.

このプロジェクトは開発中です。PCBの設計にミスがある可能性があります。
This project is still in progress. There may be some mistakes in PCB design.

![PCB view](https://imgur.com/g2gsoDg.png)

# Parts

| Part Name                                                    | Quantity | Shops I ordered from                                         |
| ------------------------------------------------------------ | -------- | ------------------------------------------------------------ |
| PCB                                                          | 2        | [Elecrow](https://www.elecrow.com/pcb-manufacturing.html?l=jp) / [JLCPCB](https://cart.jlcpcb.com/quote?orderType=1&stencilLayer=2&stencilWidth=107&stencilLength=143&stencilCounts=5) |
| Top Case・Mid Case・Bottom Case                              | 2        | アクリル板をレーザー加工機で切り出し<br />Cutting out acrylic with a laser cutting machine by myself. |
| Pro Micro or BLE Micro Pro(=BMP)                             | 2        | 遊舎工房 [ProMicro](https://shop.yushakobo.jp/products/pro-micro?_pos=1&_sid=8720c1cd6&_ss=r) [BLEMicro](https://shop.yushakobo.jp/products/ble-micro-pro?_pos=4&_sid=8720c1cd6&_ss=r) |
| 1608 LED (option for BMP)                                    | 1        | [秋月](https://akizukidenshi.com/catalog/g/gI-11881/)        |
| Constant current diode or resistor(option for BMP)           | 1        | [秋月](https://akizukidenshi.com/catalog/g/gI-06282/)        |
| Choc Key Switch                                              | 58       | [遊舎工房](https://shop.yushakobo.jp/products/pg1350?_pos=33&_sid=57b4f8c74&_ss=r) |
| Keycap(choc, chocolate type)                                 | 58       | [Aliexpress](https://ja.aliexpress.com/item/32979973961.html?spm=a2g0o.cart.0.0.4c8c3c00uyiPfq&mp=1) |
| SK6812-MINI-E                                                | 58       | [Aliexpress](https://ja.aliexpress.com/item/4000475685852.html?spm=a2g0o.productlist.0.0.7419755awSVy7F&algo_pvid=37805785-d316-40cc-8d8d-518c90b69743&algo_expid=37805785-d316-40cc-8d8d-518c90b69743-0&btsid=0ab6f8ad15936253073377411eecdc&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603) |
| OLED                                                         | 2        | [Aliexpress](https://ja.aliexpress.com/item/4001028384269.html?spm=a2g0o.cart.0.0.4c8c3c00uyiPfq&mp=1) |
| Diode 1N4148W (must be SMD type for choc case)<br>If you assemble with MX, you can use TH type. | 58       | [秋月](https://akizukidenshi.com/catalog/g/gI-07084/)        |
| Tact switch                                                  | 2        | [秋月](https://akizukidenshi.com/catalog/g/gP-08074/)        |
| TRRS jack (option for Pro Micro)                             | 2        | [秋月](https://akizukidenshi.com/catalog/g/gC-06070/)        |
| TRRS cable (opton for Pro Micro)                             | 1        | [遊舎工房](https://shop.yushakobo.jp/products/trrs_cable?_pos=1&_sid=0f41857b1&_ss=r) |
| M2 screw 10mm                                                | 10       |                                                              |
| M2 Nut                                                       | 20       |                                                              |
| M2 spacer 10mm                                               | 4        |                                                              |
| M2 screw 5mm                                                 | 8        |                                                              |
| Urethane cushion                                             | 8 or 10  |                                                              |
| Pin header(1×4 & 1×6)                                        | 2        |                                                              |
| [optional] RKJXY1000006 trackpad with DIP convertPCB         | 1        | [秋月](https://akizukidenshi.com/catalog/g/gK-15425/)        |


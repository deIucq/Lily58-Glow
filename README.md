# Lily58 - χ
ビルドガイドは[こちら](https://github.com/deIucq/Lily58-X/blob/master/buildguide.md)

BuildGuide is [here](https://github.com/deIucq/Lily58-X/blob/master/buildguide.md)

Lily58-χ(カイ)はLily58からforkされた[Lily58-glow](https://github.com/qtkb/Lily58-Glow)に以下の変更を加えたものです。
検索性向上のために，ここ以外ではLily58-Xと表記します。

- RGBLEDのpad配置をSK6812mini-e用に変更
- Underglow用LEDの場所・数を変更
- BLE Micro Proのインジケータ用にLEDを追加
- トラックパッド用のピンヘッダ・ネジ穴を追加
- 縁を覆うようなケースを追加
- I2Cと単線シリアルをスイッチできるようにジャンパーを追加
- TRRSジャックのピンアサインを変更(moduloと同様のピンアサイン)

Lily58-χ(chi) is a forked version of [Lily58-glow](https://github.com/qtkb/Lily58-Glow) from Lily58 with the following changes.

- Change RGB LED pad to SK6812mini-e's one.
- Change place and number of LEDs for underglow.
- Add LED for BLE Micro Pro's indicator.
- Add new Pinheader for trackpad modules.
- Add case that can cover edge.
- Add jumber for switching I2C and Serial
- Change TRRS pin assign

このプロジェクトは開発中です。PCBの設計にミスがある可能性があります。
This project is still in progress. There may be some mistakes in PCB design.

![PCB view](https://i.imgur.com/I7OIKBQ.png)

# Parts

| Part Name                                                    | Quantity |
| ------------------------------------------------------------ | -------- |
| PCB                                                          | 2        |
| Top Case,Mid Case,Bottom Case(t2 acrylic)                    | 2        |
| Pro Micro or BLE Micro Pro                                   | 2        |
| Choc Key Switch                                              | 58       |
| Keycap                                                       | 58       |
| SK6812-MINI-E                                                | 58       |
| OLED                                                         | 2        |
| Diode 1N4148W                                                | 58       |
| Tact switch                                                  | 2        |
| TRRS jack (option for Pro Micro)                             | 2        |
| TRRS cable (opton for Pro Micro)                             | 1        |
| M2 screw 10mm                                                | 10       |
| M2 Nut                                                       | 20       |
| M2 spacer 10mm                                               | 4        |
| M2 screw 4mm                                                 | 8        |
| Urethane cushion                                             | 10       |
| Low profile pin header(1×4 & 1×6)                            | 2        |
| [option] RKJXY1000006 trackpad with DIP convertPCB           | 1        |
| [option] 1608 LED                                            | 1        |
| [option] Constant current diode or resistor                  | 1        |

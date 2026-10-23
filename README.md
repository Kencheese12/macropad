# macropad（みるな！）

4×4（14キー＋EC11ロータリーエンコーダー×2）のマクロパッド。

AIによる補助がどこまで行けるのか検証中

下は確認用

- MCU: Adafruit KB2040（コンスルー3.5mmで裏面に実装）
- スイッチ: Kailh Choc V2（ホットスワップ CPG135001S30）
- 基板: 86.2 × 86.2 mm、2層、JLCPCB PCBA（裏面実装）
- KiCad 10.0.7

## ブラウザで見る（KiCanvas）

- [基板を見る](https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2FKencheese12%2Fmacropad%2Fblob%2Fmain%2Ffocuspad.kicad_pcb)
- [回路図を見る](https://kicanvas.org/?github=https://github.com/ユーザー名/リポジトリ名/blob/main/focuspad.kicad_sch)

## ファイル構成

- `focuspad.kicad_pro` / `.kicad_sch` / `.kicad_pcb`: KiCadプロジェクト
- `focuspad.pretty/`: 自作フットプリント
- `fp-lib-table`: プロジェクト固有のフットプリントライブラリ登録
- `make_schematic.py`: 回路図生成スクリプト
- `place_focuspad.py`: 部品配置スクリプト
- `docs/`: 製作手順書・自動配線手順書# macropad

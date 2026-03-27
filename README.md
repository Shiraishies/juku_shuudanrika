# 振り返りプリント作成ルール

## 1. 環境
- 基本的な作業環境: VSCode
- クラス: `jlreq` (15pt)
- コンパイラ: `LuaLaTeX` または `uplatex`

## プリアンブル
- `\usepackage{amsmath}`
- `\usepackage{mathtools}`
- `\mathtoolsset{showonlyrefs=true}`
- `\pagestyle{empty}`
- `\usepackage[top=15mm, bottom=20mm, left=20mm, right=20mm]{geometry}`

## タイトル
 - 中央寄せ
 - 「振り返り」を`\LARGE`で
 - その下に内容を`-(内容)-`の形
 - 名前の欄を右側に設ける

## 本文
- enumerate環境に問題を追加していく．
- 文体は「だ，である ．」，「，．」
- 回答欄を()で設置．
- 語句は`(\hspace{2cm})`，記述は`(\hspace{15cm})`程度が好ましい
- 問題の間には`\vspace{2em}`
- 選択肢の問題は，tabular環境の左詰め(l)で配置．正方行列が望ましい
- 選択肢の回答欄は4cm程度空ける．
- 複数の要素を回答させる問題はitemize環境を使用
- 数式はalign環境で式番号は基本不要
- 元素などのイタリックにしたくないアルファベットはmathrm環境を使用
- 順番を答えさせる問題は`$\rightarrow$`で回答欄に順番を指定

## 内容
- 問題数は6~8問程度
- A4用紙1ページに収めること
- 記述問題等の思考力問題を最低1問入れること
- 基本的に授業の範囲からであるが，以前の範囲も可

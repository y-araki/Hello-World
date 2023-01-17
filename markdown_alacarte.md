# Markdownアラカルト

## 箇条書き
* あ
* い
* う

## チェックボックス
- [ ] 選択肢1
- [x] 選択肢2

## 表組み
| 見出し1 | 見出し2 | 見出し3 |
| :-      |   :-:   |      -: |
| データ1 | データ2 | データ3 |
|あ|い|う|
|か|き|く|

## プログラムコード
``` Python
import whisper

model = whisper.load_model("large")    # モデルを指定
result = model.transcribe("audio.mp3") # 音声認識を実行
print(result["text"])
```

## コマンドプロンプト
``` Shell
@echo off
@echo *** This is a sample of markdown text. ***
```

## LaTex
$$ x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$

## 画像変換コマンド

画像を指定の形式に変換する
変換後の画像ファイルはカレントディレクトリに出力される

### コマンドラインオプション

| オプション | 値の説明         | デフォルト値 |
| ---------- | ---------------- | ------------ |
| -src       | 変換前の画像形式 | jpg          |
| -dest      | 変換後の画像形式 | png          |

### 使用方法

1. バイナリビルド

```bash
go build
```

2. ディレクトリを指定して実行

```bash
./image-conversion [...options] [directory]
```

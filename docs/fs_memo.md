初期値はルートディレクトリ cd = 1
lsで現在のディレクトリのファイル一覧

1. 0x808cからパステーブルのセクタを読みだす
2. パステーブルのセクタから対象のディレクトリを探し出し(6-7bitが親ディレクトリの番号)
3. 2-5bitでディレクトリのセクタを探し出す
4. ディレクトリエントリからファイル名を取得する
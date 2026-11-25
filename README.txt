ミライ残高 PWA試用版 0.2.1（ホームバー安全領域修正）

【変更点】
- iPhoneのホーム画面から起動した際、下部メニューの下に余白を設けます。
- タブの高さは44px以上にして押しやすくします。
- 横スワイプ・JSON復元・残高計算・保存データ構造は変更していません。

【GitHub Pagesへの更新】
1. このフォルダ内の index.html、sw.js、manifest.webmanifest、icon画像2個を、リポジトリのルートへ上書きアップロードします。
2. GitHubの反映後、iPhoneがオンラインの状態でホーム画面のミライ残高を開き直します。
3. アプリ上部に「PWA試用版 0.2.1」と出ることを確認してください。
4. 下部メニューがホームバーと重ならず、各項目を押せるか確認します。
5. 最後に機内モードで起動し、データが残っているかを確認します。

注意：ホーム画面のアイコン削除・Safariサイトデータ削除は行わないでください。保存データが失われる恐れがあります。更新前にJSONバックアップも推奨します。

Ver.0.2.2: iOS PWA bottom bar clearance; network-first navigation so updated HTML loads online. Existing local data storage keys unchanged.

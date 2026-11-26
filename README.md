# Chrome Theme Maker

A simple, bilingual (Japanese / English) browser-based tool for creating Chrome themes from your own images.

自分の画像からChromeテーマを作れる、シンプルな日本語／英語対応Webアプリです。

## Features / 機能

- Japanese and English interface with a language switch / 日本語・英語の切り替え
- Load images and browser-supported videos / 画像・ブラウザー対応動画の読み込み
- Drag to reposition and crop / ドラッグで切り取り位置を調整
- Zoom from 100% to 300% / 100〜300%の拡大・縮小
- Preset and custom output sizes / 比率プリセット・カスタムサイズ
- Fit or fill image modes, with background color / 全体表示・全面表示、余白の色設定
- Customize tab and toolbar colors / タブバー・ツールバーの色設定
- Export a cropped PNG or a ready-to-load Chrome theme ZIP / PNGまたはChromeテーマZIPの書き出し
- All processing happens locally in the browser / すべてブラウザー内で処理（画像のアップロードなし）
- No framework, external library, build step, or API key / フレームワーク・外部ライブラリ・ビルド・APIキー不要

## Run locally / ローカルで起動

Open `index.html` in Chrome, Edge, Firefox, or another modern browser.

`index.html` をChrome、Edge、Firefoxなどのモダンブラウザーで開いてください。

## Publish with GitHub Pages / GitHub Pagesで公開

1. Create a new GitHub repository.
2. Upload all files in this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Open the Pages URL shown by GitHub.

日本語：

1. GitHubで新しいリポジトリを作成します。
2. このフォルダー内のファイルをリポジトリ直下にアップロードします。
3. **Settings → Pages** を開きます。
4. **Deploy from a branch** を選択します。
5. `main` ブランチと `/ (root)` を指定して保存します。
6. GitHubに表示されたPagesのURLを開きます。

## Install a generated theme / 作成したテーマの適用

1. Download the theme ZIP and extract it.
2. Open `chrome://extensions` in Chrome.
3. Enable **Developer mode**.
4. Click **Load unpacked** and select the extracted folder.

日本語：

1. テーマZIPをダウンロードして解凍します。
2. Chromeで `chrome://extensions` を開きます。
3. デベロッパーモードをオンにします。
4. **パッケージ化されていない拡張機能を読み込む** をクリックし、解凍したフォルダーを選択します。

## Video support / 動画について

Chrome themes use a still image for the New Tab background. This tool lets you choose a frame from a browser-supported video and exports that frame as a PNG. Supported video formats depend on the browser.

Chromeテーマの新しいタブ背景には静止画を使用します。このツールでは、ブラウザーで再生できる動画からフレームを選択し、PNG画像として書き出します。対応する動画形式はブラウザーによって異なります。

## Privacy / プライバシー

Files are processed locally in your browser. The app does not upload images or videos to a server.

画像や動画はブラウザー内で処理され、サーバーにはアップロードされません。

## License

MIT. See [LICENSE](LICENSE).

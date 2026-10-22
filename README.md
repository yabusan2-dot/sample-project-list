## 🚀 開発プロジェクト ＆ 成果物一覧

### 1. 🎵 Web Audio API 音楽クリエイターツール（公開中）
* **公開ページ**: (https://yabusan2-dot.github.io/my-music-tools/)
* **リポジトリ**: (https://github.com/yabusan2-dot/my-music-tools)
* **技術スタック**: JavaScript (Vanilla JS), Web Audio API, Node.js, OpenAI API
* **概要**: 外部の音源ファイル（Wav/MP3等）に依存せず、CanvasとWeb Audio APIのコード制御のみで効果音やBGMを動的生成する実験的ツール群。サンプルフレーズの生成ロジックにOpenAI APIを組み込むなど、AI連携の可能性を模索した作品です。
* **内包ツール**: シーケンサー、ミキサー、リズムマシーン、SEジェネレーター

### 2. 💥 シューティングゲーム（ランキングシステム） （公開中）
* **公開ページ**:(https://yabusan2-dot.github.io/shooting-game-firebase/)
* **リポジトリ**: (https://github.com/yabusan2-dot/shooting-game-firebase)
* **技術スタック**: HTML5 Canvas,JavaScript (Vanilla JS), CSS3
* **特長**: HTML5の Canvas機能 を用いた軽量なグラフィックス描画制御と、バックエンドに Firebase Realtime Database を組み合わせた、リアルタイム・スコアランキング機能付きのシューティングゲーム。

### 3. 🥏 WebSocket エアーホッケー（リアルタイム対戦サーバー） （公開中）
* **対戦イメージ動画**:(https://github.com/yabusan2-dot/air-hockey-websocket/issues/1)
* **リポジトリ**: (https://github.com/yabusan2-dot/air-hockey-websocket)
* **技術スタック**: Node.js (標準モジュールのみ), WebSocket, HTML5 Canvas
* **特長**: 外部ライブラリ（socket.io等）に頼らず、RFC 6455準拠のバイナリフレーム解析・マスク解除を自前で実装。通信遅延（レイテンシ）を徹底検証し、すべての物理演算（衝突判定・速度計算）をサーバー側で一元管理する「サーバーサイド・オーソリティ方式」を採用したガチガチの同期型対戦エンジン。

### 4. 📱⚪ センサー連動ゲーム （公開中）
* **リポジトリ**: (https://github.com/yabusan2-dot/android-ball-control-game)
* **技術スタック**: Java, Android SDK,回転ベクトルセンサー、多層プロキシ環境自動突破システム
* **特長**: 端末の物理センサーと連動した「玉転がし迷路脱出ゲーム」

### 5. ⚾ 2.5D スマホ連動型バッティングシミュレーター 【近日公開】
* **技術スタック**: JavaScript, WebSocket, Android Java (Sensor API)
* **特長**: スマホの3軸加速度・傾き（Roll角）をリアルタイムにバットの軌道行列へコンバートするマルチデバイス連携。3Dエンジンを使わず、投球時の「斜め30度視点」とインパクト時の「真上俯瞰ビュー」を直交反転させる2.5次元カメラワークをCSSとCanvasのみで軽量実装。サードやレフトなど扇形フィールドの野手守備半径（r）と打球の仮想高さによる3次元コリジョン（当たり判定）を数理実装。

### 6. 💻 Java 暗号通信利用の通信サンプルコード（RSA、ECC）
* **リポジトリ**: (https://github.com/yabusan2-dot/RSA_sample)
* **リポジトリ**: (https://github.com/yabusan2-dot/ECC_sample)
* **技術スタック**: Java, Android SDK, BigInteger (多倍長整数演算)
* **特長**: RSA暗号や楕円曲線暗号（ECC）の数理理論を3日間で解読し、スクラッチで暗号化・復号モジュールを実装。JavaのBigInteger仕様に伴う先頭符号ビット（0x00）の除去や、ネットワーク転送時の128バイト固定長ブロックバッファの厳格なパディング制御を自力で実装し、パケット崩壊を防ぐ堅牢性を担保。

---

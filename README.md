# Liryc デスクトップ版の配布

Windows／macOS向けLirycの配布ファイルと変更履歴を公開するリポジトリです。

**現在、配布版はまだ公開していません。Mac対応と配布手順を準備中です。**

## ダウンロード

配布版の公開後は、[Releases](https://github.com/stangun1024/Liryc-releases/releases)からお使いのOS・CPUに合ったファイルを選んでください。

- Windows x64: `Liryc-<バージョン>-win32-x64.exe`
- Apple Silicon Mac: `Liryc-<バージョン>-darwin-arm64.dmg`
- Intel Mac: `Liryc-<バージョン>-darwin-x64.dmg`

すべてのCPU向け成果物が毎回提供されるとは限りません。対応OS、実機確認結果、既知の制限は各リリースの説明で確認してください。`.release.json`と`.sha256`は配布情報・整合性確認用のファイルです。

## インストール・更新

Windowsではインストーラーを起動します。MacではDMGを開き、Liryc.appをApplicationsへコピーします。初期の試験配布ではWindowsの発行元署名、MacのDeveloper ID署名・公証を行わないため、OSが警告を表示したり起動を制限したりする場合があります。

更新前にLirycのバックアップを保存し、通常版・DJ版・VJ版をすべて終了してから新版をインストールしてください。初期版の更新通知は配布ページへの案内です。自動ダウンロード・自動再起動は行いません。

自作スタイルはアプリの設定から保存フォルダーを開いて配置します。旧フォルダー版のvideo-stylesからは、設定の取り込み操作で自作JSを移せます。標準スタイルを直接編集したものは、別のID・ファイル名の自作として保存してください。

## Mac版の初期制限

Spout出力とWindows用rkbx_link.exeの起動管理は対象外です。PRO DJ LINK、外部からのOSC入力、外部画面出力などの対応状況は、実機確認後にリリースの説明へ記載します。

## 問い合わせ

不具合は[Issues](https://github.com/stangun1024/Liryc-releases/issues)へ、バージョン、OS、CPU、再現手順を添えて報告してください。ログや画面には歌詞、音源パス、認証情報などが含まれることがあるため、公開前に内容を確認してください。

# aadetailer-neoforge — asugonomi fork

Animaの顔修正などの入れ子生成へAnima Native Toolsの引数とdistilled_cfg_scaleを引き継ぐ。

元プロジェクト: https://github.com/abzaloff/aadetailer-neoforge

ベースコミット: `c4c036d3b1f8bd3a298d6e64878d8338dbfe2597`。このフォークはローカルで使用していた版を基準にしています。上流最新版に含まれるすべての変更を取り込んだという意味ではありません。

## 導入と復元

バックアップと対応版チェック付きの導入は [ForgeNeoModification](https://github.com/asugonomi/ForgeNeoModification) を利用してください。管理ツール経由の場合は元の上流版へ差分を適用し、HEAD/remoteは変更しません。

このフォークを直接利用する場合は既存拡張と二重に配置しないでください。直接導入したファイルは管理ツールの復元対象にはなりません。個人設定・モデル・APIキー・ログ・使用履歴は同梱していません。

## ライセンス

AGPL-3.0。上流のライセンス・著作権表示を保持しています。変更部分はこのドキュメントとコミット差分で識別できます。上流作者による保証・推奨を示すものではありません。

## 検証の範囲

配布元の固定コミットからのファイル適用・ハッシュ一致・復元と、該当Python/JavaScriptの構文を確認しています。今回の公開作業でGPU生成・モデルマージ・ブラウザーでの全機能確認は実施していません。

# プライバシーポリシー

## 第1条（適用範囲）
本プライバシーポリシー（以下「本ポリシー」）は、OTOKotoba BOT（以下「当BOT」）の利用者（以下「ユーザー」）が当BOTを利用する際に適用されるものとします。

## 第2条（取得する情報）

### ログ情報
当BOTは、以下の情報を記録することがあります。

- ボイスチャンネルへの参加および退出時のログ
- エラー発生時のログ
- サーバー名およびサーバーID
- チャンネル名およびチャンネルID
- メッセージを受信したことを示す「On Message」の記録
- VCチャンネル名およびメッセージがスキップされた理由

### 保存情報
当BOTは、BOTの再起動後に再接続するために、以下の情報を保存します。

- サーバーID
- ボイスチャンネルID（channel_id）

保存された情報は、ユーザーが `/leave` コマンドを実行した際に自動的に削除されます。

### 音声モデル情報
当BOTは、音声モデル情報を保存する目的でユーザーIDを取得・保存することがあります。

### 統計情報
当BOTは、以下の情報を収集し、統計データとして処理します。

- サーバー数
- ボイスチャンネル接続数
- `/misreading` が実行された場合、実行する45秒前までのメッセージ

これらの統計情報はグラフ画像として書き出され、ユーザーがコマンドを実行することで確認できる場合があります。

### 開発版における追加情報の収集
当BOTの「開発版」に限り、以下の情報を収集することがあります。

- ユーザーID
- サーバー名
- 申請理由

これらの情報は、開発版の利用資格を確認する際に使用します。

## 第3条（情報の利用目的）
取得した情報は、以下の目的で使用されます。

- BOTの正常な動作およびサービスの提供
- BOTのバグ修正、機能強化および改善
- ユーザーの利便性向上のための統計情報の作成および提供
- 誤った読みに対するAIへの学習

## 第4条（ログの保存および削除）
ログ情報には原則メッセージの内容は含まれません。ただし、第2条6-3の場合は例外とします。

ログ情報は、BOTが実行されているターミナルを閉じた際に破棄されます。

## 第5条（プライバシーポリシーの変更）
当BOTの運営者は、必要に応じて本ポリシーを変更することができるものとします。

本ポリシーの変更後に当BOTを利用した場合、ユーザーは変更後のポリシーに同意したものとみなされます。

## 第6条（同意）
ユーザーは、当BOTをサーバーに招待した時点で、本ポリシーに同意したものとみなします。

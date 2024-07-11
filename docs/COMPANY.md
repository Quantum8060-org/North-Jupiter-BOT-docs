# 企業用コマンドリスト

## 注意事項
> [!CAUTION]
> アップデートで実装・廃止・修正された機能が載っている場合があります。
>
> 基本的に更新直後にこのドキュメントも更新されますが、必ずしも最新というわけではありませんので、最新情報をご確認ください。
>
> 最新情報はノースユーピテルサーバーのお知らせチャンネルにあります。
>
> また、機能の改善案や新しい機能の案等がありましたらQuantum8060(Discord名:Q'm)に送っていただけると助かります。

## ① /compnay bal \{company\}

自分の所有する企業の所持金を確認します。

companyで企業を指定してください。


## ② /company pay \{amount\} \{mycompany\} \{user\} \{company\}

指定したユーザー・企業に送金します。

amountに金額、mycompanyに自分の企業、userに送金先のユーザー、companyに送金先の企業を入力してください。（userとcompanyを一緒に入力すると送金できません。）

残高が足りない場合は送金ができません。

※指定したユーザー・企業が口座を持っていない場合は送金ができません。ユーザーの口座があるか確認する場合は[search](https://github.com/Quantum8060-org/North-Jupiter-BOT-docs/blob/main/docs/COMMANDS.md#-search-user)コマンドを実行してください。


## ③ /company open \{name\}

nameで指定した名前で企業口座を開設します。


## ④ /company add \{user\}

企業口座を操作できるユーザーを追加します。

このコマンドを使用できるのは企業を作成したユーザーのみです。
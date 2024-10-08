# 一般ユーザー向けコマンドリスト

## 注意事項
> [!CAUTION]
> アップデートで実装・廃止・修正された機能が載っている場合があります。
>
> 基本的に更新直後にこのドキュメントも更新されますが、必ずしも最新というわけではありませんので、最新情報をご確認ください。
>
> 最新情報はノースユーピテルサーバーのお知らせチャンネルにあります。
>
> また、機能の改善案や新しい機能の案等がありましたらQuantum8060(Discord名:Q'm)に送っていただけると助かります。

## ① /bal

自分の所持金を確認できます。


## ② /pay \{amount\} \{user\} \{company\} \{reason\}

指定したユーザー・企業に送金します。

amountに金額、userに送金先のユーザー、companyに送金先の企業を入力してください。（reasonは任意です。）

userとcompanyは両方同時に指定できません。

また、指定したユーザーが口座を持っていない場合は送金ができません。


## ③ /info
ノスタルへの交換レートを表示します。


## ④ /anonymous \{text\} \{picture\}
匿名でメッセージを送信できます。


## ⑤ /tax
納税を行います。

※国民のみ使用可能です。外国の人が使用した場合の返金等はいたしません。


## ⑥ /アルバイト給与計算 \{user\} \{hourly\} \{time\}
アルバイトの給料を計算できます。

userに働いたユーザー、hourlyに時給、timeに働いた時間を入力してください。

※現時点ではこのまま送金する機能はついておりません。


## ⑦ /空色財閥返済計算 \{money\} \{year\} \{month\} \{day\}
空色財閥から借入を行っている場合に返済必要額を計算できます。

moneyに借入額、yearに借りた年、monthに借りた月、dayに借りた日付を入力してください。

上記の入力内容と現在の時刻から返済必要額を割り出します。
# ラボ06：Microsoft Purview を探索する

#### 推定時間: 30 分



### タスク 1 - Microsoft  Purview ポータルへアクセスする

> 注：タスク1は設定変更する手順は含まれてません。設定画面の確認のみを行います。

1. https://compliance.microsoft.com/ へアクセスし、以下のアカウントでサインインします。

   > 注：XXXXはご自身のアカウント番号を入力してください。
   >
   > 注：「アカウントの保護にご協力ください」と表示された場合は「今はしない」を選択してください

   | 項目       | 値                                                           |
   | ---------- | ------------------------------------------------------------ |
   | ユーザーID | `admin@XXXXXXXXXXX.onmicrosoft.com`<br />@マーク以降のXXXXXXXXXは各自異なります。 |
   | パスワード | Skillableで取得したパスワード                                |

1. サインインが完了すると「新しい Microsoft Purview ポータルへようこそ」と表示されます。「次に同意します」に✅を入れ、「開始する」をクリックします。

    

### タスク 2 - コンプライアンス マネージャーを確認する

1. 左側のナビゲーション メニューの 「ソリューション」をクリックし、「コンプライアンス マネージャー」をクリックします。
2. 「コンプライアンス マネージャーへようこそ」と表示されます。説明文を確認しつつ、「次へ」をクリックし、最後に「完了」をクリックします。
3. 「コンプライアンス マネージャー」画面の全体を確認します。
4. 左側のナビゲーション メニューの「改善アクション」をクリックします。
5. 改善のための処置が一覧に表示されます。適当な項目をクリックし、詳細を確認します。

> ※タスク2の演習はここまでですが、左側のナビゲーション メニューの項目なども時間があれば確認してみてください。



### タスク 3 - コミュニケーション コンプライアンスを確認する

1. 左側のナビゲーション メニューの 「ソリューション」をクリックし、「コミュニケーション コンプライアンス」をクリックします。
2. 「不適切なテキストを含むメッセージを調査する」の項目にある「ポリシーの作成」をクリックします。
3. 「不適切なテキストの通信の検出」画面で「レビュー担当者」に「MOD Administrator」と入力し、選択します。
4. 「ポリシーの作成」をクリックします。
5. 「ポリシーが作成されました」と表示されたら、「閉じる」をクリックします。
6. 左側のナビゲーション メニューの「分類子」をクリックし、さらに「トレーニング可能な分類子」をクリックします。
7. 一覧に表示される項目を適当にクリックし、詳細を確認します。

> ※タスク3の演習はここまでですが、左側のナビゲーション メニューの項目なども時間があれば確認してみてください。



### タスク 4 - 情報保護を確認する

1. 左側のナビゲーション メニューの 「ソリューション」をクリックし、「情報保護」をクリックします。
2. Microsoft Information Protectionの概要ページが表示されます。
3. 左側のナビゲーション メニューの「秘密度ラベル」をクリックします。
4. 「ラベルを作成」をクリックします。
5. 「名前」と表示名には「test label2」、「ユーザー向けの説明」には「test」と入力し、画面下にある「次へ」をクリックします。
6. 「このラベルの範囲を定義する」は、変更せずに画面下にある「次へ」をクリックします。
7. 「選択した項目の種類の保護設定を選択します」は、変更せずに画面下にある「次へ」をクリックします。
8. 「ファイルとメールの自動ラベル付け」は、変更せずに画面下にある「次へ」をクリックします。
9. 「グループとサイトの保護設定を定義」は、変更せずに画面下にある「次へ」をクリックします。
10. 「スキーマ化されたデータ アセットの自動ラベル付け (プレビュー)」は、変更せずに画面下にある「次へ」をクリックします。
11. 「設定を確認して完了」では「ラベルを作成」をクリックします。
12. 「秘密度ラベルが作成されました」と表示されます。「完了」をクリックします。
13. 「ラベルの発行」が表示されます。「Label Policy」では「Global sensitivity label policy」を選択し画面下にある「追加」をクリックします。
14. 「Global sensitivity label policy」では画面下にある「追加」をクリックします。
15. 最後に画面下にある「閉じる」をクリックします。

> ※タスク4の演習はここまでですが、左側のナビゲーション メニューの項目なども時間があれば確認してみてください。



### タスク 5 - データ ライフサイクル管理を確認する

1. 左側のナビゲーション メニューの 「ソリューション」をクリックし、「データ ライフサイクル管理」をクリックします。
2. データ損失防止の概要ページが表示されます。
3. 左側のナビゲーション メニューの「保持ラベル」をクリックします。
4. 「ラベルを作成」をクリックします。
5. 「名前」には「test label」と入力し、画面下にある「次へ」をクリックします。
6. 「ラベル設定の定義」は、変更せずに画面下にある「次へ」をクリックします。
7. 「保持期間の定義」は、変更せずに画面下にある「次へ」をクリックします。
8. 「保持期間後の動作を選択する」は、変更せずに画面下にある「次へ」をクリックします。
9. 「確認と完了」では「ラベルを作成」をクリックします。
10. 「保持ラベルが作成されました」と表示されます。「完了」をクリックします。
11. 「発行するラベルを選択」は、変更せずに画面下にある「次へ」をクリックします。
12. 「ポリシー スコープ」は、変更せずに画面下にある「次へ」をクリックします。
13. 「作成するアイテム保持ポリシーの種類を選択する」は「静的」に変更し、画面下にある「次へ」をクリックします。
14. 「ラベルを公開する場所を選択する 」は、変更せずに画面下にある「次へ」をクリックします。
15. 「ポリシーの名前を設定」では「sample policy」と入力し、画面下にある「次へ」をクリックします。
16. 「完了」では「送信」をクリックします。
17. 「保持ラベルが発行されました」と表示されます。「完了」をクリックします。

> ※タスク5の演習はここまでですが、左側のナビゲーション メニューの項目なども時間があれば確認してみてください。



### タスク 6 - データ損失防止を確認する

1. 左側のナビゲーション メニューの 「ソリューション」をクリックし、「データ損失防止」をクリックします。
2. データ損失防止の概要ページが表示されます。画面全体を確認します。
3. 左側のナビゲーション メニューの「ポリシー」をクリックします。
4. 「ポリシーの作成」をクリックします。
5. 「テンプレートの利用またはカスタム ポリシーの作成」では「すべての国または地域」で「日本」を選択します。
6. 「財務」をクリックし、さらに「日本金融関連データ」をクリックし、画面下にある「次へ」をクリックします。
7. 「DLP ポリシーの名前の設定」は、変更せずに画面下にある「次へ」をクリックします。
8. 「管理単位を割り当てる」は、変更せずに画面下にある「次へ」をクリックします。
9. 「このポリシーの適用先を選択します」は、変更せずに画面下にある「次へ」をクリックします。
10. 「ポリシーの設定の定義」は、変更せずに画面下にある「次へ」をクリックします。
11. 「保護対象の情報」は、変更せずに画面下にある「次へ」をクリックします。
12. 「保護処理」は、変更せずに画面下にある「次へ」をクリックします。
13. 「アクセスと上書きの設定のカスタマイズ」は、変更せずに画面下にある「次へ」をクリックします。
14. 「ポリシー モード」は、変更せずに画面下にある「次へ」をクリックします。
15. 「確認と完了」では画面下にある「送信」をクリックします。
16. 「新しいポリシーが作成されました」と表示されます。「完了」をクリックします。

> ※タスク6の演習はここまでですが、左側のナビゲーション メニューの「アラート」「アクティビティ エクスプローラー」「レポート」「 エクスプローラー」なども時間があれば確認してみてください。



### タスク 7 - 電子情報開示を確認する

1. 左側のナビゲーション メニューの 「ソリューション」をクリックし、「電子情報開示」をクリックします。
2. 電子情報開示の概要ページが表示されます。「ケース」をクリックします。
3. 「ケースを作成」をクリックします。
4. 「名前」には「test case」と入力し「次へ」をクリックします。
5. 「チームメンバー」には「MOD Administrator」を入力および選択し「次へ」をクリックします。
6. 「ケースの確認」では「送信」をクリックします。
7. 「新しいケースの準備ができました。」と表示されたら「完了」をクリックします。
8. 「test case」の画面が表示されます。「データソース」をクリックします。
9. 「データソースを追加する」をクリックし、「新しいカストディアンを追加」をクリックします。
10. 「組織のアクティブなディレクトリから新しいカストディアンを識別」に「Alex Wilber」と入力かつ選択し、画面下にある「次へ」をクリックします。
11. 「設定を保留する」変更せずに画面下にある「次へ」をクリックします。
12. 「カストディアンを確認する」では画面下にある「送信」をクリックします。
13. 「新しいカストディアンが作成されました」では画面下にある「完了」をクリックします。

> ※タスク7の演習はここまでですが、左側のナビゲーション メニューの項目なども時間があれば確認してみてください。



**Lab06は以上です。お疲れ様でした。**

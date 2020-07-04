# 日本の飲食店オープンデータ
Save the tablesが提供する日本全国の飲食店の店名・ジャンル・位置情報などを含むオープンデータです。
## 目的
[Save the tables](https://savethetables.org/)は**COVID-19**で苦境にある日本の飲食店を応援するプロジェクト**Save Restaurants**として立ち上がりました。プロジェクトに賛同した多くの人によるデータ提供があり、2020/7/1現在3600軒を超える飲食店データが集まっています。飲食店を広く応援するためには、データを広く活用していただく必要があると考え、このたびオープンデータ化いたしました。
## フォーマット
データはcsv形式です。Save the Tablesでは、Googleスプレッドシートで管理しており、[アプリ](https://savethetables.org/app)はAppSheetを利用して作っています。
## ライセンス
公開している各種データは、[MITライセンス](https://ja.osdn.net/projects/opensource/wiki/licenses%2FMIT_license)のもとでご利用いただけます。	
## 免責事項
Save the tablesは契約行為、不法行為、またはそれ以外であろうと**日本の飲食店オープンデータ**に起因または関連し、あるいはデータの使用またはその他の扱いによって生じる一切の請求、損害、その他の義務について何らの責任も負わないものとします。
## カラム（内容/データ型） ※空欄の場合有
- name（店名/string）
- ジャンル（お店の料理ジャンル/string）
- その他ジャンル（お店の量ジャンルの詳細/string）※
- 都道府県（店舗所在地の都道府県/string）
- 住所（所在地の住所/string）
- 建物名フロア数（所在地の建物名と部屋番号など/string）
- 電話番号（店舗電話番号/number）
- 最寄り駅（最寄り駅/string）
- Googleマップ（店舗のGoogleマップリンク）
- ウェブサイト（店舗のウェブサイト/string）
- イートイン（イートイン営業の有無/boolean）
- テイクアウト（テイクアウト営業の有無/boolean）
- デリバリー（デリバリー営業の有無/boolean）
- 通販（通販サイトの有無/boolean）
- クラファン・チケット（クラウドファンディングや食券サービス実施の有無/boolean）
- オンライン料理教室（オンライン料理教室実施の有無/boolean）
- 期限付酒類小売業免許（期限付き酒類小売業免許の有無/boolean）
- Twitter（店舗のTwitterアカウントURL/string）
- Facebook（店舗のフェイスブックページURL/string）
- Instagram（店舗のInstagramアカウントURL/string）
- 公式LINE（店舗の公式LINEアカウントURL/string）
- 混雑状況アプリ（店舗の混雑状況サービスURL/string）
- 位置情報(緯度経度)（店舗の緯度経度/number）
- 定休日（定休日/string）
- 営業時間（営業時間/string）
- イートインメニュー（イートインメニュー/string）
- 非接触決済（ペイペイなど非接触決済の有無/boolean）
- クレジットカード（クレジットカード使用の可否/boolean）
- 個室（個室の有無/boolean）
- 室内の完全禁煙（室内の完全禁煙実施の有無/boolean）
- バリアフリー（バリアフリー対応の有無/boolean）
- 席数（席数/number）
- 営業時間(テイクアウト)（テイクアウトの営業時間/string）
- テイクアウトメニュー（テイクアウトメニュー/string）
- 事前注文URL（テイクアウトの事前注文サービスURL/string）
- サービス名（利用できるデリバリーサービス名/string）
- サービスのURL（利用できるデリバリーサービスのURL）
- サービス名２（利用できるデリバリーサービス名/string）
- サービスのURL２（利用できるデリバリーサービスのURL/string）
- 詳細（デリバリーできるメニューの詳細/string）
- 出前のURL（その他出前注文などのURL/string）
- 通販サイト（通販サイト/string）
- 通販サイト2（通販サイト/string）
- 通販メニュー（通販で購入できる商品/string）
- サイト名（クラウドファンディングなどのサービスサイト名/string）
- タイトル（クラウドファンディング等のタイトル/string）
- サービスURL（クラウドファンディング等のURL/string）
- 終了日（クラウドファンディング等の終了日/string）
- サイト名（オンライン料理教室を行っているサイト名/string）
- 料理教室の内容（オンライン料理教室の内容/string）
- オンラインのURL（オンライン料理教室のURL/string）
## 運営元
Save the tables [ウェブサイト](https://savethetables.org/)

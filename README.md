# MarsTear
## 初めに
このドキュメントは日本人ユーザー向けに提供されています。
外国人のユーザーは翻訳サービスを利用するか、後日作成予定の外国人向けドキュメントをご参照ください。

_**This document is provided for Japanese users.
If you are a foreign user, please use the translation service or refer to the document for foreigners which will be prepared later.**_

## MarsTearとは
 MarsTearとは、自身のサーバーのDDOS攻撃の耐久性をテストするツールです。これは、完全無料で提供しています。
現在、以下の攻撃手法を利用できます。
 |  攻撃手法  |  説明  |
| ---- | ---- |
|  HTTP GET  |  HTTPのGETを用いてサーバーに攻撃を行います。URLにランダムな文字を含めることもできます。  |
|  HTTP POST  |  HTTPのPOSTを用いてサーバーに攻撃を行います。URL,REQ BODYにランダムな文字を含めることもできます。  |

攻撃手法はこれからも追加予定です。

## 攻撃サーバーについて
　MarsTearでは、攻撃サーバーを用いてDDOS攻撃を行います。
 攻撃サーバーは、通常**30~50**台稼働しています。
 攻撃サーバーのステータスは https://marstear.com/status にて確認できます。
 
## ブラックリストについて
　MarsTearは、ほとんどのウェブサイトに対してDDOS攻撃の耐久性を測定できますが、以下のリストに登録されたウェブサイトは攻撃できません。
  |  ブラックリストに登録されたウェブサイト  |
| ---- |
|  https://marstear.com  |

これは、事前予告なしに変更される場合があります。

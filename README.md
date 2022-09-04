# Japanese Language Pack for Flarum
[![CI](https://github.com/flarum-lang/japanese/workflows/CI/badge.svg)](https://github.com/flarum-lang/japanese/actions?query=workflow%3ACI)<br>
Japanese language pack to localize the Flarum.
## インストール方法 | Installation
1. Flarumがインストールされているディレクトリで以下のコマンドを実行してください。<br>
Run the following command in the location where Flarum is installed.
```
composer require flarum-lang/japanese
```

2. 管理画面の拡張機能ページから、`` Japanese ``を有効化します。<br>
Go to Extensions page of the admin interface and enable ``Japanese``.

3. 管理画面の基本ページからデフォルトの言語を``Japanese``に変更します。<br>
Go to Basics page of the admin interface and change default language to ``Japanese``.

## アップデートと削除方法 | Update and Uninstall
Flarumがインストールされているディレクトリで以下のコマンドを実行してください。<br>
Run the following command in the location where Flarum is installed.

- アップデート | Update
```
composer update flarum-lang/japanese
```
- アンインストール | Uninstall
```
composer remove flarum-lang/japanese
```

## :warning: Weblateとの統合について | About integration with Weblate
このリポジトリは[Weblate](https://weblate.rob006.net/languages/ja/flarum/)と連携しましたが、Weblateの翻訳には不自然な文言が数多く存在するため現在レビュー中です。
レビューが完了するまで、Weblateに登録された翻訳は言語パックへ反映されませんので、ご注意ください。

This repository was integrated with [Weblate](https://weblate.rob006.net/languages/ja/flarum/). However translations in the Weblate includes some weird sentences, so I'm currently reviewing all of them. Please note that Weblate translations will not be released until the completion of review.

## 翻訳状況(Flarum core) | Translation status for Flarum core

| Component | Status |
| --- | --- |
| [Core](https://github.com/flarum/flarum-core) | [![Translation status](https://weblate.rob006.net/widgets/flarum/ja/core/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/core/ja/) |
| Validation | [![Translation status](https://weblate.rob006.net/widgets/flarum/ja/validation/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/validation/ja/) |


## 翻訳状況(公式拡張機能) | Translation status for official extensions

<!-- flarum-extensions-list-start -->

| Extension | Status |
| --- | --- |

<!-- flarum-extensions-list-stop -->


## 翻訳状況(FoF拡張機能) | Translation status for Friends of Flarum extensions

<!-- fof-extensions-list-start -->

| Extension | Status |
| --- | --- |

<!-- fof-extensions-list-stop -->


## 翻訳状況(コミュニティ拡張機能) | Translation status for community extensions

<!-- various-extensions-list-start -->

| Extension | Status |
| --- | --- |

<!-- various-extensions-list-stop -->


## 翻訳状況(プレミアム拡張機能) | Translation status for premium extensions

<!-- premium-extensions-list-start -->

| Extension | Status |
| --- | --- |

<!-- premium-extensions-list-stop -->


## リンク | Links
- [Packagist](https://packagist.org/packages/takumi9942/flarum-ext-japanese)

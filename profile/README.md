# README

技術スタック等について紹介します。  
詳細は各リポジトリをご覧ください。

## [android](https://github.com/android-project-46group/android)

メインの android アプリです。

- Jetpack Compose
- Dagger Hilt による依存性注入
- Retrofit2
- Room
- DataStore
- multi-module

## [api-server](https://github.com/android-project-46group/api-server)

api サーバーです。

- Golang
- ラズパイ
- [protobuf](https://github.com/android-project-46group/protobuf)
- [open-api](https://github.com/android-project-46group/open-api)

## [core-api](https://github.com/android-project-46group/core-api)

api サーバーから gRPC でアクセスされることを期待してます。

protobuf は[こちらのリポジトリ](https://github.com/android-project-46group/protobuf)で定義されてます。

- Golang
- gRPC

## [api](https://github.com/android-project-46group/api)

api サーバーで配信する情報を収集するクローラーです。

- Python
- BeautifulSoup
- requests

## [sgi-cli](https://github.com/android-project-46group/sgi-cli)

[api-server](https://github.com/android-project-46group/api-server) の cli ツールです。

- cobra

## [ios (WIP)](https://github.com/android-project-46group/ios)

iOS のアプリです。

- SwiftUI

## [docs (WIP)](https://github.com/android-project-46group/docs)

ドキュメント（更新予定）。

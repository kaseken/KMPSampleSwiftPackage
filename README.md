# KMPSampleSwiftPackage

このリポジトリは、Kotlin Multiplatform (KMP) を使用してiOS/Android向けの共通ライブラリを作成するサンプルの一部です。
KMPで作成した共通ライブラリ `KMPSampleLibrary` をSwift Packageとして利用できるようにする方法を示しています。

> **⚠️ 注意:**  
> このリポジトリにはSwift Packageのみが含まれており、本体のライブラリ実装は別リポジトリにあります。

共通ライブラリの実装については、以下のリポジトリをご覧ください。  
📌 [KMPSampleLibrary (GitHub)](https://github.com/kaseken/KMPSampleLibrary)

## プロジェクト構成

このリポジトリには、以下のSwift Packageが含まれています。

- **KMPSampleSwiftPackage**: `KMPSampleLibrary` をWrapし、Swift Packageとして提供するライブラリ

## 詳細情報

セットアップ方法や実装の詳細については、以下の記事をご覧ください。

📖 [Kotlin MultiplatformライブラリをSwift PackageとMaven Artifactとして公開してみた (Zenn)](https://zenn.dev/kaseken/articles/e5bb09e4a96d62)

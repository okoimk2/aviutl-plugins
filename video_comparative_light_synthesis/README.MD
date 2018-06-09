VideoComparativeLightSynthesis
===

aviutlで動画のコンポジット(比較明)合成を行うためのプラグイン

project setup
---

used visual studio 2017 community

1. 新規プロジェクト > Visual C++ > 空のプロジェクト でプロジェクトを作成する
1. ソリューションエクスプローラーから既存ファイルを追加
    * ソースファイル > video_filter.cpp
    * ヘッダーファイル > filter.h
    * リソースファイル > video_filter.def
1. ソリューションエクスプローラーからプロジェクトのプロパティを編集
    1. 全般 > ターゲットの拡張子 > .auf
    1. リンカー > 入力 > モジュールの定義ファイル > video_filter.def
1. プロジェクトのビルドを行う
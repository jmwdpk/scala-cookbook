---
layout: page
title: Scala勉強会 
tagline: Tutorial of the Scala Programming Language
disquss: false
---
{% include JB/setup %}

## Scala勉強会のスケジュール

* 日時：毎週水曜日16:00~より90分。
* 場所：東京大学柏キャンパス 総合研究棟 352号室
* 参加：自由。部屋の規模が大きくないので、学外の方で参加希望の方は一度連絡していただけると助かります。

## 実施記録

* [**Lesson 0**: Scala Quick Start]({{ BASE_PATH }}/recipes/2012/06/27/scala-quick-start) (2012年6月12日)
   * サンプルコードをgitで取得
   * Scalaコードの実行
   * IntelliJのインストール、コードの実行
   * ScalaTestによるテストコードの作成とテストの実行  
   * テストを実行しながら開発(sbt)
   
* [**Lesson 1**: Scala Collections]({{BASE_PATH}}/recipes/2012/06/28/using-scala-collections) (2012年6月21日)
   * Array, Map, Set,  Tuple
   * Option
   * 要素を連結した文字列の作成(mkString)
   * immutable（変更できない）コレクションを使う
   * Builderでコレクションを作成する
   * コレクション内を探索する (map, foreach, flatMap, reduce, fold)
   * 一部の要素を取り出す (filter, collect)
   * 要素を並び替える (sort)
   * マルチコアでコレクションを並列処理する (parallel collection, par)
* **Lesson 2** (2012年6月27日)
   * [Scalaでプロジェクトを作成する]({{BASE_PATH}}/recipes/2012/06/28/create-a-scala-project)
   * [テストコードの作成]({{BASE_PATH}}/recipes/2012/06/28/scalatest)
   * [ループあれこれ]({{BASE_PATH}}/recipes/2012/06/27/loops)

* **Lesson 3** アルゴリズムとデータ構造 (2012年7月4日)
   * [Union Findで同値類をまとめる]({{BASE_PATH}}/recipes/2012/07/03/union-find)
   * [区間の交差判定]({{BASE_PATH}}/recipes/2012/07/03/interval-sweep)
     * sweep, priority search tree
	 * priority queue

* **Lesson** アルゴリズム

   * グラフ(連結リスト)とその探索
   * BFS, DFS
   * 木構造の表現
   * 償却計算量

* **Lesson** 
   * loan pattern
   
   * 特定の要素を見つける (find, exists)
   * クラスとオブジェクト
     * object (singleton)
     * パラメーターの定義
     * 初期化コード
     * lazy parameter

   * pattern matching
   * case class
   * alternative constructor
   * 変数のスコープ
   
* **Lesson** - Trait
   * インターフェースの定義
   * 実装の共有
   * 多重継承時のlinearization


* **Lesson** : デバッグ手法
   * ScalaTestを用いて、コードの挙動を確認する
   * Loggerを用いたデバッグ
   * timerで、コードの実行時間を計測する
   * Traitでfixtureを作成し、テストコードの共通設定を使い回す

* **Lesson** : 入出力 
   * ファイルの読み書き
   * 文字列の操作
   * 正規表現   
   * 外部プロセスの実行
* **Lesson** - 字句解析、構文解析
   * Combinator parsers
   * コマンドライン引数をparseする
   
* **Lesson** ゲノム情報処理
   * FASTAファイルからゲノム配列情報を取り出す
   * BEDファイルから遺伝子データの読み込み
   * WIGファイルでエピゲノム情報の管理
   * SAM/BAMファイルの読み書き
   * DPによるアラインメント (SmithWaterman(-Gotoh), Banded-alignment, Myer)
   * suffix arrayの構築 (induced sorting, parallel dc3)
   
* **Lesson** グラフの作成
   * jfreechart + iTextで、PDFチャートを作成
   * ヒストグラム
   * line chart
   * box chart
   * Rscriptを呼び出し、グラフの作成

* **Lesson** グラフィックス
   * 画像の作成

* **Lesson** データベース
   * データベースの検索
   * データベースの更新
   * テキスト検索

* **Lesson** 分散処理
   * Akkaのremote actorを使った分散処理
   * objectのserialization/deserialization

* [Scalaの文法](cheetsheet.html)

* IntelliJのカスタマイズ
   * 使用可能メモリ量を増やす




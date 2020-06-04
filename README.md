# データサイエンスのための統計学入門

[データサイエンスのための統計学入門-予測、分類、統計モデリング、統計的機械学習とRプログラミング](https://www.oreilly.co.jp/books/9784873118284/)
（Peter Bruce、Andrew Bruce　著、黒川 利明　訳、大橋 真也　技術監修）の MATLAB コード例をまとめるレポジトリです。

もともとの R コードはこちら（[GitHub](https://github.com/andrewgbruce/statistics-for-data-scientists)）にあり、
データも著者によって [Google Drive](https://drive.google.com/drive/folders/0B98qpkK5EJemYnJ1ajA1ZVJwMzg) 
もしくは [Dropbox](https://www.dropbox.com/sh/clb5aiswr7ar0ci/AABBNwTcTNey2ipoSw_kH5gra?dl=0) から入手可能です。

手を動かして理解を深められますように。


# Contributors 募集中

興味ありましたらぜひ（部分的にでもOK）一緒に勉強しましょう。README.md を編集してアカウント名を記載ください。


|  Capter  |  Owner  | Memo/Status |
| ---- | ---- | ---- |
| [1章　探索的データ分析](Chapter1/Chapter1_ExploratoryDataAnalysis.md)　| minoue-xx | Completed |
| [2章　データと標本の分布](Chapter2/Chapter2_DataandSamplingDistributions.md)　| hiroquay | Completed |
| 3章　統計実験と有意性検定　| Tajima | in progress |
| 4章　回帰と予測　| Hilobay | started |
| 5章　分類　| TBD | |
| 6章　統計的機械学習　| TBD | | 
| 7章　教師なし学習　| TBD | | 

## See also

- O'Reilly: https://oreil.ly/practicalStats_dataSci_2e
- Errata: http://oreilly.com/catalog/errata.csp?isbn=9781492072942
- 著者（Andrew Bruce）による初版の R コードは[こちら](https://github.com/andrewgbruce/statistics-for-data-scientists)


## 目次

- 1章　探索的データ分析
  - 1.1　構造化データの諸要素
    - 1.1.1　さらに学ぶために
  - 1.2　矩形データ
    - 1.2.1　データフレームとインデックス付け
    - 1.2.2　非矩形データ
    - 1.2.3　さらに学ぶために
  - 1.3　位置の推定
    - 1.3.1　平均値
    - 1.3.2　中央値と頑健推定
    - 1.3.3　例：人口と殺人事件発生率の代表値の推定
    - 1.3.4　さらに学ぶために
  - 1.4　散らばりの推定
    - 1.4.1　標準偏差と関連推定値
    - 1.4.2　パーセンタイルに基づく推定値
    - 1.4.3　例：州別人口の散らばりの推定
    - 1.4.4　さらに学ぶために
  - 1.5　データ分布の探索
    - 1.5.1　パーセンタイルと箱ひげ図
    - 1.5.2　度数分布表とヒストグラム
    - 1.5.3　密度推定
    - 1.5.4　さらに学ぶために
  - 1.6　バイナリデータとカテゴリデータの探索
    - 1.6.1　最頻値（モード）
    - 1.6.2　期待値
    - 1.6.3　さらに学ぶために
  - 1.7　相関
    - 1.7.1　散布図
    - 1.7.2　さらに学ぶために
  - 1.8　2つ以上の変量の探索
    - 1.8.1　六角ビニングと等高線（2つの数値データをプロット）
    - 1.8.2　2つのカテゴリ変数の探索
    - 1.8.3　カテゴリデータと数量データ
    - 1.8.4　多変量の可視化
    - 1.8.5　さらに学ぶために
  - 1.9　まとめ

- 2章　データと標本の分布
  - 2.1　無作為抽出と標本バイアス
    - 2.1.1　バイアス
    - 2.1.2　無作為抽出
    - 2.1.3　サイズと品質：サイズが問題になる場合
    - 2.1.4　標本平均と母集団平均
    - 2.1.5　さらに学ぶために
   - 2.2　選択バイアス
    - 2.2.1　平均への回帰
    - 2.2.2　さらに学ぶために
   - 2.3　統計量の標本分布
    - 2.3.1　中心極限定理
    - 2.3.2　標準誤差
    - 2.3.3　さらに学ぶために
  - 2.4　ブートストラップ
    - 2.4.1　リサンプリングとブートストラップ
    - 2.4.2　さらに学ぶために
  - 2.5　信頼区間
    - 2.5.1　さらに学ぶために
  - 2.6　正規分布
    - 2.6.1　標準正規分布とQQプロット
  - 2.7　ロングテールの分布
    - 2.7.1　さらに学ぶために
  - 2.8　スチューデントの t分布
    - 2.8.1　さらに学ぶために
  - 2.9　二項分布
    - 2.9.1　さらに学ぶために
  - 2.10　ポアソン分布と関連する分布
    - 2.10.1　ポアソン分布
    - 2.10.2　指数分布
    - 2.10.3　故障率の推定
    - 2.10.4　ワイブル分布
    - 2.10.5　さらに学ぶために
  - 2.11　まとめ

- 3章　統計実験と有意性検定
  - 3.1　A/Bテスト
    - 3.1.1　なぜ統制群があるか
    - 3.1.2　なぜ A/Bだけで C、D、…でないのか
    - 3.1.3　さらに学ぶために
  - 3.2　仮説検定
    - 3.2.1　帰無仮説
    - 3.2.2　対立仮説
    - 3.2.3　片側、両側仮説検定
    - 3.2.4　さらに学ぶために
  - 3.3　リサンプリング
    - 3.3.1　並べ替え検定
    - 3.3.2　例： Web粘着性
    - 3.3.3　完全並べ替え検定とブートストラップ並べ替え検定
    - 3.3.4　並べ替え検定：データサイエンスの基本
    - 3.3.5　さらに学ぶために
  - 3.4　統計的有意性と p値
    - 3.4.1　p値
    - 3.4.2　アルファ
    - 3.4.3　第一種の過誤と第二種の過誤
    - 3.4.4　データサイエンスと p値
    - 3.4.5　さらに学ぶために
  - 3.5　t検定
    - 3.5.1　さらに学ぶために
  - 3.6　多重検定
    - 3.6.1　さらに学ぶために
  - 3.7　自由度
    - 3.7.1　さらに学ぶために
  - 3.8　ANOVA
    - 3.8.1　F統計量
    - 3.8.2　二元配置分散分析（二元 ANOVA）
    - 3.8.3　さらに学ぶために
  - 3.9　カイ二乗検定
    - 3.9.1　カイ二乗検定：リサンプリング方式
    - 3.9.2　カイ二乗検定：統計理論
    - 3.9.3　フィッシャーの正確確率検定
    - 3.9.4　データサイエンスへの関わり
    - 3.9.5　さらに学ぶために
  - 3.10　多腕バンディットアルゴリズム
    - 3.10.1　さらに学ぶために
  - 3.11　検定力とサンプルサイズ
    - 3.11.1　サンプルサイズ
    - 3.11.2　さらに学ぶために
  - 3.12　まとめ

- 4章　回帰と予測
  - 4.1　単回帰
    - 4.1.1　回帰式
    - 4.1.2　予測値と残差
    - 4.1.3　最小二乗法
    - 4.1.4　予測と説明（プロファイリング）
    - 4.1.5　さらに学ぶために
  - 4.2　重回帰
    - 4.2.1　例：キング郡住宅データ
    - 4.2.2　モデルの評価
    - 4.2.3　交差検証
    - 4.2.4　モデル選択と段階的回帰
    - 4.2.5　加重回帰
    - 4.2.6　さらに学ぶために
  - 4.3　回帰を使った予測
    - 4.3.1　外挿の危険性
    - 4.3.2　信頼区間と予測区間
  - 4.4　回帰でのファクタ変数
    - 4.4.1　ダミー変数表現
    - 4.4.2　多水準のファクタ変数
    - 4.4.3　順序ファクタ変数
  - 4.5　回帰式の解釈
    - 4.5.1　相関予測変数
    - 4.5.2　多重共線性
    - 4.5.3　交絡変数
    - 4.5.4　交互作用と主効果
  - 4.6　仮定をテストする：回帰診断
    - 4.6.1　外れ値
    - 4.6.2　影響値
    - 4.6.3　不等分散性、非正規性、相関誤差
    - 4.6.4　偏残差プロットと非線形性
  - 4.7　多項式回帰およびスプライン回帰
    - 4.7.1　多項式
    - 4.7.2　スプライン
    - 4.7.3　一般化加法モデル
    - 4.7.4　さらに学ぶために
  - 4.8　まとめ

- 5章　分類
  - 5.1　ナイーブベイズ
    - 5.1.1　正確なベイズ分類はなぜ実用的でないか
    - 5.1.2　ナイーブベイズ解
    - 5.1.3　数値予測変数
    - 5.1.4　さらに学ぶために
  - 5.2　判別分析
    - 5.2.1　共分散行列
    - 5.2.2　フィッシャーの線形判別
    - 5.2.3　簡単な例
    - 5.2.4　さらに学ぶために
  - 5.3　ロジスティック回帰
    - 5.3.1　ロジスティック応答関数とロジット
    - 5.3.2　ロジスティック回帰と一般化線形モデル
    - 5.3.3　一般化線形モデル
    - 5.3.4　ロジスティック回帰の予測値
    - 5.3.5　係数とオッズ比を解釈する
    - 5.3.6　線形回帰とロジスティック回帰：類似点と相違点
    - 5.3.7　モデルを評価する
    - 5.3.8　さらに学ぶために
  - 5.4　分類モデルの評価
    - 5.4.1　混同行列
    - 5.4.2　稀なクラスの問題
    - 5.4.3　適合率、再現率、特異度
    - 5.4.4　ROC曲線
    - 5.4.5　AUC
    - 5.4.6　リフト
    - 5.4.7　さらに学ぶために
  - 5.5　不均衡データの戦略
    - 5.5.1　アンダーサンプリング
    - 5.5.2　オーバーサンプリングと重み追加 /削減
    - 5.5.3　データ生成
    - 5.5.4　コストベース分類
    - 5.5.5　予測を探索する
    - 5.5.6　さらに学ぶために
  - 5.6　まとめ

- 6章　統計的機械学習
  - 6.1　k近傍法
    - 6.1.1　簡単な例：ローンの返済不能を予測する
    - 6.1.2　距離指標
    - 6.1.3　one-hotエンコーダ
    - 6.1.4　標準化（正規化、z値）
    - 6.1.5　kの選択
    - 6.1.6　特徴量エンジンとしての k近傍法
  - 6.2　木モデル
    - 6.2.1　簡単な例
    - 6.2.2　再帰分割アルゴリズム
    - 6.2.3　同質性または不純度の測定
    - 6.2.4　木の成長を止める
    - 6.2.5　連続値を予測する
    - 6.2.6　木の使い方
    - 6.2.7　さらに学ぶために
  - 6.3　バギングとランダムフォレスト
    - 6.3.1　バギング
    - 6.3.2　ランダムフォレスト
    - 6.3.3　変数の重要度
    - 6.3.4　ハイパーパラメータ
  - 6.4　ブースティング
    - 6.4.1　ブースティングアルゴリズム
    - 6.4.2　XGBoost
    - 6.4.3　正則化：過剰適合を防ぐ
    - 6.4.4　ハイパーパラメータと交差検証
  - 6.5　まとめ

- 7章　教師なし学習
  - 7.1　主成分分析
    - 7.1.1　簡単な例
    - 7.1.2　主成分の計算
    - 7.1.3　主成分の解釈
    - 7.1.4　さらに学ぶために
  - 7.2　k平均クラスタリング
    - 7.2.1　簡単な例
    - 7.2.2　k平均アルゴリズム
    - 7.2.3　クラスタを解釈する
    - 7.2.4　クラスタの個数を選ぶ
  - 7.3　階層クラスタリング
    - 7.3.1　簡単な例
    - 7.3.2　デンドログラム
    - 7.3.3　凝集アルゴリズム
    - 7.3.4　非類似度の尺度
  - 7.4　モデルベースクラスタリング
    - 7.4.1　多変量正規分布
    - 7.4.2　正規分布の混合
    - 7.4.3　クラスタの個数を選ぶ
    - 7.4.4　さらに学ぶために
  - 7.5　スケーリングとカテゴリ変数
    - 7.5.1　変数のスケーリング
    - 7.5.2　優勢な変数
    - 7.5.3　カテゴリデータと Gower距離
    - 7.5.4　混合データクラスタリングの問題
  - 7.6　まとめ


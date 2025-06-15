# Computer Vision Practices

このリポジトリには、コンピュータビジョンの学習用Jupyterノートブックが含まれています。

## セットアップ

### 1. 仮想環境の作成と有効化

```bash
# 仮想環境を作成
python3 -m venv venv

# 仮想環境を有効化
source venv/bin/activate
```

### 2. 依存関係のインストール

```bash
pip install -r requirements.txt
```

## 使用方法

### Jupyter Notebookの起動

```bash
# 仮想環境を有効化（まだの場合）
source venv/bin/activate

# Jupyter Notebookを起動
jupyter notebook
```

ブラウザが自動的に開き、Jupyterのインターフェースが表示されます。

### ノートブックの実行

1. 任意の `.ipynb` ファイルをクリックして開く
2. 各セルを順番に実行する（Shift + Enter または再生ボタン）

## 含まれているノートブック

### cv_ex03.ipynb - Matplotlibの基礎
- データ可視化のためのmatplotlib入門
- 散布図、折れ線グラフの作成
- 線形回帰とpoly fit
- 三角関数の可視化
- グラフのカスタマイズ（タイトル、ラベル、凡例）

### cv_ex04.ipynb - 数学的基礎
- コンピュータビジョンのための線形代数と微積分
- ベクトル演算（内積、L1/L2ノルム）
- 行列演算（転置、逆行列、固有値・固有ベクトル）
- 線形変換と微分
- 接線の可視化

### cv_ex05.ipynb - OpenCVの基礎
- 画像の読み込みと色変換（BGRからグレースケール）
- 画像の変形（クロッピング、リサイズ、回転）
- アフィン変換と補間手法
- 境界処理技術

### cv_ex06.ipynb - 高度な画像処理
- 画像の閾値処理（バイナリ、Otsu法、Triangle法）
- スムージングフィルタ（ぼかし、ガウシアンぼかし、バイラテラルフィルタ）
- ノイズ除去技術
- モルフォロジー演算（膨張、収縮）

### cv_ex07.ipynb - 特徴検出
- Cannyエッジ検出
- Harrisコーナー検出
- goodFeaturesToTrackコーナー検出
- FAST（Features from Accelerated Segment Test）アルゴリズム
- ORB（Oriented FAST and Rotated BRIEF）特徴検出

### cv_ex08.ipynb - 特徴マッチングと画像合成
- AKAZEとORB特徴マッチング
- Brute Forceマッチャー
- パノラマ画像作成のための画像ステッチング
- ハミング距離ベースのマッチング

### cv_ex09.ipynb - ステレオビジョン
- ブロックマッチング法によるステレオ対応
- Semi-Global Block Matching（SGBM）
- チェスボードパターンを用いたカメラキャリブレーション
- 内部パラメータ計算とレンズ歪み補正

### cv_ex10.ipynb - 機械学習分類
- MNIST手書き数字分類
- 決定木分類
- 混同行列とデータ可視化
- 分類精度評価

### cv_ex11.ipynb - ML手法の比較と評価
- 機械学習分類手法の比較
- 交差検証によるモデル評価
- グリッドサーチによるハイパーパラメータ最適化
- Random Forest、SVM、ニューラルネットワークの比較

### cv_ex12.ipynb - Kerasによるニューラルネットワーク
- Fashion-MNISTデータセットでのディープラーニング
- Keras/TensorFlowによるニューラルネットワーク構築
- 多層パーセプトロンアーキテクチャ
- One-hotエンコーディングとデータ前処理

### cv_ex13.ipynb - ニューラルネットワークの最適化
- ドロップアウト正則化
- 活性化関数の比較（Sigmoid vs ReLU）
- オプティマイザーの比較（SGD vs Adam）
- 学習率の最適化とバッチサイズの影響

### cv_ex14.ipynb - 畳み込みニューラルネットワーク（CNN）
- 画像分類のためのCNN実装
- 畳み込み層とフィルタ
- Max Pooling演算
- 多層CNNアーキテクチャ
- 特徴マップ処理

### cv_ex15.ipynb - バッチ正規化と高度なCNN
- 訓練安定性のためのバッチ正規化
- 深いCNNアーキテクチャ
- 性能改善技術
- 訓練加速手法

## 仮想環境の無効化

作業が終了したら、仮想環境を無効化できます：

```bash
deactivate
```
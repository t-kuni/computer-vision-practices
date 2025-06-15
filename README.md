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

1. `cv_ex03.ipynb` をクリックして開く
2. 各セルを順番に実行する（Shift + Enter または再生ボタン）

## 含まれているノートブック

- `cv_ex03.ipynb`: matplotlib を使用したグラフ描画の基礎
  - 折れ線グラフ、散布図の作成
  - 直線近似
  - 三角関数のプロット
  - グラフの装飾（凡例、タイトル、軸ラベル）
  - グラフの画像ファイル保存

## 仮想環境の無効化

作業が終了したら、仮想環境を無効化できます：

```bash
deactivate
```
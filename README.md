# PyTorch学習ログ（by ○○）

このリポジトリでは、PyTorchの基礎から応用に至るまでの学習過程を記録しています。  
主に以下のテーマを扱います：

- Tensor操作と演算
- モデル構築（nn.Module）
- 学習ループ
- 自作Datasetの実装
- モデル評価・可視化

## フォルダ構成

| フォルダ | 内容 |
|----------|------|
| 01_tensors_and_operations | Tensorの基礎 |
| 02_nn_module_and_forward | モデル構築の基本 |
| requirements.txt | 使用ライブラリ一覧 |

## 使用環境

- Python 3.9
- PyTorch 2.x
- NumPy, matplotlib など


# 01 - Tensors and Operations

この章では、PyTorchにおけるテンソル操作の基礎を学びます。

- テンソルの生成（zeros, ones, random, empty, arange）
- NumPyとの相互変換
- テンソルの形状変更（view, reshape, squeeze, unsqueeze）
- 基本的な演算（加算、減算、掛け算、転置、行列積）
- ブロードキャストの理解
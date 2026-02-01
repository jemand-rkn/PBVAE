
# PBVAE

論文 "On PAC-Bayesian reconstruction guarantees for VAEs" の実装．

## 依存パッケージ

依存パッケージは `pyproject.toml` を参照．

## 計算環境

- OS: Linux 推奨
- CUDA: 任意（GPU推奨）

## 使い方

1. 仮想環境を作成し，依存パッケージをインストール
	```bash
	uv sync
	```
2. 実行
	```bash
	uv run main.py
	```
3. 各種パラメータは `config/` 内のyamlファイルで変更可能．

---

### Reference

Cherief-Abdellatif, Badr-Eddine and Shi, Yuyang and Doucet, Arnaud and Guedj, Benjamin. "On PAC-Bayesian reconstruction guarantees for VAEs." International Conference on Artificial Intelligence and Statistics. PMLR, 2022．

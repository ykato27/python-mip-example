# python-mip-example

数理最適化（混合整数最適化）ソルバー（付きインターフェース） Python-MIP のexample リポジトリです。

## リポジトリ構成

```
.
├── Dockerfile
├── README.md
├── data
├── docker-compose.yml
├── docs
├── models
├── notebooks
├── pyproject.toml
├── requirements.txt
├── setup.cfg
├── src
│   └── __init__.py
├── tests
│   └── __init__.py
└── work
```

## 環境詳細

- Python : 3.9.6

## 事前準備

- Docker インストール

## 環境構築

- Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/python-mip-example）

```
cd Desktop/python-mip-example
```

- Dockerによる環境構築（フォルダをマウント：Desktop/python-mip-example）

```
docker-compose up --build
```

- ブラウザーを立ち上げてlocalhost:8888へアクセス
- ローカルフォルダがマウントされている

## 動作環境

マシンスペック（Mac)

- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3

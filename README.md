# DG Lab AI実践講座

## Python環境構築
セミナーで利用するPython環境を[Anaconda](https://www.anaconda.com/)を使って作成します。  
自分で環境構築が出来る方はスキップしても構いません。

### Anacondaのインストール
[Anaconda インストーラ](https://www.anaconda.com/download/) を使って、Anacondaをインストールしてください。  
今回の講座では `Anaconda >= 5.1`を使用します。

### Anacondaの使い方
下記コマンドで環境を作成します。プロジェクト毎に環境名を変えてください。  


```
conda create -n ai-seminar
```

環境を有効/無効にするためには下記のコマンドを実行します。

Mac/Linuxの場合

```
# 環境名を指定して有効にする
source activate ai-seminar

# 無効にする
source deactivate
```

Windowsの場合

```
activate ai-seminar
deactivate
```

## Jupyter notebookの起動
```
jupyter notebook --notebook-dir=notebooks
```

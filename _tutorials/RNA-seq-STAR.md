---
layout: page
title: RNA-seq (STAR-RSEM)
author: "[hattyoriiiiiii](hattyoriiiiiii.github.io)"
description: STAR-RSEM
img: /assets/img/dna_green.jpg
category: ngs
---

## Introduction

<br>

STAR-RSEMのワークフローは、ENCODEプロジェクトなどでも用いられています。

- pros
  - 処理が高速
  - 利用者が多い
- cons
  - laptopではリソース不足 (哺乳類ゲノムをリファレンスとした場合、最低16 GBのRAMが必要)

<br>

## 環境構築

<br>

Dockerを用いて環境構築を行います。[こちら](/tutorials/Docker)も合わせてお読みください。

```bash
docker pull hattyoriiiiiii/rna-seq:1.0
docker run \
    -it \
    --rm \
    --name test_rna \
    -v ${PWD}:/home/you/work \
    -v ${HOME}/ref/mm10:/home/you/ref \
    hattyoriiiiiii/rna-seq:1.0 \
    /bin/bash
```

ここ以降は、コンテナ内での作業になります。

<br>

### ディレクトリの作成

<br>

```bash
./mkproj.sh
```


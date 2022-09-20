---
layout: post
author: hattyoriiiiiii
title:  Google ColabでPythonファイルの編集とスクリプトの実行をする
date: 2022-09-19
description:  notebookを開きながらPythonファイルの編集ができる
tags: tips
categories: 環境構築 Colaboratory
---

<br>

### 概要

- Google Colabolatoryは、無料で簡単にPythonの実行環境が構築できるサービス。
- notebookを開いた状態で、Pythonファイルの作成・編集・実行ができる。
- ここでは説明のために、Google Driveに「Bioinfo2」というフォルダを作成する。

<br>

### Google ColabでPythonファイルの編集とスクリプトの実行をする

<br>

<ol>
    <li>新しいフォルダから、「Bioinfo2」を作成する。</li>
    <li>新しく出来た「Bioinfo2」をダブルクリックしてフォルダ内に入る。</li>
    <li>「その他」→「Google Colabolatory」から新しいnotebookを作成する。</li>
</ol>

<br>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/blog/2022/2022-09-19-GoogleColab_01.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    まずはnotebookを作成する。
</div>



<br>

<ol>
    <li value="4">
        フォルダマークをクリックする。
    </li>
    <li>
        Google Driveのマークをクリックして、接続の許可を行う。初めて実行する場合は、<code>from google.colab import drive</code>から始まるコードが出てくるので、再生ボタンを押す(コードの実行)。許可を求められるので、アクセスの許可をする(<a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjeppid7aD6AhUNAt4KHUhwAKIQFnoECAoQAQ&url=https%3A%2F%2Faiacademy.jp%2Fmedia%2F%3Fp%3D1460&usg=AOvVaw2gTDOA1cmHqTNAbl3li3AM">こちらのサイト</a>も参考にしてみて下さい)。
    </li>
    <li>
        「Bioinfo2」の右側に出てくる「…」を90度回転させたボタンを押して新しいファイルを作成する。
    </li>
    <li>⑥で作成した「<code>~.py</code>」という名前のファイルをダブルクリックする。</li>
</ol>

<br>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/blog/2022/2022-09-19-GoogleColab_02.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    次にPythonファイルを作成する。
</div>

<br>

<ol>
    <li value="8">
        右側にダブルクリックしたPythonファイルが開かれる。
    </li>
    <li>
        <code>!python3 /content/drive/MyDrive/Bioinfo2/ファイル名.py</code>(<code>!python3</code>の後に半角の空白が1個入る)と打って再生ボタンを押す。
        <ul>
            <li>
                上手くいかない場合は、「…」が90度 回転したボタンを押して、「パスをコピー」。「!python3」+「半角の空白1個」そしてペーストする。
            </li>
            <li>
                もしくは、<code>cd /content/drive/MyDrive/Bioinfo2</code>をセルの中で実行した後、<code>!python3 ファイル名.py</code>を実行する。
            </li>
        </ul>
    </li>
</ol>

<br>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/blog/2022/2022-09-19-GoogleColab_03.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Pythonファイルを編集して、実行する。
</div>
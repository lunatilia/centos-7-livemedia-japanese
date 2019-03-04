# CentOS Linux 7 Livemedia GNOME3 Desktop 日本語環境 kickstart

## 内容
次のCentOS 7 Liveメディアを作成するためのkickstartファイルです。
1. CentOS Livemedia Minimal Desktop (ほぼ最小構成に近いGNOME3 Desktop + Firefoxの日本語版)

## 用途
- オリジナルの専用Liveメディアを作成する際のベース

## 要件
- CentOS 7またはその他RHEL7互換OSが稼働しているマシン
- root権限
- livecd-toolsおよび依存パッケージがインストールされていること。

## 実行例
```
# LANG=C livecd-creator --verbose \
--config=centos-7-lmd-jp.cfg \
--fslabel="CentOS-7-x86_64-LMD-1810-jp" \
--title="CentOS Linux 7 1810" \
--product="CentOS Linux 7 1810 LMD (JP)"
```

## ライセンス

GNU GPLv2 (CentOS Projectのデフォルトライセンス)

## 参考

- オリジナル著者   : The CentOS Project
- オリジナルks     : centos-7-livecd.cfg
  - sig-core/livemedia.git リポジトリURL : https://git.centos.org/summary/sig-core!livemedia.git
- 情報サイト    : https://seven.centos.org/2014/05/centos-7-live-media-spins/

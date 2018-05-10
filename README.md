# README
CoreOS公式のVagrantfileのコピー。

# 変更点
## [vagrant-disksize](https://github.com/sprotheroe/vagrant-disksize)の導入
デフォルトのディスクサイズだと物足りないため、サイズ変更

## VMWare関連の設定を削除
ホビーユースなのでVirtualBoxのみの設定に修正

## 開発用のローカルディレクトリの同期
Windowsでの利用のためrsyncを用いて「D:\\dev」を同期する。
あくまでもWindows側が主であることからCoreOS -> Windowsの同期は行わない。

[やった内容をまとめた記事](http://melvins-nest.com/dev/2018/05/11/coreosvagrant%E3%81%A7%E9%96%8B%E7%99%BA%E7%92%B0%E5%A2%83%E3%82%92%E4%BD%9C%E3%81%A3%E3%81%9F%E3%81%9F%E3%81%A0%E4%BD%9C%E3%81%A3%E3%81%9F%E3%81%A0%E3%81%91%E3%81%AE%E8%A8%98%E4%BA%8B/)
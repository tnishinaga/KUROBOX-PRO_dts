# KUROBOX-PRO_dts
玄箱PRO用のDTS（Device Tree Script）とLinux 4.3のビルドに使った.configです．

DTSはorion5のリファレンスNASの設定（orion5x-rd88f5182-nas.dts）をベースに，メモリを64MBから128MBに増やしただけです．

Kernelの起動及び内部SATA，Ethernetの動作のみ確認しています．
その他については未確認です．

Kernel configはsystemd環境で動作するようオプションを有効にしています．

